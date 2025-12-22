```
k-ran@k-ran-Predator-PHN16-71:~/XSStrike$ # 1) HTTP header + redirect zinciri (en önemli)
curl -svI http://rodney.lat/ 2>&1 | sed -n '1,120p'

# 2) Redirect hedefi (88.255.216.16) header
curl -svI "http://88.255.216.16/landpage?op=1&ms=http://rodney.lat/" 2>&1 | sed -n '1,120p'

# 3) HTTPS gerçekten var mı? (TLS doğrulama)
openssl s_client -connect rodney.lat:443 -servername rodney.lat -brief </dev/null

# 4) HTTP/HTTPS port kontrol (hızlı servis tespiti)
nmap -Pn -p 80,443 --script http-title,http-headers,ssl-cert rodney.lat

# 5) Cloudflare/arka IP doğrulama (A/AAAA)
dig +short A rodney.lat
dig +short AAAA rodney.lat

# 6) XSStrike için parametreli örnek endpoint var mı? (site haritalama - pasif)
curl -sL http://rodney.lat/ | egrep -oi 'href="[^"]+"' | head -n 50
* Host rodney.lat:80 was resolved.
* IPv6: 2606:4700:3036::ac43:93f0, 2606:4700:3033::6815:1cfd
* IPv4: 172.67.147.240, 104.21.28.253
*   Trying 172.67.147.240:80...
* Connected to rodney.lat (172.67.147.240) port 80
> HEAD / HTTP/1.1
> Host: rodney.lat
> User-Agent: curl/8.5.0
> Accept: */*
> 
< HTTP/1.1 307 Temporary Redirect
< Via: 1.0 middlebox
< Location: http://88.255.216.16/landpage?op=1&ms=http://rodney.lat/
< Connection: close
< 
* Closing connection
HTTP/1.1 307 Temporary Redirect
Via: 1.0 middlebox
Location: http://88.255.216.16/landpage?op=1&ms=http://rodney.lat/
Connection: close

*   Trying 88.255.216.16:80...
* Connected to 88.255.216.16 (88.255.216.16) port 80
> HEAD /landpage?op=1&ms=http://rodney.lat/ HTTP/1.1
> Host: 88.255.216.16
> User-Agent: curl/8.5.0
> Accept: */*
> 
< HTTP/1.1 400 Bad Request
< content-type: text/plain
< connection: close
< 
* Closing connection
HTTP/1.1 400 Bad Request
content-type: text/plain
connection: close

4087C6A9627D0000:error:0A00010B:SSL routines:ssl3_get_record:wrong version number:../ssl/record/ssl3_record.c:354:
Starting Nmap 7.94SVN ( https://nmap.org ) at 2025-12-22 12:55 +03
Nmap scan report for rodney.lat (104.21.28.253)
Host is up (0.053s latency).
Other addresses for rodney.lat (not scanned): 172.67.147.240 2606:4700:3036::ac43:93f0 2606:4700:3033::6815:1cfd

PORT    STATE SERVICE
80/tcp  open  http
|_http-title: Did not follow redirect to http://88.255.216.16/landpage?op=1&ms=http://rodney.lat/
| http-headers: 
|   Via: 1.0 middlebox
|   Location: http://88.255.216.16/landpage?op=1&ms=http://rodney.lat/
|   Connection: close
|   
|_  (Request type: GET)
443/tcp open  https
|_http-title: Did not follow redirect to http://88.255.216.16/landpage?op=1&ms=http://rodney.lat/
| http-headers: 
|   Via: 1.0 middlebox
|   Location: http://88.255.216.16/landpage?op=1&ms=http://rodney.lat/
|   Connection: close
|   
|_  (Request type: GET)

Nmap done: 1 IP address (1 host up) scanned in 0.58 seconds
104.21.28.253
172.67.147.240
2606:4700:3033::6815:1cfd
2606:4700:3036::ac43:93f0
```

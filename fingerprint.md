
```
NSOCK INFO [63.8500s] nsock_read(): Read request from IOD #1927 [88.255.216.16:80] (timeout: 10000ms) EID 61634
NSOCK INFO [63.8500s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61634 [88.255.216.16:80]
NSE: TCP 192.168.31.147:58012 > 88.255.216.16:80 | CLOSE
NSOCK INFO [63.8510s] nsock_iod_delete(): nsock_iod_delete (IOD #1927)
NSOCK INFO [63.8510s] nsock_iod_new2(): nsock_iod_new (IOD #1928)
NSOCK INFO [63.8520s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1928) EID 61640
NSOCK INFO [63.8650s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61640 [88.255.216.16:80]
NSE: TCP 192.168.31.147:58016 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:58016 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6c 73 73 61 6d 70 6c 65 61 64 GET /plssamplead
00000010: 6d 69 6e 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 min/ HTTP/1.1  H
00000020: 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e ost: 88.255.216.
00000030: 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 16.static.ttnet.
00000040: 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 com.tr  User-Age
00000050: 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 nt: Mozilla/5.0 
00000060: 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 (compatible; Nma
00000070: 70 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 p Scripting Engi
00000080: 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 ne; https://nmap
00000090: 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 .org/book/nse.ht
000000a0: 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a ml)  Connection:
000000b0: 20 63 6c 6f 73 65 0d 0a 0d 0a                    close    

NSOCK INFO [63.8660s] nsock_write(): Write request for 186 bytes to IOD #1928 EID 61651 [88.255.216.16:80]
NSOCK INFO [63.8660s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61651 [88.255.216.16:80]
NSE: TCP 192.168.31.147:58016 > 88.255.216.16:80 | SEND
NSOCK INFO [63.8670s] nsock_read(): Read request from IOD #1928 [88.255.216.16:80] (timeout: 10000ms) EID 61658
NSOCK INFO [64.1330s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61658 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:58016 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.1340s] nsock_read(): Read request from IOD #1928 [88.255.216.16:80] (timeout: 10000ms) EID 61666
NSOCK INFO [64.1340s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61666 [88.255.216.16:80]
NSE: TCP 192.168.31.147:58016 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.1340s] nsock_iod_delete(): nsock_iod_delete (IOD #1928)
NSOCK INFO [64.1340s] nsock_iod_new2(): nsock_iod_new (IOD #1929)
NSOCK INFO [64.1340s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1929) EID 61672
NSOCK INFO [64.1480s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61672 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35920 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35920 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6c 73 73 61 6d 70 6c 65 61 64 GET /plssamplead
00000010: 6d 69 6e 5f 68 65 6c 70 2f 20 48 54 54 50 2f 31 min_help/ HTTP/1
00000020: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000030: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000040: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000050: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000060: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000070: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000080: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000090: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
000000a0: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000b0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [64.1490s] nsock_write(): Write request for 191 bytes to IOD #1929 EID 61683 [88.255.216.16:80]
NSOCK INFO [64.1490s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61683 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35920 > 88.255.216.16:80 | SEND
NSOCK INFO [64.1510s] nsock_read(): Read request from IOD #1929 [88.255.216.16:80] (timeout: 10000ms) EID 61690
NSOCK INFO [64.1630s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61690 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35920 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.1640s] nsock_read(): Read request from IOD #1929 [88.255.216.16:80] (timeout: 10000ms) EID 61698
NSOCK INFO [64.1640s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61698 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35920 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.1640s] nsock_iod_delete(): nsock_iod_delete (IOD #1929)
NSOCK INFO [64.1640s] nsock_iod_new2(): nsock_iod_new (IOD #1930)
NSOCK INFO [64.1640s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1930) EID 61704
NSOCK INFO [64.1780s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61704 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35934 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35934 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6c 73 73 61 6d 70 6c 65 2f 20 GET /plssample/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [64.1800s] nsock_write(): Write request for 181 bytes to IOD #1930 EID 61715 [88.255.216.16:80]
NSOCK INFO [64.1800s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61715 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35934 > 88.255.216.16:80 | SEND
NSOCK INFO [64.1810s] nsock_read(): Read request from IOD #1930 [88.255.216.16:80] (timeout: 10000ms) EID 61722
NSOCK INFO [64.1980s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61722 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35934 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.1990s] nsock_read(): Read request from IOD #1930 [88.255.216.16:80] (timeout: 10000ms) EID 61730
NSOCK INFO [64.1990s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61730 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35934 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.2000s] nsock_iod_delete(): nsock_iod_delete (IOD #1930)
NSOCK INFO [64.2000s] nsock_iod_new2(): nsock_iod_new (IOD #1931)
NSOCK INFO [64.2000s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1931) EID 61736
NSOCK INFO [64.2140s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61736 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35948 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35948 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6f 6c 6c 2f 20 48 54 54 50 2f GET /poll/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [64.2160s] nsock_write(): Write request for 176 bytes to IOD #1931 EID 61747 [88.255.216.16:80]
NSOCK INFO [64.2160s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61747 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35948 > 88.255.216.16:80 | SEND
NSOCK INFO [64.2170s] nsock_read(): Read request from IOD #1931 [88.255.216.16:80] (timeout: 10000ms) EID 61754
NSOCK INFO [64.2290s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61754 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35948 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.2310s] nsock_read(): Read request from IOD #1931 [88.255.216.16:80] (timeout: 10000ms) EID 61762
NSOCK INFO [64.2310s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61762 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35948 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.2320s] nsock_iod_delete(): nsock_iod_delete (IOD #1931)
NSOCK INFO [64.2320s] nsock_iod_new2(): nsock_iod_new (IOD #1932)
NSOCK INFO [64.2330s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1932) EID 61768
NSOCK INFO [64.2460s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61768 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35950 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35950 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6f 6c 6c 73 2f 20 48 54 54 50 GET /polls/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [64.2470s] nsock_write(): Write request for 177 bytes to IOD #1932 EID 61779 [88.255.216.16:80]
NSOCK INFO [64.2470s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61779 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35950 > 88.255.216.16:80 | SEND
NSOCK INFO [64.2490s] nsock_read(): Read request from IOD #1932 [88.255.216.16:80] (timeout: 10000ms) EID 61786
NSOCK INFO [64.2610s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61786 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35950 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.2620s] nsock_read(): Read request from IOD #1932 [88.255.216.16:80] (timeout: 10000ms) EID 61794
NSOCK INFO [64.2620s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61794 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35950 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.2620s] nsock_iod_delete(): nsock_iod_delete (IOD #1932)
NSOCK INFO [64.2620s] nsock_iod_new2(): nsock_iod_new (IOD #1933)
NSOCK INFO [64.2620s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1933) EID 61800
NSOCK INFO [64.2760s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61800 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35956 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35956 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6f 72 6e 2f 20 48 54 54 50 2f GET /porn/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [64.2780s] nsock_write(): Write request for 176 bytes to IOD #1933 EID 61811 [88.255.216.16:80]
NSOCK INFO [64.2780s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61811 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35956 > 88.255.216.16:80 | SEND
NSOCK INFO [64.2800s] nsock_read(): Read request from IOD #1933 [88.255.216.16:80] (timeout: 10000ms) EID 61818
NSOCK INFO [64.2910s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61818 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35956 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.2920s] nsock_read(): Read request from IOD #1933 [88.255.216.16:80] (timeout: 10000ms) EID 61826
NSOCK INFO [64.2920s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61826 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35956 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.2930s] nsock_iod_delete(): nsock_iod_delete (IOD #1933)
NSOCK INFO [64.2930s] nsock_iod_new2(): nsock_iod_new (IOD #1934)
NSOCK INFO [64.2930s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1934) EID 61832
NSOCK INFO [64.3060s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61832 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35972 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35972 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6f 72 74 61 6c 2f 20 48 54 54 GET /portal/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [64.3070s] nsock_write(): Write request for 178 bytes to IOD #1934 EID 61843 [88.255.216.16:80]
NSOCK INFO [64.3070s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61843 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35972 > 88.255.216.16:80 | SEND
NSOCK INFO [64.3080s] nsock_read(): Read request from IOD #1934 [88.255.216.16:80] (timeout: 10000ms) EID 61850
NSOCK INFO [64.3200s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61850 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35972 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.3220s] nsock_read(): Read request from IOD #1934 [88.255.216.16:80] (timeout: 10000ms) EID 61858
NSOCK INFO [64.3220s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61858 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35972 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.3230s] nsock_iod_delete(): nsock_iod_delete (IOD #1934)
NSOCK INFO [64.3230s] nsock_iod_new2(): nsock_iod_new (IOD #1935)
NSOCK INFO [64.3230s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1935) EID 61864
NSOCK INFO [64.3350s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61864 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35986 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35986 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6f 72 74 61 6c 73 2f 20 48 54 GET /portals/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.3360s] nsock_write(): Write request for 179 bytes to IOD #1935 EID 61875 [88.255.216.16:80]
NSOCK INFO [64.3360s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61875 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35986 > 88.255.216.16:80 | SEND
NSOCK INFO [64.3370s] nsock_read(): Read request from IOD #1935 [88.255.216.16:80] (timeout: 10000ms) EID 61882
NSOCK INFO [64.3490s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61882 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35986 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.3500s] nsock_read(): Read request from IOD #1935 [88.255.216.16:80] (timeout: 10000ms) EID 61890
NSOCK INFO [64.3500s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61890 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35986 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.3510s] nsock_iod_delete(): nsock_iod_delete (IOD #1935)
NSOCK INFO [64.3510s] nsock_iod_new2(): nsock_iod_new (IOD #1936)
NSOCK INFO [64.3510s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1936) EID 61896
NSOCK INFO [64.3640s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61896 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35994 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:35994 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6f 73 74 67 72 65 73 2f 20 48 GET /postgres/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [64.3650s] nsock_write(): Write request for 180 bytes to IOD #1936 EID 61907 [88.255.216.16:80]
NSOCK INFO [64.3650s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61907 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35994 > 88.255.216.16:80 | SEND
NSOCK INFO [64.3660s] nsock_read(): Read request from IOD #1936 [88.255.216.16:80] (timeout: 10000ms) EID 61914
NSOCK INFO [64.3780s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61914 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:35994 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.3790s] nsock_read(): Read request from IOD #1936 [88.255.216.16:80] (timeout: 10000ms) EID 61922
NSOCK INFO [64.3790s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61922 [88.255.216.16:80]
NSE: TCP 192.168.31.147:35994 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.3800s] nsock_iod_delete(): nsock_iod_delete (IOD #1936)
NSOCK INFO [64.3800s] nsock_iod_new2(): nsock_iod_new (IOD #1937)
NSOCK INFO [64.3800s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1937) EID 61928
NSOCK INFO [64.3940s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61928 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36008 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36008 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 6f 73 74 6e 75 6b 65 2f 20 48 GET /postnuke/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [64.3950s] nsock_write(): Write request for 180 bytes to IOD #1937 EID 61939 [88.255.216.16:80]
NSOCK INFO [64.3950s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61939 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36008 > 88.255.216.16:80 | SEND
NSOCK INFO [64.3960s] nsock_read(): Read request from IOD #1937 [88.255.216.16:80] (timeout: 10000ms) EID 61946
NSOCK INFO [64.4080s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61946 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36008 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.4100s] nsock_read(): Read request from IOD #1937 [88.255.216.16:80] (timeout: 10000ms) EID 61954
NSOCK INFO [64.4100s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61954 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36008 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.4110s] nsock_iod_delete(): nsock_iod_delete (IOD #1937)
NSOCK INFO [64.4110s] nsock_iod_new2(): nsock_iod_new (IOD #1938)
NSOCK INFO [64.4110s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1938) EID 61960
NSOCK INFO [64.4250s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61960 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36018 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36018 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 70 77 62 2f 20 48 54 54 50 2f GET /ppwb/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [64.4250s] nsock_write(): Write request for 176 bytes to IOD #1938 EID 61971 [88.255.216.16:80]
NSOCK INFO [64.4250s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 61971 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36018 > 88.255.216.16:80 | SEND
NSOCK INFO [64.4260s] nsock_read(): Read request from IOD #1938 [88.255.216.16:80] (timeout: 10000ms) EID 61978
NSOCK INFO [64.4390s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 61978 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36018 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.4400s] nsock_read(): Read request from IOD #1938 [88.255.216.16:80] (timeout: 10000ms) EID 61986
NSOCK INFO [64.4400s] nsock_trace_handler_callback(): Callback: READ EOF for EID 61986 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36018 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.4400s] nsock_iod_delete(): nsock_iod_delete (IOD #1938)
NSOCK INFO [64.4400s] nsock_iod_new2(): nsock_iod_new (IOD #1939)
NSOCK INFO [64.4400s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1939) EID 61992
NSOCK INFO [64.4540s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 61992 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36020 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36020 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 69 6e 74 65 72 2f 20 48 54 GET /printer/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.4550s] nsock_write(): Write request for 179 bytes to IOD #1939 EID 62003 [88.255.216.16:80]
NSOCK INFO [64.4550s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62003 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36020 > 88.255.216.16:80 | SEND
NSOCK INFO [64.4560s] nsock_read(): Read request from IOD #1939 [88.255.216.16:80] (timeout: 10000ms) EID 62010
NSOCK INFO [64.4680s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62010 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36020 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.4690s] nsock_read(): Read request from IOD #1939 [88.255.216.16:80] (timeout: 10000ms) EID 62018
NSOCK INFO [64.4690s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62018 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36020 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.4700s] nsock_iod_delete(): nsock_iod_delete (IOD #1939)
NSOCK INFO [64.4700s] nsock_iod_new2(): nsock_iod_new (IOD #1940)
NSOCK INFO [64.4700s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1940) EID 62024
NSOCK INFO [64.4830s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62024 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36030 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36030 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 69 6e 74 65 72 73 2f 20 48 GET /printers/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [64.4860s] nsock_write(): Write request for 180 bytes to IOD #1940 EID 62035 [88.255.216.16:80]
NSOCK INFO [64.4860s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62035 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36030 > 88.255.216.16:80 | SEND
NSOCK INFO [64.4860s] nsock_read(): Read request from IOD #1940 [88.255.216.16:80] (timeout: 10000ms) EID 62042
NSOCK INFO [64.5000s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62042 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36030 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.5010s] nsock_read(): Read request from IOD #1940 [88.255.216.16:80] (timeout: 10000ms) EID 62050
NSOCK INFO [64.5010s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62050 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36030 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.5010s] nsock_iod_delete(): nsock_iod_delete (IOD #1940)
NSOCK INFO [64.5010s] nsock_iod_new2(): nsock_iod_new (IOD #1941)
NSOCK INFO [64.5010s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1941) EID 62056
NSOCK INFO [64.5150s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62056 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36046 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36046 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 69 76 61 63 79 2f 20 48 54 GET /privacy/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.5160s] nsock_write(): Write request for 179 bytes to IOD #1941 EID 62067 [88.255.216.16:80]
NSOCK INFO [64.5160s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62067 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36046 > 88.255.216.16:80 | SEND
NSOCK INFO [64.5160s] nsock_read(): Read request from IOD #1941 [88.255.216.16:80] (timeout: 10000ms) EID 62074
NSOCK INFO [64.5290s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62074 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36046 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.5300s] nsock_read(): Read request from IOD #1941 [88.255.216.16:80] (timeout: 10000ms) EID 62082
NSOCK INFO [64.5300s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62082 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36046 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.5310s] nsock_iod_delete(): nsock_iod_delete (IOD #1941)
NSOCK INFO [64.5310s] nsock_iod_new2(): nsock_iod_new (IOD #1942)
NSOCK INFO [64.5310s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1942) EID 62088
NSOCK INFO [64.5440s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62088 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36054 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36054 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 69 76 61 64 6f 2f 20 48 54 GET /privado/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.5440s] nsock_write(): Write request for 179 bytes to IOD #1942 EID 62099 [88.255.216.16:80]
NSOCK INFO [64.5440s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62099 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36054 > 88.255.216.16:80 | SEND
NSOCK INFO [64.5450s] nsock_read(): Read request from IOD #1942 [88.255.216.16:80] (timeout: 10000ms) EID 62106
NSOCK INFO [64.5580s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62106 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36054 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.5580s] nsock_read(): Read request from IOD #1942 [88.255.216.16:80] (timeout: 10000ms) EID 62114
NSOCK INFO [64.5580s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62114 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36054 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.5590s] nsock_iod_delete(): nsock_iod_delete (IOD #1942)
NSOCK INFO [64.5590s] nsock_iod_new2(): nsock_iod_new (IOD #1943)
NSOCK INFO [64.5590s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1943) EID 62120
NSOCK INFO [64.5720s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62120 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36062 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36062 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 5f 70 72 69 76 61 74 65 2f 20 48 GET /_private/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [64.5730s] nsock_write(): Write request for 180 bytes to IOD #1943 EID 62131 [88.255.216.16:80]
NSOCK INFO [64.5730s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62131 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36062 > 88.255.216.16:80 | SEND
NSOCK INFO [64.5730s] nsock_read(): Read request from IOD #1943 [88.255.216.16:80] (timeout: 10000ms) EID 62138
NSOCK INFO [64.5860s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62138 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36062 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.5870s] nsock_read(): Read request from IOD #1943 [88.255.216.16:80] (timeout: 10000ms) EID 62146
NSOCK INFO [64.5870s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62146 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36062 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.5870s] nsock_iod_delete(): nsock_iod_delete (IOD #1943)
NSOCK INFO [64.5870s] nsock_iod_new2(): nsock_iod_new (IOD #1944)
NSOCK INFO [64.5870s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1944) EID 62152
NSOCK INFO [64.6010s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62152 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36078 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36078 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 69 76 61 74 65 2f 20 48 54 GET /private/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.6010s] nsock_write(): Write request for 179 bytes to IOD #1944 EID 62163 [88.255.216.16:80]
NSOCK INFO [64.6010s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62163 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36078 > 88.255.216.16:80 | SEND
NSOCK INFO [64.6020s] nsock_read(): Read request from IOD #1944 [88.255.216.16:80] (timeout: 10000ms) EID 62170
NSOCK INFO [64.6150s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62170 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36078 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.6150s] nsock_read(): Read request from IOD #1944 [88.255.216.16:80] (timeout: 10000ms) EID 62178
NSOCK INFO [64.6150s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62178 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36078 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.6160s] nsock_iod_delete(): nsock_iod_delete (IOD #1944)
NSOCK INFO [64.6160s] nsock_iod_new2(): nsock_iod_new (IOD #1945)
NSOCK INFO [64.6160s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1945) EID 62184
NSOCK INFO [64.6290s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62184 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36092 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36092 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 69 76 2f 20 48 54 54 50 2f GET /priv/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [64.6310s] nsock_write(): Write request for 176 bytes to IOD #1945 EID 62195 [88.255.216.16:80]
NSOCK INFO [64.6310s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62195 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36092 > 88.255.216.16:80 | SEND
NSOCK INFO [64.6320s] nsock_read(): Read request from IOD #1945 [88.255.216.16:80] (timeout: 10000ms) EID 62202
NSOCK INFO [64.6440s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62202 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36092 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.6460s] nsock_read(): Read request from IOD #1945 [88.255.216.16:80] (timeout: 10000ms) EID 62210
NSOCK INFO [64.6460s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62210 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36092 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.6470s] nsock_iod_delete(): nsock_iod_delete (IOD #1945)
NSOCK INFO [64.6470s] nsock_iod_new2(): nsock_iod_new (IOD #1946)
NSOCK INFO [64.6470s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1946) EID 62216
NSOCK INFO [64.6610s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62216 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36098 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36098 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 6f 64 2f 20 48 54 54 50 2f GET /prod/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [64.6620s] nsock_write(): Write request for 176 bytes to IOD #1946 EID 62227 [88.255.216.16:80]
NSOCK INFO [64.6620s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62227 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36098 > 88.255.216.16:80 | SEND
NSOCK INFO [64.6630s] nsock_read(): Read request from IOD #1946 [88.255.216.16:80] (timeout: 10000ms) EID 62234
NSOCK INFO [64.6760s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62234 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36098 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.6780s] nsock_read(): Read request from IOD #1946 [88.255.216.16:80] (timeout: 10000ms) EID 62242
NSOCK INFO [64.6780s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62242 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36098 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.6780s] nsock_iod_delete(): nsock_iod_delete (IOD #1946)
NSOCK INFO [64.6780s] nsock_iod_new2(): nsock_iod_new (IOD #1947)
NSOCK INFO [64.6780s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1947) EID 62248
NSOCK INFO [64.6910s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62248 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36104 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36104 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 6f 6a 65 63 74 73 65 72 76 GET /projectserv
00000010: 65 72 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f er/ HTTP/1.1  Ho
00000020: 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 st: 88.255.216.1
00000030: 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6.static.ttnet.c
00000040: 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e om.tr  User-Agen
00000050: 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 t: Mozilla/5.0 (
00000060: 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 compatible; Nmap
00000070: 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e  Scripting Engin
00000080: 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e e; https://nmap.
00000090: 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d org/book/nse.htm
000000a0: 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 l)  Connection: 
000000b0: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.6920s] nsock_write(): Write request for 185 bytes to IOD #1947 EID 62259 [88.255.216.16:80]
NSOCK INFO [64.6920s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62259 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36104 > 88.255.216.16:80 | SEND
NSOCK INFO [64.6930s] nsock_read(): Read request from IOD #1947 [88.255.216.16:80] (timeout: 10000ms) EID 62266
NSOCK INFO [64.7050s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62266 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36104 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.7050s] nsock_read(): Read request from IOD #1947 [88.255.216.16:80] (timeout: 10000ms) EID 62274
NSOCK INFO [64.7050s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62274 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36104 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.7060s] nsock_iod_delete(): nsock_iod_delete (IOD #1947)
NSOCK INFO [64.7060s] nsock_iod_new2(): nsock_iod_new (IOD #1948)
NSOCK INFO [64.7060s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1948) EID 62280
NSOCK INFO [64.7190s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62280 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36110 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36110 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 6f 74 65 63 74 65 64 2f 20 GET /protected/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [64.7210s] nsock_write(): Write request for 181 bytes to IOD #1948 EID 62291 [88.255.216.16:80]
NSOCK INFO [64.7210s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62291 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36110 > 88.255.216.16:80 | SEND
NSOCK INFO [64.7220s] nsock_read(): Read request from IOD #1948 [88.255.216.16:80] (timeout: 10000ms) EID 62298
NSOCK INFO [64.7340s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62298 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36110 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.7350s] nsock_read(): Read request from IOD #1948 [88.255.216.16:80] (timeout: 10000ms) EID 62306
NSOCK INFO [64.7350s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62306 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36110 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.7350s] nsock_iod_delete(): nsock_iod_delete (IOD #1948)
NSOCK INFO [64.7350s] nsock_iod_new2(): nsock_iod_new (IOD #1949)
NSOCK INFO [64.7350s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1949) EID 62312
NSOCK INFO [64.7490s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62312 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36112 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36112 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 6f 78 79 2f 20 48 54 54 50 GET /proxy/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [64.7520s] nsock_write(): Write request for 177 bytes to IOD #1949 EID 62323 [88.255.216.16:80]
NSOCK INFO [64.7520s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62323 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36112 > 88.255.216.16:80 | SEND
NSOCK INFO [64.7520s] nsock_read(): Read request from IOD #1949 [88.255.216.16:80] (timeout: 10000ms) EID 62330
NSOCK INFO [64.7650s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62330 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36112 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.7660s] nsock_read(): Read request from IOD #1949 [88.255.216.16:80] (timeout: 10000ms) EID 62338
NSOCK INFO [64.7660s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62338 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36112 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.7660s] nsock_iod_delete(): nsock_iod_delete (IOD #1949)
NSOCK INFO [64.7660s] nsock_iod_new2(): nsock_iod_new (IOD #1950)
NSOCK INFO [64.7670s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1950) EID 62344
NSOCK INFO [64.7800s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62344 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36120 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36120 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 75 65 62 61 2f 20 48 54 54 GET /prueba/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [64.7810s] nsock_write(): Write request for 178 bytes to IOD #1950 EID 62355 [88.255.216.16:80]
NSOCK INFO [64.7810s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62355 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36120 > 88.255.216.16:80 | SEND
NSOCK INFO [64.7820s] nsock_read(): Read request from IOD #1950 [88.255.216.16:80] (timeout: 10000ms) EID 62362
NSOCK INFO [64.7940s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62362 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36120 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.7950s] nsock_read(): Read request from IOD #1950 [88.255.216.16:80] (timeout: 10000ms) EID 62370
NSOCK INFO [64.7950s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62370 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36120 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.7950s] nsock_iod_delete(): nsock_iod_delete (IOD #1950)
NSOCK INFO [64.7950s] nsock_iod_new2(): nsock_iod_new (IOD #1951)
NSOCK INFO [64.7950s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1951) EID 62376
NSOCK INFO [64.8080s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62376 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36126 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36126 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 75 65 62 61 73 2f 20 48 54 GET /pruebas/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.8090s] nsock_write(): Write request for 179 bytes to IOD #1951 EID 62387 [88.255.216.16:80]
NSOCK INFO [64.8090s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62387 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36126 > 88.255.216.16:80 | SEND
NSOCK INFO [64.8100s] nsock_read(): Read request from IOD #1951 [88.255.216.16:80] (timeout: 10000ms) EID 62394
NSOCK INFO [64.8220s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62394 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36126 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.8240s] nsock_read(): Read request from IOD #1951 [88.255.216.16:80] (timeout: 10000ms) EID 62402
NSOCK INFO [64.8240s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62402 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36126 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.8240s] nsock_iod_delete(): nsock_iod_delete (IOD #1951)
NSOCK INFO [64.8240s] nsock_iod_new2(): nsock_iod_new (IOD #1952)
NSOCK INFO [64.8250s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1952) EID 62408
NSOCK INFO [64.8380s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62408 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36128 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36128 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 72 76 2f 20 48 54 54 50 2f 31 GET /prv/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [64.8390s] nsock_write(): Write request for 175 bytes to IOD #1952 EID 62419 [88.255.216.16:80]
NSOCK INFO [64.8390s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62419 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36128 > 88.255.216.16:80 | SEND
NSOCK INFO [64.8390s] nsock_read(): Read request from IOD #1952 [88.255.216.16:80] (timeout: 10000ms) EID 62426
NSOCK INFO [64.8530s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62426 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36128 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.8530s] nsock_read(): Read request from IOD #1952 [88.255.216.16:80] (timeout: 10000ms) EID 62434
NSOCK INFO [64.8530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62434 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36128 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.8540s] nsock_iod_delete(): nsock_iod_delete (IOD #1952)
NSOCK INFO [64.8540s] nsock_iod_new2(): nsock_iod_new (IOD #1953)
NSOCK INFO [64.8540s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1953) EID 62440
NSOCK INFO [64.8680s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62440 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36132 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36132 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 62 2f 20 48 54 54 50 2f 31 GET /pub/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [64.8690s] nsock_write(): Write request for 175 bytes to IOD #1953 EID 62451 [88.255.216.16:80]
NSOCK INFO [64.8690s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62451 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36132 > 88.255.216.16:80 | SEND
NSOCK INFO [64.8690s] nsock_read(): Read request from IOD #1953 [88.255.216.16:80] (timeout: 10000ms) EID 62458
NSOCK INFO [64.8820s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62458 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36132 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.8830s] nsock_read(): Read request from IOD #1953 [88.255.216.16:80] (timeout: 10000ms) EID 62466
NSOCK INFO [64.8830s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62466 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36132 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.8840s] nsock_iod_delete(): nsock_iod_delete (IOD #1953)
NSOCK INFO [64.8840s] nsock_iod_new2(): nsock_iod_new (IOD #1954)
NSOCK INFO [64.8850s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1954) EID 62472
NSOCK INFO [64.8980s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62472 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36136 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36136 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 5f 70 75 62 6c 69 63 2f 20 48 54 GET /_public/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.9000s] nsock_write(): Write request for 179 bytes to IOD #1954 EID 62483 [88.255.216.16:80]
NSOCK INFO [64.9000s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62483 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36136 > 88.255.216.16:80 | SEND
NSOCK INFO [64.9010s] nsock_read(): Read request from IOD #1954 [88.255.216.16:80] (timeout: 10000ms) EID 62490
NSOCK INFO [64.9180s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62490 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36136 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.9180s] nsock_read(): Read request from IOD #1954 [88.255.216.16:80] (timeout: 10000ms) EID 62498
NSOCK INFO [64.9180s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62498 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36136 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.9190s] nsock_iod_delete(): nsock_iod_delete (IOD #1954)
NSOCK INFO [64.9190s] nsock_iod_new2(): nsock_iod_new (IOD #1955)
NSOCK INFO [64.9190s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1955) EID 62504
NSOCK INFO [64.9320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62504 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36138 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36138 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 62 6c 69 63 2f 20 48 54 54 GET /public/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [64.9330s] nsock_write(): Write request for 178 bytes to IOD #1955 EID 62515 [88.255.216.16:80]
NSOCK INFO [64.9330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62515 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36138 > 88.255.216.16:80 | SEND
NSOCK INFO [64.9350s] nsock_read(): Read request from IOD #1955 [88.255.216.16:80] (timeout: 10000ms) EID 62522
NSOCK INFO [64.9470s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62522 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36138 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.9480s] nsock_read(): Read request from IOD #1955 [88.255.216.16:80] (timeout: 10000ms) EID 62530
NSOCK INFO [64.9480s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62530 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36138 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.9480s] nsock_iod_delete(): nsock_iod_delete (IOD #1955)
NSOCK INFO [64.9480s] nsock_iod_new2(): nsock_iod_new (IOD #1956)
NSOCK INFO [64.9480s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1956) EID 62536
NSOCK INFO [64.9620s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62536 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36142 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36142 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 62 6c 69 63 61 2f 20 48 54 GET /publica/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [64.9630s] nsock_write(): Write request for 179 bytes to IOD #1956 EID 62547 [88.255.216.16:80]
NSOCK INFO [64.9630s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62547 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36142 > 88.255.216.16:80 | SEND
NSOCK INFO [64.9630s] nsock_read(): Read request from IOD #1956 [88.255.216.16:80] (timeout: 10000ms) EID 62554
NSOCK INFO [64.9750s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62554 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36142 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [64.9770s] nsock_read(): Read request from IOD #1956 [88.255.216.16:80] (timeout: 10000ms) EID 62562
NSOCK INFO [64.9770s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62562 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36142 > 88.255.216.16:80 | CLOSE
NSOCK INFO [64.9770s] nsock_iod_delete(): nsock_iod_delete (IOD #1956)
NSOCK INFO [64.9770s] nsock_iod_new2(): nsock_iod_new (IOD #1957)
NSOCK INFO [64.9780s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1957) EID 62568
NSOCK INFO [64.9910s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62568 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36158 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36158 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 62 6c 69 63 61 72 2f 20 48 GET /publicar/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [64.9920s] nsock_write(): Write request for 180 bytes to IOD #1957 EID 62579 [88.255.216.16:80]
NSOCK INFO [64.9920s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62579 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36158 > 88.255.216.16:80 | SEND
NSOCK INFO [64.9930s] nsock_read(): Read request from IOD #1957 [88.255.216.16:80] (timeout: 10000ms) EID 62586
NSOCK INFO [65.0050s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62586 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36158 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.0060s] nsock_read(): Read request from IOD #1957 [88.255.216.16:80] (timeout: 10000ms) EID 62594
NSOCK INFO [65.0060s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62594 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36158 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.0070s] nsock_iod_delete(): nsock_iod_delete (IOD #1957)
NSOCK INFO [65.0070s] nsock_iod_new2(): nsock_iod_new (IOD #1958)
NSOCK INFO [65.0070s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1958) EID 62600
NSOCK INFO [65.0200s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62600 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36168 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36168 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 62 6c 69 63 6f 2f 20 48 54 GET /publico/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [65.0210s] nsock_write(): Write request for 179 bytes to IOD #1958 EID 62611 [88.255.216.16:80]
NSOCK INFO [65.0210s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62611 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36168 > 88.255.216.16:80 | SEND
NSOCK INFO [65.0230s] nsock_read(): Read request from IOD #1958 [88.255.216.16:80] (timeout: 10000ms) EID 62618
NSOCK INFO [65.0350s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62618 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36168 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.0360s] nsock_read(): Read request from IOD #1958 [88.255.216.16:80] (timeout: 10000ms) EID 62626
NSOCK INFO [65.0360s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62626 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36168 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.0360s] nsock_iod_delete(): nsock_iod_delete (IOD #1958)
NSOCK INFO [65.0360s] nsock_iod_new2(): nsock_iod_new (IOD #1959)
NSOCK INFO [65.0370s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1959) EID 62632
NSOCK INFO [65.0500s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62632 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36170 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36170 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 62 6c 69 73 68 2f 20 48 54 GET /publish/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [65.0510s] nsock_write(): Write request for 179 bytes to IOD #1959 EID 62643 [88.255.216.16:80]
NSOCK INFO [65.0510s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62643 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36170 > 88.255.216.16:80 | SEND
NSOCK INFO [65.0520s] nsock_read(): Read request from IOD #1959 [88.255.216.16:80] (timeout: 10000ms) EID 62650
NSOCK INFO [65.0650s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62650 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36170 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.0660s] nsock_read(): Read request from IOD #1959 [88.255.216.16:80] (timeout: 10000ms) EID 62658
NSOCK INFO [65.0660s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62658 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36170 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.0670s] nsock_iod_delete(): nsock_iod_delete (IOD #1959)
NSOCK INFO [65.0670s] nsock_iod_new2(): nsock_iod_new (IOD #1960)
NSOCK INFO [65.0680s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1960) EID 62664
NSOCK INFO [65.0810s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62664 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36180 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36180 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 72 63 68 61 73 65 2f 20 48 GET /purchase/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [65.0820s] nsock_write(): Write request for 180 bytes to IOD #1960 EID 62675 [88.255.216.16:80]
NSOCK INFO [65.0820s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62675 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36180 > 88.255.216.16:80 | SEND
NSOCK INFO [65.0830s] nsock_read(): Read request from IOD #1960 [88.255.216.16:80] (timeout: 10000ms) EID 62682
NSOCK INFO [65.0960s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62682 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36180 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.0980s] nsock_read(): Read request from IOD #1960 [88.255.216.16:80] (timeout: 10000ms) EID 62690
NSOCK INFO [65.0980s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62690 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36180 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.0980s] nsock_iod_delete(): nsock_iod_delete (IOD #1960)
NSOCK INFO [65.0980s] nsock_iod_new2(): nsock_iod_new (IOD #1961)
NSOCK INFO [65.0980s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1961) EID 62696
NSOCK INFO [65.1120s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62696 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36186 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36186 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 75 72 63 68 61 73 65 73 2f 20 GET /purchases/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [65.1130s] nsock_write(): Write request for 181 bytes to IOD #1961 EID 62707 [88.255.216.16:80]
NSOCK INFO [65.1130s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62707 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36186 > 88.255.216.16:80 | SEND
NSOCK INFO [65.1130s] nsock_read(): Read request from IOD #1961 [88.255.216.16:80] (timeout: 10000ms) EID 62714
NSOCK INFO [65.1260s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62714 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36186 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.1270s] nsock_read(): Read request from IOD #1961 [88.255.216.16:80] (timeout: 10000ms) EID 62722
NSOCK INFO [65.1270s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62722 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36186 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.1280s] nsock_iod_delete(): nsock_iod_delete (IOD #1961)
NSOCK INFO [65.1280s] nsock_iod_new2(): nsock_iod_new (IOD #1962)
NSOCK INFO [65.1280s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1962) EID 62728
NSOCK INFO [65.1410s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62728 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36190 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36190 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 77 2f 20 48 54 54 50 2f 31 2e GET /pw/ HTTP/1.
00000010: 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 2e 1  Host: 88.255.
00000020: 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 74 216.16.static.tt
00000030: 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 net.com.tr  User
00000040: 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f -Agent: Mozilla/
00000050: 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 3b 5.0 (compatible;
00000060: 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 20  Nmap Scripting 
00000070: 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f 2f Engine; https://
00000080: 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 nmap.org/book/ns
00000090: 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 e.html)  Connect
000000a0: 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a       ion: close    

NSOCK INFO [65.1420s] nsock_write(): Write request for 174 bytes to IOD #1962 EID 62739 [88.255.216.16:80]
NSOCK INFO [65.1420s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62739 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36190 > 88.255.216.16:80 | SEND
NSOCK INFO [65.1440s] nsock_read(): Read request from IOD #1962 [88.255.216.16:80] (timeout: 10000ms) EID 62746
NSOCK INFO [65.1550s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62746 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36190 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.1560s] nsock_read(): Read request from IOD #1962 [88.255.216.16:80] (timeout: 10000ms) EID 62754
NSOCK INFO [65.1560s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62754 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36190 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.1560s] nsock_iod_delete(): nsock_iod_delete (IOD #1962)
NSOCK INFO [65.1560s] nsock_iod_new2(): nsock_iod_new (IOD #1963)
NSOCK INFO [65.1560s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1963) EID 62760
NSOCK INFO [65.1710s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62760 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36200 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36200 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 70 79 74 68 6f 6e 2f 20 48 54 54 GET /python/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.1720s] nsock_write(): Write request for 178 bytes to IOD #1963 EID 62771 [88.255.216.16:80]
NSOCK INFO [65.1720s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62771 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36200 > 88.255.216.16:80 | SEND
NSOCK INFO [65.1730s] nsock_read(): Read request from IOD #1963 [88.255.216.16:80] (timeout: 10000ms) EID 62778
NSOCK INFO [65.1850s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62778 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36200 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.1860s] nsock_read(): Read request from IOD #1963 [88.255.216.16:80] (timeout: 10000ms) EID 62786
NSOCK INFO [65.1860s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62786 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36200 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.1870s] nsock_iod_delete(): nsock_iod_delete (IOD #1963)
NSOCK INFO [65.1870s] nsock_iod_new2(): nsock_iod_new (IOD #1964)
NSOCK INFO [65.1870s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1964) EID 62792
NSOCK INFO [65.2000s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62792 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36204 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36204 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 61 6e 64 6f 6d 5f 62 61 6e 6e GET /random_bann
00000010: 65 72 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f er/ HTTP/1.1  Ho
00000020: 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 st: 88.255.216.1
00000030: 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6.static.ttnet.c
00000040: 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e om.tr  User-Agen
00000050: 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 t: Mozilla/5.0 (
00000060: 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 compatible; Nmap
00000070: 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e  Scripting Engin
00000080: 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e e; https://nmap.
00000090: 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d org/book/nse.htm
000000a0: 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 l)  Connection: 
000000b0: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.2020s] nsock_write(): Write request for 185 bytes to IOD #1964 EID 62803 [88.255.216.16:80]
NSOCK INFO [65.2020s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62803 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36204 > 88.255.216.16:80 | SEND
NSOCK INFO [65.2030s] nsock_read(): Read request from IOD #1964 [88.255.216.16:80] (timeout: 10000ms) EID 62810
NSOCK INFO [65.2160s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62810 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36204 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.2170s] nsock_read(): Read request from IOD #1964 [88.255.216.16:80] (timeout: 10000ms) EID 62818
NSOCK INFO [65.2170s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62818 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36204 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.2190s] nsock_iod_delete(): nsock_iod_delete (IOD #1964)
NSOCK INFO [65.2190s] nsock_iod_new2(): nsock_iod_new (IOD #1965)
NSOCK INFO [65.2190s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1965) EID 62824
NSOCK INFO [65.2320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62824 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36210 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36210 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 64 70 2f 20 48 54 54 50 2f 31 GET /rdp/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [65.2330s] nsock_write(): Write request for 175 bytes to IOD #1965 EID 62835 [88.255.216.16:80]
NSOCK INFO [65.2330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62835 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36210 > 88.255.216.16:80 | SEND
NSOCK INFO [65.2330s] nsock_read(): Read request from IOD #1965 [88.255.216.16:80] (timeout: 10000ms) EID 62842
NSOCK INFO [65.2470s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62842 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36210 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.2480s] nsock_read(): Read request from IOD #1965 [88.255.216.16:80] (timeout: 10000ms) EID 62850
NSOCK INFO [65.2480s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62850 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36210 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.2480s] nsock_iod_delete(): nsock_iod_delete (IOD #1965)
NSOCK INFO [65.2480s] nsock_iod_new2(): nsock_iod_new (IOD #1966)
NSOCK INFO [65.2490s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1966) EID 62856
NSOCK INFO [65.2620s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62856 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36218 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36218 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 52 65 61 64 6d 65 2f 20 48 54 54 GET /Readme/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.2640s] nsock_write(): Write request for 178 bytes to IOD #1966 EID 62867 [88.255.216.16:80]
NSOCK INFO [65.2640s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62867 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36218 > 88.255.216.16:80 | SEND
NSOCK INFO [65.2650s] nsock_read(): Read request from IOD #1966 [88.255.216.16:80] (timeout: 10000ms) EID 62874
NSOCK INFO [65.2770s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62874 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36218 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.2790s] nsock_read(): Read request from IOD #1966 [88.255.216.16:80] (timeout: 10000ms) EID 62882
NSOCK INFO [65.2790s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62882 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36218 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.2800s] nsock_iod_delete(): nsock_iod_delete (IOD #1966)
NSOCK INFO [65.2800s] nsock_iod_new2(): nsock_iod_new (IOD #1967)
NSOCK INFO [65.2810s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1967) EID 62888
NSOCK INFO [65.2940s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62888 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36220 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36220 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 63 79 63 6c 65 72 2f 20 48 GET /recycler/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [65.2950s] nsock_write(): Write request for 180 bytes to IOD #1967 EID 62899 [88.255.216.16:80]
NSOCK INFO [65.2950s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62899 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36220 > 88.255.216.16:80 | SEND
NSOCK INFO [65.2960s] nsock_read(): Read request from IOD #1967 [88.255.216.16:80] (timeout: 10000ms) EID 62906
NSOCK INFO [65.3080s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62906 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36220 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.3090s] nsock_read(): Read request from IOD #1967 [88.255.216.16:80] (timeout: 10000ms) EID 62914
NSOCK INFO [65.3090s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62914 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36220 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.3090s] nsock_iod_delete(): nsock_iod_delete (IOD #1967)
NSOCK INFO [65.3090s] nsock_iod_new2(): nsock_iod_new (IOD #1968)
NSOCK INFO [65.3090s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1968) EID 62920
NSOCK INFO [65.3220s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62920 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36226 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36226 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 67 69 73 74 65 72 65 64 2f GET /registered/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [65.3240s] nsock_write(): Write request for 182 bytes to IOD #1968 EID 62931 [88.255.216.16:80]
NSOCK INFO [65.3240s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62931 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36226 > 88.255.216.16:80 | SEND
NSOCK INFO [65.3250s] nsock_read(): Read request from IOD #1968 [88.255.216.16:80] (timeout: 10000ms) EID 62938
NSOCK INFO [65.3370s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62938 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36226 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.3380s] nsock_read(): Read request from IOD #1968 [88.255.216.16:80] (timeout: 10000ms) EID 62946
NSOCK INFO [65.3380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62946 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36226 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.3380s] nsock_iod_delete(): nsock_iod_delete (IOD #1968)
NSOCK INFO [65.3380s] nsock_iod_new2(): nsock_iod_new (IOD #1969)
NSOCK INFO [65.3390s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1969) EID 62952
NSOCK INFO [65.3520s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62952 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36236 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36236 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 67 69 73 74 65 72 2f 20 48 GET /register/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [65.3530s] nsock_write(): Write request for 180 bytes to IOD #1969 EID 62963 [88.255.216.16:80]
NSOCK INFO [65.3530s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62963 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36236 > 88.255.216.16:80 | SEND
NSOCK INFO [65.3540s] nsock_read(): Read request from IOD #1969 [88.255.216.16:80] (timeout: 10000ms) EID 62970
NSOCK INFO [65.3670s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 62970 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36236 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.3680s] nsock_read(): Read request from IOD #1969 [88.255.216.16:80] (timeout: 10000ms) EID 62978
NSOCK INFO [65.3680s] nsock_trace_handler_callback(): Callback: READ EOF for EID 62978 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36236 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.3690s] nsock_iod_delete(): nsock_iod_delete (IOD #1969)
NSOCK INFO [65.3690s] nsock_iod_new2(): nsock_iod_new (IOD #1970)
NSOCK INFO [65.3690s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1970) EID 62984
NSOCK INFO [65.3830s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 62984 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36246 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36246 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 67 69 73 74 72 79 2f 20 48 GET /registry/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [65.3840s] nsock_write(): Write request for 180 bytes to IOD #1970 EID 62995 [88.255.216.16:80]
NSOCK INFO [65.3840s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 62995 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36246 > 88.255.216.16:80 | SEND
NSOCK INFO [65.3850s] nsock_read(): Read request from IOD #1970 [88.255.216.16:80] (timeout: 10000ms) EID 63002
NSOCK INFO [65.3970s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63002 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36246 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.3980s] nsock_read(): Read request from IOD #1970 [88.255.216.16:80] (timeout: 10000ms) EID 63010
NSOCK INFO [65.3980s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63010 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36246 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.3990s] nsock_iod_delete(): nsock_iod_delete (IOD #1970)
NSOCK INFO [65.3990s] nsock_iod_new2(): nsock_iod_new (IOD #1971)
NSOCK INFO [65.3990s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1971) EID 63016
NSOCK INFO [65.4120s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63016 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36254 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36254 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 6d 6f 74 65 2f 20 48 54 54 GET /remote/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.4130s] nsock_write(): Write request for 178 bytes to IOD #1971 EID 63027 [88.255.216.16:80]
NSOCK INFO [65.4130s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63027 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36254 > 88.255.216.16:80 | SEND
NSOCK INFO [65.4140s] nsock_read(): Read request from IOD #1971 [88.255.216.16:80] (timeout: 10000ms) EID 63034
NSOCK INFO [65.4270s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63034 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36254 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.4280s] nsock_read(): Read request from IOD #1971 [88.255.216.16:80] (timeout: 10000ms) EID 63042
NSOCK INFO [65.4280s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63042 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36254 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.4280s] nsock_iod_delete(): nsock_iod_delete (IOD #1971)
NSOCK INFO [65.4280s] nsock_iod_new2(): nsock_iod_new (IOD #1972)
NSOCK INFO [65.4280s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1972) EID 63048
NSOCK INFO [65.4410s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63048 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36264 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36264 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 6d 6f 76 65 2f 20 48 54 54 GET /remove/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.4420s] nsock_write(): Write request for 178 bytes to IOD #1972 EID 63059 [88.255.216.16:80]
NSOCK INFO [65.4420s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63059 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36264 > 88.255.216.16:80 | SEND
NSOCK INFO [65.4420s] nsock_read(): Read request from IOD #1972 [88.255.216.16:80] (timeout: 10000ms) EID 63066
NSOCK INFO [65.4550s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63066 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36264 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.4570s] nsock_read(): Read request from IOD #1972 [88.255.216.16:80] (timeout: 10000ms) EID 63074
NSOCK INFO [65.4570s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63074 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36264 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.4570s] nsock_iod_delete(): nsock_iod_delete (IOD #1972)
NSOCK INFO [65.4570s] nsock_iod_new2(): nsock_iod_new (IOD #1973)
NSOCK INFO [65.4580s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1973) EID 63080
NSOCK INFO [65.4710s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63080 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36266 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36266 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 70 6f 72 74 2f 20 48 54 54 GET /report/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.4720s] nsock_write(): Write request for 178 bytes to IOD #1973 EID 63091 [88.255.216.16:80]
NSOCK INFO [65.4720s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63091 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36266 > 88.255.216.16:80 | SEND
NSOCK INFO [65.4730s] nsock_read(): Read request from IOD #1973 [88.255.216.16:80] (timeout: 10000ms) EID 63098
NSOCK INFO [65.4850s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63098 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36266 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.4860s] nsock_read(): Read request from IOD #1973 [88.255.216.16:80] (timeout: 10000ms) EID 63106
NSOCK INFO [65.4860s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63106 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36266 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.4870s] nsock_iod_delete(): nsock_iod_delete (IOD #1973)
NSOCK INFO [65.4870s] nsock_iod_new2(): nsock_iod_new (IOD #1974)
NSOCK INFO [65.4870s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1974) EID 63112
NSOCK INFO [65.5000s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63112 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36274 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36274 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 70 6f 72 74 73 2f 20 48 54 GET /reports/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [65.5010s] nsock_write(): Write request for 179 bytes to IOD #1974 EID 63123 [88.255.216.16:80]
NSOCK INFO [65.5010s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63123 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36274 > 88.255.216.16:80 | SEND
NSOCK INFO [65.5020s] nsock_read(): Read request from IOD #1974 [88.255.216.16:80] (timeout: 10000ms) EID 63130
NSOCK INFO [65.5150s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63130 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36274 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.5170s] nsock_read(): Read request from IOD #1974 [88.255.216.16:80] (timeout: 10000ms) EID 63138
NSOCK INFO [65.5170s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63138 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36274 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.5180s] nsock_iod_delete(): nsock_iod_delete (IOD #1974)
NSOCK INFO [65.5180s] nsock_iod_new2(): nsock_iod_new (IOD #1975)
NSOCK INFO [65.5180s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1975) EID 63144
NSOCK INFO [65.5320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63144 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36284 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36284 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 73 65 6c 6c 65 72 2f 20 48 GET /reseller/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [65.5330s] nsock_write(): Write request for 180 bytes to IOD #1975 EID 63155 [88.255.216.16:80]
NSOCK INFO [65.5330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63155 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36284 > 88.255.216.16:80 | SEND
NSOCK INFO [65.5340s] nsock_read(): Read request from IOD #1975 [88.255.216.16:80] (timeout: 10000ms) EID 63162
NSOCK INFO [65.5470s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63162 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36284 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.5480s] nsock_read(): Read request from IOD #1975 [88.255.216.16:80] (timeout: 10000ms) EID 63170
NSOCK INFO [65.5480s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63170 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36284 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.5480s] nsock_iod_delete(): nsock_iod_delete (IOD #1975)
NSOCK INFO [65.5480s] nsock_iod_new2(): nsock_iod_new (IOD #1976)
NSOCK INFO [65.5490s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1976) EID 63176
NSOCK INFO [65.5620s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63176 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36300 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36300 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 73 74 72 69 63 74 65 64 2f GET /restricted/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [65.5630s] nsock_write(): Write request for 182 bytes to IOD #1976 EID 63187 [88.255.216.16:80]
NSOCK INFO [65.5630s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63187 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36300 > 88.255.216.16:80 | SEND
NSOCK INFO [65.5650s] nsock_read(): Read request from IOD #1976 [88.255.216.16:80] (timeout: 10000ms) EID 63194
NSOCK INFO [65.5760s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63194 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36300 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.5780s] nsock_read(): Read request from IOD #1976 [88.255.216.16:80] (timeout: 10000ms) EID 63202
NSOCK INFO [65.5780s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63202 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36300 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.5780s] nsock_iod_delete(): nsock_iod_delete (IOD #1976)
NSOCK INFO [65.5780s] nsock_iod_new2(): nsock_iod_new (IOD #1977)
NSOCK INFO [65.5790s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1977) EID 63208
NSOCK INFO [65.5920s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63208 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36308 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36308 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 74 61 69 6c 2f 20 48 54 54 GET /retail/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.5930s] nsock_write(): Write request for 178 bytes to IOD #1977 EID 63219 [88.255.216.16:80]
NSOCK INFO [65.5930s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63219 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36308 > 88.255.216.16:80 | SEND
NSOCK INFO [65.5940s] nsock_read(): Read request from IOD #1977 [88.255.216.16:80] (timeout: 10000ms) EID 63226
NSOCK INFO [65.6070s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63226 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36308 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.6080s] nsock_read(): Read request from IOD #1977 [88.255.216.16:80] (timeout: 10000ms) EID 63234
NSOCK INFO [65.6080s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63234 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36308 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.6090s] nsock_iod_delete(): nsock_iod_delete (IOD #1977)
NSOCK INFO [65.6090s] nsock_iod_new2(): nsock_iod_new (IOD #1978)
NSOCK INFO [65.6090s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1978) EID 63240
NSOCK INFO [65.6230s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63240 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36314 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36314 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 76 65 61 6c 2f 20 48 54 54 GET /reveal/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.6240s] nsock_write(): Write request for 178 bytes to IOD #1978 EID 63251 [88.255.216.16:80]
NSOCK INFO [65.6240s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63251 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36314 > 88.255.216.16:80 | SEND
NSOCK INFO [65.6250s] nsock_read(): Read request from IOD #1978 [88.255.216.16:80] (timeout: 10000ms) EID 63258
NSOCK INFO [65.6370s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63258 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36314 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.6390s] nsock_read(): Read request from IOD #1978 [88.255.216.16:80] (timeout: 10000ms) EID 63266
NSOCK INFO [65.6390s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63266 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36314 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.6400s] nsock_iod_delete(): nsock_iod_delete (IOD #1978)
NSOCK INFO [65.6400s] nsock_iod_new2(): nsock_iod_new (IOD #1979)
NSOCK INFO [65.6400s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1979) EID 63272
NSOCK INFO [65.6530s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63272 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36322 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36322 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 65 76 69 65 77 73 2f 20 48 54 GET /reviews/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [65.6540s] nsock_write(): Write request for 179 bytes to IOD #1979 EID 63283 [88.255.216.16:80]
NSOCK INFO [65.6540s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63283 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36322 > 88.255.216.16:80 | SEND
NSOCK INFO [65.6550s] nsock_read(): Read request from IOD #1979 [88.255.216.16:80] (timeout: 10000ms) EID 63290
NSOCK INFO [65.6680s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63290 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36322 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.6680s] nsock_read(): Read request from IOD #1979 [88.255.216.16:80] (timeout: 10000ms) EID 63298
NSOCK INFO [65.6680s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63298 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36322 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.6690s] nsock_iod_delete(): nsock_iod_delete (IOD #1979)
NSOCK INFO [65.6690s] nsock_iod_new2(): nsock_iod_new (IOD #1980)
NSOCK INFO [65.6690s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1980) EID 63304
NSOCK INFO [65.6820s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63304 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36338 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36338 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 52 4f 41 44 53 2f 20 48 54 54 50 GET /ROADS/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [65.6850s] nsock_write(): Write request for 177 bytes to IOD #1980 EID 63315 [88.255.216.16:80]
NSOCK INFO [65.6850s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63315 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36338 > 88.255.216.16:80 | SEND
NSOCK INFO [65.6860s] nsock_read(): Read request from IOD #1980 [88.255.216.16:80] (timeout: 10000ms) EID 63322
NSOCK INFO [65.6970s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63322 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36338 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.6990s] nsock_read(): Read request from IOD #1980 [88.255.216.16:80] (timeout: 10000ms) EID 63330
NSOCK INFO [65.6990s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63330 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36338 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.6990s] nsock_iod_delete(): nsock_iod_delete (IOD #1980)
NSOCK INFO [65.6990s] nsock_iod_new2(): nsock_iod_new (IOD #1981)
NSOCK INFO [65.6990s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1981) EID 63336
NSOCK INFO [65.7130s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63336 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36354 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36354 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 6f 62 6f 74 2f 20 48 54 54 50 GET /robot/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [65.7160s] nsock_write(): Write request for 177 bytes to IOD #1981 EID 63347 [88.255.216.16:80]
NSOCK INFO [65.7160s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63347 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36354 > 88.255.216.16:80 | SEND
NSOCK INFO [65.7170s] nsock_read(): Read request from IOD #1981 [88.255.216.16:80] (timeout: 10000ms) EID 63354
NSOCK INFO [65.7290s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63354 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36354 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.7300s] nsock_read(): Read request from IOD #1981 [88.255.216.16:80] (timeout: 10000ms) EID 63362
NSOCK INFO [65.7300s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63362 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36354 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.7320s] nsock_iod_delete(): nsock_iod_delete (IOD #1981)
NSOCK INFO [65.7320s] nsock_iod_new2(): nsock_iod_new (IOD #1982)
NSOCK INFO [65.7320s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1982) EID 63368
NSOCK INFO [65.7450s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63368 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36366 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36366 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 6f 62 6f 74 73 2f 20 48 54 54 GET /robots/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.7470s] nsock_write(): Write request for 178 bytes to IOD #1982 EID 63379 [88.255.216.16:80]
NSOCK INFO [65.7470s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63379 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36366 > 88.255.216.16:80 | SEND
NSOCK INFO [65.7470s] nsock_read(): Read request from IOD #1982 [88.255.216.16:80] (timeout: 10000ms) EID 63386
NSOCK INFO [65.7600s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63386 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36366 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.7610s] nsock_read(): Read request from IOD #1982 [88.255.216.16:80] (timeout: 10000ms) EID 63394
NSOCK INFO [65.7610s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63394 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36366 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.7620s] nsock_iod_delete(): nsock_iod_delete (IOD #1982)
NSOCK INFO [65.7620s] nsock_iod_new2(): nsock_iod_new (IOD #1983)
NSOCK INFO [65.7620s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1983) EID 63400
NSOCK INFO [65.7750s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63400 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36372 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36372 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 6f 6f 74 2f 20 48 54 54 50 2f GET /root/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [65.7780s] nsock_write(): Write request for 176 bytes to IOD #1983 EID 63411 [88.255.216.16:80]
NSOCK INFO [65.7780s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63411 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36372 > 88.255.216.16:80 | SEND
NSOCK INFO [65.7790s] nsock_read(): Read request from IOD #1983 [88.255.216.16:80] (timeout: 10000ms) EID 63418
NSOCK INFO [65.7920s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63418 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36372 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.7930s] nsock_read(): Read request from IOD #1983 [88.255.216.16:80] (timeout: 10000ms) EID 63426
NSOCK INFO [65.7930s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63426 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36372 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.7940s] nsock_iod_delete(): nsock_iod_delete (IOD #1983)
NSOCK INFO [65.7940s] nsock_iod_new2(): nsock_iod_new (IOD #1984)
NSOCK INFO [65.7950s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1984) EID 63432
NSOCK INFO [65.8110s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63432 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36376 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36376 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 73 72 63 2f 20 48 54 54 50 2f GET /rsrc/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [65.8120s] nsock_write(): Write request for 176 bytes to IOD #1984 EID 63443 [88.255.216.16:80]
NSOCK INFO [65.8120s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63443 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36376 > 88.255.216.16:80 | SEND
NSOCK INFO [65.8130s] nsock_read(): Read request from IOD #1984 [88.255.216.16:80] (timeout: 10000ms) EID 63450
NSOCK INFO [65.8250s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63450 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36376 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.8270s] nsock_read(): Read request from IOD #1984 [88.255.216.16:80] (timeout: 10000ms) EID 63458
NSOCK INFO [65.8270s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63458 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36376 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.8270s] nsock_iod_delete(): nsock_iod_delete (IOD #1984)
NSOCK INFO [65.8270s] nsock_iod_new2(): nsock_iod_new (IOD #1985)
NSOCK INFO [65.8270s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1985) EID 63464
NSOCK INFO [65.8410s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63464 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36382 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36382 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 72 75 62 79 2f 20 48 54 54 50 2f GET /ruby/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [65.8410s] nsock_write(): Write request for 176 bytes to IOD #1985 EID 63475 [88.255.216.16:80]
NSOCK INFO [65.8410s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63475 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36382 > 88.255.216.16:80 | SEND
NSOCK INFO [65.8420s] nsock_read(): Read request from IOD #1985 [88.255.216.16:80] (timeout: 10000ms) EID 63482
NSOCK INFO [65.8550s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63482 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36382 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.8550s] nsock_read(): Read request from IOD #1985 [88.255.216.16:80] (timeout: 10000ms) EID 63490
NSOCK INFO [65.8550s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63490 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36382 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.8560s] nsock_iod_delete(): nsock_iod_delete (IOD #1985)
NSOCK INFO [65.8560s] nsock_iod_new2(): nsock_iod_new (IOD #1986)
NSOCK INFO [65.8570s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1986) EID 63496
NSOCK INFO [65.8700s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63496 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36388 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36388 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 61 6c 65 73 2f 20 48 54 54 50 GET /sales/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [65.8710s] nsock_write(): Write request for 177 bytes to IOD #1986 EID 63507 [88.255.216.16:80]
NSOCK INFO [65.8710s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63507 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36388 > 88.255.216.16:80 | SEND
NSOCK INFO [65.8720s] nsock_read(): Read request from IOD #1986 [88.255.216.16:80] (timeout: 10000ms) EID 63514
NSOCK INFO [65.8840s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63514 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36388 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.8860s] nsock_read(): Read request from IOD #1986 [88.255.216.16:80] (timeout: 10000ms) EID 63522
NSOCK INFO [65.8860s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63522 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36388 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.8860s] nsock_iod_delete(): nsock_iod_delete (IOD #1986)
NSOCK INFO [65.8860s] nsock_iod_new2(): nsock_iod_new (IOD #1987)
NSOCK INFO [65.8870s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1987) EID 63528
NSOCK INFO [65.9000s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63528 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36404 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36404 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 61 76 65 2f 20 48 54 54 50 2f GET /save/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [65.9010s] nsock_write(): Write request for 176 bytes to IOD #1987 EID 63539 [88.255.216.16:80]
NSOCK INFO [65.9010s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63539 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36404 > 88.255.216.16:80 | SEND
NSOCK INFO [65.9020s] nsock_read(): Read request from IOD #1987 [88.255.216.16:80] (timeout: 10000ms) EID 63546
NSOCK INFO [65.9140s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63546 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36404 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.9150s] nsock_read(): Read request from IOD #1987 [88.255.216.16:80] (timeout: 10000ms) EID 63554
NSOCK INFO [65.9150s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63554 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36404 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.9150s] nsock_iod_delete(): nsock_iod_delete (IOD #1987)
NSOCK INFO [65.9150s] nsock_iod_new2(): nsock_iod_new (IOD #1988)
NSOCK INFO [65.9160s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1988) EID 63560
NSOCK INFO [65.9290s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63560 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36420 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36420 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 63 72 69 70 74 2f 20 48 54 54 GET /script/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [65.9300s] nsock_write(): Write request for 178 bytes to IOD #1988 EID 63571 [88.255.216.16:80]
NSOCK INFO [65.9300s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63571 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36420 > 88.255.216.16:80 | SEND
NSOCK INFO [65.9300s] nsock_read(): Read request from IOD #1988 [88.255.216.16:80] (timeout: 10000ms) EID 63578
NSOCK INFO [65.9430s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63578 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36420 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.9440s] nsock_read(): Read request from IOD #1988 [88.255.216.16:80] (timeout: 10000ms) EID 63586
NSOCK INFO [65.9440s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63586 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36420 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.9440s] nsock_iod_delete(): nsock_iod_delete (IOD #1988)
NSOCK INFO [65.9440s] nsock_iod_new2(): nsock_iod_new (IOD #1989)
NSOCK INFO [65.9440s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1989) EID 63592
NSOCK INFO [65.9570s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63592 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36436 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36436 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 53 63 72 69 70 74 4c 69 62 72 61 GET /ScriptLibra
00000010: 72 79 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f ry/ HTTP/1.1  Ho
00000020: 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 st: 88.255.216.1
00000030: 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6.static.ttnet.c
00000040: 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e om.tr  User-Agen
00000050: 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 t: Mozilla/5.0 (
00000060: 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 compatible; Nmap
00000070: 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e  Scripting Engin
00000080: 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e e; https://nmap.
00000090: 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d org/book/nse.htm
000000a0: 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 l)  Connection: 
000000b0: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.9580s] nsock_write(): Write request for 185 bytes to IOD #1989 EID 63603 [88.255.216.16:80]
NSOCK INFO [65.9580s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63603 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36436 > 88.255.216.16:80 | SEND
NSOCK INFO [65.9580s] nsock_read(): Read request from IOD #1989 [88.255.216.16:80] (timeout: 10000ms) EID 63610
NSOCK INFO [65.9710s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63610 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36436 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [65.9730s] nsock_read(): Read request from IOD #1989 [88.255.216.16:80] (timeout: 10000ms) EID 63618
NSOCK INFO [65.9730s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63618 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36436 > 88.255.216.16:80 | CLOSE
NSOCK INFO [65.9740s] nsock_iod_delete(): nsock_iod_delete (IOD #1989)
NSOCK INFO [65.9740s] nsock_iod_new2(): nsock_iod_new (IOD #1990)
NSOCK INFO [65.9740s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1990) EID 63624
NSOCK INFO [65.9890s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63624 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36452 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36452 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 63 72 69 70 74 73 2f 20 48 54 GET /scripts/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [65.9900s] nsock_write(): Write request for 179 bytes to IOD #1990 EID 63635 [88.255.216.16:80]
NSOCK INFO [65.9900s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63635 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36452 > 88.255.216.16:80 | SEND
NSOCK INFO [65.9900s] nsock_read(): Read request from IOD #1990 [88.255.216.16:80] (timeout: 10000ms) EID 63642
NSOCK INFO [66.0030s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63642 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36452 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.0040s] nsock_read(): Read request from IOD #1990 [88.255.216.16:80] (timeout: 10000ms) EID 63650
NSOCK INFO [66.0040s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63650 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36452 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.0050s] nsock_iod_delete(): nsock_iod_delete (IOD #1990)
NSOCK INFO [66.0050s] nsock_iod_new2(): nsock_iod_new (IOD #1991)
NSOCK INFO [66.0050s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1991) EID 63656
NSOCK INFO [66.0170s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63656 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36466 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36466 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 61 72 63 68 2f 20 48 54 54 GET /search/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [66.0190s] nsock_write(): Write request for 178 bytes to IOD #1991 EID 63667 [88.255.216.16:80]
NSOCK INFO [66.0190s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63667 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36466 > 88.255.216.16:80 | SEND
NSOCK INFO [66.0200s] nsock_read(): Read request from IOD #1991 [88.255.216.16:80] (timeout: 10000ms) EID 63674
NSOCK INFO [66.0320s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63674 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36466 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.0320s] nsock_read(): Read request from IOD #1991 [88.255.216.16:80] (timeout: 10000ms) EID 63682
NSOCK INFO [66.0320s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63682 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36466 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.0330s] nsock_iod_delete(): nsock_iod_delete (IOD #1991)
NSOCK INFO [66.0330s] nsock_iod_new2(): nsock_iod_new (IOD #1992)
NSOCK INFO [66.0330s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1992) EID 63688
NSOCK INFO [66.0470s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63688 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36480 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36480 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 61 72 63 68 2d 75 69 2f 20 GET /search-ui/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [66.0480s] nsock_write(): Write request for 181 bytes to IOD #1992 EID 63699 [88.255.216.16:80]
NSOCK INFO [66.0480s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63699 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36480 > 88.255.216.16:80 | SEND
NSOCK INFO [66.0490s] nsock_read(): Read request from IOD #1992 [88.255.216.16:80] (timeout: 10000ms) EID 63706
NSOCK INFO [66.0610s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63706 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36480 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.0620s] nsock_read(): Read request from IOD #1992 [88.255.216.16:80] (timeout: 10000ms) EID 63714
NSOCK INFO [66.0620s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63714 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36480 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.0630s] nsock_iod_delete(): nsock_iod_delete (IOD #1992)
NSOCK INFO [66.0630s] nsock_iod_new2(): nsock_iod_new (IOD #1993)
NSOCK INFO [66.0630s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1993) EID 63720
NSOCK INFO [66.0760s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63720 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36482 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36482 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 63 2f 20 48 54 54 50 2f 31 GET /sec/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [66.0770s] nsock_write(): Write request for 175 bytes to IOD #1993 EID 63731 [88.255.216.16:80]
NSOCK INFO [66.0770s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63731 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36482 > 88.255.216.16:80 | SEND
NSOCK INFO [66.0770s] nsock_read(): Read request from IOD #1993 [88.255.216.16:80] (timeout: 10000ms) EID 63738
NSOCK INFO [66.0910s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63738 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36482 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.0910s] nsock_read(): Read request from IOD #1993 [88.255.216.16:80] (timeout: 10000ms) EID 63746
NSOCK INFO [66.0910s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63746 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36482 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.0920s] nsock_iod_delete(): nsock_iod_delete (IOD #1993)
NSOCK INFO [66.0920s] nsock_iod_new2(): nsock_iod_new (IOD #1994)
NSOCK INFO [66.0920s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1994) EID 63752
NSOCK INFO [66.1060s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63752 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36492 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36492 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 63 72 65 74 2f 20 48 54 54 GET /secret/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [66.1080s] nsock_write(): Write request for 178 bytes to IOD #1994 EID 63763 [88.255.216.16:80]
NSOCK INFO [66.1080s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63763 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36492 > 88.255.216.16:80 | SEND
NSOCK INFO [66.1080s] nsock_read(): Read request from IOD #1994 [88.255.216.16:80] (timeout: 10000ms) EID 63770
NSOCK INFO [66.1210s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63770 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36492 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.1230s] nsock_read(): Read request from IOD #1994 [88.255.216.16:80] (timeout: 10000ms) EID 63778
NSOCK INFO [66.1230s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63778 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36492 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.1240s] nsock_iod_delete(): nsock_iod_delete (IOD #1994)
NSOCK INFO [66.1240s] nsock_iod_new2(): nsock_iod_new (IOD #1995)
NSOCK INFO [66.1240s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1995) EID 63784
NSOCK INFO [66.1370s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63784 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36502 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36502 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 63 75 72 65 64 2f 20 48 54 GET /secured/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [66.1380s] nsock_write(): Write request for 179 bytes to IOD #1995 EID 63795 [88.255.216.16:80]
NSOCK INFO [66.1380s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63795 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36502 > 88.255.216.16:80 | SEND
NSOCK INFO [66.1380s] nsock_read(): Read request from IOD #1995 [88.255.216.16:80] (timeout: 10000ms) EID 63802
NSOCK INFO [66.1500s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63802 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36502 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.1510s] nsock_read(): Read request from IOD #1995 [88.255.216.16:80] (timeout: 10000ms) EID 63810
NSOCK INFO [66.1510s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63810 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36502 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.1510s] nsock_iod_delete(): nsock_iod_delete (IOD #1995)
NSOCK INFO [66.1510s] nsock_iod_new2(): nsock_iod_new (IOD #1996)
NSOCK INFO [66.1520s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1996) EID 63816
NSOCK INFO [66.1640s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63816 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36518 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36518 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 63 75 72 65 2f 20 48 54 54 GET /secure/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [66.1650s] nsock_write(): Write request for 178 bytes to IOD #1996 EID 63827 [88.255.216.16:80]
NSOCK INFO [66.1650s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63827 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36518 > 88.255.216.16:80 | SEND
NSOCK INFO [66.1660s] nsock_read(): Read request from IOD #1996 [88.255.216.16:80] (timeout: 10000ms) EID 63834
NSOCK INFO [66.1790s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63834 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36518 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.1810s] nsock_read(): Read request from IOD #1996 [88.255.216.16:80] (timeout: 10000ms) EID 63842
NSOCK INFO [66.1810s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63842 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36518 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.1810s] nsock_iod_delete(): nsock_iod_delete (IOD #1996)
NSOCK INFO [66.1810s] nsock_iod_new2(): nsock_iod_new (IOD #1997)
NSOCK INFO [66.1810s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1997) EID 63848
NSOCK INFO [66.1940s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63848 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36522 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36522 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 63 75 72 69 74 79 2f 20 48 GET /security/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [66.1950s] nsock_write(): Write request for 180 bytes to IOD #1997 EID 63859 [88.255.216.16:80]
NSOCK INFO [66.1950s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63859 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36522 > 88.255.216.16:80 | SEND
NSOCK INFO [66.1950s] nsock_read(): Read request from IOD #1997 [88.255.216.16:80] (timeout: 10000ms) EID 63866
NSOCK INFO [66.2070s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63866 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36522 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.2090s] nsock_read(): Read request from IOD #1997 [88.255.216.16:80] (timeout: 10000ms) EID 63874
NSOCK INFO [66.2090s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63874 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36522 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.2090s] nsock_iod_delete(): nsock_iod_delete (IOD #1997)
NSOCK INFO [66.2090s] nsock_iod_new2(): nsock_iod_new (IOD #1998)
NSOCK INFO [66.2090s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1998) EID 63880
NSOCK INFO [66.2230s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63880 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36530 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36530 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 6c 6c 2f 20 48 54 54 50 2f GET /sell/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [66.2240s] nsock_write(): Write request for 176 bytes to IOD #1998 EID 63891 [88.255.216.16:80]
NSOCK INFO [66.2240s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63891 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36530 > 88.255.216.16:80 | SEND
NSOCK INFO [66.2250s] nsock_read(): Read request from IOD #1998 [88.255.216.16:80] (timeout: 10000ms) EID 63898
NSOCK INFO [66.2380s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63898 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36530 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.2390s] nsock_read(): Read request from IOD #1998 [88.255.216.16:80] (timeout: 10000ms) EID 63906
NSOCK INFO [66.2390s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63906 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36530 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.2400s] nsock_iod_delete(): nsock_iod_delete (IOD #1998)
NSOCK INFO [66.2400s] nsock_iod_new2(): nsock_iod_new (IOD #1999)
NSOCK INFO [66.2400s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #1999) EID 63912
NSOCK INFO [66.2520s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63912 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36536 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36536 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 65 72 2f 20 48 54 54 GET /server/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [66.2530s] nsock_write(): Write request for 178 bytes to IOD #1999 EID 63923 [88.255.216.16:80]
NSOCK INFO [66.2530s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63923 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36536 > 88.255.216.16:80 | SEND
NSOCK INFO [66.2540s] nsock_read(): Read request from IOD #1999 [88.255.216.16:80] (timeout: 10000ms) EID 63930
NSOCK INFO [66.2650s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63930 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36536 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.2660s] nsock_read(): Read request from IOD #1999 [88.255.216.16:80] (timeout: 10000ms) EID 63938
NSOCK INFO [66.2660s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63938 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36536 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.2670s] nsock_iod_delete(): nsock_iod_delete (IOD #1999)
NSOCK INFO [66.2670s] nsock_iod_new2(): nsock_iod_new (IOD #2000)
NSOCK INFO [66.2670s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2000) EID 63944
NSOCK INFO [66.2810s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63944 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36538 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36538 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 65 72 2d 69 6e 66 6f GET /server-info
00000010: 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 / HTTP/1.1  Host
00000020: 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e : 88.255.216.16.
00000030: 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d static.ttnet.com
00000040: 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a .tr  User-Agent:
00000050: 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f  Mozilla/5.0 (co
00000060: 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 mpatible; Nmap S
00000070: 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b cripting Engine;
00000080: 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72  https://nmap.or
00000090: 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 g/book/nse.html)
000000a0: 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c   Connection: cl
000000b0: 6f 73 65 0d 0a 0d 0a                            ose    

NSOCK INFO [66.2820s] nsock_write(): Write request for 183 bytes to IOD #2000 EID 63955 [88.255.216.16:80]
NSOCK INFO [66.2820s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63955 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36538 > 88.255.216.16:80 | SEND
NSOCK INFO [66.2840s] nsock_read(): Read request from IOD #2000 [88.255.216.16:80] (timeout: 10000ms) EID 63962
NSOCK INFO [66.2960s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63962 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36538 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.2970s] nsock_read(): Read request from IOD #2000 [88.255.216.16:80] (timeout: 10000ms) EID 63970
NSOCK INFO [66.2970s] nsock_trace_handler_callback(): Callback: READ EOF for EID 63970 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36538 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.2980s] nsock_iod_delete(): nsock_iod_delete (IOD #2000)
NSOCK INFO [66.2980s] nsock_iod_new2(): nsock_iod_new (IOD #2001)
NSOCK INFO [66.2980s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2001) EID 63976
NSOCK INFO [66.3120s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 63976 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36542 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36542 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 65 72 73 2f 20 48 54 GET /servers/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [66.3140s] nsock_write(): Write request for 179 bytes to IOD #2001 EID 63987 [88.255.216.16:80]
NSOCK INFO [66.3140s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 63987 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36542 > 88.255.216.16:80 | SEND
NSOCK INFO [66.3140s] nsock_read(): Read request from IOD #2001 [88.255.216.16:80] (timeout: 10000ms) EID 63994
NSOCK INFO [66.3270s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 63994 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36542 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.3280s] nsock_read(): Read request from IOD #2001 [88.255.216.16:80] (timeout: 10000ms) EID 64002
NSOCK INFO [66.3280s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64002 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36542 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.3290s] nsock_iod_delete(): nsock_iod_delete (IOD #2001)
NSOCK INFO [66.3290s] nsock_iod_new2(): nsock_iod_new (IOD #2002)
NSOCK INFO [66.3290s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2002) EID 64008
NSOCK INFO [66.3480s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64008 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36550 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36550 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 65 72 5f 73 74 61 74 GET /server_stat
00000010: 73 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 s/ HTTP/1.1  Hos
00000020: 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 t: 88.255.216.16
00000030: 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f .static.ttnet.co
00000040: 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 m.tr  User-Agent
00000050: 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 : Mozilla/5.0 (c
00000060: 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 ompatible; Nmap 
00000070: 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 Scripting Engine
00000080: 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f ; https://nmap.o
00000090: 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c rg/book/nse.html
000000a0: 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 )  Connection: c
000000b0: 6c 6f 73 65 0d 0a 0d 0a                         lose    

NSOCK INFO [66.3490s] nsock_write(): Write request for 184 bytes to IOD #2002 EID 64019 [88.255.216.16:80]
NSOCK INFO [66.3490s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64019 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36550 > 88.255.216.16:80 | SEND
NSOCK INFO [66.3490s] nsock_read(): Read request from IOD #2002 [88.255.216.16:80] (timeout: 10000ms) EID 64026
NSOCK INFO [66.3660s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64026 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36550 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.3670s] nsock_read(): Read request from IOD #2002 [88.255.216.16:80] (timeout: 10000ms) EID 64034
NSOCK INFO [66.3670s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64034 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36550 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.3670s] nsock_iod_delete(): nsock_iod_delete (IOD #2002)
NSOCK INFO [66.3670s] nsock_iod_new2(): nsock_iod_new (IOD #2003)
NSOCK INFO [66.3680s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2003) EID 64040
NSOCK INFO [66.3810s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64040 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36556 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36556 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 65 72 73 74 61 74 73 GET /serverstats
00000010: 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 / HTTP/1.1  Host
00000020: 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e : 88.255.216.16.
00000030: 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d static.ttnet.com
00000040: 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a .tr  User-Agent:
00000050: 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f  Mozilla/5.0 (co
00000060: 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 mpatible; Nmap S
00000070: 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b cripting Engine;
00000080: 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72  https://nmap.or
00000090: 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 g/book/nse.html)
000000a0: 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c   Connection: cl
000000b0: 6f 73 65 0d 0a 0d 0a                            ose    

NSOCK INFO [66.3830s] nsock_write(): Write request for 183 bytes to IOD #2003 EID 64051 [88.255.216.16:80]
NSOCK INFO [66.3830s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64051 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36556 > 88.255.216.16:80 | SEND
NSOCK INFO [66.3840s] nsock_read(): Read request from IOD #2003 [88.255.216.16:80] (timeout: 10000ms) EID 64058
NSOCK INFO [66.3960s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64058 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36556 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.3970s] nsock_read(): Read request from IOD #2003 [88.255.216.16:80] (timeout: 10000ms) EID 64066
NSOCK INFO [66.3970s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64066 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36556 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.3970s] nsock_iod_delete(): nsock_iod_delete (IOD #2003)
NSOCK INFO [66.3970s] nsock_iod_new2(): nsock_iod_new (IOD #2004)
NSOCK INFO [66.3980s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2004) EID 64072
NSOCK INFO [66.4110s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64072 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36558 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36558 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 65 72 2d 73 74 61 74 GET /server-stat
00000010: 75 73 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f us/ HTTP/1.1  Ho
00000020: 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 st: 88.255.216.1
00000030: 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6.static.ttnet.c
00000040: 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e om.tr  User-Agen
00000050: 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 t: Mozilla/5.0 (
00000060: 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 compatible; Nmap
00000070: 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e  Scripting Engin
00000080: 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e e; https://nmap.
00000090: 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d org/book/nse.htm
000000a0: 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 l)  Connection: 
000000b0: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.4120s] nsock_write(): Write request for 185 bytes to IOD #2004 EID 64083 [88.255.216.16:80]
NSOCK INFO [66.4120s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64083 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36558 > 88.255.216.16:80 | SEND
NSOCK INFO [66.4130s] nsock_read(): Read request from IOD #2004 [88.255.216.16:80] (timeout: 10000ms) EID 64090
NSOCK INFO [66.4260s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64090 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36558 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.4270s] nsock_read(): Read request from IOD #2004 [88.255.216.16:80] (timeout: 10000ms) EID 64098
NSOCK INFO [66.4270s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64098 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36558 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.4280s] nsock_iod_delete(): nsock_iod_delete (IOD #2004)
NSOCK INFO [66.4280s] nsock_iod_new2(): nsock_iod_new (IOD #2005)
NSOCK INFO [66.4280s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2005) EID 64104
NSOCK INFO [66.4420s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64104 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36564 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36564 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 69 63 65 2f 20 48 54 GET /service/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [66.4430s] nsock_write(): Write request for 179 bytes to IOD #2005 EID 64115 [88.255.216.16:80]
NSOCK INFO [66.4430s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64115 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36564 > 88.255.216.16:80 | SEND
NSOCK INFO [66.4440s] nsock_read(): Read request from IOD #2005 [88.255.216.16:80] (timeout: 10000ms) EID 64122
NSOCK INFO [66.4560s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64122 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36564 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.4570s] nsock_read(): Read request from IOD #2005 [88.255.216.16:80] (timeout: 10000ms) EID 64130
NSOCK INFO [66.4570s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64130 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36564 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.4570s] nsock_iod_delete(): nsock_iod_delete (IOD #2005)
NSOCK INFO [66.4570s] nsock_iod_new2(): nsock_iod_new (IOD #2006)
NSOCK INFO [66.4570s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2006) EID 64136
NSOCK INFO [66.4710s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64136 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36576 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36576 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 69 63 65 73 2f 20 48 GET /services/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [66.4720s] nsock_write(): Write request for 180 bytes to IOD #2006 EID 64147 [88.255.216.16:80]
NSOCK INFO [66.4720s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64147 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36576 > 88.255.216.16:80 | SEND
NSOCK INFO [66.4730s] nsock_read(): Read request from IOD #2006 [88.255.216.16:80] (timeout: 10000ms) EID 64154
NSOCK INFO [66.4850s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64154 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36576 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.4860s] nsock_read(): Read request from IOD #2006 [88.255.216.16:80] (timeout: 10000ms) EID 64162
NSOCK INFO [66.4860s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64162 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36576 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.4870s] nsock_iod_delete(): nsock_iod_delete (IOD #2006)
NSOCK INFO [66.4870s] nsock_iod_new2(): nsock_iod_new (IOD #2007)
NSOCK INFO [66.4870s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2007) EID 64168
NSOCK INFO [66.5000s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64168 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36578 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36578 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 69 63 69 6f 2f 20 48 GET /servicio/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [66.5020s] nsock_write(): Write request for 180 bytes to IOD #2007 EID 64179 [88.255.216.16:80]
NSOCK INFO [66.5020s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64179 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36578 > 88.255.216.16:80 | SEND
NSOCK INFO [66.5040s] nsock_read(): Read request from IOD #2007 [88.255.216.16:80] (timeout: 10000ms) EID 64186
NSOCK INFO [66.5160s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64186 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36578 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.5160s] nsock_read(): Read request from IOD #2007 [88.255.216.16:80] (timeout: 10000ms) EID 64194
NSOCK INFO [66.5160s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64194 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36578 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.5170s] nsock_iod_delete(): nsock_iod_delete (IOD #2007)
NSOCK INFO [66.5170s] nsock_iod_new2(): nsock_iod_new (IOD #2008)
NSOCK INFO [66.5170s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2008) EID 64200
NSOCK INFO [66.5300s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64200 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36590 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36590 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 69 63 69 6f 73 2f 20 GET /servicios/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [66.5310s] nsock_write(): Write request for 181 bytes to IOD #2008 EID 64211 [88.255.216.16:80]
NSOCK INFO [66.5310s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64211 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36590 > 88.255.216.16:80 | SEND
NSOCK INFO [66.5320s] nsock_read(): Read request from IOD #2008 [88.255.216.16:80] (timeout: 10000ms) EID 64218
NSOCK INFO [66.5440s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64218 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36590 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.5450s] nsock_read(): Read request from IOD #2008 [88.255.216.16:80] (timeout: 10000ms) EID 64226
NSOCK INFO [66.5450s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64226 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36590 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.5450s] nsock_iod_delete(): nsock_iod_delete (IOD #2008)
NSOCK INFO [66.5450s] nsock_iod_new2(): nsock_iod_new (IOD #2009)
NSOCK INFO [66.5450s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2009) EID 64232
NSOCK INFO [66.5590s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64232 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36600 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36600 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 6c 65 74 2f 20 48 54 GET /servlet/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [66.5610s] nsock_write(): Write request for 179 bytes to IOD #2009 EID 64243 [88.255.216.16:80]
NSOCK INFO [66.5610s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64243 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36600 > 88.255.216.16:80 | SEND
NSOCK INFO [66.5630s] nsock_read(): Read request from IOD #2009 [88.255.216.16:80] (timeout: 10000ms) EID 64250
NSOCK INFO [66.5750s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64250 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36600 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.5750s] nsock_read(): Read request from IOD #2009 [88.255.216.16:80] (timeout: 10000ms) EID 64258
NSOCK INFO [66.5750s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64258 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36600 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.5760s] nsock_iod_delete(): nsock_iod_delete (IOD #2009)
NSOCK INFO [66.5760s] nsock_iod_new2(): nsock_iod_new (IOD #2010)
NSOCK INFO [66.5760s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2010) EID 64264
NSOCK INFO [66.5900s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64264 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36616 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36616 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 72 76 6c 65 74 73 2f 20 48 GET /servlets/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [66.5910s] nsock_write(): Write request for 180 bytes to IOD #2010 EID 64275 [88.255.216.16:80]
NSOCK INFO [66.5910s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64275 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36616 > 88.255.216.16:80 | SEND
NSOCK INFO [66.5920s] nsock_read(): Read request from IOD #2010 [88.255.216.16:80] (timeout: 10000ms) EID 64282
NSOCK INFO [66.6050s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64282 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36616 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.6070s] nsock_read(): Read request from IOD #2010 [88.255.216.16:80] (timeout: 10000ms) EID 64290
NSOCK INFO [66.6070s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64290 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36616 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.6080s] nsock_iod_delete(): nsock_iod_delete (IOD #2010)
NSOCK INFO [66.6080s] nsock_iod_new2(): nsock_iod_new (IOD #2011)
NSOCK INFO [66.6090s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2011) EID 64296
NSOCK INFO [66.6220s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64296 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36618 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36618 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 73 73 69 6f 6e 2f 20 48 54 GET /session/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [66.6230s] nsock_write(): Write request for 179 bytes to IOD #2011 EID 64307 [88.255.216.16:80]
NSOCK INFO [66.6230s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64307 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36618 > 88.255.216.16:80 | SEND
NSOCK INFO [66.6250s] nsock_read(): Read request from IOD #2011 [88.255.216.16:80] (timeout: 10000ms) EID 64314
NSOCK INFO [66.6370s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64314 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36618 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.6380s] nsock_read(): Read request from IOD #2011 [88.255.216.16:80] (timeout: 10000ms) EID 64322
NSOCK INFO [66.6380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64322 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36618 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.6380s] nsock_iod_delete(): nsock_iod_delete (IOD #2011)
NSOCK INFO [66.6380s] nsock_iod_new2(): nsock_iod_new (IOD #2012)
NSOCK INFO [66.6380s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2012) EID 64328
NSOCK INFO [66.6510s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64328 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36620 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36620 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 65 74 75 70 2f 20 48 54 54 50 GET /setup/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [66.6520s] nsock_write(): Write request for 177 bytes to IOD #2012 EID 64339 [88.255.216.16:80]
NSOCK INFO [66.6520s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64339 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36620 > 88.255.216.16:80 | SEND
NSOCK INFO [66.6530s] nsock_read(): Read request from IOD #2012 [88.255.216.16:80] (timeout: 10000ms) EID 64346
NSOCK INFO [66.6650s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64346 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36620 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.6650s] nsock_read(): Read request from IOD #2012 [88.255.216.16:80] (timeout: 10000ms) EID 64354
NSOCK INFO [66.6650s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64354 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36620 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.6660s] nsock_iod_delete(): nsock_iod_delete (IOD #2012)
NSOCK INFO [66.6660s] nsock_iod_new2(): nsock_iod_new (IOD #2013)
NSOCK INFO [66.6660s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2013) EID 64360
NSOCK INFO [66.6800s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64360 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36634 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36634 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 61 72 65 64 2f 20 48 54 54 GET /shared/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [66.6810s] nsock_write(): Write request for 178 bytes to IOD #2013 EID 64371 [88.255.216.16:80]
NSOCK INFO [66.6810s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64371 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36634 > 88.255.216.16:80 | SEND
NSOCK INFO [66.6820s] nsock_read(): Read request from IOD #2013 [88.255.216.16:80] (timeout: 10000ms) EID 64378
NSOCK INFO [66.6950s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64378 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36634 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.6970s] nsock_read(): Read request from IOD #2013 [88.255.216.16:80] (timeout: 10000ms) EID 64386
NSOCK INFO [66.6970s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64386 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36634 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.6970s] nsock_iod_delete(): nsock_iod_delete (IOD #2013)
NSOCK INFO [66.6970s] nsock_iod_new2(): nsock_iod_new (IOD #2014)
NSOCK INFO [66.6970s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2014) EID 64392
NSOCK INFO [66.7120s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64392 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36644 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36644 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 61 72 65 64 74 65 6d 70 6c GET /sharedtempl
00000010: 61 74 65 73 2f 20 48 54 54 50 2f 31 2e 31 0d 0a ates/ HTTP/1.1  
00000020: 48 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 Host: 88.255.216
00000030: 2e 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 .16.static.ttnet
00000040: 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 .com.tr  User-Ag
00000050: 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 ent: Mozilla/5.0
00000060: 20 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d  (compatible; Nm
00000070: 61 70 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 ap Scripting Eng
00000080: 69 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 ine; https://nma
00000090: 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 p.org/book/nse.h
000000a0: 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e tml)  Connection
000000b0: 3a 20 63 6c 6f 73 65 0d 0a 0d 0a                : close    

NSOCK INFO [66.7120s] nsock_write(): Write request for 187 bytes to IOD #2014 EID 64403 [88.255.216.16:80]
NSOCK INFO [66.7120s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64403 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36644 > 88.255.216.16:80 | SEND
NSOCK INFO [66.7130s] nsock_read(): Read request from IOD #2014 [88.255.216.16:80] (timeout: 10000ms) EID 64410
NSOCK INFO [66.7250s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64410 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36644 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.7270s] nsock_read(): Read request from IOD #2014 [88.255.216.16:80] (timeout: 10000ms) EID 64418
NSOCK INFO [66.7270s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64418 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36644 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.7280s] nsock_iod_delete(): nsock_iod_delete (IOD #2014)
NSOCK INFO [66.7280s] nsock_iod_new2(): nsock_iod_new (IOD #2015)
NSOCK INFO [66.7280s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2015) EID 64424
NSOCK INFO [66.7410s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64424 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36652 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36652 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 61 72 65 2f 20 48 54 54 50 GET /share/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [66.7430s] nsock_write(): Write request for 177 bytes to IOD #2015 EID 64435 [88.255.216.16:80]
NSOCK INFO [66.7430s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64435 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36652 > 88.255.216.16:80 | SEND
NSOCK INFO [66.7440s] nsock_read(): Read request from IOD #2015 [88.255.216.16:80] (timeout: 10000ms) EID 64442
NSOCK INFO [66.7570s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64442 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36652 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [66.7580s] nsock_read(): Read request from IOD #2015 [88.255.216.16:80] (timeout: 10000ms) EID 64450
NSOCK INFO [66.7580s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64450 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36652 > 88.255.216.16:80 | CLOSE
NSOCK INFO [66.7590s] nsock_iod_delete(): nsock_iod_delete (IOD #2015)
NSOCK INFO [66.7590s] nsock_iod_new2(): nsock_iod_new (IOD #2016)
NSOCK INFO [66.7590s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2016) EID 64456
NSOCK INFO [66.7720s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64456 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36656 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36656 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 65 6c 6c 2d 63 67 69 2f 20 GET /shell-cgi/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [66.7740s] nsock_write(): Write request for 181 bytes to IOD #2016 EID 64467 [88.255.216.16:80]
NSOCK INFO [66.7740s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64467 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36656 > 88.255.216.16:80 | SEND
NSOCK INFO [66.7750s] nsock_read(): Read request from IOD #2016 [88.255.216.16:80] (timeout: 10000ms) EID 64474
NSOCK INFO [67.0360s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64474 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36656 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [67.0370s] nsock_read(): Read request from IOD #2016 [88.255.216.16:80] (timeout: 10000ms) EID 64482
NSOCK INFO [67.0370s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64482 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36656 > 88.255.216.16:80 | CLOSE
NSOCK INFO [67.0370s] nsock_iod_delete(): nsock_iod_delete (IOD #2016)
NSOCK INFO [67.0370s] nsock_iod_new2(): nsock_iod_new (IOD #2017)
NSOCK INFO [67.0370s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2017) EID 64488
NSOCK INFO [67.0510s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64488 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36672 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36672 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 69 70 70 69 6e 67 2f 20 48 GET /shipping/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [67.0530s] nsock_write(): Write request for 180 bytes to IOD #2017 EID 64499 [88.255.216.16:80]
NSOCK INFO [67.0530s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64499 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36672 > 88.255.216.16:80 | SEND
NSOCK INFO [67.0540s] nsock_read(): Read request from IOD #2017 [88.255.216.16:80] (timeout: 10000ms) EID 64506
NSOCK INFO [67.0660s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64506 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36672 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [67.0680s] nsock_read(): Read request from IOD #2017 [88.255.216.16:80] (timeout: 10000ms) EID 64514
NSOCK INFO [67.0680s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64514 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36672 > 88.255.216.16:80 | CLOSE
NSOCK INFO [67.0690s] nsock_iod_delete(): nsock_iod_delete (IOD #2017)
NSOCK INFO [67.0690s] nsock_iod_new2(): nsock_iod_new (IOD #2018)
NSOCK INFO [67.0690s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2018) EID 64520
NSOCK INFO [67.0830s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64520 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36676 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36676 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 6f 70 2f 20 48 54 54 50 2f GET /shop/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [67.0850s] nsock_write(): Write request for 176 bytes to IOD #2018 EID 64531 [88.255.216.16:80]
NSOCK INFO [67.0850s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64531 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36676 > 88.255.216.16:80 | SEND
NSOCK INFO [67.0860s] nsock_read(): Read request from IOD #2018 [88.255.216.16:80] (timeout: 10000ms) EID 64538
NSOCK INFO [67.0990s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64538 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36676 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [67.1000s] nsock_read(): Read request from IOD #2018 [88.255.216.16:80] (timeout: 10000ms) EID 64546
NSOCK INFO [67.1000s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64546 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36676 > 88.255.216.16:80 | CLOSE
NSOCK INFO [67.1000s] nsock_iod_delete(): nsock_iod_delete (IOD #2018)
NSOCK INFO [67.1000s] nsock_iod_new2(): nsock_iod_new (IOD #2019)
NSOCK INFO [67.1000s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2019) EID 64552
NSOCK INFO [67.1140s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64552 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36692 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36692 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 6f 70 70 65 72 2f 20 48 54 GET /shopper/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [67.1150s] nsock_write(): Write request for 179 bytes to IOD #2019 EID 64563 [88.255.216.16:80]
NSOCK INFO [67.1150s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64563 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36692 > 88.255.216.16:80 | SEND
NSOCK INFO [67.1160s] nsock_read(): Read request from IOD #2019 [88.255.216.16:80] (timeout: 10000ms) EID 64570
NSOCK INFO [67.1280s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64570 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36692 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [67.1310s] nsock_read(): Read request from IOD #2019 [88.255.216.16:80] (timeout: 10000ms) EID 64578
NSOCK INFO [67.1310s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64578 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36692 > 88.255.216.16:80 | CLOSE
NSOCK INFO [67.1310s] nsock_iod_delete(): nsock_iod_delete (IOD #2019)
NSOCK INFO [67.1310s] nsock_iod_new2(): nsock_iod_new (IOD #2020)
NSOCK INFO [67.1310s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2020) EID 64584
NSOCK INFO [67.1450s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64584 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36696 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36696 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 68 6f 77 2f 20 48 54 54 50 2f GET /show/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [67.1460s] nsock_write(): Write request for 176 bytes to IOD #2020 EID 64595 [88.255.216.16:80]
NSOCK INFO [67.1460s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64595 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36696 > 88.255.216.16:80 | SEND
NSOCK INFO [67.1460s] nsock_read(): Read request from IOD #2020 [88.255.216.16:80] (timeout: 10000ms) EID 64602
NSOCK INFO [67.1590s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64602 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36696 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [67.1610s] nsock_read(): Read request from IOD #2020 [88.255.216.16:80] (timeout: 10000ms) EID 64610
NSOCK INFO [67.1610s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64610 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36696 > 88.255.216.16:80 | CLOSE
NSOCK INFO [67.1610s] nsock_iod_delete(): nsock_iod_delete (IOD #2020)
NSOCK INFO [67.1610s] nsock_iod_new2(): nsock_iod_new (IOD #2021)
NSOCK INFO [67.1610s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2021) EID 64616
NSOCK INFO [67.1740s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64616 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36704 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36704 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 53 69 6c 76 65 72 53 74 72 65 61 GET /SilverStrea
00000010: 6d 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 m/ HTTP/1.1  Hos
00000020: 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 t: 88.255.216.16
00000030: 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f .static.ttnet.co
00000040: 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 m.tr  User-Agent
00000050: 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 : Mozilla/5.0 (c
00000060: 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 ompatible; Nmap 
00000070: 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 Scripting Engine
00000080: 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f ; https://nmap.o
00000090: 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c rg/book/nse.html
000000a0: 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 )  Connection: c
000000b0: 6c 6f 73 65 0d 0a 0d 0a                         lose    

NSOCK INFO [67.1750s] nsock_write(): Write request for 184 bytes to IOD #2021 EID 64627 [88.255.216.16:80]
NSOCK INFO [67.1760s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64627 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36704 > 88.255.216.16:80 | SEND
NSOCK INFO [67.1770s] nsock_read(): Read request from IOD #2021 [88.255.216.16:80] (timeout: 10000ms) EID 64634
NSOCK INFO [67.1890s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64634 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36704 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [67.1900s] nsock_read(): Read request from IOD #2021 [88.255.216.16:80] (timeout: 10000ms) EID 64642
NSOCK INFO [67.1900s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64642 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36704 > 88.255.216.16:80 | CLOSE
NSOCK INFO [67.1910s] nsock_iod_delete(): nsock_iod_delete (IOD #2021)
NSOCK INFO [67.1910s] nsock_iod_new2(): nsock_iod_new (IOD #2022)
NSOCK INFO [67.1910s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2022) EID 64648
NSOCK INFO [67.2050s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64648 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36708 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36708 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 61 64 6d 69 6e 2f 20 GET /siteadmin/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [67.2070s] nsock_write(): Write request for 181 bytes to IOD #2022 EID 64659 [88.255.216.16:80]
NSOCK INFO [67.2070s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64659 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36708 > 88.255.216.16:80 | SEND
NSOCK INFO [67.2070s] nsock_read(): Read request from IOD #2022 [88.255.216.16:80] (timeout: 10000ms) EID 64666
NSOCK INFO [67.2210s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64666 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36708 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [67.2220s] nsock_read(): Read request from IOD #2022 [88.255.216.16:80] (timeout: 10000ms) EID 64674
NSOCK INFO [67.2220s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64674 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36708 > 88.255.216.16:80 | CLOSE
NSOCK INFO [67.2220s] nsock_iod_delete(): nsock_iod_delete (IOD #2022)
NSOCK INFO [67.2220s] nsock_iod_new2(): nsock_iod_new (IOD #2023)
NSOCK INFO [67.2220s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2023) EID 64680
NSOCK INFO [68.2370s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64680 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36714 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36714 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 2f 20 48 54 54 50 2f GET /site/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [68.2380s] nsock_write(): Write request for 176 bytes to IOD #2023 EID 64691 [88.255.216.16:80]
NSOCK INFO [68.2380s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64691 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36714 > 88.255.216.16:80 | SEND
NSOCK INFO [68.2390s] nsock_read(): Read request from IOD #2023 [88.255.216.16:80] (timeout: 10000ms) EID 64698
NSOCK INFO [68.2510s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64698 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36714 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.2520s] nsock_read(): Read request from IOD #2023 [88.255.216.16:80] (timeout: 10000ms) EID 64706
NSOCK INFO [68.2520s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64706 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36714 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.2520s] nsock_iod_delete(): nsock_iod_delete (IOD #2023)
NSOCK INFO [68.2520s] nsock_iod_new2(): nsock_iod_new (IOD #2024)
NSOCK INFO [68.2530s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2024) EID 64712
NSOCK INFO [68.2650s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64712 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36718 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36718 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 6d 67 72 2f 20 48 54 GET /sitemgr/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [68.2670s] nsock_write(): Write request for 179 bytes to IOD #2024 EID 64723 [88.255.216.16:80]
NSOCK INFO [68.2670s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64723 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36718 > 88.255.216.16:80 | SEND
NSOCK INFO [68.2680s] nsock_read(): Read request from IOD #2024 [88.255.216.16:80] (timeout: 10000ms) EID 64730
NSOCK INFO [68.2800s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64730 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36718 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.2810s] nsock_read(): Read request from IOD #2024 [88.255.216.16:80] (timeout: 10000ms) EID 64738
NSOCK INFO [68.2810s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64738 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36718 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.2810s] nsock_iod_delete(): nsock_iod_delete (IOD #2024)
NSOCK INFO [68.2810s] nsock_iod_new2(): nsock_iod_new (IOD #2025)
NSOCK INFO [68.2820s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2025) EID 64744
NSOCK INFO [68.2940s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64744 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36728 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36728 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 6d 69 6e 64 65 72 61 GET /sitemindera
00000010: 67 65 6e 74 2f 20 48 54 54 50 2f 31 2e 31 0d 0a gent/ HTTP/1.1  
00000020: 48 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 Host: 88.255.216
00000030: 2e 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 .16.static.ttnet
00000040: 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 .com.tr  User-Ag
00000050: 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 ent: Mozilla/5.0
00000060: 20 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d  (compatible; Nm
00000070: 61 70 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 ap Scripting Eng
00000080: 69 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 ine; https://nma
00000090: 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 p.org/book/nse.h
000000a0: 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e tml)  Connection
000000b0: 3a 20 63 6c 6f 73 65 0d 0a 0d 0a                : close    

NSOCK INFO [68.2960s] nsock_write(): Write request for 187 bytes to IOD #2025 EID 64755 [88.255.216.16:80]
NSOCK INFO [68.2960s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64755 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36728 > 88.255.216.16:80 | SEND
NSOCK INFO [68.2980s] nsock_read(): Read request from IOD #2025 [88.255.216.16:80] (timeout: 10000ms) EID 64762
NSOCK INFO [68.3090s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64762 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36728 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.3110s] nsock_read(): Read request from IOD #2025 [88.255.216.16:80] (timeout: 10000ms) EID 64770
NSOCK INFO [68.3110s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64770 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36728 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.3110s] nsock_iod_delete(): nsock_iod_delete (IOD #2025)
NSOCK INFO [68.3110s] nsock_iod_new2(): nsock_iod_new (IOD #2026)
NSOCK INFO [68.3110s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2026) EID 64776
NSOCK INFO [68.3240s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64776 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36730 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36730 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 6d 69 6e 64 65 72 2f GET /siteminder/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [68.3250s] nsock_write(): Write request for 182 bytes to IOD #2026 EID 64787 [88.255.216.16:80]
NSOCK INFO [68.3250s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64787 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36730 > 88.255.216.16:80 | SEND
NSOCK INFO [68.3260s] nsock_read(): Read request from IOD #2026 [88.255.216.16:80] (timeout: 10000ms) EID 64794
NSOCK INFO [68.3380s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64794 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36730 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.3380s] nsock_read(): Read request from IOD #2026 [88.255.216.16:80] (timeout: 10000ms) EID 64802
NSOCK INFO [68.3380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64802 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36730 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.3390s] nsock_iod_delete(): nsock_iod_delete (IOD #2026)
NSOCK INFO [68.3390s] nsock_iod_new2(): nsock_iod_new (IOD #2027)
NSOCK INFO [68.3390s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2027) EID 64808
NSOCK INFO [68.3550s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64808 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36736 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36736 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 73 65 72 76 65 72 2f GET /siteserver/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [68.3570s] nsock_write(): Write request for 182 bytes to IOD #2027 EID 64819 [88.255.216.16:80]
NSOCK INFO [68.3570s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64819 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36736 > 88.255.216.16:80 | SEND
NSOCK INFO [68.3590s] nsock_read(): Read request from IOD #2027 [88.255.216.16:80] (timeout: 10000ms) EID 64826
NSOCK INFO [68.3760s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64826 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36736 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.3760s] nsock_read(): Read request from IOD #2027 [88.255.216.16:80] (timeout: 10000ms) EID 64834
NSOCK INFO [68.3760s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64834 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36736 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.3770s] nsock_iod_delete(): nsock_iod_delete (IOD #2027)
NSOCK INFO [68.3770s] nsock_iod_new2(): nsock_iod_new (IOD #2028)
NSOCK INFO [68.3770s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2028) EID 64840
NSOCK INFO [68.3940s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64840 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36746 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36746 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 73 2f 20 48 54 54 50 GET /sites/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [68.3960s] nsock_write(): Write request for 177 bytes to IOD #2028 EID 64851 [88.255.216.16:80]
NSOCK INFO [68.3960s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64851 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36746 > 88.255.216.16:80 | SEND
NSOCK INFO [68.3970s] nsock_read(): Read request from IOD #2028 [88.255.216.16:80] (timeout: 10000ms) EID 64858
NSOCK INFO [68.4130s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64858 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36746 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.4140s] nsock_read(): Read request from IOD #2028 [88.255.216.16:80] (timeout: 10000ms) EID 64866
NSOCK INFO [68.4140s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64866 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36746 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.4140s] nsock_iod_delete(): nsock_iod_delete (IOD #2028)
NSOCK INFO [68.4140s] nsock_iod_new2(): nsock_iod_new (IOD #2029)
NSOCK INFO [68.4140s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2029) EID 64872
NSOCK INFO [68.4270s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64872 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36748 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36748 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 73 74 61 74 73 2f 20 GET /sitestats/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [68.4280s] nsock_write(): Write request for 181 bytes to IOD #2029 EID 64883 [88.255.216.16:80]
NSOCK INFO [68.4280s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64883 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36748 > 88.255.216.16:80 | SEND
NSOCK INFO [68.4290s] nsock_read(): Read request from IOD #2029 [88.255.216.16:80] (timeout: 10000ms) EID 64890
NSOCK INFO [68.4410s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64890 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36748 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.4420s] nsock_read(): Read request from IOD #2029 [88.255.216.16:80] (timeout: 10000ms) EID 64898
NSOCK INFO [68.4420s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64898 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36748 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.4420s] nsock_iod_delete(): nsock_iod_delete (IOD #2029)
NSOCK INFO [68.4420s] nsock_iod_new2(): nsock_iod_new (IOD #2030)
NSOCK INFO [68.4430s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2030) EID 64904
NSOCK INFO [68.4560s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64904 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36764 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36764 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 75 70 64 61 74 65 2f GET /siteupdate/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [68.4570s] nsock_write(): Write request for 182 bytes to IOD #2030 EID 64915 [88.255.216.16:80]
NSOCK INFO [68.4570s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64915 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36764 > 88.255.216.16:80 | SEND
NSOCK INFO [68.4580s] nsock_read(): Read request from IOD #2030 [88.255.216.16:80] (timeout: 10000ms) EID 64922
NSOCK INFO [68.4710s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64922 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36764 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.4720s] nsock_read(): Read request from IOD #2030 [88.255.216.16:80] (timeout: 10000ms) EID 64930
NSOCK INFO [68.4720s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64930 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36764 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.4740s] nsock_iod_delete(): nsock_iod_delete (IOD #2030)
NSOCK INFO [68.4740s] nsock_iod_new2(): nsock_iod_new (IOD #2031)
NSOCK INFO [68.4740s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2031) EID 64936
NSOCK INFO [68.4880s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64936 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36770 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36770 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 6d 72 65 70 6f 72 74 73 2f 20 GET /smreports/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [68.4890s] nsock_write(): Write request for 181 bytes to IOD #2031 EID 64947 [88.255.216.16:80]
NSOCK INFO [68.4890s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64947 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36770 > 88.255.216.16:80 | SEND
NSOCK INFO [68.4910s] nsock_read(): Read request from IOD #2031 [88.255.216.16:80] (timeout: 10000ms) EID 64954
NSOCK INFO [68.5030s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64954 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36770 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.5030s] nsock_read(): Read request from IOD #2031 [88.255.216.16:80] (timeout: 10000ms) EID 64962
NSOCK INFO [68.5030s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64962 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36770 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.5040s] nsock_iod_delete(): nsock_iod_delete (IOD #2031)
NSOCK INFO [68.5040s] nsock_iod_new2(): nsock_iod_new (IOD #2032)
NSOCK INFO [68.5040s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2032) EID 64968
NSOCK INFO [68.5170s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 64968 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36782 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36782 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 6d 72 65 70 6f 72 74 73 76 69 GET /smreportsvi
00000010: 65 77 65 72 2f 20 48 54 54 50 2f 31 2e 31 0d 0a ewer/ HTTP/1.1  
00000020: 48 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 Host: 88.255.216
00000030: 2e 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 .16.static.ttnet
00000040: 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 .com.tr  User-Ag
00000050: 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 ent: Mozilla/5.0
00000060: 20 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d  (compatible; Nm
00000070: 61 70 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 ap Scripting Eng
00000080: 69 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 ine; https://nma
00000090: 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 p.org/book/nse.h
000000a0: 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e tml)  Connection
000000b0: 3a 20 63 6c 6f 73 65 0d 0a 0d 0a                : close    

NSOCK INFO [68.5180s] nsock_write(): Write request for 187 bytes to IOD #2032 EID 64979 [88.255.216.16:80]
NSOCK INFO [68.5180s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 64979 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36782 > 88.255.216.16:80 | SEND
NSOCK INFO [68.5190s] nsock_read(): Read request from IOD #2032 [88.255.216.16:80] (timeout: 10000ms) EID 64986
NSOCK INFO [68.5310s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 64986 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36782 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.5320s] nsock_read(): Read request from IOD #2032 [88.255.216.16:80] (timeout: 10000ms) EID 64994
NSOCK INFO [68.5320s] nsock_trace_handler_callback(): Callback: READ EOF for EID 64994 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36782 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.5320s] nsock_iod_delete(): nsock_iod_delete (IOD #2032)
NSOCK INFO [68.5320s] nsock_iod_new2(): nsock_iod_new (IOD #2033)
NSOCK INFO [68.5320s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2033) EID 65000
NSOCK INFO [68.5450s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65000 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36784 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36784 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 6f 61 70 64 6f 63 73 2f 20 48 GET /soapdocs/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [68.5460s] nsock_write(): Write request for 180 bytes to IOD #2033 EID 65011 [88.255.216.16:80]
NSOCK INFO [68.5460s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65011 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36784 > 88.255.216.16:80 | SEND
NSOCK INFO [68.5460s] nsock_read(): Read request from IOD #2033 [88.255.216.16:80] (timeout: 10000ms) EID 65018
NSOCK INFO [68.5590s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65018 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36784 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.5600s] nsock_read(): Read request from IOD #2033 [88.255.216.16:80] (timeout: 10000ms) EID 65026
NSOCK INFO [68.5600s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65026 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36784 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.5600s] nsock_iod_delete(): nsock_iod_delete (IOD #2033)
NSOCK INFO [68.5600s] nsock_iod_new2(): nsock_iod_new (IOD #2034)
NSOCK INFO [68.5610s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2034) EID 65032
NSOCK INFO [68.5730s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65032 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36794 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36794 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 6f 61 70 2f 20 48 54 54 50 2f GET /soap/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [68.5740s] nsock_write(): Write request for 176 bytes to IOD #2034 EID 65043 [88.255.216.16:80]
NSOCK INFO [68.5740s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65043 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36794 > 88.255.216.16:80 | SEND
NSOCK INFO [68.5750s] nsock_read(): Read request from IOD #2034 [88.255.216.16:80] (timeout: 10000ms) EID 65050
NSOCK INFO [68.5880s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65050 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36794 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.5880s] nsock_read(): Read request from IOD #2034 [88.255.216.16:80] (timeout: 10000ms) EID 65058
NSOCK INFO [68.5880s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65058 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36794 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.5890s] nsock_iod_delete(): nsock_iod_delete (IOD #2034)
NSOCK INFO [68.5890s] nsock_iod_new2(): nsock_iod_new (IOD #2035)
NSOCK INFO [68.5890s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2035) EID 65064
NSOCK INFO [68.6020s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65064 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36796 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36796 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 6f 66 74 77 61 72 65 2f 20 48 GET /software/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [68.6040s] nsock_write(): Write request for 180 bytes to IOD #2035 EID 65075 [88.255.216.16:80]
NSOCK INFO [68.6040s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65075 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36796 > 88.255.216.16:80 | SEND
NSOCK INFO [68.6050s] nsock_read(): Read request from IOD #2035 [88.255.216.16:80] (timeout: 10000ms) EID 65082
NSOCK INFO [68.6170s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65082 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36796 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.6180s] nsock_read(): Read request from IOD #2035 [88.255.216.16:80] (timeout: 10000ms) EID 65090
NSOCK INFO [68.6180s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65090 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36796 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.6180s] nsock_iod_delete(): nsock_iod_delete (IOD #2035)
NSOCK INFO [68.6180s] nsock_iod_new2(): nsock_iod_new (IOD #2036)
NSOCK INFO [68.6190s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2036) EID 65096
NSOCK INFO [68.6320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65096 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36804 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36804 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 6f 6c 61 72 69 73 2f 20 48 54 GET /solaris/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [68.6330s] nsock_write(): Write request for 179 bytes to IOD #2036 EID 65107 [88.255.216.16:80]
NSOCK INFO [68.6330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65107 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36804 > 88.255.216.16:80 | SEND
NSOCK INFO [68.6340s] nsock_read(): Read request from IOD #2036 [88.255.216.16:80] (timeout: 10000ms) EID 65114
NSOCK INFO [68.6460s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65114 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36804 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.6470s] nsock_read(): Read request from IOD #2036 [88.255.216.16:80] (timeout: 10000ms) EID 65122
NSOCK INFO [68.6470s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65122 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36804 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.6480s] nsock_iod_delete(): nsock_iod_delete (IOD #2036)
NSOCK INFO [68.6480s] nsock_iod_new2(): nsock_iod_new (IOD #2037)
NSOCK INFO [68.6490s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2037) EID 65128
NSOCK INFO [68.6630s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65128 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36816 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36816 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 6f 75 72 63 65 2f 20 48 54 54 GET /source/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [68.6630s] nsock_write(): Write request for 178 bytes to IOD #2037 EID 65139 [88.255.216.16:80]
NSOCK INFO [68.6630s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65139 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36816 > 88.255.216.16:80 | SEND
NSOCK INFO [68.6650s] nsock_read(): Read request from IOD #2037 [88.255.216.16:80] (timeout: 10000ms) EID 65146
NSOCK INFO [68.6770s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65146 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36816 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.6780s] nsock_read(): Read request from IOD #2037 [88.255.216.16:80] (timeout: 10000ms) EID 65154
NSOCK INFO [68.6780s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65154 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36816 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.6780s] nsock_iod_delete(): nsock_iod_delete (IOD #2037)
NSOCK INFO [68.6780s] nsock_iod_new2(): nsock_iod_new (IOD #2038)
NSOCK INFO [68.6780s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2038) EID 65160
NSOCK INFO [68.6920s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65160 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36822 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36822 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 71 6c 2f 20 48 54 54 50 2f 31 GET /sql/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [68.6930s] nsock_write(): Write request for 175 bytes to IOD #2038 EID 65171 [88.255.216.16:80]
NSOCK INFO [68.6930s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65171 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36822 > 88.255.216.16:80 | SEND
NSOCK INFO [68.6930s] nsock_read(): Read request from IOD #2038 [88.255.216.16:80] (timeout: 10000ms) EID 65178
NSOCK INFO [68.7060s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65178 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36822 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.7080s] nsock_read(): Read request from IOD #2038 [88.255.216.16:80] (timeout: 10000ms) EID 65186
NSOCK INFO [68.7080s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65186 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36822 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.7090s] nsock_iod_delete(): nsock_iod_delete (IOD #2038)
NSOCK INFO [68.7090s] nsock_iod_new2(): nsock_iod_new (IOD #2039)
NSOCK INFO [68.7090s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2039) EID 65192
NSOCK INFO [68.7220s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65192 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36836 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36836 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 71 75 69 64 2f 20 48 54 54 50 GET /squid/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [68.7230s] nsock_write(): Write request for 177 bytes to IOD #2039 EID 65203 [88.255.216.16:80]
NSOCK INFO [68.7230s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65203 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36836 > 88.255.216.16:80 | SEND
NSOCK INFO [68.7240s] nsock_read(): Read request from IOD #2039 [88.255.216.16:80] (timeout: 10000ms) EID 65210
NSOCK INFO [68.7360s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65210 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36836 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.7370s] nsock_read(): Read request from IOD #2039 [88.255.216.16:80] (timeout: 10000ms) EID 65218
NSOCK INFO [68.7370s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65218 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36836 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.7370s] nsock_iod_delete(): nsock_iod_delete (IOD #2039)
NSOCK INFO [68.7370s] nsock_iod_new2(): nsock_iod_new (IOD #2040)
NSOCK INFO [68.7380s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2040) EID 65224
NSOCK INFO [68.7500s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65224 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36840 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36840 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 72 63 2f 20 48 54 54 50 2f 31 GET /src/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [68.7510s] nsock_write(): Write request for 175 bytes to IOD #2040 EID 65235 [88.255.216.16:80]
NSOCK INFO [68.7510s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65235 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36840 > 88.255.216.16:80 | SEND
NSOCK INFO [68.7510s] nsock_read(): Read request from IOD #2040 [88.255.216.16:80] (timeout: 10000ms) EID 65242
NSOCK INFO [68.7640s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65242 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36840 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.7650s] nsock_read(): Read request from IOD #2040 [88.255.216.16:80] (timeout: 10000ms) EID 65250
NSOCK INFO [68.7650s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65250 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36840 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.7650s] nsock_iod_delete(): nsock_iod_delete (IOD #2040)
NSOCK INFO [68.7650s] nsock_iod_new2(): nsock_iod_new (IOD #2041)
NSOCK INFO [68.7650s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2041) EID 65256
NSOCK INFO [68.7780s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65256 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36842 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36842 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 72 63 68 61 64 6d 2f 20 48 54 GET /srchadm/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [68.7790s] nsock_write(): Write request for 179 bytes to IOD #2041 EID 65267 [88.255.216.16:80]
NSOCK INFO [68.7790s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65267 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36842 > 88.255.216.16:80 | SEND
NSOCK INFO [68.7800s] nsock_read(): Read request from IOD #2041 [88.255.216.16:80] (timeout: 10000ms) EID 65274
NSOCK INFO [68.7920s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65274 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36842 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.7930s] nsock_read(): Read request from IOD #2041 [88.255.216.16:80] (timeout: 10000ms) EID 65282
NSOCK INFO [68.7930s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65282 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36842 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.7930s] nsock_iod_delete(): nsock_iod_delete (IOD #2041)
NSOCK INFO [68.7930s] nsock_iod_new2(): nsock_iod_new (IOD #2042)
NSOCK INFO [68.7940s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2042) EID 65288
NSOCK INFO [68.8070s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65288 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36856 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36856 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 73 69 2f 20 48 54 54 50 2f 31 GET /ssi/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [68.8080s] nsock_write(): Write request for 175 bytes to IOD #2042 EID 65299 [88.255.216.16:80]
NSOCK INFO [68.8080s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65299 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36856 > 88.255.216.16:80 | SEND
NSOCK INFO [68.8090s] nsock_read(): Read request from IOD #2042 [88.255.216.16:80] (timeout: 10000ms) EID 65306
NSOCK INFO [68.8220s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65306 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36856 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.8230s] nsock_read(): Read request from IOD #2042 [88.255.216.16:80] (timeout: 10000ms) EID 65314
NSOCK INFO [68.8230s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65314 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36856 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.8240s] nsock_iod_delete(): nsock_iod_delete (IOD #2042)
NSOCK INFO [68.8240s] nsock_iod_new2(): nsock_iod_new (IOD #2043)
NSOCK INFO [68.8240s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2043) EID 65320
NSOCK INFO [68.8380s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65320 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36872 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36872 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 73 6c 2f 20 48 54 54 50 2f 31 GET /ssl/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [68.8380s] nsock_write(): Write request for 175 bytes to IOD #2043 EID 65331 [88.255.216.16:80]
NSOCK INFO [68.8380s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65331 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36872 > 88.255.216.16:80 | SEND
NSOCK INFO [68.8390s] nsock_read(): Read request from IOD #2043 [88.255.216.16:80] (timeout: 10000ms) EID 65338
NSOCK INFO [68.8520s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65338 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36872 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.8530s] nsock_read(): Read request from IOD #2043 [88.255.216.16:80] (timeout: 10000ms) EID 65346
NSOCK INFO [68.8530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65346 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36872 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.8530s] nsock_iod_delete(): nsock_iod_delete (IOD #2043)
NSOCK INFO [68.8530s] nsock_iod_new2(): nsock_iod_new (IOD #2044)
NSOCK INFO [68.8540s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2044) EID 65352
NSOCK INFO [68.8670s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65352 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36888 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36888 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 73 6c 6b 65 79 73 2f 20 48 54 GET /sslkeys/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [68.8680s] nsock_write(): Write request for 179 bytes to IOD #2044 EID 65363 [88.255.216.16:80]
NSOCK INFO [68.8680s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65363 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36888 > 88.255.216.16:80 | SEND
NSOCK INFO [68.8690s] nsock_read(): Read request from IOD #2044 [88.255.216.16:80] (timeout: 10000ms) EID 65370
NSOCK INFO [68.8810s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65370 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36888 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.8830s] nsock_read(): Read request from IOD #2044 [88.255.216.16:80] (timeout: 10000ms) EID 65378
NSOCK INFO [68.8830s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65378 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36888 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.8840s] nsock_iod_delete(): nsock_iod_delete (IOD #2044)
NSOCK INFO [68.8840s] nsock_iod_new2(): nsock_iod_new (IOD #2045)
NSOCK INFO [68.8840s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2045) EID 65384
NSOCK INFO [68.8970s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65384 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36904 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36904 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 66 66 2f 20 48 54 54 50 GET /staff/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [68.8980s] nsock_write(): Write request for 177 bytes to IOD #2045 EID 65395 [88.255.216.16:80]
NSOCK INFO [68.8980s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65395 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36904 > 88.255.216.16:80 | SEND
NSOCK INFO [68.8990s] nsock_read(): Read request from IOD #2045 [88.255.216.16:80] (timeout: 10000ms) EID 65402
NSOCK INFO [68.9110s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65402 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36904 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.9120s] nsock_read(): Read request from IOD #2045 [88.255.216.16:80] (timeout: 10000ms) EID 65410
NSOCK INFO [68.9120s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65410 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36904 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.9130s] nsock_iod_delete(): nsock_iod_delete (IOD #2045)
NSOCK INFO [68.9130s] nsock_iod_new2(): nsock_iod_new (IOD #2046)
NSOCK INFO [68.9130s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2046) EID 65416
NSOCK INFO [68.9260s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65416 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36908 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36908 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 65 2f 20 48 54 54 50 GET /state/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [68.9270s] nsock_write(): Write request for 177 bytes to IOD #2046 EID 65427 [88.255.216.16:80]
NSOCK INFO [68.9270s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65427 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36908 > 88.255.216.16:80 | SEND
NSOCK INFO [68.9280s] nsock_read(): Read request from IOD #2046 [88.255.216.16:80] (timeout: 10000ms) EID 65434
NSOCK INFO [68.9410s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65434 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36908 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.9410s] nsock_read(): Read request from IOD #2046 [88.255.216.16:80] (timeout: 10000ms) EID 65442
NSOCK INFO [68.9410s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65442 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36908 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.9420s] nsock_iod_delete(): nsock_iod_delete (IOD #2046)
NSOCK INFO [68.9420s] nsock_iod_new2(): nsock_iod_new (IOD #2047)
NSOCK INFO [68.9420s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2047) EID 65448
NSOCK INFO [68.9560s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65448 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36918 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36918 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 2f 20 48 54 54 50 2f GET /stat/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [68.9570s] nsock_write(): Write request for 176 bytes to IOD #2047 EID 65459 [88.255.216.16:80]
NSOCK INFO [68.9570s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65459 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36918 > 88.255.216.16:80 | SEND
NSOCK INFO [68.9580s] nsock_read(): Read request from IOD #2047 [88.255.216.16:80] (timeout: 10000ms) EID 65466
NSOCK INFO [68.9710s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65466 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36918 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [68.9720s] nsock_read(): Read request from IOD #2047 [88.255.216.16:80] (timeout: 10000ms) EID 65474
NSOCK INFO [68.9720s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65474 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36918 > 88.255.216.16:80 | CLOSE
NSOCK INFO [68.9720s] nsock_iod_delete(): nsock_iod_delete (IOD #2047)
NSOCK INFO [68.9720s] nsock_iod_new2(): nsock_iod_new (IOD #2048)
NSOCK INFO [68.9730s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2048) EID 65480
NSOCK INFO [68.9850s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65480 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36924 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36924 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 69 73 74 69 63 2f 20 GET /statistic/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [68.9860s] nsock_write(): Write request for 181 bytes to IOD #2048 EID 65491 [88.255.216.16:80]
NSOCK INFO [68.9860s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65491 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36924 > 88.255.216.16:80 | SEND
NSOCK INFO [68.9870s] nsock_read(): Read request from IOD #2048 [88.255.216.16:80] (timeout: 10000ms) EID 65498
NSOCK INFO [69.0000s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65498 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36924 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.0000s] nsock_read(): Read request from IOD #2048 [88.255.216.16:80] (timeout: 10000ms) EID 65506
NSOCK INFO [69.0000s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65506 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36924 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.0010s] nsock_iod_delete(): nsock_iod_delete (IOD #2048)
NSOCK INFO [69.0010s] nsock_iod_new2(): nsock_iod_new (IOD #2049)
NSOCK INFO [69.0010s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2049) EID 65512
NSOCK INFO [69.0190s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65512 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36928 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36928 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 69 73 74 69 63 73 2f GET /statistics/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [69.0210s] nsock_write(): Write request for 182 bytes to IOD #2049 EID 65523 [88.255.216.16:80]
NSOCK INFO [69.0210s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65523 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36928 > 88.255.216.16:80 | SEND
NSOCK INFO [69.0220s] nsock_read(): Read request from IOD #2049 [88.255.216.16:80] (timeout: 10000ms) EID 65530
NSOCK INFO [69.0370s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65530 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36928 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.0380s] nsock_read(): Read request from IOD #2049 [88.255.216.16:80] (timeout: 10000ms) EID 65538
NSOCK INFO [69.0380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65538 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36928 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.0390s] nsock_iod_delete(): nsock_iod_delete (IOD #2049)
NSOCK INFO [69.0390s] nsock_iod_new2(): nsock_iod_new (IOD #2050)
NSOCK INFO [69.0390s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2050) EID 65544
NSOCK INFO [69.0530s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65544 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36940 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36940 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 73 2d 62 69 6e 2d 70 GET /stats-bin-p
00000010: 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 / HTTP/1.1  Host
00000020: 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e : 88.255.216.16.
00000030: 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d static.ttnet.com
00000040: 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a .tr  User-Agent:
00000050: 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f  Mozilla/5.0 (co
00000060: 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 mpatible; Nmap S
00000070: 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b cripting Engine;
00000080: 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72  https://nmap.or
00000090: 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 g/book/nse.html)
000000a0: 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c   Connection: cl
000000b0: 6f 73 65 0d 0a 0d 0a                            ose    

NSOCK INFO [69.0540s] nsock_write(): Write request for 183 bytes to IOD #2050 EID 65555 [88.255.216.16:80]
NSOCK INFO [69.0540s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65555 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36940 > 88.255.216.16:80 | SEND
NSOCK INFO [69.0550s] nsock_read(): Read request from IOD #2050 [88.255.216.16:80] (timeout: 10000ms) EID 65562
NSOCK INFO [69.0670s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65562 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36940 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.0680s] nsock_read(): Read request from IOD #2050 [88.255.216.16:80] (timeout: 10000ms) EID 65570
NSOCK INFO [69.0680s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65570 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36940 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.0680s] nsock_iod_delete(): nsock_iod_delete (IOD #2050)
NSOCK INFO [69.0680s] nsock_iod_new2(): nsock_iod_new (IOD #2051)
NSOCK INFO [69.0690s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2051) EID 65576
NSOCK INFO [69.0810s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65576 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36948 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36948 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 73 2f 20 48 54 54 50 GET /stats/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [69.0820s] nsock_write(): Write request for 177 bytes to IOD #2051 EID 65587 [88.255.216.16:80]
NSOCK INFO [69.0820s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65587 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36948 > 88.255.216.16:80 | SEND
NSOCK INFO [69.0830s] nsock_read(): Read request from IOD #2051 [88.255.216.16:80] (timeout: 10000ms) EID 65594
NSOCK INFO [69.0960s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65594 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36948 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.0970s] nsock_read(): Read request from IOD #2051 [88.255.216.16:80] (timeout: 10000ms) EID 65602
NSOCK INFO [69.0970s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65602 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36948 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.0970s] nsock_iod_delete(): nsock_iod_delete (IOD #2051)
NSOCK INFO [69.0970s] nsock_iod_new2(): nsock_iod_new (IOD #2052)
NSOCK INFO [69.0970s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2052) EID 65608
NSOCK INFO [69.1110s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65608 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36952 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36952 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 73 5f 6f 6c 64 2f 20 GET /stats_old/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [69.1120s] nsock_write(): Write request for 181 bytes to IOD #2052 EID 65619 [88.255.216.16:80]
NSOCK INFO [69.1120s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65619 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36952 > 88.255.216.16:80 | SEND
NSOCK INFO [69.1140s] nsock_read(): Read request from IOD #2052 [88.255.216.16:80] (timeout: 10000ms) EID 65626
NSOCK INFO [69.1260s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65626 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36952 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.1270s] nsock_read(): Read request from IOD #2052 [88.255.216.16:80] (timeout: 10000ms) EID 65634
NSOCK INFO [69.1270s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65634 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36952 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.1270s] nsock_iod_delete(): nsock_iod_delete (IOD #2052)
NSOCK INFO [69.1270s] nsock_iod_new2(): nsock_iod_new (IOD #2053)
NSOCK INFO [69.1270s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2053) EID 65640
NSOCK INFO [69.1400s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65640 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36966 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36966 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 61 74 75 73 2f 20 48 54 54 GET /status/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [69.1410s] nsock_write(): Write request for 178 bytes to IOD #2053 EID 65651 [88.255.216.16:80]
NSOCK INFO [69.1410s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65651 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36966 > 88.255.216.16:80 | SEND
NSOCK INFO [69.1430s] nsock_read(): Read request from IOD #2053 [88.255.216.16:80] (timeout: 10000ms) EID 65658
NSOCK INFO [69.1540s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65658 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36966 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.1560s] nsock_read(): Read request from IOD #2053 [88.255.216.16:80] (timeout: 10000ms) EID 65666
NSOCK INFO [69.1560s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65666 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36966 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.1560s] nsock_iod_delete(): nsock_iod_delete (IOD #2053)
NSOCK INFO [69.1560s] nsock_iod_new2(): nsock_iod_new (IOD #2054)
NSOCK INFO [69.1560s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2054) EID 65672
NSOCK INFO [69.1690s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65672 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36970 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36970 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 6f 72 61 67 65 2f 20 48 54 GET /storage/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [69.1700s] nsock_write(): Write request for 179 bytes to IOD #2054 EID 65683 [88.255.216.16:80]
NSOCK INFO [69.1700s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65683 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36970 > 88.255.216.16:80 | SEND
NSOCK INFO [69.1720s] nsock_read(): Read request from IOD #2054 [88.255.216.16:80] (timeout: 10000ms) EID 65690
NSOCK INFO [69.1840s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65690 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36970 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.1850s] nsock_read(): Read request from IOD #2054 [88.255.216.16:80] (timeout: 10000ms) EID 65698
NSOCK INFO [69.1850s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65698 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36970 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.1860s] nsock_iod_delete(): nsock_iod_delete (IOD #2054)
NSOCK INFO [69.1860s] nsock_iod_new2(): nsock_iod_new (IOD #2055)
NSOCK INFO [69.1860s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2055) EID 65704
NSOCK INFO [69.1990s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65704 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36986 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:36986 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 53 74 6f 72 65 44 42 2f 20 48 54 GET /StoreDB/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [69.2010s] nsock_write(): Write request for 179 bytes to IOD #2055 EID 65715 [88.255.216.16:80]
NSOCK INFO [69.2010s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65715 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36986 > 88.255.216.16:80 | SEND
NSOCK INFO [69.2030s] nsock_read(): Read request from IOD #2055 [88.255.216.16:80] (timeout: 10000ms) EID 65722
NSOCK INFO [69.2150s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65722 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:36986 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.2150s] nsock_read(): Read request from IOD #2055 [88.255.216.16:80] (timeout: 10000ms) EID 65730
NSOCK INFO [69.2150s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65730 [88.255.216.16:80]
NSE: TCP 192.168.31.147:36986 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.2160s] nsock_iod_delete(): nsock_iod_delete (IOD #2055)
NSOCK INFO [69.2160s] nsock_iod_new2(): nsock_iod_new (IOD #2056)
NSOCK INFO [69.2160s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2056) EID 65736
NSOCK INFO [69.2300s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65736 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37002 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37002 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 6f 72 65 2f 20 48 54 54 50 GET /store/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [69.2310s] nsock_write(): Write request for 177 bytes to IOD #2056 EID 65747 [88.255.216.16:80]
NSOCK INFO [69.2310s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65747 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37002 > 88.255.216.16:80 | SEND
NSOCK INFO [69.2320s] nsock_read(): Read request from IOD #2056 [88.255.216.16:80] (timeout: 10000ms) EID 65754
NSOCK INFO [69.2440s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65754 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37002 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.2450s] nsock_read(): Read request from IOD #2056 [88.255.216.16:80] (timeout: 10000ms) EID 65762
NSOCK INFO [69.2450s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65762 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37002 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.2450s] nsock_iod_delete(): nsock_iod_delete (IOD #2056)
NSOCK INFO [69.2450s] nsock_iod_new2(): nsock_iod_new (IOD #2057)
NSOCK INFO [69.2460s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2057) EID 65768
NSOCK INFO [69.2590s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65768 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37010 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37010 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 6f 72 65 6d 67 72 2f 20 48 GET /storemgr/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [69.2600s] nsock_write(): Write request for 180 bytes to IOD #2057 EID 65779 [88.255.216.16:80]
NSOCK INFO [69.2600s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65779 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37010 > 88.255.216.16:80 | SEND
NSOCK INFO [69.2600s] nsock_read(): Read request from IOD #2057 [88.255.216.16:80] (timeout: 10000ms) EID 65786
NSOCK INFO [69.2720s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65786 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37010 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.2730s] nsock_read(): Read request from IOD #2057 [88.255.216.16:80] (timeout: 10000ms) EID 65794
NSOCK INFO [69.2730s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65794 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37010 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.2740s] nsock_iod_delete(): nsock_iod_delete (IOD #2057)
NSOCK INFO [69.2740s] nsock_iod_new2(): nsock_iod_new (IOD #2058)
NSOCK INFO [69.2740s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2058) EID 65800
NSOCK INFO [69.2880s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65800 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37014 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37014 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 72 6f 6e 67 68 6f 6c 64 2d GET /stronghold-
00000010: 69 6e 66 6f 2f 20 48 54 54 50 2f 31 2e 31 0d 0a info/ HTTP/1.1  
00000020: 48 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 Host: 88.255.216
00000030: 2e 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 .16.static.ttnet
00000040: 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 .com.tr  User-Ag
00000050: 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 ent: Mozilla/5.0
00000060: 20 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d  (compatible; Nm
00000070: 61 70 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 ap Scripting Eng
00000080: 69 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 ine; https://nma
00000090: 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 p.org/book/nse.h
000000a0: 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e tml)  Connection
000000b0: 3a 20 63 6c 6f 73 65 0d 0a 0d 0a                : close    

NSOCK INFO [69.2890s] nsock_write(): Write request for 187 bytes to IOD #2058 EID 65811 [88.255.216.16:80]
NSOCK INFO [69.2890s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65811 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37014 > 88.255.216.16:80 | SEND
NSOCK INFO [69.2890s] nsock_read(): Read request from IOD #2058 [88.255.216.16:80] (timeout: 10000ms) EID 65818
NSOCK INFO [69.3020s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65818 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37014 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.3030s] nsock_read(): Read request from IOD #2058 [88.255.216.16:80] (timeout: 10000ms) EID 65826
NSOCK INFO [69.3030s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65826 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37014 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.3040s] nsock_iod_delete(): nsock_iod_delete (IOD #2058)
NSOCK INFO [69.3040s] nsock_iod_new2(): nsock_iod_new (IOD #2059)
NSOCK INFO [69.3040s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2059) EID 65832
NSOCK INFO [69.3170s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65832 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37024 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37024 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 72 6f 6e 67 68 6f 6c 64 2d GET /stronghold-
00000010: 73 74 61 74 75 73 2f 20 48 54 54 50 2f 31 2e 31 status/ HTTP/1.1
00000020: 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32   Host: 88.255.2
00000030: 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 16.16.static.ttn
00000040: 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d et.com.tr  User-
00000050: 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 Agent: Mozilla/5
00000060: 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 .0 (compatible; 
00000070: 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 20 45 Nmap Scripting E
00000080: 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e ngine; https://n
00000090: 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 map.org/book/nse
000000a0: 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 .html)  Connecti
000000b0: 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a          on: close    

NSOCK INFO [69.3180s] nsock_write(): Write request for 189 bytes to IOD #2059 EID 65843 [88.255.216.16:80]
NSOCK INFO [69.3180s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65843 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37024 > 88.255.216.16:80 | SEND
NSOCK INFO [69.3190s] nsock_read(): Read request from IOD #2059 [88.255.216.16:80] (timeout: 10000ms) EID 65850
NSOCK INFO [69.3310s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65850 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37024 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.3330s] nsock_read(): Read request from IOD #2059 [88.255.216.16:80] (timeout: 10000ms) EID 65858
NSOCK INFO [69.3330s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65858 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37024 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.3330s] nsock_iod_delete(): nsock_iod_delete (IOD #2059)
NSOCK INFO [69.3330s] nsock_iod_new2(): nsock_iod_new (IOD #2060)
NSOCK INFO [69.3330s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2060) EID 65864
NSOCK INFO [69.3470s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65864 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37040 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37040 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 75 66 66 2f 20 48 54 54 50 GET /stuff/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [69.3470s] nsock_write(): Write request for 177 bytes to IOD #2060 EID 65875 [88.255.216.16:80]
NSOCK INFO [69.3470s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65875 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37040 > 88.255.216.16:80 | SEND
NSOCK INFO [69.3480s] nsock_read(): Read request from IOD #2060 [88.255.216.16:80] (timeout: 10000ms) EID 65882
NSOCK INFO [69.3610s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65882 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37040 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.3620s] nsock_read(): Read request from IOD #2060 [88.255.216.16:80] (timeout: 10000ms) EID 65890
NSOCK INFO [69.3630s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65890 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37040 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.3630s] nsock_iod_delete(): nsock_iod_delete (IOD #2060)
NSOCK INFO [69.3630s] nsock_iod_new2(): nsock_iod_new (IOD #2061)
NSOCK INFO [69.3630s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2061) EID 65896
NSOCK INFO [69.3770s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65896 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37054 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37054 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 79 6c 65 2f 20 48 54 54 50 GET /style/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [69.3770s] nsock_write(): Write request for 177 bytes to IOD #2061 EID 65907 [88.255.216.16:80]
NSOCK INFO [69.3770s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65907 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37054 > 88.255.216.16:80 | SEND
NSOCK INFO [69.3780s] nsock_read(): Read request from IOD #2061 [88.255.216.16:80] (timeout: 10000ms) EID 65914
NSOCK INFO [69.3920s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65914 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37054 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.3930s] nsock_read(): Read request from IOD #2061 [88.255.216.16:80] (timeout: 10000ms) EID 65922
NSOCK INFO [69.3930s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65922 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37054 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.3930s] nsock_iod_delete(): nsock_iod_delete (IOD #2061)
NSOCK INFO [69.3930s] nsock_iod_new2(): nsock_iod_new (IOD #2062)
NSOCK INFO [69.3940s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2062) EID 65928
NSOCK INFO [69.4070s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65928 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37056 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37056 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 79 6c 65 73 2f 20 48 54 54 GET /styles/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [69.4080s] nsock_write(): Write request for 178 bytes to IOD #2062 EID 65939 [88.255.216.16:80]
NSOCK INFO [69.4080s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65939 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37056 > 88.255.216.16:80 | SEND
NSOCK INFO [69.4080s] nsock_read(): Read request from IOD #2062 [88.255.216.16:80] (timeout: 10000ms) EID 65946
NSOCK INFO [69.4220s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65946 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37056 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.4220s] nsock_read(): Read request from IOD #2062 [88.255.216.16:80] (timeout: 10000ms) EID 65954
NSOCK INFO [69.4220s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65954 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37056 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.4230s] nsock_iod_delete(): nsock_iod_delete (IOD #2062)
NSOCK INFO [69.4230s] nsock_iod_new2(): nsock_iod_new (IOD #2063)
NSOCK INFO [69.4230s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2063) EID 65960
NSOCK INFO [69.4370s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65960 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37068 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37068 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 79 6c 65 73 68 65 65 74 2f GET /stylesheet/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [69.4380s] nsock_write(): Write request for 182 bytes to IOD #2063 EID 65971 [88.255.216.16:80]
NSOCK INFO [69.4380s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 65971 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37068 > 88.255.216.16:80 | SEND
NSOCK INFO [69.4390s] nsock_read(): Read request from IOD #2063 [88.255.216.16:80] (timeout: 10000ms) EID 65978
NSOCK INFO [69.4520s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 65978 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37068 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.4530s] nsock_read(): Read request from IOD #2063 [88.255.216.16:80] (timeout: 10000ms) EID 65986
NSOCK INFO [69.4530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 65986 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37068 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.4530s] nsock_iod_delete(): nsock_iod_delete (IOD #2063)
NSOCK INFO [69.4530s] nsock_iod_new2(): nsock_iod_new (IOD #2064)
NSOCK INFO [69.4540s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2064) EID 65992
NSOCK INFO [69.4660s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 65992 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37070 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37070 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 74 79 6c 65 73 68 65 65 74 73 GET /stylesheets
00000010: 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 / HTTP/1.1  Host
00000020: 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e : 88.255.216.16.
00000030: 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d static.ttnet.com
00000040: 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a .tr  User-Agent:
00000050: 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f  Mozilla/5.0 (co
00000060: 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 mpatible; Nmap S
00000070: 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b cripting Engine;
00000080: 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72  https://nmap.or
00000090: 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 g/book/nse.html)
000000a0: 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c   Connection: cl
000000b0: 6f 73 65 0d 0a 0d 0a                            ose    

NSOCK INFO [69.4680s] nsock_write(): Write request for 183 bytes to IOD #2064 EID 66003 [88.255.216.16:80]
NSOCK INFO [69.4680s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66003 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37070 > 88.255.216.16:80 | SEND
NSOCK INFO [69.4700s] nsock_read(): Read request from IOD #2064 [88.255.216.16:80] (timeout: 10000ms) EID 66010
NSOCK INFO [69.4820s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66010 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37070 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.4830s] nsock_read(): Read request from IOD #2064 [88.255.216.16:80] (timeout: 10000ms) EID 66018
NSOCK INFO [69.4830s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66018 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37070 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.4840s] nsock_iod_delete(): nsock_iod_delete (IOD #2064)
NSOCK INFO [69.4840s] nsock_iod_new2(): nsock_iod_new (IOD #2065)
NSOCK INFO [69.4840s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2065) EID 66024
NSOCK INFO [69.4970s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66024 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37080 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37080 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 62 69 72 2f 20 48 54 54 50 GET /subir/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [69.4980s] nsock_write(): Write request for 177 bytes to IOD #2065 EID 66035 [88.255.216.16:80]
NSOCK INFO [69.4980s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66035 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37080 > 88.255.216.16:80 | SEND
NSOCK INFO [69.5000s] nsock_read(): Read request from IOD #2065 [88.255.216.16:80] (timeout: 10000ms) EID 66042
NSOCK INFO [69.5110s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66042 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37080 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.5120s] nsock_read(): Read request from IOD #2065 [88.255.216.16:80] (timeout: 10000ms) EID 66050
NSOCK INFO [69.5120s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66050 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37080 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.5130s] nsock_iod_delete(): nsock_iod_delete (IOD #2065)
NSOCK INFO [69.5130s] nsock_iod_new2(): nsock_iod_new (IOD #2066)
NSOCK INFO [69.5140s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2066) EID 66056
NSOCK INFO [69.5270s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66056 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37082 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37082 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 6e 2f 20 48 54 54 50 2f 31 GET /sun/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [69.5280s] nsock_write(): Write request for 175 bytes to IOD #2066 EID 66067 [88.255.216.16:80]
NSOCK INFO [69.5280s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66067 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37082 > 88.255.216.16:80 | SEND
NSOCK INFO [69.5290s] nsock_read(): Read request from IOD #2066 [88.255.216.16:80] (timeout: 10000ms) EID 66074
NSOCK INFO [69.5410s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66074 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37082 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.5420s] nsock_read(): Read request from IOD #2066 [88.255.216.16:80] (timeout: 10000ms) EID 66082
NSOCK INFO [69.5420s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66082 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37082 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.5420s] nsock_iod_delete(): nsock_iod_delete (IOD #2066)
NSOCK INFO [69.5420s] nsock_iod_new2(): nsock_iod_new (IOD #2067)
NSOCK INFO [69.5420s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2067) EID 66088
NSOCK INFO [69.5560s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66088 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37086 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37086 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 70 65 72 5f 73 74 61 74 73 GET /super_stats
00000010: 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 / HTTP/1.1  Host
00000020: 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e : 88.255.216.16.
00000030: 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d static.ttnet.com
00000040: 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a .tr  User-Agent:
00000050: 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f  Mozilla/5.0 (co
00000060: 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 mpatible; Nmap S
00000070: 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b cripting Engine;
00000080: 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72  https://nmap.or
00000090: 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 g/book/nse.html)
000000a0: 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c   Connection: cl
000000b0: 6f 73 65 0d 0a 0d 0a                            ose    

NSOCK INFO [69.5570s] nsock_write(): Write request for 183 bytes to IOD #2067 EID 66099 [88.255.216.16:80]
NSOCK INFO [69.5570s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66099 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37086 > 88.255.216.16:80 | SEND
NSOCK INFO [69.5590s] nsock_read(): Read request from IOD #2067 [88.255.216.16:80] (timeout: 10000ms) EID 66106
NSOCK INFO [69.5710s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66106 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37086 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.5720s] nsock_read(): Read request from IOD #2067 [88.255.216.16:80] (timeout: 10000ms) EID 66114
NSOCK INFO [69.5720s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66114 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37086 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.5720s] nsock_iod_delete(): nsock_iod_delete (IOD #2067)
NSOCK INFO [69.5720s] nsock_iod_new2(): nsock_iod_new (IOD #2068)
NSOCK INFO [69.5730s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2068) EID 66120
NSOCK INFO [69.5870s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66120 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37088 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37088 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 70 70 6c 69 65 72 2f 20 48 GET /supplier/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [69.5880s] nsock_write(): Write request for 180 bytes to IOD #2068 EID 66131 [88.255.216.16:80]
NSOCK INFO [69.5880s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66131 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37088 > 88.255.216.16:80 | SEND
NSOCK INFO [69.5890s] nsock_read(): Read request from IOD #2068 [88.255.216.16:80] (timeout: 10000ms) EID 66138
NSOCK INFO [69.6010s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66138 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37088 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.6030s] nsock_read(): Read request from IOD #2068 [88.255.216.16:80] (timeout: 10000ms) EID 66146
NSOCK INFO [69.6030s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66146 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37088 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.6040s] nsock_iod_delete(): nsock_iod_delete (IOD #2068)
NSOCK INFO [69.6040s] nsock_iod_new2(): nsock_iod_new (IOD #2069)
NSOCK INFO [69.6040s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2069) EID 66152
NSOCK INFO [69.6170s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66152 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37104 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37104 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 70 70 6c 69 65 72 73 2f 20 GET /suppliers/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [69.6180s] nsock_write(): Write request for 181 bytes to IOD #2069 EID 66163 [88.255.216.16:80]
NSOCK INFO [69.6180s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66163 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37104 > 88.255.216.16:80 | SEND
NSOCK INFO [69.6190s] nsock_read(): Read request from IOD #2069 [88.255.216.16:80] (timeout: 10000ms) EID 66170
NSOCK INFO [69.6310s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66170 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37104 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.6320s] nsock_read(): Read request from IOD #2069 [88.255.216.16:80] (timeout: 10000ms) EID 66178
NSOCK INFO [69.6320s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66178 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37104 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.6320s] nsock_iod_delete(): nsock_iod_delete (IOD #2069)
NSOCK INFO [69.6320s] nsock_iod_new2(): nsock_iod_new (IOD #2070)
NSOCK INFO [69.6330s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2070) EID 66184
NSOCK INFO [69.6470s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66184 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37116 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37116 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 70 70 6c 79 2f 20 48 54 54 GET /supply/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [69.6480s] nsock_write(): Write request for 178 bytes to IOD #2070 EID 66195 [88.255.216.16:80]
NSOCK INFO [69.6480s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66195 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37116 > 88.255.216.16:80 | SEND
NSOCK INFO [69.6490s] nsock_read(): Read request from IOD #2070 [88.255.216.16:80] (timeout: 10000ms) EID 66202
NSOCK INFO [69.6610s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66202 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37116 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.6620s] nsock_read(): Read request from IOD #2070 [88.255.216.16:80] (timeout: 10000ms) EID 66210
NSOCK INFO [69.6620s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66210 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37116 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.6630s] nsock_iod_delete(): nsock_iod_delete (IOD #2070)
NSOCK INFO [69.6630s] nsock_iod_new2(): nsock_iod_new (IOD #2071)
NSOCK INFO [69.6630s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2071) EID 66216
NSOCK INFO [69.6770s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66216 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37128 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37128 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 70 70 6f 72 74 65 72 2f 20 GET /supporter/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [69.6770s] nsock_write(): Write request for 181 bytes to IOD #2071 EID 66227 [88.255.216.16:80]
NSOCK INFO [69.6770s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66227 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37128 > 88.255.216.16:80 | SEND
NSOCK INFO [69.6780s] nsock_read(): Read request from IOD #2071 [88.255.216.16:80] (timeout: 10000ms) EID 66234
NSOCK INFO [69.6900s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66234 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37128 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.6910s] nsock_read(): Read request from IOD #2071 [88.255.216.16:80] (timeout: 10000ms) EID 66242
NSOCK INFO [69.6910s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66242 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37128 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.6910s] nsock_iod_delete(): nsock_iod_delete (IOD #2071)
NSOCK INFO [69.6910s] nsock_iod_new2(): nsock_iod_new (IOD #2072)
NSOCK INFO [69.6920s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2072) EID 66248
NSOCK INFO [69.7060s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66248 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37134 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37134 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 75 70 70 6f 72 74 2f 20 48 54 GET /support/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [69.7070s] nsock_write(): Write request for 179 bytes to IOD #2072 EID 66259 [88.255.216.16:80]
NSOCK INFO [69.7070s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66259 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37134 > 88.255.216.16:80 | SEND
NSOCK INFO [69.7080s] nsock_read(): Read request from IOD #2072 [88.255.216.16:80] (timeout: 10000ms) EID 66266
NSOCK INFO [69.7200s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66266 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37134 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.7210s] nsock_read(): Read request from IOD #2072 [88.255.216.16:80] (timeout: 10000ms) EID 66274
NSOCK INFO [69.7210s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66274 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37134 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.7210s] nsock_iod_delete(): nsock_iod_delete (IOD #2072)
NSOCK INFO [69.7210s] nsock_iod_new2(): nsock_iod_new (IOD #2073)
NSOCK INFO [69.7220s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2073) EID 66280
NSOCK INFO [69.7340s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66280 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37138 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37138 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 79 73 61 64 6d 69 6e 2f 20 48 GET /sysadmin/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [69.7360s] nsock_write(): Write request for 180 bytes to IOD #2073 EID 66291 [88.255.216.16:80]
NSOCK INFO [69.7360s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66291 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37138 > 88.255.216.16:80 | SEND
NSOCK INFO [69.7370s] nsock_read(): Read request from IOD #2073 [88.255.216.16:80] (timeout: 10000ms) EID 66298
NSOCK INFO [69.7500s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66298 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37138 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.7510s] nsock_read(): Read request from IOD #2073 [88.255.216.16:80] (timeout: 10000ms) EID 66306
NSOCK INFO [69.7510s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66306 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37138 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.7510s] nsock_iod_delete(): nsock_iod_delete (IOD #2073)
NSOCK INFO [69.7510s] nsock_iod_new2(): nsock_iod_new (IOD #2074)
NSOCK INFO [69.7520s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2074) EID 66312
NSOCK INFO [69.7640s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66312 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37144 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37144 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 79 73 62 61 63 6b 75 70 2f 20 GET /sysbackup/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [69.7650s] nsock_write(): Write request for 181 bytes to IOD #2074 EID 66323 [88.255.216.16:80]
NSOCK INFO [69.7650s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66323 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37144 > 88.255.216.16:80 | SEND
NSOCK INFO [69.7660s] nsock_read(): Read request from IOD #2074 [88.255.216.16:80] (timeout: 10000ms) EID 66330
NSOCK INFO [69.7790s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66330 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37144 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.7790s] nsock_read(): Read request from IOD #2074 [88.255.216.16:80] (timeout: 10000ms) EID 66338
NSOCK INFO [69.7790s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66338 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37144 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.7800s] nsock_iod_delete(): nsock_iod_delete (IOD #2074)
NSOCK INFO [69.7800s] nsock_iod_new2(): nsock_iod_new (IOD #2075)
NSOCK INFO [69.7810s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2075) EID 66344
NSOCK INFO [69.7940s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66344 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37150 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37150 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 79 73 2f 20 48 54 54 50 2f 31 GET /sys/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [69.7950s] nsock_write(): Write request for 175 bytes to IOD #2075 EID 66355 [88.255.216.16:80]
NSOCK INFO [69.7950s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66355 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37150 > 88.255.216.16:80 | SEND
NSOCK INFO [69.7970s] nsock_read(): Read request from IOD #2075 [88.255.216.16:80] (timeout: 10000ms) EID 66362
NSOCK INFO [69.8080s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66362 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37150 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.8090s] nsock_read(): Read request from IOD #2075 [88.255.216.16:80] (timeout: 10000ms) EID 66370
NSOCK INFO [69.8090s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66370 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37150 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.8090s] nsock_iod_delete(): nsock_iod_delete (IOD #2075)
NSOCK INFO [69.8090s] nsock_iod_new2(): nsock_iod_new (IOD #2076)
NSOCK INFO [69.8100s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2076) EID 66376
NSOCK INFO [69.8230s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66376 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37166 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37166 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 79 73 74 65 6d 2f 20 48 54 54 GET /system/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [69.8230s] nsock_write(): Write request for 178 bytes to IOD #2076 EID 66387 [88.255.216.16:80]
NSOCK INFO [69.8230s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66387 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37166 > 88.255.216.16:80 | SEND
NSOCK INFO [69.8240s] nsock_read(): Read request from IOD #2076 [88.255.216.16:80] (timeout: 10000ms) EID 66394
NSOCK INFO [69.8370s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66394 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37166 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.8380s] nsock_read(): Read request from IOD #2076 [88.255.216.16:80] (timeout: 10000ms) EID 66402
NSOCK INFO [69.8380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66402 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37166 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.8390s] nsock_iod_delete(): nsock_iod_delete (IOD #2076)
NSOCK INFO [69.8390s] nsock_iod_new2(): nsock_iod_new (IOD #2077)
NSOCK INFO [69.8390s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2077) EID 66408
NSOCK INFO [69.8530s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66408 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37170 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37170 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 79 73 74 65 6d 73 2f 20 48 54 GET /systems/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [69.8540s] nsock_write(): Write request for 179 bytes to IOD #2077 EID 66419 [88.255.216.16:80]
NSOCK INFO [69.8540s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66419 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37170 > 88.255.216.16:80 | SEND
NSOCK INFO [69.8550s] nsock_read(): Read request from IOD #2077 [88.255.216.16:80] (timeout: 10000ms) EID 66426
NSOCK INFO [69.8670s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66426 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37170 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.8680s] nsock_read(): Read request from IOD #2077 [88.255.216.16:80] (timeout: 10000ms) EID 66434
NSOCK INFO [69.8680s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66434 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37170 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.8690s] nsock_iod_delete(): nsock_iod_delete (IOD #2077)
NSOCK INFO [69.8690s] nsock_iod_new2(): nsock_iod_new (IOD #2078)
NSOCK INFO [69.8700s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2078) EID 66440
NSOCK INFO [69.8830s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66440 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37186 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37186 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 61 72 2f 20 48 54 54 50 2f 31 GET /tar/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [69.8840s] nsock_write(): Write request for 175 bytes to IOD #2078 EID 66451 [88.255.216.16:80]
NSOCK INFO [69.8840s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66451 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37186 > 88.255.216.16:80 | SEND
NSOCK INFO [69.8850s] nsock_read(): Read request from IOD #2078 [88.255.216.16:80] (timeout: 10000ms) EID 66458
NSOCK INFO [69.8970s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66458 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37186 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.8970s] nsock_read(): Read request from IOD #2078 [88.255.216.16:80] (timeout: 10000ms) EID 66466
NSOCK INFO [69.8970s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66466 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37186 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.8980s] nsock_iod_delete(): nsock_iod_delete (IOD #2078)
NSOCK INFO [69.8980s] nsock_iod_new2(): nsock_iod_new (IOD #2079)
NSOCK INFO [69.8980s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2079) EID 66472
NSOCK INFO [69.9110s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66472 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37194 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37194 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 61 72 67 65 74 2f 20 48 54 54 GET /target/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [69.9110s] nsock_write(): Write request for 178 bytes to IOD #2079 EID 66483 [88.255.216.16:80]
NSOCK INFO [69.9110s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66483 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37194 > 88.255.216.16:80 | SEND
NSOCK INFO [69.9120s] nsock_read(): Read request from IOD #2079 [88.255.216.16:80] (timeout: 10000ms) EID 66490
NSOCK INFO [69.9240s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66490 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37194 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.9240s] nsock_read(): Read request from IOD #2079 [88.255.216.16:80] (timeout: 10000ms) EID 66498
NSOCK INFO [69.9240s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66498 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37194 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.9250s] nsock_iod_delete(): nsock_iod_delete (IOD #2079)
NSOCK INFO [69.9250s] nsock_iod_new2(): nsock_iod_new (IOD #2080)
NSOCK INFO [69.9250s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2080) EID 66504
NSOCK INFO [69.9380s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66504 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37210 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37210 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 61 72 6a 65 74 61 73 2f 20 48 GET /tarjetas/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [69.9390s] nsock_write(): Write request for 180 bytes to IOD #2080 EID 66515 [88.255.216.16:80]
NSOCK INFO [69.9390s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66515 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37210 > 88.255.216.16:80 | SEND
NSOCK INFO [69.9400s] nsock_read(): Read request from IOD #2080 [88.255.216.16:80] (timeout: 10000ms) EID 66522
NSOCK INFO [69.9520s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66522 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37210 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.9530s] nsock_read(): Read request from IOD #2080 [88.255.216.16:80] (timeout: 10000ms) EID 66530
NSOCK INFO [69.9530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66530 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37210 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.9530s] nsock_iod_delete(): nsock_iod_delete (IOD #2080)
NSOCK INFO [69.9530s] nsock_iod_new2(): nsock_iod_new (IOD #2081)
NSOCK INFO [69.9540s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2081) EID 66536
NSOCK INFO [69.9670s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66536 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37220 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37220 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 63 68 2f 20 48 54 54 50 2f GET /tech/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [69.9680s] nsock_write(): Write request for 176 bytes to IOD #2081 EID 66547 [88.255.216.16:80]
NSOCK INFO [69.9680s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66547 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37220 > 88.255.216.16:80 | SEND
NSOCK INFO [69.9700s] nsock_read(): Read request from IOD #2081 [88.255.216.16:80] (timeout: 10000ms) EID 66554
NSOCK INFO [69.9810s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66554 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37220 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [69.9830s] nsock_read(): Read request from IOD #2081 [88.255.216.16:80] (timeout: 10000ms) EID 66562
NSOCK INFO [69.9830s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66562 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37220 > 88.255.216.16:80 | CLOSE
NSOCK INFO [69.9830s] nsock_iod_delete(): nsock_iod_delete (IOD #2081)
NSOCK INFO [69.9830s] nsock_iod_new2(): nsock_iod_new (IOD #2082)
NSOCK INFO [69.9850s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2082) EID 66568
NSOCK INFO [69.9980s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66568 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37226 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37226 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 63 68 6e 6f 74 65 2f 20 48 GET /technote/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [69.9990s] nsock_write(): Write request for 180 bytes to IOD #2082 EID 66579 [88.255.216.16:80]
NSOCK INFO [69.9990s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66579 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37226 > 88.255.216.16:80 | SEND
NSOCK INFO [70.0000s] nsock_read(): Read request from IOD #2082 [88.255.216.16:80] (timeout: 10000ms) EID 66586
NSOCK INFO [70.0110s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66586 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37226 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.0130s] nsock_read(): Read request from IOD #2082 [88.255.216.16:80] (timeout: 10000ms) EID 66594
NSOCK INFO [70.0130s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66594 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37226 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.0130s] nsock_iod_delete(): nsock_iod_delete (IOD #2082)
NSOCK INFO [70.0130s] nsock_iod_new2(): nsock_iod_new (IOD #2083)
NSOCK INFO [70.0130s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2083) EID 66600
NSOCK INFO [70.0260s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66600 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37238 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37238 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 5f 68 74 6d 6c 2f 20 48 54 GET /te_html/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [70.0270s] nsock_write(): Write request for 179 bytes to IOD #2083 EID 66611 [88.255.216.16:80]
NSOCK INFO [70.0270s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66611 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37238 > 88.255.216.16:80 | SEND
NSOCK INFO [70.0280s] nsock_read(): Read request from IOD #2083 [88.255.216.16:80] (timeout: 10000ms) EID 66618
NSOCK INFO [70.0400s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66618 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37238 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.0400s] nsock_read(): Read request from IOD #2083 [88.255.216.16:80] (timeout: 10000ms) EID 66626
NSOCK INFO [70.0410s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66626 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37238 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.0410s] nsock_iod_delete(): nsock_iod_delete (IOD #2083)
NSOCK INFO [70.0410s] nsock_iod_new2(): nsock_iod_new (IOD #2084)
NSOCK INFO [70.0410s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2084) EID 66632
NSOCK INFO [70.0550s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66632 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37240 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37240 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 6d 70 2f 20 48 54 54 50 2f GET /temp/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [70.0560s] nsock_write(): Write request for 176 bytes to IOD #2084 EID 66643 [88.255.216.16:80]
NSOCK INFO [70.0560s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66643 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37240 > 88.255.216.16:80 | SEND
NSOCK INFO [70.0570s] nsock_read(): Read request from IOD #2084 [88.255.216.16:80] (timeout: 10000ms) EID 66650
NSOCK INFO [70.0700s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66650 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37240 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.0720s] nsock_read(): Read request from IOD #2084 [88.255.216.16:80] (timeout: 10000ms) EID 66658
NSOCK INFO [70.0720s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66658 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37240 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.0720s] nsock_iod_delete(): nsock_iod_delete (IOD #2084)
NSOCK INFO [70.0720s] nsock_iod_new2(): nsock_iod_new (IOD #2085)
NSOCK INFO [70.0730s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2085) EID 66664
NSOCK INFO [70.0870s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66664 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37254 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37254 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 6d 70 6c 61 74 65 2f 20 48 GET /template/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [70.0880s] nsock_write(): Write request for 180 bytes to IOD #2085 EID 66675 [88.255.216.16:80]
NSOCK INFO [70.0880s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66675 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37254 > 88.255.216.16:80 | SEND
NSOCK INFO [70.0880s] nsock_read(): Read request from IOD #2085 [88.255.216.16:80] (timeout: 10000ms) EID 66682
NSOCK INFO [70.1010s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66682 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37254 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.1020s] nsock_read(): Read request from IOD #2085 [88.255.216.16:80] (timeout: 10000ms) EID 66690
NSOCK INFO [70.1020s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66690 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37254 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.1030s] nsock_iod_delete(): nsock_iod_delete (IOD #2085)
NSOCK INFO [70.1030s] nsock_iod_new2(): nsock_iod_new (IOD #2086)
NSOCK INFO [70.1030s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2086) EID 66696
NSOCK INFO [70.1170s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66696 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37266 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37266 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 6d 70 6c 61 74 65 73 2f 20 GET /templates/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [70.1180s] nsock_write(): Write request for 181 bytes to IOD #2086 EID 66707 [88.255.216.16:80]
NSOCK INFO [70.1180s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66707 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37266 > 88.255.216.16:80 | SEND
NSOCK INFO [70.1180s] nsock_read(): Read request from IOD #2086 [88.255.216.16:80] (timeout: 10000ms) EID 66714
NSOCK INFO [70.1320s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66714 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37266 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.1340s] nsock_read(): Read request from IOD #2086 [88.255.216.16:80] (timeout: 10000ms) EID 66722
NSOCK INFO [70.1340s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66722 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37266 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.1350s] nsock_iod_delete(): nsock_iod_delete (IOD #2086)
NSOCK INFO [70.1350s] nsock_iod_new2(): nsock_iod_new (IOD #2087)
NSOCK INFO [70.1350s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2087) EID 66728
NSOCK INFO [70.1490s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66728 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37276 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37276 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 6d 70 6f 72 61 6c 2f 20 48 GET /temporal/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [70.1490s] nsock_write(): Write request for 180 bytes to IOD #2087 EID 66739 [88.255.216.16:80]
NSOCK INFO [70.1490s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66739 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37276 > 88.255.216.16:80 | SEND
NSOCK INFO [70.1500s] nsock_read(): Read request from IOD #2087 [88.255.216.16:80] (timeout: 10000ms) EID 66746
NSOCK INFO [70.1630s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66746 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37276 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.1640s] nsock_read(): Read request from IOD #2087 [88.255.216.16:80] (timeout: 10000ms) EID 66754
NSOCK INFO [70.1640s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66754 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37276 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.1640s] nsock_iod_delete(): nsock_iod_delete (IOD #2087)
NSOCK INFO [70.1640s] nsock_iod_new2(): nsock_iod_new (IOD #2088)
NSOCK INFO [70.1650s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2088) EID 66760
NSOCK INFO [70.1790s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66760 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37278 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37278 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 73 74 2d 63 67 69 2f 20 48 GET /test-cgi/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [70.1800s] nsock_write(): Write request for 180 bytes to IOD #2088 EID 66771 [88.255.216.16:80]
NSOCK INFO [70.1800s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66771 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37278 > 88.255.216.16:80 | SEND
NSOCK INFO [70.1820s] nsock_read(): Read request from IOD #2088 [88.255.216.16:80] (timeout: 10000ms) EID 66778
NSOCK INFO [70.1940s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66778 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37278 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.1950s] nsock_read(): Read request from IOD #2088 [88.255.216.16:80] (timeout: 10000ms) EID 66786
NSOCK INFO [70.1950s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66786 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37278 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.1970s] nsock_iod_delete(): nsock_iod_delete (IOD #2088)
NSOCK INFO [70.1970s] nsock_iod_new2(): nsock_iod_new (IOD #2089)
NSOCK INFO [70.1970s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2089) EID 66792
NSOCK INFO [70.2100s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66792 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37286 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37286 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 73 74 69 6e 67 2f 20 48 54 GET /testing/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [70.2110s] nsock_write(): Write request for 179 bytes to IOD #2089 EID 66803 [88.255.216.16:80]
NSOCK INFO [70.2110s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66803 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37286 > 88.255.216.16:80 | SEND
NSOCK INFO [70.2120s] nsock_read(): Read request from IOD #2089 [88.255.216.16:80] (timeout: 10000ms) EID 66810
NSOCK INFO [70.2240s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66810 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37286 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.2240s] nsock_read(): Read request from IOD #2089 [88.255.216.16:80] (timeout: 10000ms) EID 66818
NSOCK INFO [70.2240s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66818 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37286 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.2250s] nsock_iod_delete(): nsock_iod_delete (IOD #2089)
NSOCK INFO [70.2250s] nsock_iod_new2(): nsock_iod_new (IOD #2090)
NSOCK INFO [70.2250s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2090) EID 66824
NSOCK INFO [70.2380s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66824 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37288 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37288 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 73 74 73 2f 20 48 54 54 50 GET /tests/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [70.2400s] nsock_write(): Write request for 177 bytes to IOD #2090 EID 66835 [88.255.216.16:80]
NSOCK INFO [70.2400s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66835 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37288 > 88.255.216.16:80 | SEND
NSOCK INFO [70.2410s] nsock_read(): Read request from IOD #2090 [88.255.216.16:80] (timeout: 10000ms) EID 66842
NSOCK INFO [70.2530s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66842 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37288 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.2530s] nsock_read(): Read request from IOD #2090 [88.255.216.16:80] (timeout: 10000ms) EID 66850
NSOCK INFO [70.2530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66850 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37288 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.2540s] nsock_iod_delete(): nsock_iod_delete (IOD #2090)
NSOCK INFO [70.2540s] nsock_iod_new2(): nsock_iod_new (IOD #2091)
NSOCK INFO [70.2550s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2091) EID 66856
NSOCK INFO [70.2690s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66856 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37304 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37304 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 65 73 74 77 65 62 2f 20 48 54 GET /testweb/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [70.2690s] nsock_write(): Write request for 179 bytes to IOD #2091 EID 66867 [88.255.216.16:80]
NSOCK INFO [70.2690s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66867 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37304 > 88.255.216.16:80 | SEND
NSOCK INFO [70.2700s] nsock_read(): Read request from IOD #2091 [88.255.216.16:80] (timeout: 10000ms) EID 66874
NSOCK INFO [70.2830s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66874 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37304 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.2840s] nsock_read(): Read request from IOD #2091 [88.255.216.16:80] (timeout: 10000ms) EID 66882
NSOCK INFO [70.2840s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66882 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37304 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.2850s] nsock_iod_delete(): nsock_iod_delete (IOD #2091)
NSOCK INFO [70.2850s] nsock_iod_new2(): nsock_iod_new (IOD #2092)
NSOCK INFO [70.2860s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2092) EID 66888
NSOCK INFO [70.2990s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66888 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37320 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37320 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 68 65 6d 65 73 2f 20 48 54 54 GET /themes/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [70.2990s] nsock_write(): Write request for 178 bytes to IOD #2092 EID 66899 [88.255.216.16:80]
NSOCK INFO [70.2990s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66899 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37320 > 88.255.216.16:80 | SEND
NSOCK INFO [70.3000s] nsock_read(): Read request from IOD #2092 [88.255.216.16:80] (timeout: 10000ms) EID 66906
NSOCK INFO [70.3120s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66906 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37320 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.3130s] nsock_read(): Read request from IOD #2092 [88.255.216.16:80] (timeout: 10000ms) EID 66914
NSOCK INFO [70.3130s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66914 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37320 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.3130s] nsock_iod_delete(): nsock_iod_delete (IOD #2092)
NSOCK INFO [70.3130s] nsock_iod_new2(): nsock_iod_new (IOD #2093)
NSOCK INFO [70.3140s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2093) EID 66920
NSOCK INFO [70.3260s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66920 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37324 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37324 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 69 63 6b 65 74 2f 20 48 54 54 GET /ticket/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [70.3270s] nsock_write(): Write request for 178 bytes to IOD #2093 EID 66931 [88.255.216.16:80]
NSOCK INFO [70.3270s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66931 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37324 > 88.255.216.16:80 | SEND
NSOCK INFO [70.3280s] nsock_read(): Read request from IOD #2093 [88.255.216.16:80] (timeout: 10000ms) EID 66938
NSOCK INFO [70.3400s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66938 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37324 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.3410s] nsock_read(): Read request from IOD #2093 [88.255.216.16:80] (timeout: 10000ms) EID 66946
NSOCK INFO [70.3410s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66946 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37324 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.3410s] nsock_iod_delete(): nsock_iod_delete (IOD #2093)
NSOCK INFO [70.3410s] nsock_iod_new2(): nsock_iod_new (IOD #2094)
NSOCK INFO [70.3420s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2094) EID 66952
NSOCK INFO [70.3550s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66952 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37332 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37332 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 69 63 6b 65 74 73 2f 20 48 54 GET /tickets/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [70.3550s] nsock_write(): Write request for 179 bytes to IOD #2094 EID 66963 [88.255.216.16:80]
NSOCK INFO [70.3550s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66963 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37332 > 88.255.216.16:80 | SEND
NSOCK INFO [70.3560s] nsock_read(): Read request from IOD #2094 [88.255.216.16:80] (timeout: 10000ms) EID 66970
NSOCK INFO [70.3680s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 66970 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37332 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.3690s] nsock_read(): Read request from IOD #2094 [88.255.216.16:80] (timeout: 10000ms) EID 66978
NSOCK INFO [70.3690s] nsock_trace_handler_callback(): Callback: READ EOF for EID 66978 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37332 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.3700s] nsock_iod_delete(): nsock_iod_delete (IOD #2094)
NSOCK INFO [70.3700s] nsock_iod_new2(): nsock_iod_new (IOD #2095)
NSOCK INFO [70.3700s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2095) EID 66984
NSOCK INFO [70.3840s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 66984 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37342 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37342 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 69 70 2f 20 48 54 54 50 2f 31 GET /tip/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [70.3850s] nsock_write(): Write request for 175 bytes to IOD #2095 EID 66995 [88.255.216.16:80]
NSOCK INFO [70.3850s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 66995 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37342 > 88.255.216.16:80 | SEND
NSOCK INFO [70.3870s] nsock_read(): Read request from IOD #2095 [88.255.216.16:80] (timeout: 10000ms) EID 67002
NSOCK INFO [70.3980s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67002 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37342 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.3980s] nsock_read(): Read request from IOD #2095 [88.255.216.16:80] (timeout: 10000ms) EID 67010
NSOCK INFO [70.3980s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67010 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37342 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.3980s] nsock_iod_delete(): nsock_iod_delete (IOD #2095)
NSOCK INFO [70.3980s] nsock_iod_new2(): nsock_iod_new (IOD #2096)
NSOCK INFO [70.3990s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2096) EID 67016
NSOCK INFO [70.4130s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67016 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37348 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37348 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 69 70 73 2f 20 48 54 54 50 2f GET /tips/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [70.4130s] nsock_write(): Write request for 176 bytes to IOD #2096 EID 67027 [88.255.216.16:80]
NSOCK INFO [70.4130s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67027 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37348 > 88.255.216.16:80 | SEND
NSOCK INFO [70.4140s] nsock_read(): Read request from IOD #2096 [88.255.216.16:80] (timeout: 10000ms) EID 67034
NSOCK INFO [70.4270s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67034 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37348 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.4270s] nsock_read(): Read request from IOD #2096 [88.255.216.16:80] (timeout: 10000ms) EID 67042
NSOCK INFO [70.4270s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67042 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37348 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.4280s] nsock_iod_delete(): nsock_iod_delete (IOD #2096)
NSOCK INFO [70.4280s] nsock_iod_new2(): nsock_iod_new (IOD #2097)
NSOCK INFO [70.4280s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2097) EID 67048
NSOCK INFO [70.4420s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67048 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37364 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37364 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 6d 70 2f 20 48 54 54 50 2f 31 GET /tmp/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [70.4430s] nsock_write(): Write request for 175 bytes to IOD #2097 EID 67059 [88.255.216.16:80]
NSOCK INFO [70.4430s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67059 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37364 > 88.255.216.16:80 | SEND
NSOCK INFO [70.4440s] nsock_read(): Read request from IOD #2097 [88.255.216.16:80] (timeout: 10000ms) EID 67066
NSOCK INFO [70.4560s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67066 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37364 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.4560s] nsock_read(): Read request from IOD #2097 [88.255.216.16:80] (timeout: 10000ms) EID 67074
NSOCK INFO [70.4560s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67074 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37364 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.4570s] nsock_iod_delete(): nsock_iod_delete (IOD #2097)
NSOCK INFO [70.4570s] nsock_iod_new2(): nsock_iod_new (IOD #2098)
NSOCK INFO [70.4580s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2098) EID 67080
NSOCK INFO [70.4720s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67080 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37376 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37376 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 54 6f 44 6f 2f 20 48 54 54 50 2f GET /ToDo/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [70.4730s] nsock_write(): Write request for 176 bytes to IOD #2098 EID 67091 [88.255.216.16:80]
NSOCK INFO [70.4730s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67091 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37376 > 88.255.216.16:80 | SEND
NSOCK INFO [70.4740s] nsock_read(): Read request from IOD #2098 [88.255.216.16:80] (timeout: 10000ms) EID 67098
NSOCK INFO [70.4860s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67098 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37376 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.4870s] nsock_read(): Read request from IOD #2098 [88.255.216.16:80] (timeout: 10000ms) EID 67106
NSOCK INFO [70.4870s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67106 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37376 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.4870s] nsock_iod_delete(): nsock_iod_delete (IOD #2098)
NSOCK INFO [70.4870s] nsock_iod_new2(): nsock_iod_new (IOD #2099)
NSOCK INFO [70.4880s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2099) EID 67112
NSOCK INFO [70.5000s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67112 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37380 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37380 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 6f 6f 6c 2f 20 48 54 54 50 2f GET /tool/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [70.5010s] nsock_write(): Write request for 176 bytes to IOD #2099 EID 67123 [88.255.216.16:80]
NSOCK INFO [70.5010s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67123 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37380 > 88.255.216.16:80 | SEND
NSOCK INFO [70.5020s] nsock_read(): Read request from IOD #2099 [88.255.216.16:80] (timeout: 10000ms) EID 67130
NSOCK INFO [70.5140s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67130 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37380 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.5150s] nsock_read(): Read request from IOD #2099 [88.255.216.16:80] (timeout: 10000ms) EID 67138
NSOCK INFO [70.5150s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67138 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37380 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.5160s] nsock_iod_delete(): nsock_iod_delete (IOD #2099)
NSOCK INFO [70.5160s] nsock_iod_new2(): nsock_iod_new (IOD #2100)
NSOCK INFO [70.5170s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2100) EID 67144
NSOCK INFO [70.5310s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67144 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37388 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37388 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 6f 6f 6c 73 2f 20 48 54 54 50 GET /tools/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [70.5320s] nsock_write(): Write request for 177 bytes to IOD #2100 EID 67155 [88.255.216.16:80]
NSOCK INFO [70.5320s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67155 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37388 > 88.255.216.16:80 | SEND
NSOCK INFO [70.5330s] nsock_read(): Read request from IOD #2100 [88.255.216.16:80] (timeout: 10000ms) EID 67162
NSOCK INFO [70.5460s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67162 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37388 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.5470s] nsock_read(): Read request from IOD #2100 [88.255.216.16:80] (timeout: 10000ms) EID 67170
NSOCK INFO [70.5470s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67170 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37388 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.5480s] nsock_iod_delete(): nsock_iod_delete (IOD #2100)
NSOCK INFO [70.5480s] nsock_iod_new2(): nsock_iod_new (IOD #2101)
NSOCK INFO [70.5490s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2101) EID 67176
NSOCK INFO [70.5620s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67176 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37398 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37398 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 54 6f 70 41 63 63 65 73 73 2f 20 GET /TopAccess/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [70.5640s] nsock_write(): Write request for 181 bytes to IOD #2101 EID 67187 [88.255.216.16:80]
NSOCK INFO [70.5640s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67187 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37398 > 88.255.216.16:80 | SEND
NSOCK INFO [70.5650s] nsock_read(): Read request from IOD #2101 [88.255.216.16:80] (timeout: 10000ms) EID 67194
NSOCK INFO [70.5770s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67194 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37398 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.5770s] nsock_read(): Read request from IOD #2101 [88.255.216.16:80] (timeout: 10000ms) EID 67202
NSOCK INFO [70.5770s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67202 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37398 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.5780s] nsock_iod_delete(): nsock_iod_delete (IOD #2101)
NSOCK INFO [70.5780s] nsock_iod_new2(): nsock_iod_new (IOD #2102)
NSOCK INFO [70.5780s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2102) EID 67208
NSOCK INFO [70.5910s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67208 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37402 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37402 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 6f 70 2f 20 48 54 54 50 2f 31 GET /top/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [70.5920s] nsock_write(): Write request for 175 bytes to IOD #2102 EID 67219 [88.255.216.16:80]
NSOCK INFO [70.5920s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67219 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37402 > 88.255.216.16:80 | SEND
NSOCK INFO [70.5920s] nsock_read(): Read request from IOD #2102 [88.255.216.16:80] (timeout: 10000ms) EID 67226
NSOCK INFO [70.6050s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67226 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37402 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.6050s] nsock_read(): Read request from IOD #2102 [88.255.216.16:80] (timeout: 10000ms) EID 67234
NSOCK INFO [70.6050s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67234 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37402 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.6060s] nsock_iod_delete(): nsock_iod_delete (IOD #2102)
NSOCK INFO [70.6060s] nsock_iod_new2(): nsock_iod_new (IOD #2103)
NSOCK INFO [70.6060s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2103) EID 67240
NSOCK INFO [70.6190s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67240 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37414 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37414 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 70 76 2f 20 48 54 54 50 2f 31 GET /tpv/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [70.6200s] nsock_write(): Write request for 175 bytes to IOD #2103 EID 67251 [88.255.216.16:80]
NSOCK INFO [70.6200s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67251 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37414 > 88.255.216.16:80 | SEND
NSOCK INFO [70.6210s] nsock_read(): Read request from IOD #2103 [88.255.216.16:80] (timeout: 10000ms) EID 67258
NSOCK INFO [70.6330s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67258 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37414 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.6340s] nsock_read(): Read request from IOD #2103 [88.255.216.16:80] (timeout: 10000ms) EID 67266
NSOCK INFO [70.6340s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67266 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37414 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.6340s] nsock_iod_delete(): nsock_iod_delete (IOD #2103)
NSOCK INFO [70.6340s] nsock_iod_new2(): nsock_iod_new (IOD #2104)
NSOCK INFO [70.6350s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2104) EID 67272
NSOCK INFO [70.6480s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67272 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37430 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37430 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 61 62 61 6a 6f 2f 20 48 54 GET /trabajo/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [70.6490s] nsock_write(): Write request for 179 bytes to IOD #2104 EID 67283 [88.255.216.16:80]
NSOCK INFO [70.6490s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67283 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37430 > 88.255.216.16:80 | SEND
NSOCK INFO [70.6490s] nsock_read(): Read request from IOD #2104 [88.255.216.16:80] (timeout: 10000ms) EID 67290
NSOCK INFO [70.6620s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67290 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37430 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.6630s] nsock_read(): Read request from IOD #2104 [88.255.216.16:80] (timeout: 10000ms) EID 67298
NSOCK INFO [70.6630s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67298 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37430 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.6640s] nsock_iod_delete(): nsock_iod_delete (IOD #2104)
NSOCK INFO [70.6640s] nsock_iod_new2(): nsock_iod_new (IOD #2105)
NSOCK INFO [70.6650s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2105) EID 67304
NSOCK INFO [70.6780s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67304 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37434 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37434 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 61 63 6b 2f 20 48 54 54 50 GET /track/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [70.6790s] nsock_write(): Write request for 177 bytes to IOD #2105 EID 67315 [88.255.216.16:80]
NSOCK INFO [70.6790s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67315 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37434 > 88.255.216.16:80 | SEND
NSOCK INFO [70.6800s] nsock_read(): Read request from IOD #2105 [88.255.216.16:80] (timeout: 10000ms) EID 67322
NSOCK INFO [70.6920s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67322 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37434 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.6920s] nsock_read(): Read request from IOD #2105 [88.255.216.16:80] (timeout: 10000ms) EID 67330
NSOCK INFO [70.6920s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67330 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37434 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.6930s] nsock_iod_delete(): nsock_iod_delete (IOD #2105)
NSOCK INFO [70.6930s] nsock_iod_new2(): nsock_iod_new (IOD #2106)
NSOCK INFO [70.6930s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2106) EID 67336
NSOCK INFO [70.7060s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67336 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37448 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37448 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 61 63 6b 69 6e 67 2f 20 48 GET /tracking/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [70.7070s] nsock_write(): Write request for 180 bytes to IOD #2106 EID 67347 [88.255.216.16:80]
NSOCK INFO [70.7070s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67347 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37448 > 88.255.216.16:80 | SEND
NSOCK INFO [70.7080s] nsock_read(): Read request from IOD #2106 [88.255.216.16:80] (timeout: 10000ms) EID 67354
NSOCK INFO [70.7200s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67354 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37448 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.7210s] nsock_read(): Read request from IOD #2106 [88.255.216.16:80] (timeout: 10000ms) EID 67362
NSOCK INFO [70.7210s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67362 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37448 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.7220s] nsock_iod_delete(): nsock_iod_delete (IOD #2106)
NSOCK INFO [70.7220s] nsock_iod_new2(): nsock_iod_new (IOD #2107)
NSOCK INFO [70.7220s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2107) EID 67368
NSOCK INFO [70.7350s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67368 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37458 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37458 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 61 6e 73 66 65 72 2f 20 48 GET /transfer/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [70.7360s] nsock_write(): Write request for 180 bytes to IOD #2107 EID 67379 [88.255.216.16:80]
NSOCK INFO [70.7360s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67379 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37458 > 88.255.216.16:80 | SEND
NSOCK INFO [70.7360s] nsock_read(): Read request from IOD #2107 [88.255.216.16:80] (timeout: 10000ms) EID 67386
NSOCK INFO [70.7490s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67386 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37458 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.7490s] nsock_read(): Read request from IOD #2107 [88.255.216.16:80] (timeout: 10000ms) EID 67394
NSOCK INFO [70.7490s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67394 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37458 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.7500s] nsock_iod_delete(): nsock_iod_delete (IOD #2107)
NSOCK INFO [70.7500s] nsock_iod_new2(): nsock_iod_new (IOD #2108)
NSOCK INFO [70.7500s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2108) EID 67400
NSOCK INFO [70.7630s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67400 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37474 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37474 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 61 6e 73 69 74 6f 2f 20 48 GET /transito/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [70.7650s] nsock_write(): Write request for 180 bytes to IOD #2108 EID 67411 [88.255.216.16:80]
NSOCK INFO [70.7650s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67411 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37474 > 88.255.216.16:80 | SEND
NSOCK INFO [70.7660s] nsock_read(): Read request from IOD #2108 [88.255.216.16:80] (timeout: 10000ms) EID 67418
NSOCK INFO [70.7780s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67418 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37474 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.7790s] nsock_read(): Read request from IOD #2108 [88.255.216.16:80] (timeout: 10000ms) EID 67426
NSOCK INFO [70.7790s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67426 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37474 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.7790s] nsock_iod_delete(): nsock_iod_delete (IOD #2108)
NSOCK INFO [70.7790s] nsock_iod_new2(): nsock_iod_new (IOD #2109)
NSOCK INFO [70.7800s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2109) EID 67432
NSOCK INFO [70.7930s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67432 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37484 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37484 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 61 6e 73 70 6f 6c 61 72 2f GET /transpolar/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [70.7930s] nsock_write(): Write request for 182 bytes to IOD #2109 EID 67443 [88.255.216.16:80]
NSOCK INFO [70.7930s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67443 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37484 > 88.255.216.16:80 | SEND
NSOCK INFO [70.7950s] nsock_read(): Read request from IOD #2109 [88.255.216.16:80] (timeout: 10000ms) EID 67450
NSOCK INFO [70.8060s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67450 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37484 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.8070s] nsock_read(): Read request from IOD #2109 [88.255.216.16:80] (timeout: 10000ms) EID 67458
NSOCK INFO [70.8070s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67458 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37484 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.8070s] nsock_iod_delete(): nsock_iod_delete (IOD #2109)
NSOCK INFO [70.8070s] nsock_iod_new2(): nsock_iod_new (IOD #2110)
NSOCK INFO [70.8070s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2110) EID 67464
NSOCK INFO [70.8210s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67464 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37498 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37498 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 65 65 2f 20 48 54 54 50 2f GET /tree/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [70.8220s] nsock_write(): Write request for 176 bytes to IOD #2110 EID 67475 [88.255.216.16:80]
NSOCK INFO [70.8220s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67475 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37498 > 88.255.216.16:80 | SEND
NSOCK INFO [70.8250s] nsock_read(): Read request from IOD #2110 [88.255.216.16:80] (timeout: 10000ms) EID 67482
NSOCK INFO [70.8360s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67482 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37498 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.8380s] nsock_read(): Read request from IOD #2110 [88.255.216.16:80] (timeout: 10000ms) EID 67490
NSOCK INFO [70.8380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67490 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37498 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.8380s] nsock_iod_delete(): nsock_iod_delete (IOD #2110)
NSOCK INFO [70.8380s] nsock_iod_new2(): nsock_iod_new (IOD #2111)
NSOCK INFO [70.8410s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2111) EID 67496
NSOCK INFO [70.8540s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67496 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37512 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37512 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 65 65 73 2f 20 48 54 54 50 GET /trees/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [70.8550s] nsock_write(): Write request for 177 bytes to IOD #2111 EID 67507 [88.255.216.16:80]
NSOCK INFO [70.8550s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67507 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37512 > 88.255.216.16:80 | SEND
NSOCK INFO [70.8560s] nsock_read(): Read request from IOD #2111 [88.255.216.16:80] (timeout: 10000ms) EID 67514
NSOCK INFO [70.8680s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67514 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37512 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.8690s] nsock_read(): Read request from IOD #2111 [88.255.216.16:80] (timeout: 10000ms) EID 67522
NSOCK INFO [70.8690s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67522 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37512 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.8690s] nsock_iod_delete(): nsock_iod_delete (IOD #2111)
NSOCK INFO [70.8690s] nsock_iod_new2(): nsock_iod_new (IOD #2112)
NSOCK INFO [70.8700s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2112) EID 67528
NSOCK INFO [70.8820s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67528 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37524 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37524 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 69 63 6b 2f 20 48 54 54 50 GET /trick/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [70.8830s] nsock_write(): Write request for 177 bytes to IOD #2112 EID 67539 [88.255.216.16:80]
NSOCK INFO [70.8830s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67539 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37524 > 88.255.216.16:80 | SEND
NSOCK INFO [70.8840s] nsock_read(): Read request from IOD #2112 [88.255.216.16:80] (timeout: 10000ms) EID 67546
NSOCK INFO [70.8960s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67546 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37524 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.8970s] nsock_read(): Read request from IOD #2112 [88.255.216.16:80] (timeout: 10000ms) EID 67554
NSOCK INFO [70.8970s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67554 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37524 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.8980s] nsock_iod_delete(): nsock_iod_delete (IOD #2112)
NSOCK INFO [70.8980s] nsock_iod_new2(): nsock_iod_new (IOD #2113)
NSOCK INFO [70.9000s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2113) EID 67560
NSOCK INFO [70.9130s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67560 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37526 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37526 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 74 72 69 63 6b 73 2f 20 48 54 54 GET /tricks/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [70.9140s] nsock_write(): Write request for 178 bytes to IOD #2113 EID 67571 [88.255.216.16:80]
NSOCK INFO [70.9140s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67571 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37526 > 88.255.216.16:80 | SEND
NSOCK INFO [70.9150s] nsock_read(): Read request from IOD #2113 [88.255.216.16:80] (timeout: 10000ms) EID 67578
NSOCK INFO [70.9270s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67578 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37526 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.9280s] nsock_read(): Read request from IOD #2113 [88.255.216.16:80] (timeout: 10000ms) EID 67586
NSOCK INFO [70.9280s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67586 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37526 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.9280s] nsock_iod_delete(): nsock_iod_delete (IOD #2113)
NSOCK INFO [70.9280s] nsock_iod_new2(): nsock_iod_new (IOD #2114)
NSOCK INFO [70.9300s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2114) EID 67592
NSOCK INFO [70.9430s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67592 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37532 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37532 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 30 32 2f 20 48 54 54 50 2f 31 GET /u02/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [70.9440s] nsock_write(): Write request for 175 bytes to IOD #2114 EID 67603 [88.255.216.16:80]
NSOCK INFO [70.9440s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67603 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37532 > 88.255.216.16:80 | SEND
NSOCK INFO [70.9440s] nsock_read(): Read request from IOD #2114 [88.255.216.16:80] (timeout: 10000ms) EID 67610
NSOCK INFO [70.9570s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67610 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37532 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.9580s] nsock_read(): Read request from IOD #2114 [88.255.216.16:80] (timeout: 10000ms) EID 67618
NSOCK INFO [70.9580s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67618 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37532 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.9590s] nsock_iod_delete(): nsock_iod_delete (IOD #2114)
NSOCK INFO [70.9590s] nsock_iod_new2(): nsock_iod_new (IOD #2115)
NSOCK INFO [70.9600s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2115) EID 67624
NSOCK INFO [70.9730s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67624 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37542 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37542 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 6e 69 78 2f 20 48 54 54 50 2f GET /unix/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [70.9740s] nsock_write(): Write request for 176 bytes to IOD #2115 EID 67635 [88.255.216.16:80]
NSOCK INFO [70.9740s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67635 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37542 > 88.255.216.16:80 | SEND
NSOCK INFO [70.9760s] nsock_read(): Read request from IOD #2115 [88.255.216.16:80] (timeout: 10000ms) EID 67642
NSOCK INFO [70.9880s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67642 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37542 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [70.9880s] nsock_read(): Read request from IOD #2115 [88.255.216.16:80] (timeout: 10000ms) EID 67650
NSOCK INFO [70.9880s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67650 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37542 > 88.255.216.16:80 | CLOSE
NSOCK INFO [70.9880s] nsock_iod_delete(): nsock_iod_delete (IOD #2115)
NSOCK INFO [70.9880s] nsock_iod_new2(): nsock_iod_new (IOD #2116)
NSOCK INFO [70.9890s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2116) EID 67656
NSOCK INFO [71.0010s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67656 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37556 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37556 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 6e 6b 6e 6f 77 6e 2f 20 48 54 GET /unknown/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.0030s] nsock_write(): Write request for 179 bytes to IOD #2116 EID 67667 [88.255.216.16:80]
NSOCK INFO [71.0030s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67667 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37556 > 88.255.216.16:80 | SEND
NSOCK INFO [71.0040s] nsock_read(): Read request from IOD #2116 [88.255.216.16:80] (timeout: 10000ms) EID 67674
NSOCK INFO [71.0160s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67674 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37556 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.0170s] nsock_read(): Read request from IOD #2116 [88.255.216.16:80] (timeout: 10000ms) EID 67682
NSOCK INFO [71.0170s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67682 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37556 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.0180s] nsock_iod_delete(): nsock_iod_delete (IOD #2116)
NSOCK INFO [71.0180s] nsock_iod_new2(): nsock_iod_new (IOD #2117)
NSOCK INFO [71.0190s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2117) EID 67688
NSOCK INFO [71.0320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67688 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37558 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37558 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 70 64 61 74 65 73 2f 20 48 54 GET /updates/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.0330s] nsock_write(): Write request for 179 bytes to IOD #2117 EID 67699 [88.255.216.16:80]
NSOCK INFO [71.0330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67699 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37558 > 88.255.216.16:80 | SEND
NSOCK INFO [71.0340s] nsock_read(): Read request from IOD #2117 [88.255.216.16:80] (timeout: 10000ms) EID 67706
NSOCK INFO [71.0460s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67706 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37558 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.0470s] nsock_read(): Read request from IOD #2117 [88.255.216.16:80] (timeout: 10000ms) EID 67714
NSOCK INFO [71.0470s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67714 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37558 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.0470s] nsock_iod_delete(): nsock_iod_delete (IOD #2117)
NSOCK INFO [71.0470s] nsock_iod_new2(): nsock_iod_new (IOD #2118)
NSOCK INFO [71.0480s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2118) EID 67720
NSOCK INFO [71.0610s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67720 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37572 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37572 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 70 6c 6f 61 64 2f 20 48 54 54 GET /upload/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [71.0630s] nsock_write(): Write request for 178 bytes to IOD #2118 EID 67731 [88.255.216.16:80]
NSOCK INFO [71.0630s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67731 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37572 > 88.255.216.16:80 | SEND
NSOCK INFO [71.0650s] nsock_read(): Read request from IOD #2118 [88.255.216.16:80] (timeout: 10000ms) EID 67738
NSOCK INFO [71.0780s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67738 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37572 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.0790s] nsock_read(): Read request from IOD #2118 [88.255.216.16:80] (timeout: 10000ms) EID 67746
NSOCK INFO [71.0790s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67746 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37572 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.0800s] nsock_iod_delete(): nsock_iod_delete (IOD #2118)
NSOCK INFO [71.0800s] nsock_iod_new2(): nsock_iod_new (IOD #2119)
NSOCK INFO [71.0810s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2119) EID 67752
NSOCK INFO [71.0950s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67752 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37580 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37580 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 70 6c 6f 61 64 73 2f 20 48 54 GET /uploads/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.0950s] nsock_write(): Write request for 179 bytes to IOD #2119 EID 67763 [88.255.216.16:80]
NSOCK INFO [71.0950s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67763 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37580 > 88.255.216.16:80 | SEND
NSOCK INFO [71.0960s] nsock_read(): Read request from IOD #2119 [88.255.216.16:80] (timeout: 10000ms) EID 67770
NSOCK INFO [71.1090s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67770 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37580 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.1090s] nsock_read(): Read request from IOD #2119 [88.255.216.16:80] (timeout: 10000ms) EID 67778
NSOCK INFO [71.1090s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67778 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37580 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.1100s] nsock_iod_delete(): nsock_iod_delete (IOD #2119)
NSOCK INFO [71.1100s] nsock_iod_new2(): nsock_iod_new (IOD #2120)
NSOCK INFO [71.1100s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2120) EID 67784
NSOCK INFO [71.1230s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67784 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37592 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37592 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 61 67 65 2f 20 48 54 54 50 GET /usage/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [71.1240s] nsock_write(): Write request for 177 bytes to IOD #2120 EID 67795 [88.255.216.16:80]
NSOCK INFO [71.1240s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67795 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37592 > 88.255.216.16:80 | SEND
NSOCK INFO [71.1240s] nsock_read(): Read request from IOD #2120 [88.255.216.16:80] (timeout: 10000ms) EID 67802
NSOCK INFO [71.1370s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67802 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37592 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.1380s] nsock_read(): Read request from IOD #2120 [88.255.216.16:80] (timeout: 10000ms) EID 67810
NSOCK INFO [71.1380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67810 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37592 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.1380s] nsock_iod_delete(): nsock_iod_delete (IOD #2120)
NSOCK INFO [71.1380s] nsock_iod_new2(): nsock_iod_new (IOD #2121)
NSOCK INFO [71.1390s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2121) EID 67816
NSOCK INFO [71.1520s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67816 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37602 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37602 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 65 72 64 62 2f 20 48 54 54 GET /userdb/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [71.1530s] nsock_write(): Write request for 178 bytes to IOD #2121 EID 67827 [88.255.216.16:80]
NSOCK INFO [71.1530s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67827 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37602 > 88.255.216.16:80 | SEND
NSOCK INFO [71.1550s] nsock_read(): Read request from IOD #2121 [88.255.216.16:80] (timeout: 10000ms) EID 67834
NSOCK INFO [71.1670s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67834 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37602 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.1680s] nsock_read(): Read request from IOD #2121 [88.255.216.16:80] (timeout: 10000ms) EID 67842
NSOCK INFO [71.1680s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67842 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37602 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.1680s] nsock_iod_delete(): nsock_iod_delete (IOD #2121)
NSOCK INFO [71.1680s] nsock_iod_new2(): nsock_iod_new (IOD #2122)
NSOCK INFO [71.1680s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2122) EID 67848
NSOCK INFO [71.1820s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67848 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37606 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37606 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 65 72 2f 20 48 54 54 50 2f GET /user/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [71.1830s] nsock_write(): Write request for 176 bytes to IOD #2122 EID 67859 [88.255.216.16:80]
NSOCK INFO [71.1830s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67859 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37606 > 88.255.216.16:80 | SEND
NSOCK INFO [71.1840s] nsock_read(): Read request from IOD #2122 [88.255.216.16:80] (timeout: 10000ms) EID 67866
NSOCK INFO [71.1970s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67866 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37606 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.1990s] nsock_read(): Read request from IOD #2122 [88.255.216.16:80] (timeout: 10000ms) EID 67874
NSOCK INFO [71.1990s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67874 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37606 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.1990s] nsock_iod_delete(): nsock_iod_delete (IOD #2122)
NSOCK INFO [71.1990s] nsock_iod_new2(): nsock_iod_new (IOD #2123)
NSOCK INFO [71.2000s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2123) EID 67880
NSOCK INFO [71.2140s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67880 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37620 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37620 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 65 72 73 2f 20 48 54 54 50 GET /users/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [71.2150s] nsock_write(): Write request for 177 bytes to IOD #2123 EID 67891 [88.255.216.16:80]
NSOCK INFO [71.2150s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67891 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37620 > 88.255.216.16:80 | SEND
NSOCK INFO [71.2160s] nsock_read(): Read request from IOD #2123 [88.255.216.16:80] (timeout: 10000ms) EID 67898
NSOCK INFO [71.2300s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67898 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37620 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.2300s] nsock_read(): Read request from IOD #2123 [88.255.216.16:80] (timeout: 10000ms) EID 67906
NSOCK INFO [71.2300s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67906 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37620 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.2310s] nsock_iod_delete(): nsock_iod_delete (IOD #2123)
NSOCK INFO [71.2310s] nsock_iod_new2(): nsock_iod_new (IOD #2124)
NSOCK INFO [71.2310s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2124) EID 67912
NSOCK INFO [71.2450s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67912 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37630 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37630 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 2f 20 48 54 54 50 2f 31 2e GET /us/ HTTP/1.
00000010: 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 2e 1  Host: 88.255.
00000020: 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 74 216.16.static.tt
00000030: 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 net.com.tr  User
00000040: 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f -Agent: Mozilla/
00000050: 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 3b 5.0 (compatible;
00000060: 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 20  Nmap Scripting 
00000070: 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f 2f Engine; https://
00000080: 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 nmap.org/book/ns
00000090: 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 e.html)  Connect
000000a0: 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a       ion: close    

NSOCK INFO [71.2460s] nsock_write(): Write request for 174 bytes to IOD #2124 EID 67923 [88.255.216.16:80]
NSOCK INFO [71.2460s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67923 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37630 > 88.255.216.16:80 | SEND
NSOCK INFO [71.2470s] nsock_read(): Read request from IOD #2124 [88.255.216.16:80] (timeout: 10000ms) EID 67930
NSOCK INFO [71.2590s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67930 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37630 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.2600s] nsock_read(): Read request from IOD #2124 [88.255.216.16:80] (timeout: 10000ms) EID 67938
NSOCK INFO [71.2600s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67938 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37630 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.2600s] nsock_iod_delete(): nsock_iod_delete (IOD #2124)
NSOCK INFO [71.2600s] nsock_iod_new2(): nsock_iod_new (IOD #2125)
NSOCK INFO [71.2600s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2125) EID 67944
NSOCK INFO [71.2730s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67944 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37644 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37644 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 72 2f 20 48 54 54 50 2f 31 GET /usr/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [71.2740s] nsock_write(): Write request for 175 bytes to IOD #2125 EID 67955 [88.255.216.16:80]
NSOCK INFO [71.2740s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67955 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37644 > 88.255.216.16:80 | SEND
NSOCK INFO [71.2750s] nsock_read(): Read request from IOD #2125 [88.255.216.16:80] (timeout: 10000ms) EID 67962
NSOCK INFO [71.2880s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67962 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37644 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.2880s] nsock_read(): Read request from IOD #2125 [88.255.216.16:80] (timeout: 10000ms) EID 67970
NSOCK INFO [71.2880s] nsock_trace_handler_callback(): Callback: READ EOF for EID 67970 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37644 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.2890s] nsock_iod_delete(): nsock_iod_delete (IOD #2125)
NSOCK INFO [71.2890s] nsock_iod_new2(): nsock_iod_new (IOD #2126)
NSOCK INFO [71.2890s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2126) EID 67976
NSOCK INFO [71.3030s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 67976 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37650 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37650 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 74 61 74 73 2f 20 48 54 54 GET /ustats/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [71.3040s] nsock_write(): Write request for 178 bytes to IOD #2126 EID 67987 [88.255.216.16:80]
NSOCK INFO [71.3040s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 67987 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37650 > 88.255.216.16:80 | SEND
NSOCK INFO [71.3050s] nsock_read(): Read request from IOD #2126 [88.255.216.16:80] (timeout: 10000ms) EID 67994
NSOCK INFO [71.3180s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 67994 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37650 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.3190s] nsock_read(): Read request from IOD #2126 [88.255.216.16:80] (timeout: 10000ms) EID 68002
NSOCK INFO [71.3190s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68002 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37650 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.3190s] nsock_iod_delete(): nsock_iod_delete (IOD #2126)
NSOCK INFO [71.3190s] nsock_iod_new2(): nsock_iod_new (IOD #2127)
NSOCK INFO [71.3190s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2127) EID 68008
NSOCK INFO [71.3340s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68008 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37660 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37660 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 75 61 72 69 6f 2f 20 48 54 GET /usuario/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.3360s] nsock_write(): Write request for 179 bytes to IOD #2127 EID 68019 [88.255.216.16:80]
NSOCK INFO [71.3360s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68019 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37660 > 88.255.216.16:80 | SEND
NSOCK INFO [71.3370s] nsock_read(): Read request from IOD #2127 [88.255.216.16:80] (timeout: 10000ms) EID 68026
NSOCK INFO [71.3520s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68026 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37660 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.3530s] nsock_read(): Read request from IOD #2127 [88.255.216.16:80] (timeout: 10000ms) EID 68034
NSOCK INFO [71.3530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68034 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37660 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.3530s] nsock_iod_delete(): nsock_iod_delete (IOD #2127)
NSOCK INFO [71.3530s] nsock_iod_new2(): nsock_iod_new (IOD #2128)
NSOCK INFO [71.3540s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2128) EID 68040
NSOCK INFO [71.3670s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68040 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37672 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37672 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 73 75 61 72 69 6f 73 2f 20 48 GET /usuarios/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [71.3670s] nsock_write(): Write request for 180 bytes to IOD #2128 EID 68051 [88.255.216.16:80]
NSOCK INFO [71.3670s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68051 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37672 > 88.255.216.16:80 | SEND
NSOCK INFO [71.3680s] nsock_read(): Read request from IOD #2128 [88.255.216.16:80] (timeout: 10000ms) EID 68058
NSOCK INFO [71.3800s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68058 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37672 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.3810s] nsock_read(): Read request from IOD #2128 [88.255.216.16:80] (timeout: 10000ms) EID 68066
NSOCK INFO [71.3810s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68066 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37672 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.3810s] nsock_iod_delete(): nsock_iod_delete (IOD #2128)
NSOCK INFO [71.3810s] nsock_iod_new2(): nsock_iod_new (IOD #2129)
NSOCK INFO [71.3830s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2129) EID 68072
NSOCK INFO [71.3970s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68072 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37674 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37674 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 74 69 6c 2f 20 48 54 54 50 2f GET /util/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [71.3980s] nsock_write(): Write request for 176 bytes to IOD #2129 EID 68083 [88.255.216.16:80]
NSOCK INFO [71.3980s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68083 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37674 > 88.255.216.16:80 | SEND
NSOCK INFO [71.3980s] nsock_read(): Read request from IOD #2129 [88.255.216.16:80] (timeout: 10000ms) EID 68090
NSOCK INFO [71.4120s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68090 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37674 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.4130s] nsock_read(): Read request from IOD #2129 [88.255.216.16:80] (timeout: 10000ms) EID 68098
NSOCK INFO [71.4130s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68098 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37674 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.4150s] nsock_iod_delete(): nsock_iod_delete (IOD #2129)
NSOCK INFO [71.4150s] nsock_iod_new2(): nsock_iod_new (IOD #2130)
NSOCK INFO [71.4150s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2130) EID 68104
NSOCK INFO [71.4280s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68104 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37690 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37690 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 75 74 69 6c 73 2f 20 48 54 54 50 GET /utils/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [71.4290s] nsock_write(): Write request for 177 bytes to IOD #2130 EID 68115 [88.255.216.16:80]
NSOCK INFO [71.4290s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68115 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37690 > 88.255.216.16:80 | SEND
NSOCK INFO [71.4300s] nsock_read(): Read request from IOD #2130 [88.255.216.16:80] (timeout: 10000ms) EID 68122
NSOCK INFO [71.4430s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68122 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37690 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.4430s] nsock_read(): Read request from IOD #2130 [88.255.216.16:80] (timeout: 10000ms) EID 68130
NSOCK INFO [71.4430s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68130 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37690 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.4440s] nsock_iod_delete(): nsock_iod_delete (IOD #2130)
NSOCK INFO [71.4440s] nsock_iod_new2(): nsock_iod_new (IOD #2131)
NSOCK INFO [71.4450s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2131) EID 68136
NSOCK INFO [71.4570s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68136 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37692 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37692 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 76 65 6e 64 6f 72 2f 20 48 54 54 GET /vendor/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [71.4580s] nsock_write(): Write request for 178 bytes to IOD #2131 EID 68147 [88.255.216.16:80]
NSOCK INFO [71.4580s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68147 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37692 > 88.255.216.16:80 | SEND
NSOCK INFO [71.4590s] nsock_read(): Read request from IOD #2131 [88.255.216.16:80] (timeout: 10000ms) EID 68154
NSOCK INFO [71.4720s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68154 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37692 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.4730s] nsock_read(): Read request from IOD #2131 [88.255.216.16:80] (timeout: 10000ms) EID 68162
NSOCK INFO [71.4730s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68162 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37692 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.4730s] nsock_iod_delete(): nsock_iod_delete (IOD #2131)
NSOCK INFO [71.4730s] nsock_iod_new2(): nsock_iod_new (IOD #2132)
NSOCK INFO [71.4730s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2132) EID 68168
NSOCK INFO [71.4870s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68168 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37698 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37698 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 76 66 73 2f 20 48 54 54 50 2f 31 GET /vfs/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [71.4870s] nsock_write(): Write request for 175 bytes to IOD #2132 EID 68179 [88.255.216.16:80]
NSOCK INFO [71.4870s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68179 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37698 > 88.255.216.16:80 | SEND
NSOCK INFO [71.4880s] nsock_read(): Read request from IOD #2132 [88.255.216.16:80] (timeout: 10000ms) EID 68186
NSOCK INFO [71.5010s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68186 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37698 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.5020s] nsock_read(): Read request from IOD #2132 [88.255.216.16:80] (timeout: 10000ms) EID 68194
NSOCK INFO [71.5020s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68194 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37698 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.5020s] nsock_iod_delete(): nsock_iod_delete (IOD #2132)
NSOCK INFO [71.5020s] nsock_iod_new2(): nsock_iod_new (IOD #2133)
NSOCK INFO [71.5030s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2133) EID 68200
NSOCK INFO [71.5160s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68200 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37708 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37708 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 76 69 65 77 2f 20 48 54 54 50 2f GET /view/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [71.5170s] nsock_write(): Write request for 176 bytes to IOD #2133 EID 68211 [88.255.216.16:80]
NSOCK INFO [71.5170s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68211 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37708 > 88.255.216.16:80 | SEND
NSOCK INFO [71.5170s] nsock_read(): Read request from IOD #2133 [88.255.216.16:80] (timeout: 10000ms) EID 68218
NSOCK INFO [71.5300s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68218 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37708 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.5310s] nsock_read(): Read request from IOD #2133 [88.255.216.16:80] (timeout: 10000ms) EID 68226
NSOCK INFO [71.5310s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68226 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37708 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.5310s] nsock_iod_delete(): nsock_iod_delete (IOD #2133)
NSOCK INFO [71.5310s] nsock_iod_new2(): nsock_iod_new (IOD #2134)
NSOCK INFO [71.5320s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2134) EID 68232
NSOCK INFO [71.5450s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68232 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37712 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37712 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 76 70 6e 2f 20 48 54 54 50 2f 31 GET /vpn/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [71.5460s] nsock_write(): Write request for 175 bytes to IOD #2134 EID 68243 [88.255.216.16:80]
NSOCK INFO [71.5460s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68243 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37712 > 88.255.216.16:80 | SEND
NSOCK INFO [71.5470s] nsock_read(): Read request from IOD #2134 [88.255.216.16:80] (timeout: 10000ms) EID 68250
NSOCK INFO [71.5590s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68250 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37712 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.5600s] nsock_read(): Read request from IOD #2134 [88.255.216.16:80] (timeout: 10000ms) EID 68258
NSOCK INFO [71.5600s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68258 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37712 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.5600s] nsock_iod_delete(): nsock_iod_delete (IOD #2134)
NSOCK INFO [71.5600s] nsock_iod_new2(): nsock_iod_new (IOD #2135)
NSOCK INFO [71.5610s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2135) EID 68264
NSOCK INFO [71.5740s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68264 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37728 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37728 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 76 74 69 5f 74 78 74 2f 20 48 54 GET /vti_txt/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.5750s] nsock_write(): Write request for 179 bytes to IOD #2135 EID 68275 [88.255.216.16:80]
NSOCK INFO [71.5750s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68275 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37728 > 88.255.216.16:80 | SEND
NSOCK INFO [71.5750s] nsock_read(): Read request from IOD #2135 [88.255.216.16:80] (timeout: 10000ms) EID 68282
NSOCK INFO [71.5890s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68282 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37728 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.5900s] nsock_read(): Read request from IOD #2135 [88.255.216.16:80] (timeout: 10000ms) EID 68290
NSOCK INFO [71.5900s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68290 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37728 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.5900s] nsock_iod_delete(): nsock_iod_delete (IOD #2135)
NSOCK INFO [71.5900s] nsock_iod_new2(): nsock_iod_new (IOD #2136)
NSOCK INFO [71.5910s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2136) EID 68296
NSOCK INFO [71.6050s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68296 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37730 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37730 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 32 30 30 30 2f 20 48 54 54 50 GET /w2000/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [71.6060s] nsock_write(): Write request for 177 bytes to IOD #2136 EID 68307 [88.255.216.16:80]
NSOCK INFO [71.6060s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68307 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37730 > 88.255.216.16:80 | SEND
NSOCK INFO [71.6070s] nsock_read(): Read request from IOD #2136 [88.255.216.16:80] (timeout: 10000ms) EID 68314
NSOCK INFO [71.6190s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68314 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37730 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.6200s] nsock_read(): Read request from IOD #2136 [88.255.216.16:80] (timeout: 10000ms) EID 68322
NSOCK INFO [71.6200s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68322 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37730 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.6200s] nsock_iod_delete(): nsock_iod_delete (IOD #2136)
NSOCK INFO [71.6200s] nsock_iod_new2(): nsock_iod_new (IOD #2137)
NSOCK INFO [71.6210s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2137) EID 68328
NSOCK INFO [71.6340s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68328 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37744 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37744 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 32 6b 2f 20 48 54 54 50 2f 31 GET /w2k/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [71.6350s] nsock_write(): Write request for 175 bytes to IOD #2137 EID 68339 [88.255.216.16:80]
NSOCK INFO [71.6350s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68339 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37744 > 88.255.216.16:80 | SEND
NSOCK INFO [71.6360s] nsock_read(): Read request from IOD #2137 [88.255.216.16:80] (timeout: 10000ms) EID 68346
NSOCK INFO [71.6490s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68346 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37744 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.6490s] nsock_read(): Read request from IOD #2137 [88.255.216.16:80] (timeout: 10000ms) EID 68354
NSOCK INFO [71.6490s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68354 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37744 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.6490s] nsock_iod_delete(): nsock_iod_delete (IOD #2137)
NSOCK INFO [71.6490s] nsock_iod_new2(): nsock_iod_new (IOD #2138)
NSOCK INFO [71.6500s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2138) EID 68360
NSOCK INFO [71.6630s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68360 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37752 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37752 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 33 70 65 72 6c 2f 20 48 54 54 GET /w3perl/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [71.6630s] nsock_write(): Write request for 178 bytes to IOD #2138 EID 68371 [88.255.216.16:80]
NSOCK INFO [71.6630s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68371 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37752 > 88.255.216.16:80 | SEND
NSOCK INFO [71.6640s] nsock_read(): Read request from IOD #2138 [88.255.216.16:80] (timeout: 10000ms) EID 68378
NSOCK INFO [71.6770s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68378 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37752 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.6770s] nsock_read(): Read request from IOD #2138 [88.255.216.16:80] (timeout: 10000ms) EID 68386
NSOCK INFO [71.6770s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68386 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37752 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.6780s] nsock_iod_delete(): nsock_iod_delete (IOD #2138)
NSOCK INFO [71.6780s] nsock_iod_new2(): nsock_iod_new (IOD #2139)
NSOCK INFO [71.6780s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2139) EID 68392
NSOCK INFO [71.6910s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68392 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37768 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37768 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 2d 61 67 6f 72 61 2f 20 48 54 GET /w-agora/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.6920s] nsock_write(): Write request for 179 bytes to IOD #2139 EID 68403 [88.255.216.16:80]
NSOCK INFO [71.6920s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68403 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37768 > 88.255.216.16:80 | SEND
NSOCK INFO [71.6930s] nsock_read(): Read request from IOD #2139 [88.255.216.16:80] (timeout: 10000ms) EID 68410
NSOCK INFO [71.7050s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68410 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37768 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.7070s] nsock_read(): Read request from IOD #2139 [88.255.216.16:80] (timeout: 10000ms) EID 68418
NSOCK INFO [71.7070s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68418 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37768 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.7080s] nsock_iod_delete(): nsock_iod_delete (IOD #2139)
NSOCK INFO [71.7080s] nsock_iod_new2(): nsock_iod_new (IOD #2140)
NSOCK INFO [71.7090s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2140) EID 68424
NSOCK INFO [71.7260s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68424 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37774 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37774 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 61 79 2d 62 6f 61 72 64 2f 20 GET /way-board/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [71.7280s] nsock_write(): Write request for 181 bytes to IOD #2140 EID 68435 [88.255.216.16:80]
NSOCK INFO [71.7280s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68435 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37774 > 88.255.216.16:80 | SEND
NSOCK INFO [71.7290s] nsock_read(): Read request from IOD #2140 [88.255.216.16:80] (timeout: 10000ms) EID 68442
NSOCK INFO [71.7460s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68442 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37774 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.7460s] nsock_read(): Read request from IOD #2140 [88.255.216.16:80] (timeout: 10000ms) EID 68450
NSOCK INFO [71.7460s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68450 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37774 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.7470s] nsock_iod_delete(): nsock_iod_delete (IOD #2140)
NSOCK INFO [71.7470s] nsock_iod_new2(): nsock_iod_new (IOD #2141)
NSOCK INFO [71.7470s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2141) EID 68456
NSOCK INFO [71.7610s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68456 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37784 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37784 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 38 30 30 66 6f 2f 20 48 GET /web800fo/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [71.7610s] nsock_write(): Write request for 180 bytes to IOD #2141 EID 68467 [88.255.216.16:80]
NSOCK INFO [71.7610s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68467 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37784 > 88.255.216.16:80 | SEND
NSOCK INFO [71.7620s] nsock_read(): Read request from IOD #2141 [88.255.216.16:80] (timeout: 10000ms) EID 68474
NSOCK INFO [71.7740s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68474 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37784 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.7750s] nsock_read(): Read request from IOD #2141 [88.255.216.16:80] (timeout: 10000ms) EID 68482
NSOCK INFO [71.7750s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68482 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37784 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.7760s] nsock_iod_delete(): nsock_iod_delete (IOD #2141)
NSOCK INFO [71.7760s] nsock_iod_new2(): nsock_iod_new (IOD #2142)
NSOCK INFO [71.7760s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2142) EID 68488
NSOCK INFO [71.7890s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68488 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37790 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37790 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 61 63 63 65 73 73 2f 20 GET /webaccess/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [71.7900s] nsock_write(): Write request for 181 bytes to IOD #2142 EID 68499 [88.255.216.16:80]
NSOCK INFO [71.7900s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68499 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37790 > 88.255.216.16:80 | SEND
NSOCK INFO [71.7910s] nsock_read(): Read request from IOD #2142 [88.255.216.16:80] (timeout: 10000ms) EID 68506
NSOCK INFO [71.8040s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68506 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37790 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.8050s] nsock_read(): Read request from IOD #2142 [88.255.216.16:80] (timeout: 10000ms) EID 68514
NSOCK INFO [71.8050s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68514 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37790 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.8050s] nsock_iod_delete(): nsock_iod_delete (IOD #2142)
NSOCK INFO [71.8050s] nsock_iod_new2(): nsock_iod_new (IOD #2143)
NSOCK INFO [71.8060s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2143) EID 68520
NSOCK INFO [71.8200s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68520 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37796 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37796 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 61 64 6d 69 6e 2f 20 48 GET /webadmin/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [71.8220s] nsock_write(): Write request for 180 bytes to IOD #2143 EID 68531 [88.255.216.16:80]
NSOCK INFO [71.8220s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68531 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37796 > 88.255.216.16:80 | SEND
NSOCK INFO [71.8230s] nsock_read(): Read request from IOD #2143 [88.255.216.16:80] (timeout: 10000ms) EID 68538
NSOCK INFO [71.8350s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68538 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37796 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.8380s] nsock_read(): Read request from IOD #2143 [88.255.216.16:80] (timeout: 10000ms) EID 68546
NSOCK INFO [71.8380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68546 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37796 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.8390s] nsock_iod_delete(): nsock_iod_delete (IOD #2143)
NSOCK INFO [71.8390s] nsock_iod_new2(): nsock_iod_new (IOD #2144)
NSOCK INFO [71.8400s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2144) EID 68552
NSOCK INFO [71.8530s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68552 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37802 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37802 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 41 64 6d 69 6e 2f 20 48 GET /webAdmin/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [71.8540s] nsock_write(): Write request for 180 bytes to IOD #2144 EID 68563 [88.255.216.16:80]
NSOCK INFO [71.8540s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68563 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37802 > 88.255.216.16:80 | SEND
NSOCK INFO [71.8550s] nsock_read(): Read request from IOD #2144 [88.255.216.16:80] (timeout: 10000ms) EID 68570
NSOCK INFO [71.8670s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68570 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37802 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.8680s] nsock_read(): Read request from IOD #2144 [88.255.216.16:80] (timeout: 10000ms) EID 68578
NSOCK INFO [71.8680s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68578 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37802 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.8690s] nsock_iod_delete(): nsock_iod_delete (IOD #2144)
NSOCK INFO [71.8690s] nsock_iod_new2(): nsock_iod_new (IOD #2145)
NSOCK INFO [71.8710s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2145) EID 68584
NSOCK INFO [71.8840s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68584 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37806 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37806 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 61 6c 69 7a 65 72 2f 20 GET /webalizer/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [71.8850s] nsock_write(): Write request for 181 bytes to IOD #2145 EID 68595 [88.255.216.16:80]
NSOCK INFO [71.8850s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68595 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37806 > 88.255.216.16:80 | SEND
NSOCK INFO [71.8860s] nsock_read(): Read request from IOD #2145 [88.255.216.16:80] (timeout: 10000ms) EID 68602
NSOCK INFO [71.8990s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68602 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37806 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.9010s] nsock_read(): Read request from IOD #2145 [88.255.216.16:80] (timeout: 10000ms) EID 68610
NSOCK INFO [71.9010s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68610 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37806 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.9020s] nsock_iod_delete(): nsock_iod_delete (IOD #2145)
NSOCK INFO [71.9020s] nsock_iod_new2(): nsock_iod_new (IOD #2146)
NSOCK INFO [71.9030s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2146) EID 68616
NSOCK INFO [71.9160s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68616 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37816 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37816 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 61 70 70 73 2f 20 48 54 GET /webapps/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.9170s] nsock_write(): Write request for 179 bytes to IOD #2146 EID 68627 [88.255.216.16:80]
NSOCK INFO [71.9170s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68627 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37816 > 88.255.216.16:80 | SEND
NSOCK INFO [71.9180s] nsock_read(): Read request from IOD #2146 [88.255.216.16:80] (timeout: 10000ms) EID 68634
NSOCK INFO [71.9310s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68634 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37816 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.9320s] nsock_read(): Read request from IOD #2146 [88.255.216.16:80] (timeout: 10000ms) EID 68642
NSOCK INFO [71.9320s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68642 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37816 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.9320s] nsock_iod_delete(): nsock_iod_delete (IOD #2146)
NSOCK INFO [71.9320s] nsock_iod_new2(): nsock_iod_new (IOD #2147)
NSOCK INFO [71.9330s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2147) EID 68648
NSOCK INFO [71.9470s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68648 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37822 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37822 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 57 65 62 42 61 6e 6b 2f 20 48 54 GET /WebBank/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [71.9480s] nsock_write(): Write request for 179 bytes to IOD #2147 EID 68659 [88.255.216.16:80]
NSOCK INFO [71.9480s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68659 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37822 > 88.255.216.16:80 | SEND
NSOCK INFO [71.9500s] nsock_read(): Read request from IOD #2147 [88.255.216.16:80] (timeout: 10000ms) EID 68666
NSOCK INFO [71.9610s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68666 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37822 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.9610s] nsock_read(): Read request from IOD #2147 [88.255.216.16:80] (timeout: 10000ms) EID 68674
NSOCK INFO [71.9610s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68674 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37822 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.9620s] nsock_iod_delete(): nsock_iod_delete (IOD #2147)
NSOCK INFO [71.9620s] nsock_iod_new2(): nsock_iod_new (IOD #2148)
NSOCK INFO [71.9620s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2148) EID 68680
NSOCK INFO [71.9770s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68680 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37838 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37838 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 62 6f 61 72 64 2f 20 48 GET /webboard/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [71.9780s] nsock_write(): Write request for 180 bytes to IOD #2148 EID 68691 [88.255.216.16:80]
NSOCK INFO [71.9780s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68691 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37838 > 88.255.216.16:80 | SEND
NSOCK INFO [71.9790s] nsock_read(): Read request from IOD #2148 [88.255.216.16:80] (timeout: 10000ms) EID 68698
NSOCK INFO [71.9920s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68698 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37838 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [71.9940s] nsock_read(): Read request from IOD #2148 [88.255.216.16:80] (timeout: 10000ms) EID 68706
NSOCK INFO [71.9940s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68706 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37838 > 88.255.216.16:80 | CLOSE
NSOCK INFO [71.9940s] nsock_iod_delete(): nsock_iod_delete (IOD #2148)
NSOCK INFO [71.9940s] nsock_iod_new2(): nsock_iod_new (IOD #2149)
NSOCK INFO [71.9950s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2149) EID 68712
NSOCK INFO [72.0060s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68712 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37846 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37846 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 57 65 62 43 61 6c 65 6e 64 61 72 GET /WebCalendar
00000010: 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 / HTTP/1.1  Host
00000020: 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e : 88.255.216.16.
00000030: 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d static.ttnet.com
00000040: 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a .tr  User-Agent:
00000050: 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f  Mozilla/5.0 (co
00000060: 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 mpatible; Nmap S
00000070: 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b cripting Engine;
00000080: 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72  https://nmap.or
00000090: 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 g/book/nse.html)
000000a0: 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c   Connection: cl
000000b0: 6f 73 65 0d 0a 0d 0a                            ose    

NSOCK INFO [72.0070s] nsock_write(): Write request for 183 bytes to IOD #2149 EID 68723 [88.255.216.16:80]
NSOCK INFO [72.0070s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68723 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37846 > 88.255.216.16:80 | SEND
NSOCK INFO [72.0090s] nsock_read(): Read request from IOD #2149 [88.255.216.16:80] (timeout: 10000ms) EID 68730
NSOCK INFO [72.0200s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68730 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37846 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [72.0210s] nsock_read(): Read request from IOD #2149 [88.255.216.16:80] (timeout: 10000ms) EID 68738
NSOCK INFO [72.0210s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68738 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37846 > 88.255.216.16:80 | CLOSE
NSOCK INFO [72.0210s] nsock_iod_delete(): nsock_iod_delete (IOD #2149)
NSOCK INFO [72.0210s] nsock_iod_new2(): nsock_iod_new (IOD #2150)
NSOCK INFO [72.0220s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2150) EID 68744
NSOCK INFO [72.0360s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68744 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37854 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37854 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 63 61 72 74 2f 20 48 54 GET /webcart/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [72.0370s] nsock_write(): Write request for 179 bytes to IOD #2150 EID 68755 [88.255.216.16:80]
NSOCK INFO [72.0370s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68755 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37854 > 88.255.216.16:80 | SEND
NSOCK INFO [72.0380s] nsock_read(): Read request from IOD #2150 [88.255.216.16:80] (timeout: 10000ms) EID 68762
NSOCK INFO [72.0500s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68762 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37854 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [72.0510s] nsock_read(): Read request from IOD #2150 [88.255.216.16:80] (timeout: 10000ms) EID 68770
NSOCK INFO [72.0510s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68770 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37854 > 88.255.216.16:80 | CLOSE
NSOCK INFO [72.0510s] nsock_iod_delete(): nsock_iod_delete (IOD #2150)
NSOCK INFO [72.0510s] nsock_iod_new2(): nsock_iod_new (IOD #2151)
NSOCK INFO [72.0520s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2151) EID 68776
NSOCK INFO [72.0650s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68776 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37870 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37870 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 63 61 72 74 2d 6c 69 74 GET /webcart-lit
00000010: 65 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 e/ HTTP/1.1  Hos
00000020: 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 t: 88.255.216.16
00000030: 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f .static.ttnet.co
00000040: 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 m.tr  User-Agent
00000050: 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 : Mozilla/5.0 (c
00000060: 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 ompatible; Nmap 
00000070: 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 Scripting Engine
00000080: 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f ; https://nmap.o
00000090: 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c rg/book/nse.html
000000a0: 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 )  Connection: c
000000b0: 6c 6f 73 65 0d 0a 0d 0a                         lose    

NSOCK INFO [72.0660s] nsock_write(): Write request for 184 bytes to IOD #2151 EID 68787 [88.255.216.16:80]
NSOCK INFO [72.0660s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68787 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37870 > 88.255.216.16:80 | SEND
NSOCK INFO [72.0680s] nsock_read(): Read request from IOD #2151 [88.255.216.16:80] (timeout: 10000ms) EID 68794
NSOCK INFO [72.3010s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68794 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37870 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [72.3020s] nsock_read(): Read request from IOD #2151 [88.255.216.16:80] (timeout: 10000ms) EID 68802
NSOCK INFO [72.3020s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68802 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37870 > 88.255.216.16:80 | CLOSE
NSOCK INFO [72.3020s] nsock_iod_delete(): nsock_iod_delete (IOD #2151)
NSOCK INFO [72.3020s] nsock_iod_new2(): nsock_iod_new (IOD #2152)
NSOCK INFO [72.3030s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2152) EID 68808
NSOCK INFO [72.3160s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68808 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37874 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37874 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 63 67 69 2f 20 48 54 54 GET /webcgi/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [72.3170s] nsock_write(): Write request for 178 bytes to IOD #2152 EID 68819 [88.255.216.16:80]
NSOCK INFO [72.3170s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68819 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37874 > 88.255.216.16:80 | SEND
NSOCK INFO [72.3180s] nsock_read(): Read request from IOD #2152 [88.255.216.16:80] (timeout: 10000ms) EID 68826
NSOCK INFO [72.3310s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68826 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37874 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [72.3320s] nsock_read(): Read request from IOD #2152 [88.255.216.16:80] (timeout: 10000ms) EID 68834
NSOCK INFO [72.3320s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68834 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37874 > 88.255.216.16:80 | CLOSE
NSOCK INFO [72.3320s] nsock_iod_delete(): nsock_iod_delete (IOD #2152)
NSOCK INFO [72.3320s] nsock_iod_new2(): nsock_iod_new (IOD #2153)
NSOCK INFO [72.3330s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2153) EID 68840
NSOCK INFO [72.3460s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68840 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37886 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37886 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 64 61 74 61 2f 20 48 54 GET /webdata/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [72.3470s] nsock_write(): Write request for 179 bytes to IOD #2153 EID 68851 [88.255.216.16:80]
NSOCK INFO [72.3470s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68851 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37886 > 88.255.216.16:80 | SEND
NSOCK INFO [72.3480s] nsock_read(): Read request from IOD #2153 [88.255.216.16:80] (timeout: 10000ms) EID 68858
NSOCK INFO [72.3600s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68858 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37886 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [72.3610s] nsock_read(): Read request from IOD #2153 [88.255.216.16:80] (timeout: 10000ms) EID 68866
NSOCK INFO [72.3610s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68866 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37886 > 88.255.216.16:80 | CLOSE
NSOCK INFO [72.3610s] nsock_iod_delete(): nsock_iod_delete (IOD #2153)
NSOCK INFO [72.3610s] nsock_iod_new2(): nsock_iod_new (IOD #2154)
NSOCK INFO [72.3620s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2154) EID 68872
NSOCK INFO [73.4320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68872 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37898 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37898 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 64 61 76 2f 20 48 54 54 GET /webdav/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [73.4330s] nsock_write(): Write request for 178 bytes to IOD #2154 EID 68883 [88.255.216.16:80]
NSOCK INFO [73.4330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68883 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37898 > 88.255.216.16:80 | SEND
NSOCK INFO [73.4340s] nsock_read(): Read request from IOD #2154 [88.255.216.16:80] (timeout: 10000ms) EID 68890
NSOCK INFO [73.4510s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68890 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37898 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.4530s] nsock_read(): Read request from IOD #2154 [88.255.216.16:80] (timeout: 10000ms) EID 68898
NSOCK INFO [73.4530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68898 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37898 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.4530s] nsock_iod_delete(): nsock_iod_delete (IOD #2154)
NSOCK INFO [73.4530s] nsock_iod_new2(): nsock_iod_new (IOD #2155)
NSOCK INFO [73.4540s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2155) EID 68904
NSOCK INFO [73.4800s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68904 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37900 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37900 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 64 62 2f 20 48 54 54 50 GET /webdb/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [73.4810s] nsock_write(): Write request for 177 bytes to IOD #2155 EID 68915 [88.255.216.16:80]
NSOCK INFO [73.4810s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68915 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37900 > 88.255.216.16:80 | SEND
NSOCK INFO [73.4830s] nsock_read(): Read request from IOD #2155 [88.255.216.16:80] (timeout: 10000ms) EID 68922
NSOCK INFO [73.7380s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68922 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37900 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.7380s] nsock_read(): Read request from IOD #2155 [88.255.216.16:80] (timeout: 10000ms) EID 68930
NSOCK INFO [73.7380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68930 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37900 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.7390s] nsock_iod_delete(): nsock_iod_delete (IOD #2155)
NSOCK INFO [73.7390s] nsock_iod_new2(): nsock_iod_new (IOD #2156)
NSOCK INFO [73.7400s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2156) EID 68936
NSOCK INFO [73.7550s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68936 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37908 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37908 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 44 42 2f 20 48 54 54 50 GET /webDB/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [73.7560s] nsock_write(): Write request for 177 bytes to IOD #2156 EID 68947 [88.255.216.16:80]
NSOCK INFO [73.7560s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68947 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37908 > 88.255.216.16:80 | SEND
NSOCK INFO [73.7580s] nsock_read(): Read request from IOD #2156 [88.255.216.16:80] (timeout: 10000ms) EID 68954
NSOCK INFO [73.7740s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68954 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37908 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.7760s] nsock_read(): Read request from IOD #2156 [88.255.216.16:80] (timeout: 10000ms) EID 68962
NSOCK INFO [73.7760s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68962 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37908 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.7760s] nsock_iod_delete(): nsock_iod_delete (IOD #2156)
NSOCK INFO [73.7760s] nsock_iod_new2(): nsock_iod_new (IOD #2157)
NSOCK INFO [73.7780s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2157) EID 68968
NSOCK INFO [73.7980s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 68968 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37914 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37914 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 2f 20 48 54 54 50 2f 31 GET /web/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [73.7990s] nsock_write(): Write request for 175 bytes to IOD #2157 EID 68979 [88.255.216.16:80]
NSOCK INFO [73.7990s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 68979 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37914 > 88.255.216.16:80 | SEND
NSOCK INFO [73.8020s] nsock_read(): Read request from IOD #2157 [88.255.216.16:80] (timeout: 10000ms) EID 68986
NSOCK INFO [73.8310s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 68986 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37914 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.8320s] nsock_read(): Read request from IOD #2157 [88.255.216.16:80] (timeout: 10000ms) EID 68994
NSOCK INFO [73.8320s] nsock_trace_handler_callback(): Callback: READ EOF for EID 68994 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37914 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.8330s] nsock_iod_delete(): nsock_iod_delete (IOD #2157)
NSOCK INFO [73.8330s] nsock_iod_new2(): nsock_iod_new (IOD #2158)
NSOCK INFO [73.8340s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2158) EID 69000
NSOCK INFO [73.8620s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69000 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37916 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37916 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 69 6d 61 67 65 73 32 2f GET /webimages2/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [73.8620s] nsock_write(): Write request for 182 bytes to IOD #2158 EID 69011 [88.255.216.16:80]
NSOCK INFO [73.8630s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69011 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37916 > 88.255.216.16:80 | SEND
NSOCK INFO [73.8630s] nsock_read(): Read request from IOD #2158 [88.255.216.16:80] (timeout: 10000ms) EID 69018
NSOCK INFO [73.8780s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69018 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37916 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.8790s] nsock_read(): Read request from IOD #2158 [88.255.216.16:80] (timeout: 10000ms) EID 69026
NSOCK INFO [73.8790s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69026 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37916 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.8790s] nsock_iod_delete(): nsock_iod_delete (IOD #2158)
NSOCK INFO [73.8790s] nsock_iod_new2(): nsock_iod_new (IOD #2159)
NSOCK INFO [73.8800s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2159) EID 69032
NSOCK INFO [73.8920s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69032 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37928 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37928 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 69 6d 61 67 65 73 2f 20 GET /webimages/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [73.8930s] nsock_write(): Write request for 181 bytes to IOD #2159 EID 69043 [88.255.216.16:80]
NSOCK INFO [73.8930s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69043 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37928 > 88.255.216.16:80 | SEND
NSOCK INFO [73.8940s] nsock_read(): Read request from IOD #2159 [88.255.216.16:80] (timeout: 10000ms) EID 69050
NSOCK INFO [73.9120s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69050 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37928 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.9130s] nsock_read(): Read request from IOD #2159 [88.255.216.16:80] (timeout: 10000ms) EID 69058
NSOCK INFO [73.9130s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69058 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37928 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.9130s] nsock_iod_delete(): nsock_iod_delete (IOD #2159)
NSOCK INFO [73.9130s] nsock_iod_new2(): nsock_iod_new (IOD #2160)
NSOCK INFO [73.9140s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2160) EID 69064
NSOCK INFO [73.9440s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69064 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37932 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37932 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 2d 69 6e 66 2f 20 48 54 GET /web-inf/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [73.9450s] nsock_write(): Write request for 179 bytes to IOD #2160 EID 69075 [88.255.216.16:80]
NSOCK INFO [73.9450s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69075 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37932 > 88.255.216.16:80 | SEND
NSOCK INFO [73.9470s] nsock_read(): Read request from IOD #2160 [88.255.216.16:80] (timeout: 10000ms) EID 69082
NSOCK INFO [73.9680s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69082 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37932 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.9690s] nsock_read(): Read request from IOD #2160 [88.255.216.16:80] (timeout: 10000ms) EID 69090
NSOCK INFO [73.9690s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69090 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37932 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.9690s] nsock_iod_delete(): nsock_iod_delete (IOD #2160)
NSOCK INFO [73.9690s] nsock_iod_new2(): nsock_iod_new (IOD #2161)
NSOCK INFO [73.9700s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2161) EID 69096
NSOCK INFO [73.9830s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69096 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37934 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37934 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 6d 61 73 74 65 72 2f 20 GET /webmaster/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [73.9840s] nsock_write(): Write request for 181 bytes to IOD #2161 EID 69107 [88.255.216.16:80]
NSOCK INFO [73.9840s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69107 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37934 > 88.255.216.16:80 | SEND
NSOCK INFO [73.9850s] nsock_read(): Read request from IOD #2161 [88.255.216.16:80] (timeout: 10000ms) EID 69114
NSOCK INFO [73.9980s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69114 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37934 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [73.9980s] nsock_read(): Read request from IOD #2161 [88.255.216.16:80] (timeout: 10000ms) EID 69122
NSOCK INFO [73.9980s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69122 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37934 > 88.255.216.16:80 | CLOSE
NSOCK INFO [73.9990s] nsock_iod_delete(): nsock_iod_delete (IOD #2161)
NSOCK INFO [73.9990s] nsock_iod_new2(): nsock_iod_new (IOD #2162)
NSOCK INFO [73.9990s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2162) EID 69128
NSOCK INFO [74.0280s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69128 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37936 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37936 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 6d 61 73 74 65 72 5f 6c GET /webmaster_l
00000010: 6f 67 73 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 ogs/ HTTP/1.1  H
00000020: 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e ost: 88.255.216.
00000030: 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 16.static.ttnet.
00000040: 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 com.tr  User-Age
00000050: 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 nt: Mozilla/5.0 
00000060: 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 (compatible; Nma
00000070: 70 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 p Scripting Engi
00000080: 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 ne; https://nmap
00000090: 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 .org/book/nse.ht
000000a0: 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a ml)  Connection:
000000b0: 20 63 6c 6f 73 65 0d 0a 0d 0a                    close    

NSOCK INFO [74.0290s] nsock_write(): Write request for 186 bytes to IOD #2162 EID 69139 [88.255.216.16:80]
NSOCK INFO [74.0290s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69139 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37936 > 88.255.216.16:80 | SEND
NSOCK INFO [74.0300s] nsock_read(): Read request from IOD #2162 [88.255.216.16:80] (timeout: 10000ms) EID 69146
NSOCK INFO [74.0580s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69146 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37936 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [74.0590s] nsock_read(): Read request from IOD #2162 [88.255.216.16:80] (timeout: 10000ms) EID 69154
NSOCK INFO [74.0590s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69154 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37936 > 88.255.216.16:80 | CLOSE
NSOCK INFO [74.0590s] nsock_iod_delete(): nsock_iod_delete (IOD #2162)
NSOCK INFO [74.0590s] nsock_iod_new2(): nsock_iod_new (IOD #2163)
NSOCK INFO [74.0600s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2163) EID 69160
NSOCK INFO [75.0850s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69160 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37940 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:37940 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 4d 61 74 68 65 6d 61 74 GET /webMathemat
00000010: 69 63 61 2f 20 48 54 54 50 2f 31 2e 31 0d 0a 48 ica/ HTTP/1.1  H
00000020: 6f 73 74 3a 20 38 38 2e 32 35 35 2e 32 31 36 2e ost: 88.255.216.
00000030: 31 36 2e 73 74 61 74 69 63 2e 74 74 6e 65 74 2e 16.static.ttnet.
00000040: 63 6f 6d 2e 74 72 0d 0a 55 73 65 72 2d 41 67 65 com.tr  User-Age
00000050: 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 nt: Mozilla/5.0 
00000060: 28 63 6f 6d 70 61 74 69 62 6c 65 3b 20 4e 6d 61 (compatible; Nma
00000070: 70 20 53 63 72 69 70 74 69 6e 67 20 45 6e 67 69 p Scripting Engi
00000080: 6e 65 3b 20 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 ne; https://nmap
00000090: 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 .org/book/nse.ht
000000a0: 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a ml)  Connection:
000000b0: 20 63 6c 6f 73 65 0d 0a 0d 0a                    close    

NSOCK INFO [75.0860s] nsock_write(): Write request for 186 bytes to IOD #2163 EID 69171 [88.255.216.16:80]
NSOCK INFO [75.0860s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69171 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37940 > 88.255.216.16:80 | SEND
NSOCK INFO [75.0870s] nsock_read(): Read request from IOD #2163 [88.255.216.16:80] (timeout: 10000ms) EID 69178
NSOCK INFO [75.0990s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69178 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:37940 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [75.1000s] nsock_read(): Read request from IOD #2163 [88.255.216.16:80] (timeout: 10000ms) EID 69186
NSOCK INFO [75.1000s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69186 [88.255.216.16:80]
NSE: TCP 192.168.31.147:37940 > 88.255.216.16:80 | CLOSE
NSOCK INFO [75.1000s] nsock_iod_delete(): nsock_iod_delete (IOD #2163)
NSOCK INFO [75.1000s] nsock_iod_new2(): nsock_iod_new (IOD #2164)
NSOCK INFO [75.1010s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2164) EID 69192
NSOCK INFO [75.1140s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69192 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33322 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33322 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 70 75 62 2f 20 48 54 54 GET /webpub/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [75.1150s] nsock_write(): Write request for 178 bytes to IOD #2164 EID 69203 [88.255.216.16:80]
NSOCK INFO [75.1150s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69203 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33322 > 88.255.216.16:80 | SEND
NSOCK INFO [75.1160s] nsock_read(): Read request from IOD #2164 [88.255.216.16:80] (timeout: 10000ms) EID 69210
NSOCK INFO [75.1290s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69210 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33322 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [75.1290s] nsock_read(): Read request from IOD #2164 [88.255.216.16:80] (timeout: 10000ms) EID 69218
NSOCK INFO [75.1290s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69218 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33322 > 88.255.216.16:80 | CLOSE
NSOCK INFO [75.1300s] nsock_iod_delete(): nsock_iod_delete (IOD #2164)
NSOCK INFO [75.1300s] nsock_iod_new2(): nsock_iod_new (IOD #2165)
NSOCK INFO [75.1300s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2165) EID 69224
NSOCK INFO [75.1450s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69224 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33338 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33338 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 70 75 62 2d 75 69 2f 20 GET /webpub-ui/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [75.1460s] nsock_write(): Write request for 181 bytes to IOD #2165 EID 69235 [88.255.216.16:80]
NSOCK INFO [75.1460s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69235 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33338 > 88.255.216.16:80 | SEND
NSOCK INFO [75.1470s] nsock_read(): Read request from IOD #2165 [88.255.216.16:80] (timeout: 10000ms) EID 69242
NSOCK INFO [75.1660s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69242 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33338 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [75.1670s] nsock_read(): Read request from IOD #2165 [88.255.216.16:80] (timeout: 10000ms) EID 69250
NSOCK INFO [75.1670s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69250 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33338 > 88.255.216.16:80 | CLOSE
NSOCK INFO [75.1670s] nsock_iod_delete(): nsock_iod_delete (IOD #2165)
NSOCK INFO [75.1670s] nsock_iod_new2(): nsock_iod_new (IOD #2166)
NSOCK INFO [75.1680s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2166) EID 69256
NSOCK INFO [75.1810s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69256 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33342 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33342 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 72 65 70 6f 72 74 73 2f GET /webreports/
00000010: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000020: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000030: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000040: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000050: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000060: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000070: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000080: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
00000090: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000a0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000b0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [75.1830s] nsock_write(): Write request for 182 bytes to IOD #2166 EID 69267 [88.255.216.16:80]
NSOCK INFO [75.1830s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69267 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33342 > 88.255.216.16:80 | SEND
NSOCK INFO [75.1840s] nsock_read(): Read request from IOD #2166 [88.255.216.16:80] (timeout: 10000ms) EID 69274
NSOCK INFO [75.2040s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69274 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33342 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [75.2050s] nsock_read(): Read request from IOD #2166 [88.255.216.16:80] (timeout: 10000ms) EID 69282
NSOCK INFO [75.2050s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69282 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33342 > 88.255.216.16:80 | CLOSE
NSOCK INFO [75.2050s] nsock_iod_delete(): nsock_iod_delete (IOD #2166)
NSOCK INFO [75.2050s] nsock_iod_new2(): nsock_iod_new (IOD #2167)
NSOCK INFO [75.2070s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2167) EID 69288
NSOCK INFO [76.2530s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69288 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33356 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33356 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 72 65 70 73 2f 20 48 54 GET /webreps/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [76.2540s] nsock_write(): Write request for 179 bytes to IOD #2167 EID 69299 [88.255.216.16:80]
NSOCK INFO [76.2540s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69299 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33356 > 88.255.216.16:80 | SEND
NSOCK INFO [76.2550s] nsock_read(): Read request from IOD #2167 [88.255.216.16:80] (timeout: 10000ms) EID 69306
NSOCK INFO [76.2680s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69306 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33356 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.2690s] nsock_read(): Read request from IOD #2167 [88.255.216.16:80] (timeout: 10000ms) EID 69314
NSOCK INFO [76.2690s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69314 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33356 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.2690s] nsock_iod_delete(): nsock_iod_delete (IOD #2167)
NSOCK INFO [76.2690s] nsock_iod_new2(): nsock_iod_new (IOD #2168)
NSOCK INFO [76.2690s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2168) EID 69320
NSOCK INFO [76.2840s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69320 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33372 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33372 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 73 68 61 72 65 2f 20 48 GET /webshare/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [76.2850s] nsock_write(): Write request for 180 bytes to IOD #2168 EID 69331 [88.255.216.16:80]
NSOCK INFO [76.2850s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69331 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33372 > 88.255.216.16:80 | SEND
NSOCK INFO [76.2860s] nsock_read(): Read request from IOD #2168 [88.255.216.16:80] (timeout: 10000ms) EID 69338
NSOCK INFO [76.2980s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69338 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33372 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.2990s] nsock_read(): Read request from IOD #2168 [88.255.216.16:80] (timeout: 10000ms) EID 69346
NSOCK INFO [76.2990s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69346 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33372 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.2990s] nsock_iod_delete(): nsock_iod_delete (IOD #2168)
NSOCK INFO [76.2990s] nsock_iod_new2(): nsock_iod_new (IOD #2169)
NSOCK INFO [76.3000s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2169) EID 69352
NSOCK INFO [76.3130s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69352 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33378 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33378 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 57 65 62 53 68 6f 70 2f 20 48 54 GET /WebShop/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [76.3150s] nsock_write(): Write request for 179 bytes to IOD #2169 EID 69363 [88.255.216.16:80]
NSOCK INFO [76.3150s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69363 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33378 > 88.255.216.16:80 | SEND
NSOCK INFO [76.3160s] nsock_read(): Read request from IOD #2169 [88.255.216.16:80] (timeout: 10000ms) EID 69370
NSOCK INFO [76.3280s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69370 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33378 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.3290s] nsock_read(): Read request from IOD #2169 [88.255.216.16:80] (timeout: 10000ms) EID 69378
NSOCK INFO [76.3290s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69378 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33378 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.3290s] nsock_iod_delete(): nsock_iod_delete (IOD #2169)
NSOCK INFO [76.3290s] nsock_iod_new2(): nsock_iod_new (IOD #2170)
NSOCK INFO [76.3300s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2170) EID 69384
NSOCK INFO [76.3420s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69384 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33382 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33382 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 73 69 74 65 2f 20 48 54 GET /website/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [76.3430s] nsock_write(): Write request for 179 bytes to IOD #2170 EID 69395 [88.255.216.16:80]
NSOCK INFO [76.3430s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69395 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33382 > 88.255.216.16:80 | SEND
NSOCK INFO [76.3440s] nsock_read(): Read request from IOD #2170 [88.255.216.16:80] (timeout: 10000ms) EID 69402
NSOCK INFO [76.3560s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69402 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33382 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.3570s] nsock_read(): Read request from IOD #2170 [88.255.216.16:80] (timeout: 10000ms) EID 69410
NSOCK INFO [76.3570s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69410 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33382 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.3570s] nsock_iod_delete(): nsock_iod_delete (IOD #2170)
NSOCK INFO [76.3570s] nsock_iod_new2(): nsock_iod_new (IOD #2171)
NSOCK INFO [76.3580s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2171) EID 69416
NSOCK INFO [76.3710s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69416 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33396 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33396 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 73 74 61 74 2f 20 48 54 GET /webstat/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [76.3710s] nsock_write(): Write request for 179 bytes to IOD #2171 EID 69427 [88.255.216.16:80]
NSOCK INFO [76.3710s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69427 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33396 > 88.255.216.16:80 | SEND
NSOCK INFO [76.3720s] nsock_read(): Read request from IOD #2171 [88.255.216.16:80] (timeout: 10000ms) EID 69434
NSOCK INFO [76.3860s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69434 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33396 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.3880s] nsock_read(): Read request from IOD #2171 [88.255.216.16:80] (timeout: 10000ms) EID 69442
NSOCK INFO [76.3880s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69442 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33396 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.3890s] nsock_iod_delete(): nsock_iod_delete (IOD #2171)
NSOCK INFO [76.3890s] nsock_iod_new2(): nsock_iod_new (IOD #2172)
NSOCK INFO [76.3890s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2172) EID 69448
NSOCK INFO [76.4020s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69448 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33404 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33404 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 73 74 61 74 73 2f 20 48 GET /webstats/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [76.4030s] nsock_write(): Write request for 180 bytes to IOD #2172 EID 69459 [88.255.216.16:80]
NSOCK INFO [76.4030s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69459 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33404 > 88.255.216.16:80 | SEND
NSOCK INFO [76.4050s] nsock_read(): Read request from IOD #2172 [88.255.216.16:80] (timeout: 10000ms) EID 69466
NSOCK INFO [76.4170s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69466 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33404 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.4170s] nsock_read(): Read request from IOD #2172 [88.255.216.16:80] (timeout: 10000ms) EID 69474
NSOCK INFO [76.4170s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69474 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33404 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.4180s] nsock_iod_delete(): nsock_iod_delete (IOD #2172)
NSOCK INFO [76.4180s] nsock_iod_new2(): nsock_iod_new (IOD #2173)
NSOCK INFO [76.4180s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2173) EID 69480
NSOCK INFO [76.4310s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69480 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33410 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33410 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 57 65 62 5f 73 74 6f 72 65 2f 20 GET /Web_store/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [76.4320s] nsock_write(): Write request for 181 bytes to IOD #2173 EID 69491 [88.255.216.16:80]
NSOCK INFO [76.4320s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69491 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33410 > 88.255.216.16:80 | SEND
NSOCK INFO [76.4330s] nsock_read(): Read request from IOD #2173 [88.255.216.16:80] (timeout: 10000ms) EID 69498
NSOCK INFO [76.4450s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69498 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33410 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.4460s] nsock_read(): Read request from IOD #2173 [88.255.216.16:80] (timeout: 10000ms) EID 69506
NSOCK INFO [76.4460s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69506 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33410 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.4460s] nsock_iod_delete(): nsock_iod_delete (IOD #2173)
NSOCK INFO [76.4460s] nsock_iod_new2(): nsock_iod_new (IOD #2174)
NSOCK INFO [76.4470s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2174) EID 69512
NSOCK INFO [76.4600s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69512 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33420 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33420 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 74 72 61 63 65 2f 20 48 GET /webtrace/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [76.4610s] nsock_write(): Write request for 180 bytes to IOD #2174 EID 69523 [88.255.216.16:80]
NSOCK INFO [76.4610s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69523 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33420 > 88.255.216.16:80 | SEND
NSOCK INFO [76.4620s] nsock_read(): Read request from IOD #2174 [88.255.216.16:80] (timeout: 10000ms) EID 69530
NSOCK INFO [76.4740s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69530 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33420 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.4740s] nsock_read(): Read request from IOD #2174 [88.255.216.16:80] (timeout: 10000ms) EID 69538
NSOCK INFO [76.4740s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69538 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33420 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.4740s] nsock_iod_delete(): nsock_iod_delete (IOD #2174)
NSOCK INFO [76.4740s] nsock_iod_new2(): nsock_iod_new (IOD #2175)
NSOCK INFO [76.4750s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2175) EID 69544
NSOCK INFO [76.4890s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69544 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33432 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33432 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 57 65 62 54 72 65 6e 64 2f 20 48 GET /WebTrend/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [76.4900s] nsock_write(): Write request for 180 bytes to IOD #2175 EID 69555 [88.255.216.16:80]
NSOCK INFO [76.4900s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69555 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33432 > 88.255.216.16:80 | SEND
NSOCK INFO [76.4910s] nsock_read(): Read request from IOD #2175 [88.255.216.16:80] (timeout: 10000ms) EID 69562
NSOCK INFO [76.5040s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69562 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33432 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.5050s] nsock_read(): Read request from IOD #2175 [88.255.216.16:80] (timeout: 10000ms) EID 69570
NSOCK INFO [76.5050s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69570 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33432 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.5050s] nsock_iod_delete(): nsock_iod_delete (IOD #2175)
NSOCK INFO [76.5050s] nsock_iod_new2(): nsock_iod_new (IOD #2176)
NSOCK INFO [76.5060s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2176) EID 69576
NSOCK INFO [76.5200s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69576 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33436 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33436 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 74 72 65 6e 64 73 2f 20 GET /webtrends/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [76.5200s] nsock_write(): Write request for 181 bytes to IOD #2176 EID 69587 [88.255.216.16:80]
NSOCK INFO [76.5200s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69587 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33436 > 88.255.216.16:80 | SEND
NSOCK INFO [76.5210s] nsock_read(): Read request from IOD #2176 [88.255.216.16:80] (timeout: 10000ms) EID 69594
NSOCK INFO [76.5340s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69594 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33436 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.5340s] nsock_read(): Read request from IOD #2176 [88.255.216.16:80] (timeout: 10000ms) EID 69602
NSOCK INFO [76.5340s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69602 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33436 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.5350s] nsock_iod_delete(): nsock_iod_delete (IOD #2176)
NSOCK INFO [76.5350s] nsock_iod_new2(): nsock_iod_new (IOD #2177)
NSOCK INFO [76.5350s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2177) EID 69608
NSOCK INFO [76.5480s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69608 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33440 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33440 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 65 62 5f 75 73 61 67 65 2f 20 GET /web_usage/ 
00000010: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000020: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000030: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000040: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000050: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000060: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000070: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000080: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
00000090: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000a0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000b0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [76.5480s] nsock_write(): Write request for 181 bytes to IOD #2177 EID 69619 [88.255.216.16:80]
NSOCK INFO [76.5480s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69619 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33440 > 88.255.216.16:80 | SEND
NSOCK INFO [76.5510s] nsock_read(): Read request from IOD #2177 [88.255.216.16:80] (timeout: 10000ms) EID 69626
NSOCK INFO [76.5620s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69626 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33440 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.5640s] nsock_read(): Read request from IOD #2177 [88.255.216.16:80] (timeout: 10000ms) EID 69634
NSOCK INFO [76.5640s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69634 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33440 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.5650s] nsock_iod_delete(): nsock_iod_delete (IOD #2177)
NSOCK INFO [76.5650s] nsock_iod_new2(): nsock_iod_new (IOD #2178)
NSOCK INFO [76.5660s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2178) EID 69640
NSOCK INFO [76.5790s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69640 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33442 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33442 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 69 6e 32 6b 2f 20 48 54 54 50 GET /win2k/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [76.5800s] nsock_write(): Write request for 177 bytes to IOD #2178 EID 69651 [88.255.216.16:80]
NSOCK INFO [76.5800s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69651 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33442 > 88.255.216.16:80 | SEND
NSOCK INFO [76.5810s] nsock_read(): Read request from IOD #2178 [88.255.216.16:80] (timeout: 10000ms) EID 69658
NSOCK INFO [76.5930s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69658 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33442 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.5940s] nsock_read(): Read request from IOD #2178 [88.255.216.16:80] (timeout: 10000ms) EID 69666
NSOCK INFO [76.5940s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69666 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33442 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.5940s] nsock_iod_delete(): nsock_iod_delete (IOD #2178)
NSOCK INFO [76.5940s] nsock_iod_new2(): nsock_iod_new (IOD #2179)
NSOCK INFO [76.5950s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2179) EID 69672
NSOCK INFO [76.6070s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69672 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33452 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33452 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 69 6e 64 6f 77 2f 20 48 54 54 GET /window/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [76.6080s] nsock_write(): Write request for 178 bytes to IOD #2179 EID 69683 [88.255.216.16:80]
NSOCK INFO [76.6080s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69683 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33452 > 88.255.216.16:80 | SEND
NSOCK INFO [76.6090s] nsock_read(): Read request from IOD #2179 [88.255.216.16:80] (timeout: 10000ms) EID 69690
NSOCK INFO [76.6210s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69690 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33452 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.6210s] nsock_read(): Read request from IOD #2179 [88.255.216.16:80] (timeout: 10000ms) EID 69698
NSOCK INFO [76.6210s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69698 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33452 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.6220s] nsock_iod_delete(): nsock_iod_delete (IOD #2179)
NSOCK INFO [76.6220s] nsock_iod_new2(): nsock_iod_new (IOD #2180)
NSOCK INFO [76.6220s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2180) EID 69704
NSOCK INFO [76.6360s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69704 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33462 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33462 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 69 6e 64 6f 77 73 2f 20 48 54 GET /windows/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [76.6380s] nsock_write(): Write request for 179 bytes to IOD #2180 EID 69715 [88.255.216.16:80]
NSOCK INFO [76.6380s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69715 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33462 > 88.255.216.16:80 | SEND
NSOCK INFO [76.6390s] nsock_read(): Read request from IOD #2180 [88.255.216.16:80] (timeout: 10000ms) EID 69722
NSOCK INFO [76.6510s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69722 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33462 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.6530s] nsock_read(): Read request from IOD #2180 [88.255.216.16:80] (timeout: 10000ms) EID 69730
NSOCK INFO [76.6530s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69730 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33462 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.6530s] nsock_iod_delete(): nsock_iod_delete (IOD #2180)
NSOCK INFO [76.6530s] nsock_iod_new2(): nsock_iod_new (IOD #2181)
NSOCK INFO [76.6540s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2181) EID 69736
NSOCK INFO [76.6660s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69736 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33468 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33468 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 69 6e 2f 20 48 54 54 50 2f 31 GET /win/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [76.6680s] nsock_write(): Write request for 175 bytes to IOD #2181 EID 69747 [88.255.216.16:80]
NSOCK INFO [76.6680s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69747 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33468 > 88.255.216.16:80 | SEND
NSOCK INFO [76.6690s] nsock_read(): Read request from IOD #2181 [88.255.216.16:80] (timeout: 10000ms) EID 69754
NSOCK INFO [76.6810s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69754 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33468 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.6810s] nsock_read(): Read request from IOD #2181 [88.255.216.16:80] (timeout: 10000ms) EID 69762
NSOCK INFO [76.6810s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69762 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33468 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.6820s] nsock_iod_delete(): nsock_iod_delete (IOD #2181)
NSOCK INFO [76.6820s] nsock_iod_new2(): nsock_iod_new (IOD #2182)
NSOCK INFO [76.6820s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2182) EID 69768
NSOCK INFO [76.6950s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69768 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33484 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33484 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 69 6e 6e 74 2f 20 48 54 54 50 GET /winnt/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [76.6970s] nsock_write(): Write request for 177 bytes to IOD #2182 EID 69779 [88.255.216.16:80]
NSOCK INFO [76.6970s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69779 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33484 > 88.255.216.16:80 | SEND
NSOCK INFO [76.6980s] nsock_read(): Read request from IOD #2182 [88.255.216.16:80] (timeout: 10000ms) EID 69786
NSOCK INFO [76.7100s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69786 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33484 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.7110s] nsock_read(): Read request from IOD #2182 [88.255.216.16:80] (timeout: 10000ms) EID 69794
NSOCK INFO [76.7110s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69794 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33484 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.7110s] nsock_iod_delete(): nsock_iod_delete (IOD #2182)
NSOCK INFO [76.7110s] nsock_iod_new2(): nsock_iod_new (IOD #2183)
NSOCK INFO [76.7110s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2183) EID 69800
NSOCK INFO [76.7240s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69800 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33486 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33486 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 6f 72 64 2f 20 48 54 54 50 2f GET /word/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [76.7250s] nsock_write(): Write request for 176 bytes to IOD #2183 EID 69811 [88.255.216.16:80]
NSOCK INFO [76.7250s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69811 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33486 > 88.255.216.16:80 | SEND
NSOCK INFO [76.7260s] nsock_read(): Read request from IOD #2183 [88.255.216.16:80] (timeout: 10000ms) EID 69818
NSOCK INFO [76.7380s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69818 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33486 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.7400s] nsock_read(): Read request from IOD #2183 [88.255.216.16:80] (timeout: 10000ms) EID 69826
NSOCK INFO [76.7400s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69826 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33486 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.7410s] nsock_iod_delete(): nsock_iod_delete (IOD #2183)
NSOCK INFO [76.7410s] nsock_iod_new2(): nsock_iod_new (IOD #2184)
NSOCK INFO [76.7420s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2184) EID 69832
NSOCK INFO [76.7550s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69832 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33498 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33498 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 6f 72 6b 2f 20 48 54 54 50 2f GET /work/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [76.7570s] nsock_write(): Write request for 176 bytes to IOD #2184 EID 69843 [88.255.216.16:80]
NSOCK INFO [76.7570s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69843 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33498 > 88.255.216.16:80 | SEND
NSOCK INFO [76.7580s] nsock_read(): Read request from IOD #2184 [88.255.216.16:80] (timeout: 10000ms) EID 69850
NSOCK INFO [76.7700s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69850 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33498 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.7700s] nsock_read(): Read request from IOD #2184 [88.255.216.16:80] (timeout: 10000ms) EID 69858
NSOCK INFO [76.7700s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69858 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33498 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.7710s] nsock_iod_delete(): nsock_iod_delete (IOD #2184)
NSOCK INFO [76.7710s] nsock_iod_new2(): nsock_iod_new (IOD #2185)
NSOCK INFO [76.7710s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2185) EID 69864
NSOCK INFO [76.7850s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69864 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33502 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33502 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 6f 72 6c 64 2f 20 48 54 54 50 GET /world/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [76.7860s] nsock_write(): Write request for 177 bytes to IOD #2185 EID 69875 [88.255.216.16:80]
NSOCK INFO [76.7860s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69875 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33502 > 88.255.216.16:80 | SEND
NSOCK INFO [76.7870s] nsock_read(): Read request from IOD #2185 [88.255.216.16:80] (timeout: 10000ms) EID 69882
NSOCK INFO [76.8000s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69882 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33502 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.8010s] nsock_read(): Read request from IOD #2185 [88.255.216.16:80] (timeout: 10000ms) EID 69890
NSOCK INFO [76.8010s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69890 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33502 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.8010s] nsock_iod_delete(): nsock_iod_delete (IOD #2185)
NSOCK INFO [76.8010s] nsock_iod_new2(): nsock_iod_new (IOD #2186)
NSOCK INFO [76.8020s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2186) EID 69896
NSOCK INFO [76.8150s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69896 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33514 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33514 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 73 64 6f 63 73 2f 20 48 54 54 GET /wsdocs/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [76.8160s] nsock_write(): Write request for 178 bytes to IOD #2186 EID 69907 [88.255.216.16:80]
NSOCK INFO [76.8160s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69907 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33514 > 88.255.216.16:80 | SEND
NSOCK INFO [76.8170s] nsock_read(): Read request from IOD #2186 [88.255.216.16:80] (timeout: 10000ms) EID 69914
NSOCK INFO [76.8290s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69914 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33514 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.8300s] nsock_read(): Read request from IOD #2186 [88.255.216.16:80] (timeout: 10000ms) EID 69922
NSOCK INFO [76.8300s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69922 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33514 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.8300s] nsock_iod_delete(): nsock_iod_delete (IOD #2186)
NSOCK INFO [76.8300s] nsock_iod_new2(): nsock_iod_new (IOD #2187)
NSOCK INFO [76.8310s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2187) EID 69928
NSOCK INFO [76.8450s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69928 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33522 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33522 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 57 53 5f 46 54 50 2f 20 48 54 54 GET /WS_FTP/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [76.8460s] nsock_write(): Write request for 178 bytes to IOD #2187 EID 69939 [88.255.216.16:80]
NSOCK INFO [76.8460s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69939 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33522 > 88.255.216.16:80 | SEND
NSOCK INFO [76.8470s] nsock_read(): Read request from IOD #2187 [88.255.216.16:80] (timeout: 10000ms) EID 69946
NSOCK INFO [76.8600s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69946 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33522 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.8600s] nsock_read(): Read request from IOD #2187 [88.255.216.16:80] (timeout: 10000ms) EID 69954
NSOCK INFO [76.8600s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69954 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33522 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.8610s] nsock_iod_delete(): nsock_iod_delete (IOD #2187)
NSOCK INFO [76.8610s] nsock_iod_new2(): nsock_iod_new (IOD #2188)
NSOCK INFO [76.8610s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2188) EID 69960
NSOCK INFO [76.8750s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69960 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33528 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33528 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 73 74 61 74 73 2f 20 48 54 54 GET /wstats/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [76.8760s] nsock_write(): Write request for 178 bytes to IOD #2188 EID 69971 [88.255.216.16:80]
NSOCK INFO [76.8760s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 69971 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33528 > 88.255.216.16:80 | SEND
NSOCK INFO [76.8760s] nsock_read(): Read request from IOD #2188 [88.255.216.16:80] (timeout: 10000ms) EID 69978
NSOCK INFO [76.8880s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 69978 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33528 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.8900s] nsock_read(): Read request from IOD #2188 [88.255.216.16:80] (timeout: 10000ms) EID 69986
NSOCK INFO [76.8900s] nsock_trace_handler_callback(): Callback: READ EOF for EID 69986 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33528 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.8900s] nsock_iod_delete(): nsock_iod_delete (IOD #2188)
NSOCK INFO [76.8900s] nsock_iod_new2(): nsock_iod_new (IOD #2189)
NSOCK INFO [76.8910s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2189) EID 69992
NSOCK INFO [76.9040s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 69992 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33536 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33536 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 75 73 61 67 65 2f 20 48 54 54 GET /wusage/ HTT
00000010: 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e P/1.1  Host: 88.
00000020: 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 255.216.16.stati
00000030: 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a c.ttnet.com.tr  
00000040: 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 User-Agent: Mozi
00000050: 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 lla/5.0 (compati
00000060: 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 ble; Nmap Script
00000070: 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 ing Engine; http
00000080: 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f s://nmap.org/boo
00000090: 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e k/nse.html)  Con
000000a0: 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a nection: close  
000000b0: 0d 0a                                             

NSOCK INFO [76.9060s] nsock_write(): Write request for 178 bytes to IOD #2189 EID 70003 [88.255.216.16:80]
NSOCK INFO [76.9060s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70003 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33536 > 88.255.216.16:80 | SEND
NSOCK INFO [76.9070s] nsock_read(): Read request from IOD #2189 [88.255.216.16:80] (timeout: 10000ms) EID 70010
NSOCK INFO [76.9200s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70010 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33536 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.9200s] nsock_read(): Read request from IOD #2189 [88.255.216.16:80] (timeout: 10000ms) EID 70018
NSOCK INFO [76.9200s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70018 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33536 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.9210s] nsock_iod_delete(): nsock_iod_delete (IOD #2189)
NSOCK INFO [76.9210s] nsock_iod_new2(): nsock_iod_new (IOD #2190)
NSOCK INFO [76.9210s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2190) EID 70024
NSOCK INFO [76.9350s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70024 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33552 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33552 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 30 2f 20 48 54 54 50 2f GET /www0/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [76.9360s] nsock_write(): Write request for 176 bytes to IOD #2190 EID 70035 [88.255.216.16:80]
NSOCK INFO [76.9360s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70035 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33552 > 88.255.216.16:80 | SEND
NSOCK INFO [76.9370s] nsock_read(): Read request from IOD #2190 [88.255.216.16:80] (timeout: 10000ms) EID 70042
NSOCK INFO [76.9490s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70042 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33552 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.9510s] nsock_read(): Read request from IOD #2190 [88.255.216.16:80] (timeout: 10000ms) EID 70050
NSOCK INFO [76.9510s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70050 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33552 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.9520s] nsock_iod_delete(): nsock_iod_delete (IOD #2190)
NSOCK INFO [76.9520s] nsock_iod_new2(): nsock_iod_new (IOD #2191)
NSOCK INFO [76.9520s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2191) EID 70056
NSOCK INFO [76.9650s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70056 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33566 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33566 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 32 2f 20 48 54 54 50 2f GET /www2/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [76.9660s] nsock_write(): Write request for 176 bytes to IOD #2191 EID 70067 [88.255.216.16:80]
NSOCK INFO [76.9660s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70067 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33566 > 88.255.216.16:80 | SEND
NSOCK INFO [76.9670s] nsock_read(): Read request from IOD #2191 [88.255.216.16:80] (timeout: 10000ms) EID 70074
NSOCK INFO [76.9790s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70074 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33566 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [76.9800s] nsock_read(): Read request from IOD #2191 [88.255.216.16:80] (timeout: 10000ms) EID 70082
NSOCK INFO [76.9800s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70082 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33566 > 88.255.216.16:80 | CLOSE
NSOCK INFO [76.9810s] nsock_iod_delete(): nsock_iod_delete (IOD #2191)
NSOCK INFO [76.9810s] nsock_iod_new2(): nsock_iod_new (IOD #2192)
NSOCK INFO [76.9820s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2192) EID 70088
NSOCK INFO [76.9950s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70088 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33572 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33572 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 33 2f 20 48 54 54 50 2f GET /www3/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [76.9950s] nsock_write(): Write request for 176 bytes to IOD #2192 EID 70099 [88.255.216.16:80]
NSOCK INFO [76.9950s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70099 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33572 > 88.255.216.16:80 | SEND
NSOCK INFO [76.9970s] nsock_read(): Read request from IOD #2192 [88.255.216.16:80] (timeout: 10000ms) EID 70106
NSOCK INFO [77.0080s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70106 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33572 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.0090s] nsock_read(): Read request from IOD #2192 [88.255.216.16:80] (timeout: 10000ms) EID 70114
NSOCK INFO [77.0090s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70114 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33572 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.0090s] nsock_iod_delete(): nsock_iod_delete (IOD #2192)
NSOCK INFO [77.0090s] nsock_iod_new2(): nsock_iod_new (IOD #2193)
NSOCK INFO [77.0100s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2193) EID 70120
NSOCK INFO [77.0230s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70120 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33584 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33584 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 34 2f 20 48 54 54 50 2f GET /www4/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [77.0240s] nsock_write(): Write request for 176 bytes to IOD #2193 EID 70131 [88.255.216.16:80]
NSOCK INFO [77.0240s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70131 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33584 > 88.255.216.16:80 | SEND
NSOCK INFO [77.0250s] nsock_read(): Read request from IOD #2193 [88.255.216.16:80] (timeout: 10000ms) EID 70138
NSOCK INFO [77.0380s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70138 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33584 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.0380s] nsock_read(): Read request from IOD #2193 [88.255.216.16:80] (timeout: 10000ms) EID 70146
NSOCK INFO [77.0380s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70146 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33584 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.0390s] nsock_iod_delete(): nsock_iod_delete (IOD #2193)
NSOCK INFO [77.0390s] nsock_iod_new2(): nsock_iod_new (IOD #2194)
NSOCK INFO [77.0390s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2194) EID 70152
NSOCK INFO [77.0520s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70152 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33590 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33590 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 2f 20 48 54 54 50 2f 31 GET /www/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [77.0530s] nsock_write(): Write request for 175 bytes to IOD #2194 EID 70163 [88.255.216.16:80]
NSOCK INFO [77.0530s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70163 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33590 > 88.255.216.16:80 | SEND
NSOCK INFO [77.0540s] nsock_read(): Read request from IOD #2194 [88.255.216.16:80] (timeout: 10000ms) EID 70170
NSOCK INFO [77.0670s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70170 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33590 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.0670s] nsock_read(): Read request from IOD #2194 [88.255.216.16:80] (timeout: 10000ms) EID 70178
NSOCK INFO [77.0670s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70178 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33590 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.0680s] nsock_iod_delete(): nsock_iod_delete (IOD #2194)
NSOCK INFO [77.0680s] nsock_iod_new2(): nsock_iod_new (IOD #2195)
NSOCK INFO [77.0680s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2195) EID 70184
NSOCK INFO [77.0810s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70184 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33600 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33600 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 6a 6f 69 6e 2f 20 48 54 GET /wwwjoin/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [77.0830s] nsock_write(): Write request for 179 bytes to IOD #2195 EID 70195 [88.255.216.16:80]
NSOCK INFO [77.0830s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70195 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33600 > 88.255.216.16:80 | SEND
NSOCK INFO [77.0840s] nsock_read(): Read request from IOD #2195 [88.255.216.16:80] (timeout: 10000ms) EID 70202
NSOCK INFO [77.0960s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70202 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33600 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.0960s] nsock_read(): Read request from IOD #2195 [88.255.216.16:80] (timeout: 10000ms) EID 70210
NSOCK INFO [77.0960s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70210 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33600 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.0970s] nsock_iod_delete(): nsock_iod_delete (IOD #2195)
NSOCK INFO [77.0970s] nsock_iod_new2(): nsock_iod_new (IOD #2196)
NSOCK INFO [77.0970s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2196) EID 70216
NSOCK INFO [77.1110s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70216 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33606 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33606 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 72 6f 6f 6f 74 2f 20 48 GET /wwwrooot/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [77.1110s] nsock_write(): Write request for 180 bytes to IOD #2196 EID 70227 [88.255.216.16:80]
NSOCK INFO [77.1110s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70227 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33606 > 88.255.216.16:80 | SEND
NSOCK INFO [77.1130s] nsock_read(): Read request from IOD #2196 [88.255.216.16:80] (timeout: 10000ms) EID 70234
NSOCK INFO [77.1250s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70234 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33606 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.1260s] nsock_read(): Read request from IOD #2196 [88.255.216.16:80] (timeout: 10000ms) EID 70242
NSOCK INFO [77.1260s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70242 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33606 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.1270s] nsock_iod_delete(): nsock_iod_delete (IOD #2196)
NSOCK INFO [77.1270s] nsock_iod_new2(): nsock_iod_new (IOD #2197)
NSOCK INFO [77.1280s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2197) EID 70248
NSOCK INFO [77.1420s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70248 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33620 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33620 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 2d 73 71 6c 2f 20 48 54 GET /www-sql/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [77.1440s] nsock_write(): Write request for 179 bytes to IOD #2197 EID 70259 [88.255.216.16:80]
NSOCK INFO [77.1440s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70259 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33620 > 88.255.216.16:80 | SEND
NSOCK INFO [77.1450s] nsock_read(): Read request from IOD #2197 [88.255.216.16:80] (timeout: 10000ms) EID 70266
NSOCK INFO [77.1570s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70266 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33620 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.1580s] nsock_read(): Read request from IOD #2197 [88.255.216.16:80] (timeout: 10000ms) EID 70274
NSOCK INFO [77.1580s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70274 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33620 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.1580s] nsock_iod_delete(): nsock_iod_delete (IOD #2197)
NSOCK INFO [77.1580s] nsock_iod_new2(): nsock_iod_new (IOD #2198)
NSOCK INFO [77.1590s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2198) EID 70280
NSOCK INFO [77.1720s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70280 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33628 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33628 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 73 74 61 74 2f 20 48 54 GET /wwwstat/ HT
00000010: 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 TP/1.1  Host: 88
00000020: 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 .255.216.16.stat
00000030: 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d ic.ttnet.com.tr 
00000040: 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a  User-Agent: Moz
00000050: 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 illa/5.0 (compat
00000060: 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 ible; Nmap Scrip
00000070: 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 ting Engine; htt
00000080: 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f ps://nmap.org/bo
00000090: 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f ok/nse.html)  Co
000000a0: 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d nnection: close 
000000b0: 0a 0d 0a                                           

NSOCK INFO [77.1730s] nsock_write(): Write request for 179 bytes to IOD #2198 EID 70291 [88.255.216.16:80]
NSOCK INFO [77.1730s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70291 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33628 > 88.255.216.16:80 | SEND
NSOCK INFO [77.1730s] nsock_read(): Read request from IOD #2198 [88.255.216.16:80] (timeout: 10000ms) EID 70298
NSOCK INFO [77.1860s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70298 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33628 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.1870s] nsock_read(): Read request from IOD #2198 [88.255.216.16:80] (timeout: 10000ms) EID 70306
NSOCK INFO [77.1870s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70306 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33628 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.1880s] nsock_iod_delete(): nsock_iod_delete (IOD #2198)
NSOCK INFO [77.1880s] nsock_iod_new2(): nsock_iod_new (IOD #2199)
NSOCK INFO [77.1880s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2199) EID 70312
NSOCK INFO [77.2020s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70312 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33638 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33638 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 77 77 77 73 74 61 74 73 2f 20 48 GET /wwwstats/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [77.2030s] nsock_write(): Write request for 180 bytes to IOD #2199 EID 70323 [88.255.216.16:80]
NSOCK INFO [77.2030s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70323 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33638 > 88.255.216.16:80 | SEND
NSOCK INFO [77.2050s] nsock_read(): Read request from IOD #2199 [88.255.216.16:80] (timeout: 10000ms) EID 70330
NSOCK INFO [77.2160s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70330 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33638 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.2180s] nsock_read(): Read request from IOD #2199 [88.255.216.16:80] (timeout: 10000ms) EID 70338
NSOCK INFO [77.2180s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70338 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33638 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.2180s] nsock_iod_delete(): nsock_iod_delete (IOD #2199)
NSOCK INFO [77.2180s] nsock_iod_new2(): nsock_iod_new (IOD #2200)
NSOCK INFO [77.2190s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2200) EID 70344
NSOCK INFO [77.2320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70344 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33648 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33648 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 78 47 42 2f 20 48 54 54 50 2f 31 GET /xGB/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [77.2330s] nsock_write(): Write request for 175 bytes to IOD #2200 EID 70355 [88.255.216.16:80]
NSOCK INFO [77.2330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70355 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33648 > 88.255.216.16:80 | SEND
NSOCK INFO [77.2340s] nsock_read(): Read request from IOD #2200 [88.255.216.16:80] (timeout: 10000ms) EID 70362
NSOCK INFO [77.2460s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70362 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33648 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.2480s] nsock_read(): Read request from IOD #2200 [88.255.216.16:80] (timeout: 10000ms) EID 70370
NSOCK INFO [77.2480s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70370 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33648 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.2480s] nsock_iod_delete(): nsock_iod_delete (IOD #2200)
NSOCK INFO [77.2480s] nsock_iod_new2(): nsock_iod_new (IOD #2201)
NSOCK INFO [77.2490s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2201) EID 70376
NSOCK INFO [77.2620s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70376 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33656 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33656 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 78 6d 6c 2f 20 48 54 54 50 2f 31 GET /xml/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [77.2620s] nsock_write(): Write request for 175 bytes to IOD #2201 EID 70387 [88.255.216.16:80]
NSOCK INFO [77.2620s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70387 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33656 > 88.255.216.16:80 | SEND
NSOCK INFO [77.2630s] nsock_read(): Read request from IOD #2201 [88.255.216.16:80] (timeout: 10000ms) EID 70394
NSOCK INFO [77.2760s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70394 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33656 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.2770s] nsock_read(): Read request from IOD #2201 [88.255.216.16:80] (timeout: 10000ms) EID 70402
NSOCK INFO [77.2770s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70402 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33656 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.2780s] nsock_iod_delete(): nsock_iod_delete (IOD #2201)
NSOCK INFO [77.2780s] nsock_iod_new2(): nsock_iod_new (IOD #2202)
NSOCK INFO [77.2790s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2202) EID 70408
NSOCK INFO [77.2930s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70408 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33658 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33658 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 58 53 4c 2f 20 48 54 54 50 2f 31 GET /XSL/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [77.2940s] nsock_write(): Write request for 175 bytes to IOD #2202 EID 70419 [88.255.216.16:80]
NSOCK INFO [77.2940s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70419 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33658 > 88.255.216.16:80 | SEND
NSOCK INFO [77.2940s] nsock_read(): Read request from IOD #2202 [88.255.216.16:80] (timeout: 10000ms) EID 70426
NSOCK INFO [77.3070s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70426 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33658 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.3080s] nsock_read(): Read request from IOD #2202 [88.255.216.16:80] (timeout: 10000ms) EID 70434
NSOCK INFO [77.3080s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70434 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33658 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.3080s] nsock_iod_delete(): nsock_iod_delete (IOD #2202)
NSOCK INFO [77.3080s] nsock_iod_new2(): nsock_iod_new (IOD #2203)
NSOCK INFO [77.3090s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2203) EID 70440
NSOCK INFO [77.3220s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70440 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33662 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33662 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 78 74 65 6d 70 2f 20 48 54 54 50 GET /xtemp/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [77.3230s] nsock_write(): Write request for 177 bytes to IOD #2203 EID 70451 [88.255.216.16:80]
NSOCK INFO [77.3230s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70451 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33662 > 88.255.216.16:80 | SEND
NSOCK INFO [77.3240s] nsock_read(): Read request from IOD #2203 [88.255.216.16:80] (timeout: 10000ms) EID 70458
NSOCK INFO [77.3360s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70458 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33662 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.3370s] nsock_read(): Read request from IOD #2203 [88.255.216.16:80] (timeout: 10000ms) EID 70466
NSOCK INFO [77.3370s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70466 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33662 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.3370s] nsock_iod_delete(): nsock_iod_delete (IOD #2203)
NSOCK INFO [77.3370s] nsock_iod_new2(): nsock_iod_new (IOD #2204)
NSOCK INFO [77.3380s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2204) EID 70472
NSOCK INFO [77.3510s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70472 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33674 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33674 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 78 79 6d 6f 6e 2f 20 48 54 54 50 GET /xymon/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [77.3520s] nsock_write(): Write request for 177 bytes to IOD #2204 EID 70483 [88.255.216.16:80]
NSOCK INFO [77.3520s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70483 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33674 > 88.255.216.16:80 | SEND
NSOCK INFO [77.3530s] nsock_read(): Read request from IOD #2204 [88.255.216.16:80] (timeout: 10000ms) EID 70490
NSOCK INFO [77.3660s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70490 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33674 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.3670s] nsock_read(): Read request from IOD #2204 [88.255.216.16:80] (timeout: 10000ms) EID 70498
NSOCK INFO [77.3670s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70498 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33674 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.3670s] nsock_iod_delete(): nsock_iod_delete (IOD #2204)
NSOCK INFO [77.3670s] nsock_iod_new2(): nsock_iod_new (IOD #2205)
NSOCK INFO [77.3680s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2205) EID 70504
NSOCK INFO [77.3810s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70504 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33678 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33678 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 7a 62 34 31 2f 20 48 54 54 50 2f GET /zb41/ HTTP/
00000010: 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 1.1  Host: 88.25
00000020: 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 5.216.16.static.
00000030: 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 ttnet.com.tr  Us
00000040: 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c er-Agent: Mozill
00000050: 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c a/5.0 (compatibl
00000060: 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e e; Nmap Scriptin
00000070: 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a g Engine; https:
00000080: 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f //nmap.org/book/
00000090: 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 nse.html)  Conne
000000a0: 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a ction: close    

NSOCK INFO [77.3840s] nsock_write(): Write request for 176 bytes to IOD #2205 EID 70515 [88.255.216.16:80]
NSOCK INFO [77.3840s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70515 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33678 > 88.255.216.16:80 | SEND
NSOCK INFO [77.3850s] nsock_read(): Read request from IOD #2205 [88.255.216.16:80] (timeout: 10000ms) EID 70522
NSOCK INFO [77.3970s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70522 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33678 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.3970s] nsock_read(): Read request from IOD #2205 [88.255.216.16:80] (timeout: 10000ms) EID 70530
NSOCK INFO [77.3970s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70530 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33678 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.3980s] nsock_iod_delete(): nsock_iod_delete (IOD #2205)
NSOCK INFO [77.3980s] nsock_iod_new2(): nsock_iod_new (IOD #2206)
NSOCK INFO [77.3980s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2206) EID 70536
NSOCK INFO [77.4110s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70536 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33688 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33688 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 7a 69 70 66 69 6c 65 73 2f 20 48 GET /zipfiles/ H
00000010: 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 TTP/1.1  Host: 8
00000020: 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 8.255.216.16.sta
00000030: 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 tic.ttnet.com.tr
00000040: 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f   User-Agent: Mo
00000050: 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 zilla/5.0 (compa
00000060: 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 tible; Nmap Scri
00000070: 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 pting Engine; ht
00000080: 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 tps://nmap.org/b
00000090: 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 ook/nse.html)  C
000000a0: 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 onnection: close
000000b0: 0d 0a 0d 0a                                         

NSOCK INFO [77.4130s] nsock_write(): Write request for 180 bytes to IOD #2206 EID 70547 [88.255.216.16:80]
NSOCK INFO [77.4130s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70547 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33688 > 88.255.216.16:80 | SEND
NSOCK INFO [77.4140s] nsock_read(): Read request from IOD #2206 [88.255.216.16:80] (timeout: 10000ms) EID 70554
NSOCK INFO [77.4260s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70554 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33688 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.4270s] nsock_read(): Read request from IOD #2206 [88.255.216.16:80] (timeout: 10000ms) EID 70562
NSOCK INFO [77.4270s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70562 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33688 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.4270s] nsock_iod_delete(): nsock_iod_delete (IOD #2206)
NSOCK INFO [77.4270s] nsock_iod_new2(): nsock_iod_new (IOD #2207)
NSOCK INFO [77.4270s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2207) EID 70568
NSOCK INFO [77.4400s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70568 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33696 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33696 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 7a 69 70 2f 20 48 54 54 50 2f 31 GET /zip/ HTTP/1
00000010: 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 35 35 .1  Host: 88.255
00000020: 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 2e 74 .216.16.static.t
00000030: 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 73 65 tnet.com.tr  Use
00000040: 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c 6c 61 r-Agent: Mozilla
00000050: 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 6c 65 /5.0 (compatible
00000060: 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 6e 67 ; Nmap Scripting
00000070: 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 3a 2f  Engine; https:/
00000080: 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b 2f 6e /nmap.org/book/n
00000090: 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e 65 63 se.html)  Connec
000000a0: 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d 0a    tion: close    

NSOCK INFO [77.4410s] nsock_write(): Write request for 175 bytes to IOD #2207 EID 70579 [88.255.216.16:80]
NSOCK INFO [77.4410s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70579 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33696 > 88.255.216.16:80 | SEND
NSOCK INFO [77.4430s] nsock_read(): Read request from IOD #2207 [88.255.216.16:80] (timeout: 10000ms) EID 70586
NSOCK INFO [77.4540s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70586 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33696 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.4550s] nsock_read(): Read request from IOD #2207 [88.255.216.16:80] (timeout: 10000ms) EID 70594
NSOCK INFO [77.4550s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70594 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33696 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.4550s] nsock_iod_delete(): nsock_iod_delete (IOD #2207)
NSOCK INFO [77.4550s] nsock_iod_new2(): nsock_iod_new (IOD #2208)
NSOCK INFO [77.4560s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2208) EID 70600
NSOCK INFO [77.4690s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70600 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33710 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33710 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 5f 64 6f 63 73 2f 20 48 54 54 50 GET /_docs/ HTTP
00000010: 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 38 38 2e 32 /1.1  Host: 88.2
00000020: 35 35 2e 32 31 36 2e 31 36 2e 73 74 61 74 69 63 55.216.16.static
00000030: 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 72 0d 0a 55 .ttnet.com.tr  U
00000040: 73 65 72 2d 41 67 65 6e 74 3a 20 4d 6f 7a 69 6c ser-Agent: Mozil
00000050: 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 61 74 69 62 la/5.0 (compatib
00000060: 6c 65 3b 20 4e 6d 61 70 20 53 63 72 69 70 74 69 le; Nmap Scripti
00000070: 6e 67 20 45 6e 67 69 6e 65 3b 20 68 74 74 70 73 ng Engine; https
00000080: 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f 62 6f 6f 6b ://nmap.org/book
00000090: 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a 43 6f 6e 6e /nse.html)  Conn
000000a0: 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 65 0d 0a 0d ection: close   
000000b0: 0a                                               

NSOCK INFO [77.4710s] nsock_write(): Write request for 177 bytes to IOD #2208 EID 70611 [88.255.216.16:80]
NSOCK INFO [77.4710s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70611 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33710 > 88.255.216.16:80 | SEND
NSOCK INFO [77.4720s] nsock_read(): Read request from IOD #2208 [88.255.216.16:80] (timeout: 10000ms) EID 70618
NSOCK INFO [77.4850s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70618 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33710 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.4860s] nsock_read(): Read request from IOD #2208 [88.255.216.16:80] (timeout: 10000ms) EID 70626
NSOCK INFO [77.4860s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70626 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33710 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.4860s] nsock_iod_delete(): nsock_iod_delete (IOD #2208)
NSOCK INFO [77.4860s] nsock_iod_new2(): nsock_iod_new (IOD #2209)
NSOCK INFO [77.4870s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2209) EID 70632
NSOCK INFO [77.5000s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70632 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33712 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33712 > 88.255.216.16:80 | GET /sitecore/shell/sitecore.version.xml HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.5010s] nsock_write(): Write request for 206 bytes to IOD #2209 EID 70643 [88.255.216.16:80]
NSOCK INFO [77.5010s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70643 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33712 > 88.255.216.16:80 | SEND
NSOCK INFO [77.5020s] nsock_read(): Read request from IOD #2209 [88.255.216.16:80] (timeout: 10000ms) EID 70650
NSOCK INFO [77.5150s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70650 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33712 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.5150s] nsock_read(): Read request from IOD #2209 [88.255.216.16:80] (timeout: 10000ms) EID 70658
NSOCK INFO [77.5150s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70658 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33712 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.5160s] nsock_iod_delete(): nsock_iod_delete (IOD #2209)
NSOCK INFO [77.5160s] nsock_iod_new2(): nsock_iod_new (IOD #2210)
NSOCK INFO [77.5160s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2210) EID 70664
NSOCK INFO [77.5290s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70664 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33718 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33718 > 88.255.216.16:80 | 00000000: 47 45 54 20 2f 73 69 74 65 63 6f 72 65 2f 6c 6f GET /sitecore/lo
00000010: 67 69 6e 2f 64 65 66 61 75 6c 74 2e 61 73 70 78 gin/default.aspx
00000020: 20 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a  HTTP/1.1  Host:
00000030: 20 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73  88.255.216.16.s
00000040: 74 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e tatic.ttnet.com.
00000050: 74 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 tr  User-Agent: 
00000060: 4d 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d Mozilla/5.0 (com
00000070: 70 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 patible; Nmap Sc
00000080: 72 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 ripting Engine; 
00000090: 68 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 https://nmap.org
000000a0: 2f 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d /book/nse.html) 
000000b0: 0a 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f  Connection: clo
000000c0: 73 65 0d 0a 0d 0a                               se    

NSOCK INFO [77.5290s] nsock_write(): Write request for 198 bytes to IOD #2210 EID 70675 [88.255.216.16:80]
NSOCK INFO [77.5290s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70675 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33718 > 88.255.216.16:80 | SEND
NSOCK INFO [77.5310s] nsock_read(): Read request from IOD #2210 [88.255.216.16:80] (timeout: 10000ms) EID 70682
NSOCK INFO [77.5420s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70682 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33718 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.5430s] nsock_read(): Read request from IOD #2210 [88.255.216.16:80] (timeout: 10000ms) EID 70690
NSOCK INFO [77.5430s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70690 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33718 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.5430s] nsock_iod_delete(): nsock_iod_delete (IOD #2210)
NSOCK INFO [77.5430s] nsock_iod_new2(): nsock_iod_new (IOD #2211)
NSOCK INFO [77.5440s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2211) EID 70696
NSOCK INFO [77.5570s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70696 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33724 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33724 > 88.255.216.16:80 | 00000000: 48 45 41 44 20 2f 73 69 74 65 63 6f 72 65 2f 61 HEAD /sitecore/a
00000010: 64 6d 69 6e 2f 73 74 61 74 73 2e 61 73 70 78 20 dmin/stats.aspx 
00000020: 48 54 54 50 2f 31 2e 31 0d 0a 48 6f 73 74 3a 20 HTTP/1.1  Host: 
00000030: 38 38 2e 32 35 35 2e 32 31 36 2e 31 36 2e 73 74 88.255.216.16.st
00000040: 61 74 69 63 2e 74 74 6e 65 74 2e 63 6f 6d 2e 74 atic.ttnet.com.t
00000050: 72 0d 0a 55 73 65 72 2d 41 67 65 6e 74 3a 20 4d r  User-Agent: M
00000060: 6f 7a 69 6c 6c 61 2f 35 2e 30 20 28 63 6f 6d 70 ozilla/5.0 (comp
00000070: 61 74 69 62 6c 65 3b 20 4e 6d 61 70 20 53 63 72 atible; Nmap Scr
00000080: 69 70 74 69 6e 67 20 45 6e 67 69 6e 65 3b 20 68 ipting Engine; h
00000090: 74 74 70 73 3a 2f 2f 6e 6d 61 70 2e 6f 72 67 2f ttps://nmap.org/
000000a0: 62 6f 6f 6b 2f 6e 73 65 2e 68 74 6d 6c 29 0d 0a book/nse.html)  
000000b0: 43 6f 6e 6e 65 63 74 69 6f 6e 3a 20 63 6c 6f 73 Connection: clos
000000c0: 65 0d 0a 0d 0a                                  e    

NSOCK INFO [77.5580s] nsock_write(): Write request for 197 bytes to IOD #2211 EID 70707 [88.255.216.16:80]
NSOCK INFO [77.5580s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70707 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33724 > 88.255.216.16:80 | SEND
NSOCK INFO [77.5590s] nsock_read(): Read request from IOD #2211 [88.255.216.16:80] (timeout: 10000ms) EID 70714
NSOCK INFO [77.5730s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70714 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33724 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.5730s] nsock_read(): Read request from IOD #2211 [88.255.216.16:80] (timeout: 10000ms) EID 70722
NSOCK INFO [77.5730s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70722 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33724 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.5730s] nsock_iod_delete(): nsock_iod_delete (IOD #2211)
NSOCK INFO [77.5730s] nsock_iod_new2(): nsock_iod_new (IOD #2212)
NSOCK INFO [77.5740s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2212) EID 70728
NSOCK INFO [77.5870s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70728 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33734 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33734 > 88.255.216.16:80 | HEAD /sitecore/admin/unlock_admin.aspx HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.5870s] nsock_write(): Write request for 204 bytes to IOD #2212 EID 70739 [88.255.216.16:80]
NSOCK INFO [77.5870s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70739 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33734 > 88.255.216.16:80 | SEND
NSOCK INFO [77.5890s] nsock_read(): Read request from IOD #2212 [88.255.216.16:80] (timeout: 10000ms) EID 70746
NSOCK INFO [77.6000s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70746 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33734 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.6010s] nsock_read(): Read request from IOD #2212 [88.255.216.16:80] (timeout: 10000ms) EID 70754
NSOCK INFO [77.6010s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70754 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33734 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.6010s] nsock_iod_delete(): nsock_iod_delete (IOD #2212)
NSOCK INFO [77.6010s] nsock_iod_new2(): nsock_iod_new (IOD #2213)
NSOCK INFO [77.6020s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2213) EID 70760
NSOCK INFO [77.6150s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70760 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33738 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33738 > 88.255.216.16:80 | HEAD /sitecore/shell/Applications/shell.xml HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.6160s] nsock_write(): Write request for 209 bytes to IOD #2213 EID 70771 [88.255.216.16:80]
NSOCK INFO [77.6160s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70771 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33738 > 88.255.216.16:80 | SEND
NSOCK INFO [77.6170s] nsock_read(): Read request from IOD #2213 [88.255.216.16:80] (timeout: 10000ms) EID 70778
NSOCK INFO [77.6290s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70778 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33738 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.6300s] nsock_read(): Read request from IOD #2213 [88.255.216.16:80] (timeout: 10000ms) EID 70786
NSOCK INFO [77.6300s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70786 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33738 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.6300s] nsock_iod_delete(): nsock_iod_delete (IOD #2213)
NSOCK INFO [77.6300s] nsock_iod_new2(): nsock_iod_new (IOD #2214)
NSOCK INFO [77.6310s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2214) EID 70792
NSOCK INFO [77.6440s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70792 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33752 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33752 > 88.255.216.16:80 | HEAD /sitecore/admin/ShowConfig.aspx HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.6450s] nsock_write(): Write request for 202 bytes to IOD #2214 EID 70803 [88.255.216.16:80]
NSOCK INFO [77.6450s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70803 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33752 > 88.255.216.16:80 | SEND
NSOCK INFO [77.6460s] nsock_read(): Read request from IOD #2214 [88.255.216.16:80] (timeout: 10000ms) EID 70810
NSOCK INFO [77.6580s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70810 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33752 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.6590s] nsock_read(): Read request from IOD #2214 [88.255.216.16:80] (timeout: 10000ms) EID 70818
NSOCK INFO [77.6590s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70818 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33752 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.6590s] nsock_iod_delete(): nsock_iod_delete (IOD #2214)
NSOCK INFO [77.6590s] nsock_iod_new2(): nsock_iod_new (IOD #2215)
NSOCK INFO [77.6600s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2215) EID 70824
NSOCK INFO [77.6730s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70824 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33768 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33768 > 88.255.216.16:80 | HEAD /App_Config/Security/Domains.config.xml HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.6740s] nsock_write(): Write request for 210 bytes to IOD #2215 EID 70835 [88.255.216.16:80]
NSOCK INFO [77.6740s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70835 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33768 > 88.255.216.16:80 | SEND
NSOCK INFO [77.6750s] nsock_read(): Read request from IOD #2215 [88.255.216.16:80] (timeout: 10000ms) EID 70842
NSOCK INFO [77.6880s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70842 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33768 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.6880s] nsock_read(): Read request from IOD #2215 [88.255.216.16:80] (timeout: 10000ms) EID 70850
NSOCK INFO [77.6880s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70850 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33768 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.6890s] nsock_iod_delete(): nsock_iod_delete (IOD #2215)
NSOCK INFO [77.6890s] nsock_iod_new2(): nsock_iod_new (IOD #2216)
NSOCK INFO [77.6890s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2216) EID 70856
NSOCK INFO [77.7030s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70856 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33784 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33784 > 88.255.216.16:80 | HEAD /App_Config/Security/GlobalRoles.config.xml HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.7040s] nsock_write(): Write request for 214 bytes to IOD #2216 EID 70867 [88.255.216.16:80]
NSOCK INFO [77.7040s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70867 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33784 > 88.255.216.16:80 | SEND
NSOCK INFO [77.7060s] nsock_read(): Read request from IOD #2216 [88.255.216.16:80] (timeout: 10000ms) EID 70874
NSOCK INFO [77.7180s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70874 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33784 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.7180s] nsock_read(): Read request from IOD #2216 [88.255.216.16:80] (timeout: 10000ms) EID 70882
NSOCK INFO [77.7180s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70882 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33784 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.7190s] nsock_iod_delete(): nsock_iod_delete (IOD #2216)
NSOCK INFO [77.7190s] nsock_iod_new2(): nsock_iod_new (IOD #2217)
NSOCK INFO [77.7190s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2217) EID 70888
NSOCK INFO [77.7320s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70888 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33792 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33792 > 88.255.216.16:80 | HEAD /sitecore%20modules/staging/service/api.asmx HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.7330s] nsock_write(): Write request for 215 bytes to IOD #2217 EID 70899 [88.255.216.16:80]
NSOCK INFO [77.7330s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70899 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33792 > 88.255.216.16:80 | SEND
NSOCK INFO [77.7340s] nsock_read(): Read request from IOD #2217 [88.255.216.16:80] (timeout: 10000ms) EID 70906
NSOCK INFO [77.7460s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70906 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33792 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.7460s] nsock_read(): Read request from IOD #2217 [88.255.216.16:80] (timeout: 10000ms) EID 70914
NSOCK INFO [77.7460s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70914 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33792 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.7470s] nsock_iod_delete(): nsock_iod_delete (IOD #2217)
NSOCK INFO [77.7470s] nsock_iod_new2(): nsock_iod_new (IOD #2218)
NSOCK INFO [77.7470s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2218) EID 70920
NSOCK INFO [77.7650s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70920 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33802 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33802 > 88.255.216.16:80 | HEAD /sitecore%20modules/staging/workdir HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.7660s] nsock_write(): Write request for 206 bytes to IOD #2218 EID 70931 [88.255.216.16:80]
NSOCK INFO [77.7660s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70931 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33802 > 88.255.216.16:80 | SEND
NSOCK INFO [77.7670s] nsock_read(): Read request from IOD #2218 [88.255.216.16:80] (timeout: 10000ms) EID 70938
NSOCK INFO [77.7790s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70938 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33802 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.7800s] nsock_read(): Read request from IOD #2218 [88.255.216.16:80] (timeout: 10000ms) EID 70946
NSOCK INFO [77.7800s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70946 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33802 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.7800s] nsock_iod_delete(): nsock_iod_delete (IOD #2218)
NSOCK INFO [77.7800s] nsock_iod_new2(): nsock_iod_new (IOD #2219)
NSOCK INFO [77.7820s] nsock_connect_tcp(): TCP connection requested to 88.255.216.16:80 (IOD #2219) EID 70952
NSOCK INFO [77.7950s] nsock_trace_handler_callback(): Callback: CONNECT SUCCESS for EID 70952 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33816 > 88.255.216.16:80 | CONNECT
NSE: TCP 192.168.31.147:33816 > 88.255.216.16:80 | HEAD /sitecore/system/Settings/Security/Profiles HTTP/1.1
Host: 88.255.216.16.static.ttnet.com.tr
User-Agent: Mozilla/5.0 (compatible; Nmap Scripting Engine; https://nmap.org/book/nse.html)
Connection: close


NSOCK INFO [77.7960s] nsock_write(): Write request for 214 bytes to IOD #2219 EID 70963 [88.255.216.16:80]
NSOCK INFO [77.7960s] nsock_trace_handler_callback(): Callback: WRITE SUCCESS for EID 70963 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33816 > 88.255.216.16:80 | SEND
NSOCK INFO [77.7970s] nsock_read(): Read request from IOD #2219 [88.255.216.16:80] (timeout: 10000ms) EID 70970
NSOCK INFO [77.8090s] nsock_trace_handler_callback(): Callback: READ SUCCESS for EID 70970 [88.255.216.16:80] (73 bytes): HTTP/1.1 400 Bad Request..content-type: text/plain..connection: close....
NSE: TCP 192.168.31.147:33816 < 88.255.216.16:80 | 00000000: 48 54 54 50 2f 31 2e 31 20 34 30 30 20 42 61 64 HTTP/1.1 400 Bad
00000010: 20 52 65 71 75 65 73 74 0d 0a 63 6f 6e 74 65 6e  Request  conten
00000020: 74 2d 74 79 70 65 3a 20 74 65 78 74 2f 70 6c 61 t-type: text/pla
00000030: 69 6e 0d 0a 63 6f 6e 6e 65 63 74 69 6f 6e 3a 20 in  connection: 
00000040: 63 6c 6f 73 65 0d 0a 0d 0a                      close    

NSOCK INFO [77.8100s] nsock_read(): Read request from IOD #2219 [88.255.216.16:80] (timeout: 10000ms) EID 70978
NSOCK INFO [77.8100s] nsock_trace_handler_callback(): Callback: READ EOF for EID 70978 [88.255.216.16:80]
NSE: TCP 192.168.31.147:33816 > 88.255.216.16:80 | CLOSE
NSOCK INFO [77.8100s] nsock_iod_delete(): nsock_iod_delete (IOD #2219)
Nmap scan report for 88.255.216.16.static.ttnet.com.tr (88.255.216.16)
Host is up, received user-set (0.024s latency).

Bug in http-security-headers: no string output.
PORT   STATE SERVICE REASON
80/tcp open  http    syn-ack ttl 54
| http-headers: 
|   content-type: text/plain
|   connection: close
|   
|_  (Request type: GET)
|_http-title: Site doesn't have a title (text/plain).

Nmap done: 1 IP address (1 host up) scanned in 77.81 seconds
```

Features And Method
๐ฃ Layer7

get GET | GET Flood

post POST | POST Flood

ovh OVH | Bypass OVH

stress STRESS | Send HTTP Packet With High Byte

ostress OSTRESS | STRESS Without Proxy

dyn DYN | A New Method With Random SubDomain

slow SLOW | Slowloris Old Method of DDoS

head HEAD | https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/HEAD

hit HIT | POST Without PROXY

null NULL | Null UserAgent and ...

cookie COOKIE | Random Cookie PHP 'if (isset($_COOKIE))'

brust BRUST | A Method with more header

pps PPS | Only 'GET / HTTP/1.1\r\n\r\n'

even EVEN | GET Method with more header

googleshield GSB | Google Project Shield Bypass

DDoSGuard DGB | DDoS Guard Bypass

ArvanCloud AVB | Arvan Cloud Bypass

CloudFlare CFB | CloudFlare Bypass

bypass BYPASS | Bypass Normal AntiDDoS

_______________________________________________________________________________

๐งจ Layer4:

tcp TCP | TCP Flood Bypass

udp UDP | UDP Flood Bypass

syn SYN | SYN Flood

vse VSE | VSE Flood Only Connection

mem MEM | Memcached Flood

ntp NTP | NTP Flood OLD Method Of Layer4

๐น Layer3

icmp ICMP | Flood ICMP Request

โ๏ธ POD | Ping Of Death OLD Method Of DDoS

โ๏ธ Tools - Run With 'python3 start.py tools'


๐ CFIP | Find Real IP address of Website Powered by Cloudflare


๐ช DNS | Show Site DNS Records

โ ๏ธ PING | PING server

๐ CHECK | Check Website Die or no

๐ DSTAT | a Method show Receive And Send Bytes Size

๐ฉ Other

โ STOP | STOP All Attacks

๐  TOOLS | Tools Console

๐ HELP | Show Usge Script

Layer4 DDoS Script



git clone https://github.com/yvsv/36ddos.git

cd 36ddos 

pip3 install -r requirements.txt

Launch Script

python3 start.py

python3 start.py bypass https://*********.com 5 1000 socks5.txt 100 100

1. Transport Control Protocol (TCP)
   -   TCP Connections (Sockets)
     - bidirectional inter-process communication; Google chrome to Web server/Web server to Google chrome
   - TCP Port Numbers
     - Ports, an application-specific or process-specific software communications endpoint
2. Python
`import socket`
`mysock = socket.socket(socket.AF_INET, socket.SOXKET_STREAM)`
`mysock.connect(('data.pr4e.org, 80'))`
3. Application Protocol
   - HTTP (HyperText Transfer Protocol), example: "http://www.dr-chuck.com/page1.htm"
     - http:// -> protocol
     - www.dr-chuck.com -> host
     - /page1.htm -> document
  - HTML (HyperText Markup Language)
  - Internet Standards
    - governed by the Internet Engineering Task Force (IETF)
4. ASCII (American Standard Code for Information Interchange)
   - UTF-16 & UTF-32 are both fixed lengths (in terms of bytes)
     - UTF-8 varies btw 1~4 bytes and is upward compatible with ASCII
   - In Python 3, all strings are internally unicode
     - String (o), Data (o), Network resources using sockets (x)
       - We need to encode and decode data to UTF-8 when we are dealing with network resources in Python 3
5. Web Scraping/Crawling
   - Pull data (e.g. social data)
     - Beautiful Soup
   *you can make yourself a search engine*

![Web Vulnerability Scanner](CyberProject1.png)

# Web Application Vulnerability Scanner 

A Python + Flask based web vulnerability scanner that detects **XSS** and **SQL Injection** vulnerabilities in web applications by crawling HTML forms and analyzing responses.



##  Features

- Detects HTML forms on target URLs
- Injects test payloads for:
  - Cross-Site Scripting (XSS)
  - SQL Injection (SQLi)
- Analyzes server response for vulnerability evidence
- Browser-based UI using Flask + Bootstrap
- Logs scan results to timestamped `.txt` files



##  Tech Stack

- **Python 3**
- **Flask**
- **BeautifulSoup**
- **requests**
- **Bootstrap (CDN)**

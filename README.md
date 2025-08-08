# Automated Vulnerability Scanner

## Overview  
A tool to automate network and web vulnerability scanning using Nmap and OWASP ZAP, with a web dashboard to view results.

## Tech Stack  
- Python 3.x, Flask/FastAPI  
- Nmap, OWASP ZAP  
- PostgreSQL/SQLite  
- Celery + Redis  
- React.js (optional)  
- Docker  

## How to Run  
1. Install dependencies: `pip install -r requirements.txt`  
2. Run scanner: `python scanner/nmap_scanner.py`  
3. Start backend: `python backend/app.py`  
4. Open frontend: (if available)  

## Features  
- Run and parse Nmap scans  
- Store and query scan results  
- Schedule scans  
- View reports in dashboard  


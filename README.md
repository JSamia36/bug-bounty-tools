# bug-bounty-tools
Different tools with basic commands for bug hunting

## Subdomain Finder
**crtsh**

  python3 crtsh.py -d website.com

**subfinder**

  ./subfinder -d website.com

## Fuzzing
**ffuf**

  ffuf -u http://website.com/FUZZ -w wordlist.txt -mc 200,301 -recursion

## URL Testing
**HTTPX**

  ./httpx -l subdomain.txt -o httpx.txt

  ./httpx -l subdomain.txt -status-code -title

## Vuln Scanner
**BBOT**

  ./bbot -t https://website.com -f web-thorough -m nuclei robots secretsdb threatminer --allow-deadly


# Insecam IP Scraper
Scrapes camera IPs from Insecam.

Program extracts HTML Source code for each Insecam page and performs a regex to extract all IPs on the page in the format `IP:PORT`. Prints results to terminal and writes to filename "IP.txt" 

Just run with `python GetInsecamIP.py`

Default URL is Defeway models. Change URL on line 28 to any Insecam page (Model/ Country/ etc) and page incrementer to `{i}` 

Uses urllib and re (Regex library).

**For educational use only. I take no responsibility for any damages caused by misuse of this software.**

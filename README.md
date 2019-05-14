<h1 align="center">
    <br>
    <a href="https://github.com/jaxBCD/ReconT">
    <img src="src/utils/reconT.png" alt="ReconT" width="250" height="250">
    </a>
    <br>    
</h1>

<h4 align="center">Reconnaisance Toolkit.</h4>
<p align="center">
   <a href="https://github.com/jaxBCD/ReconT">
      <img src="https://img.shields.io/badge/👣-Recon--T-green.svg">
   </a>
   
   <a href="https://www.python.org">
      <img src="https://img.shields.io/badge/python-3.x-blue.svg">
   </a>
</p>

### About
 Recon-Tool made for reconnaissance and information gathering with an emphasis on simplicity.<br> 
 It will do everything from.</br>

### Features
 * Information Security Headers
   - Click Jacking Analyzer
   - Cors Wildcard Analyzer
   - XSS Protector Analyzer
 * WAF Analyzer
 * Information Disclosure
   - robot.txt
   - sitemap
   - mailman 
 * Banner Grabbing
   - Phone Number
   - Credit Card Number
   - Email 
   - US Social Security Number
 * Url Crawl
   - Dom Paramter Url
   - Internal Dynamic Paramter
   - External Dynamic Paramter
   - Internal Link
   - External Link
 * HTML Form Detector
 * Port Scanner
 * Get SSL Information
 * Subdomain Enumeration
 * Host Information
   - DNS Server Analysis
   - MX Records Analysis
   - TXT Records Analysis
   - Subdomain Analysis

#### Requirements
 * click
 * requests
 * colorlog
 * bs4
 * tldextract

#### Usage & Installation
 ```
 $ apt-get install python3 nmap
 $ pip3 install -r requirements.txt
 $ python3 reconT.py http://target.co.li
 
 $ python reconT.py --help
 Usage: reconT.py [OPTIONS] TARGET
 
 Options:
   --timeout INTEGER  Seconds to wait before timeout connections
   --proxy TEXT       if Use a proxy ex: 0.0.0.0:8888if with auth
                      0.0.0.0:8888@user:password
   --cookies TEXT     if use cookie comma separated cookies to add the
                      requestex: PHPSESS:123,kontol=True
   --help             Show this message and exit.
   
 ```

##### Info
 Support For Python Version: ```3.x```<br>
 ReconT Version: ```0.7```<br>
 By: ```407 Authentic Exploit ```<br>
 Codename: ```JaxBCD```<br>
 





  

  
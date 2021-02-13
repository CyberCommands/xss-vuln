# XSS Vulnerability
[![Python3.x](https://img.shields.io/badge/python-3.x-FADA5E.svg?logo=python)](https://www.python.org/) [![PEP8](https://img.shields.io/badge/code%20style-pep8-red.svg)](https://www.python.org/dev/peps/pep-0008/)

* This tool is for test Cross Site Scripting (XSS) Vulnerability and educational purposes only.

**Do not use it for illegal purposes!**

## Installation
You'll need to install the [PhantomJS](https://github.com/ariya/phantomjs).
```
git clone https://github.com/CyberCommands/xss-vuln.git
```
```
cd xss-vuln/
```
```
pip install -r requirements.txt
```
```
python3 xss.py -h
```
```
usage: xss.py [-h] [-a PATH] [-c COOKIES] [-n PHANTOM] [-o HOSTS]
              [-p PAYLOADS] [-s SCHEME] [-t THREADS] [-u URLS] [-v VERBOSE]

optional arguments:
  -h, --help            show this help message and exit
  -a PATH, --path PATH  set paths list
  -c COOKIES, --cookies COOKIES
                        cookies separated by semi-colon, e.g.:
                        cookie1=value1;cookie2=value2...
  -n PHANTOM, --phantom PHANTOM
                        phantomjs path
  -o HOSTS, --hosts HOSTS
                        set host list (required or -u)
  -p PAYLOADS, --payloads PAYLOADS
                        set payloads list
  -s SCHEME, --scheme SCHEME
                        scheme to use, default=http,https
  -t THREADS, --threads THREADS
                        threads, default 10
  -u URLS, --urls URLS  set url list (required or -o)
  -v VERBOSE, --verbose VERBOSE
                        display output, 0=nothing, 1=only vulnerable, 2=all
                        requests, 3=full debug, 4=only vulnerable,no extra
                        text like banner, default: 1
```

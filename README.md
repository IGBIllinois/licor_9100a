# Licor LI-8100A Scripts
- Various scripts to help download data and set the time on LI-8100A Devices
- https://www.licor.com/env/support/LI-8100A/home.html
- The XML Grammer Document is located in the docs folder

## Requirements
* Python 2.7 or Greater

## Scripts
* set_time.py - Sets the time 
* Specify an IP Address, port number (default 1526), UTC or Local time
```
Usage: Sets Date on Licor LI-8100A devices.

Options:
  -h, --help            show this help message and exit
  -i IPADDRESS, --ipaddress=IPADDRESS
                        IP Address
  -p PORT, --port=PORT  TCP/IP Port
  --utc                 Set Time to UTC
  --local               Set Time to Local Time
```
---

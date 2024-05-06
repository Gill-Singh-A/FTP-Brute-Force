# FTP Brute Force
A Python Program that uses **ftplib** module to brute force FTP (File Transfer Protocol) Server
## Requirements
Language Used = Python3<br />
Modules/Packages used:
* ftplib
* datetime
* optparse
* colorama
* multiprocessing
* time
<!-- -->
Install the dependencies:
```bash
pip install -r requirements.txt
```
## Arguments
* '-s', "--server" : Target FTP Server
* '-p', "--port" : Port of Target FTP Server (Default=21)
* '-u', "--users" : Target Users (seperated by ',') or File containing List of Users
* '-P', "--password" : Passwords (seperated by ',') or File containing List of Passwords
* '-c', "--credentials" : Name of File containing Credentials in format ({user}:{password})
* '-w', "--write" : CSV File to Dump Successful Logins (default=current data and time)
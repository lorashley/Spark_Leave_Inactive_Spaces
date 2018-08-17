# Cisco Webex Teams
## Leave Inactive Spaces & Named Spaces
A Python Script that will remove a user from Cisco Webex Teams spaces that have been inactive for over a defined period of time.

Requires Python3 (3.6.1 used for development) with the requests and python-dateutil modules.
 
## Install commands for the modules:

```
pip3 install requests
pip3 install python-dateutil
``` 
 
Also requires a Cisco Webex Teams authorization token obtained from the [Webex from Developers](https://developer.webex.com/) site.
 
## Get started:
```
python leaveInactiveSpaces.py -h
```



#

##1.9.2


##mgo could not enabe go path in PATH
 - mgo choud show new path ,then go version
 - however, after mgo , the PATH is still unchanged 
 - add to /root/.bashrc is also not work 

## add /etc/profile to /root/.bashrc
- add go PATH to PATH in /etc/profile
- source /etc/profile is ok ,but mgo is not ok always
- so, source /etc/profile is added to /root/.bashrc



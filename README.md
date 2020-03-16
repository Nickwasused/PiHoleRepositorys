# PiHoleRepositorys
Repository for PiHoles
These files are used to update your block/whitelists inside your PiHole. The files are located at /etc/pihole/<br>

# regex.list
The original list.

# regex-sort.list
The orginal list, but sorted together.

# Usgae
Download the file:
```https://raw.githubusercontent.com/Nickwasused/PiHoleRepositorys/master/regex-sort.list -O regex.list```
or
```wget https://raw.githubusercontent.com/Nickwasused/PiHoleRepositorys/master/regex.list```
Move the file to the Pi-hole installation:
```sudo mv regex.list /etc/pihole```
Fix regex.list permission:
```sudo chown pihole:www-data /etc/pihole/regex.list```
Restart the Pi-hole service:
```sudo service pihole-FTL restart```

# PiHoleRepositorys
Repository for PiHoles
These files are used to update your block/whitelists inside your PiHole. The files are located at /etc/pihole/<br>

# regex.list
The original list.

# regex-sort.list
The orginal list, but sorted together.

# Usgae
Download the file:<br>
```https://raw.githubusercontent.com/Nickwasused/PiHoleRepositorys/master/regex-sort.list -O regex.list```<br>
or<br>
```wget https://raw.githubusercontent.com/Nickwasused/PiHoleRepositorys/master/regex.list```<br>
Move the file to the Pi-hole installation:<br>
```sudo mv regex.list /etc/pihole```<br>
Fix regex.list permission:<br>
```sudo chown pihole:www-data /etc/pihole/regex.list```<br>
Restart the Pi-hole service:<br>
```sudo service pihole-FTL restart```<br>

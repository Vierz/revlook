# About
Reverse lookup listing tool for an ip range example 120.20.20.**(0-255)**

# Setup
- **Download:** [revlook](revlook)
- **Make the file executable:** chmod +x revlook
- **Move the file to:** /usr/sbin/

# Use
- **Command:** revlook iṕ
- **Example:** revlook 120.20.20.20
- **NOTE:** It doesn't matter if you add the last part of the ip, the script is going to delete it and only use this "120.20.20" and then execute the reverse lookup with this range "120.20.20.0-255"

```console
vierz@hostname:~$ sublist 120.20.20.20
120.20.20.20.12 >> subdomain.domain.com
120.20.20.20.129 >> domain1.com
120.20.20.20.130 >> .domain2.com
120.20.20.20.132 >> blog.domain3.com
120.20.20.20.133 >> subdomain2.domain.com
120.20.20.20.180 >> smtp.domain.com
120.20.20.20.193 >> cms.domain.com
```

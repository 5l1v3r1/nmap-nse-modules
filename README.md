# nmap-nse-modules
my collection of nmap nse modules

# Description
    this working directory contains diferent nmap nse modules
    writen by me to be of assistence in post-exploitation common tasks.

# Install
    Download module from github
    edit module to read the description
    port module to nmap nse database
    update nse database: --script-updatedb


# [file-checker.nse] help argument
![file-checker.nse](http://2.1m.yt/9LeMt0a.png)

# [file-checker.nse] --script-args read=true
![file-checker.nse](http://3.1m.yt/VripF6i.png)

# [nse] --script-args index=/etc/passwd,read=true
![file-checker.nse](http://3.1m.yt/7LjWoFj.png)

# [nse] --script-args command=msfconsole -q -x 'use auxiliary/scanner/http/dir_scanner; set RHOSTS www.youtube.com; exploit'
![file-checker.nse](http://3.1m.yt/luV6hP.png)


# Please read my 'WIKI' for further information.

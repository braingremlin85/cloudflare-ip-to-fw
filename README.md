# cloudflare-ip-to-fw
add firewall rules to accept HTTP/HTTPS connections from cloudflare ip's only

> [!WARNING]  
> Some GUI file managers (i.e.: Dolphin) open a lot of connection if using SFTP.
> This could trigger ssh limit rule and slow down your remote connection.
> If you need SSH/SFTP remote access on host running this script please consider using a FTP client like FileZilla or comment out ssh limit rules (lines 64-66)

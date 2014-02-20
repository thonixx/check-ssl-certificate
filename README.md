### check-ssl-certificate
Detect which SSL certificate is behind a specific IP or hostname.  
Additionally you can specify a custom port to check i.e. POP3S, SMTPS and so on.

#### Most common ports
HTTPS 443  
SMTPS 465  
POP3S 993  
IMAPS 995

### Usage and command options
```
Usage: check-ssl-certificate	-H/--hostname hostname [-p/--port portnumber]
		[-h/--help]

Overview:
	Print which SSL certificate is used for the secure connection to the given host.

	The options:
	****
	-H/--hostname server	IP address or hostname to connect to
	-p/--port port number	Port number to connect to (default: 443)

	I need help:
	****
        -h/--help		this help
```

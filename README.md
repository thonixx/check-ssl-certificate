### Script check-ssl-certificate
Detect which SSL certificate is behind a specific IP or hostname.  
Additionally you can specify a custom port to check i.e. POP3S, SMTPS and so on.

#### Most common ports
HTTPS 443  
SMTPS 465  
POP3S 993  
IMAPS 995

### Installation
After checkout you can run the command as usual with ```./check-ssl-certificate``` from the directory where the script is stored.  
Without any option/argument you will get the help output.  
  
If you would like to run the command without an absolute path symlink to ```/usr/local/bin``` or any other directory from your ```$PATH``` variable:  
```
ln -s /path/to/git/check-ssl-certificate/check-ssl-certificate /usr/local/bin/
```

### Usage and command options
```
Usage: check-ssl-certificate	-H/--hostname hostname [-p/--port portnumber] [-h/--help]

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

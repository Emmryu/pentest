### Utilities

#### Netcat
nc -lnvp [port]  
nc -lnvp [port] > [output_file]  
	nc -w 3 [ip_address] [port] < [input_file]  

#### Python
python -m SimpleHTTPServer  
python -c 'import pty;pty.spawn("/bin/bash")'


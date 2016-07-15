# S2-devMode

### struts2-devMode exp by python

	usage: s2-devmode.py [-h] [-u URL] [-c CMD] [--upload]
	                     [--remote_file REMOTE_FILE] [--local_file LOCAL_FILE]
	                     [-f FILE]
	
	optional arguments:
	  -h, --help            show this help message and exit
	  -u URL, --url URL     test target url,for
	                        example:http://www.abc.com/index.action
	  -c CMD, --cmd CMD     the cmd to execute,for examble:"cat /etc/passwd"
	  --upload              upload file,PLEASE set --remote_file and --local_file
	  --remote_file REMOTE_FILE
	                        upload file to remote
	  --local_file LOCAL_FILE
	                        local file to upload
	  -f FILE, --file FILE  load target url from file

# How to Use Python_JSRAT:

## JSRat Server
Usage: MyJSRat.py [options]
Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -i IP, --ip=IP        IP to Bind Server to (i.e. 192.168.0.69)
  -p PORT, --port=PORT  Port to Run Server on
  -u URL, --url=URL     URL to Initiate Client Connection (default: /connect)
  -f, --find-ip         Display Current Internal and External IP Addresses
  -c CMD, --command=CMD
                        auto Send command to client (No interaction)
  -v                    Enable Verbose Output

## Two Modes:
  1-Interactive mode
   python MyJSRat.py -i 192.168.1.101 -p 8080
  2-Command mode
  python MyJSRat.py -i 192.168.1.101 -p 8080 -c "whoami"
  
## Url explain:
http://192.168.1.101:8080/connect  default reverse url

http://192.168.1.101:8080/wtf To see the code ran on the client

http://192.168.1.101:8080/hook IE hook link

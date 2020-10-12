# Domain-name
opnsense setup for Webserver

I hope this will help anyone that is pulling their hair out.

First let's make some assumptions:

    Your external IP address is 123.45.67.89
    Your LAN interface is configured as 192.168.10.1/24
    Your webserver running HTTP (port 80) and HTTPS (port 443) lives at address 192.168.10.30
    You are the owner of the domain mysite.com and the URL for your webserver is www.mysite.com
    In external DNS, you have an A record for www.mysite.com pointing to 123.45.67.89 (your external IP address)

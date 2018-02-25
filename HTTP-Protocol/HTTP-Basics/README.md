# Experiential-Learning 
## HTTP-Protocol 
### HTTP Basics

The examples as shown in tables in article "Exploring Basics of the HTTP Protocol" are
listed. The description of each is given below. These examples assume that hostname
*myweb.com* is resolvable to IP address for network communication to work. To ensure this,
please ensure to make an entry in the file */etc/hosts* of computer running the web server
e.g. *Apache* web server.

**welcome.pcap**:
	This file contains the wireshark capture of a web request when a simple web page
	*welcome.html* is access in browser.

**Table1-HTTP-Request.txt**: 
	Contains the *Request line and the *request headers* sent by the web client e.g.
	web browser, when access URL *http://myweb.com/welcome.html*.

**Table2-HTTP-Response.txt**: 
	Contains the *Status line and the *Response headers* sent by the web server  e.g.
	Apache, when a browser accesses URL *http://myweb.com/welcome.html*.

**Table3-welcome.html**: 
	Contains the contents of webpage *welcome.html* deployed at web server e.g.
	*Apache*.

**Table5-Req-Badheader.txt**:
	This is the content of web request with bad headers.
	When using this with *telnet* command, please ensure to provide one empty line at
	the end to indicate end of request headers. This can be used with *nc* as follows.
	*cat Table5-Req-Badheader.txt | nc myweb.com 80*

**Table6-Resp-BadHeader.txt**:
	This is the content of web response when web request contains *bad* HTTP Request
	headers.


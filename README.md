Llamato
--------
WebRTC client and server architecture for Service Providers
This is the application based on Open Source projects

High level Architecture

    -lb-> (https) --> apache -> apache ---> nosqldb -------------- 
aws  								 |
    -lb-> (wss) --> ngnix --> kamailio -> freeswitch -> asterisk -

Software
--------------------------------------
FrontEnd	|Apache Web Server			
FrontEnd	|Nginx Load Balancer
App	 	|sipML5 Application Server 	
SipRegistrar	|Kamalio Sip Registrar			
SipCallControl	|FreeSwitch Sip B2BUA		
Media		|Asterisk

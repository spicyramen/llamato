Llamato
--------
Unified communications architecture for Service Providers
This solution is based on Open Source projects

High level Architecture

    -lb -- (https) -- apache - apache --- mysql ---------o
    -lb -- (wss) ---- ngnix -- kamailio - freeswitch -o asterisk 

## Software

**FrontEnd**
    Apache Web Server			

**FrontEnd**
    Nginx Load Balancer

**App**
    sipML5 Application Server 	

**SipRegistrar	and Sbc**
    Kamalio Sip Registrar			

**SipCallControl**
    FreeSwitch Sip B2BUA		

**Media**
    Asterisk,mcuWeb,Jitsi

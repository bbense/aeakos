aeakos
======

Automated install of kerberos keytabs. 

This software should be viewed as more of a case study than a ready to go solution.
It's an example of how one site implemented automated keytab installs as part of
provisioning bare metal. In particular the extkeytab program makes many assumptions
( heimdal kadmin for one) and will likely need to be reworked for your site. 

The INSTALL document is bare bones at this point. I plan to flesh it out as time
allows. Here are some slides that might help in understanding the approach used. 

 http://workshop.openafs.org/afsbpw07/talks/bbense.pdf
AppStore Report SFTP Service

2014-12-19<br>
Miles Poindexter<br>
selfpropelledcity@gmail.com<br>

This service monitors a folder and sends any report that appears there to a specified site, using SFTP.

Written in XML using Apache Camel and Blueprint, a dependency injection framework for OSGi.<br>
http://camel.apache.org/<br>
hhttp://aries.apache.org/modules/blueprint.html<br>

This client is designed to run as a service inside Apache ServiceMix (SMX).<br>
http://servicemix.apache.org/

It has also been tested for Talend ESB, which is based in SMX.<br>
https://www.talend.com/products/esb



Report directory:
/app/appstore/reports/

Sent directory:
/app/appstore/sent/

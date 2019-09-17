# zabbixjmxagentautoregistration
This bash script use Zabbix API to do JMX agent auto registration



How to 

1. We need add a script on zabbix server 

Login in Zabbx Server with Admin user 
then got Administration ====> Script ==== Create Script

select type = script and Execute on  "Zabbix Server"

in command type /bin/bash /usr/lib/zabbix/externalscripts/testmyzab.sh

Copy the scripton zabbix server in  /usr/lib/zabbix/externalscripts/ directory 


2. Configure Zabbix Agent auto registration under action , auto registration .










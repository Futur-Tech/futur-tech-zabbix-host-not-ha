# Futur-Tech Zabbix Template Host Not High-Availability
This is a template used for any Zabbix Agent or SNMP device that will be shutdown from time to time.

This template will change macro in order to:
- Increase No Data timeout trigger to 20d (Zabbix Agent and SNMP check)
- Disable trigger for network cards being down
- Increase StorageCraft timeout  (https://github.com/Futur-Tech/futur-tech-zabbix-storagecraft)
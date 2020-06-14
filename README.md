# NXOS_SNMP_Grafana
Demo about how to monitor Cisco NX-OS and ACI Switches via SNMPv3 and the TIG-Stack (Telegraf, InfluxDB, Grafana)

![TIG-Stack](https://github.com/NWMichl/NXOS_SNMP_Grafana/blob/master/TIG-Stack.png)

Visit my blog post over at https://nwmichl.net/2020/06/14/monitor-cisco-nx-os-aci-via-snmp-and-the-tig-stack/ for full documentation.

## Telegraf configuration
The Ansible playbook generates Telegraf .conf files in the /etc/telegraf/telegraf.d directory of the TIG host to query all metrics and populate the Grafana dashboad.


## Grafana 
The Dashboard is a first idea to visualize metrics per device and should help to get started developing own solutions.

![Cisco NXOS/ACI Switches](https://github.com/NWMichl/NXOS_SNMP_Grafana/blob/master/Cisco_NXOS_Dashboard.png)

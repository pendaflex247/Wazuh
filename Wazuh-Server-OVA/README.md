# Wazuh Server Installation OVA method

Download server OVA
-

https://documentation.wazuh.com/current/virtual-machine/virtual-machine.html

Wazuh Server Credentials
-
	user: wazuh-user
	password: wazuh

Wazuh Dashboard Credential
-
	URL: https://<wazuh_server_ip>
	user: admin
	password: admin
	
Find Wazuh IP
-
	$ ip a
	
Configuration Files Locations
-
	Wazuh manager:
    
	/var/ossec/etc/ossec.conf
	
	Wazuh indexer:

	/etc/wazuh-indexer/opensearch.yml
	
	Filebeat-OSS: 

	/etc/filebeat/filebeat.yml
	
	Wazuh dashboard:

	/etc/wazuh-dashboard/opensearch_dashboards.yml
	/usr/share/wazuh-dashboard/data/wazuh/config/wazuh.yml
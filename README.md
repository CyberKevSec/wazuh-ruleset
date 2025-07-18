# wazuh-ruleset
Custom Wazuh decoders and rules


When using syslog ensure proper file permissions are set. If proper permission is not set on any syslog.log file Wazuh will not be able to access the logs in the file. Logs will not appear in dashboard.

chown syslog:adm pfsense.log

Wazuh active response is configured to stop powershell.exe and powershell_ise.exe processes when triggered by rules 100106, 100172, or 100604.


ossec.conf snippet paste to /var/ossec/etc/ossec.conf restart wazuh-manager

kill-procs.ps1 and kill-procs.bat paste to C:\Program Files (x86)\ossec-agent\active-response\bin and restart wazuh agent

# namesilo_ddns_synology
update the namesilo domain name at synology devices with only bash, no need to install other plugins.
## How to use:
* Download and save the bash script to your synology device.
* Get your APIKEY from Namesilo control panel, https://www.namesilo.com/account_api.php
* Modify the script, set "domain", "host", and "api_key" with yours at the script.
* Set file permission to make it executable.
* Create schdule job at control panel
* Check the ip updated log at /tmp/namesilo_ip_update.log

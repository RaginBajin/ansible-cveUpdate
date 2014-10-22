## Ansible CVE Updater ##
This is an ansible playbook that will run to update openssl.

### How to Use ###

- Ensure that Ansible is installed on your system. (yum or downloading it)
- Update the hosts files and fill in the blanks with either IPs or FQDNs
- Update the username that you will be using in the openssl_update.yml or web-servers.yml file
- Run the script as follows: ansible-playbook -i hosts <openssl_update.yml or web-servers.yml>  -K 
- It will ask you for your sudo password, enter in that password and press enter.
- ??
- Watch it profit

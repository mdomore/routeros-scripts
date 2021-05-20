# routeros-scripts
RouterOS scripts

Some usefull scripts for managing RouterOS devices

backup_configuration : for sending the running configuration to a ftp server

link_switch_automation : Need explaination, but it can check if pppoe and l2tp links are running.
                         Based on thos status, the RouterOs device choose to activate or deactivate
                         links.

remote_cap_securisation : Script created to change some security parameters one caps connected deveices

send_report : Script that log the status of pppoe and l2tp links, with a /system logging configuration,
              you can send those inforamtions to a syslog server.

vpn_configuration : Used to create openvpn configuration, and backup it on a remote server.
                    The script can also retrieve certificat from the server or from local files (after a reset for example)

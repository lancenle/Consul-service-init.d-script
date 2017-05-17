# Consul-service-init.d-script

Script consul should be placed in directory /etc/init.d/.
Configuration file consul.cfg should be placed in directory /etc/consul/.


You will need tweak the consul script to fetch the IP address for your network, and the configuration should be updated to reflect the IP addresses of your network.


Once the script and configuration files are in place, these are the valid commands on CentOS and Ubuntu systems:


service consul start
service consul stop
service consul status

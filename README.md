## Berofore running:
You should have configured Eve-ng with a Cisco 7200 family router.
A linux server with ansible packages, Loganalyzer (for syslog), cati(for snmp) and tacsgui (for tacacs).

# network-ansible
Network automation usign ansible. Trying to make a real environment where two servers are providing tacacs, syslog and snmp. Futhermore the routers are preconfigured with a VRF just to have connection with the servers, then all the config is automated with ansible.

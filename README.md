# opnsense-dns-failover

a script to automatically change a cloudflare dns record to point to a different IP address whenever gateways change in opnsense.

for example you may have two wan connections configured in failover mode. when the primary connection goes down you would like some dns record to update to point to the secondary. this script does that.

copy config.py.example to config.py, and follow the instructions in config.py to get set up.

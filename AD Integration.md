Supports: 
- delegated authentication
- user provisioning

Agent install - it imports users/groups into okta

Service account needs: 
read all from all synced users
	write to each user if write provisioning is enabled

outbound 443
set period of import

Server must be on the domain (2CPU 8 GB RAM)

Settings --> Downloads

setup profile - can map attributes into Okta


# HA
2 agents per domain
system selects agent based on user location for provisioning
120 seconds: marked isn't available
# Multiple Forests
ignores forests

# Sizing
0-30k - 2 agents
30k-100k - 3 agents
then more

# Tuning
program files - okta - agent
the ad config file
* logging on or off
* Modify Threads per agents

# Security
do not install it on a domain controller (use member server)
install on server core
do not use ad administrator
dont create the user in Okta
deny active logon
lock down comms with DC's and jump box
# Important AWS Considerations:
The following settings are necessary while deploying virtual routers and firewalls in AWS
- Disable source/destination checks on the Palo Alto data interfaces
- Disable source/destination checks on the Cisco router interfaces
- Configure AWS route tables to forward traffic through the firewall and router
- Use seperate management and data-plane secuirty groups
- Avoid exposing management interfaces directly to the internet
- Restrict SSH and HTTPS access to trusted public IP addresses

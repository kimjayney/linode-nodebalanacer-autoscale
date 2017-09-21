# linode-nodebalanacer-autoscale

## Requirements
- linode-cli
- Bash shell
- Stackscript must be added to "Manage Stackscripts"
- You can get Stackscript index with linode stackscripts list --api-key "Linode API Key"

## Features
- Health check 
- when Nodebalancer node health bad (Up nodes < down nodes) then add new node, and add to Nodebalancer.
- Create Linode with Stackscript, and Private IP
- Add node to Nodebalancer


## explain this program
$(https://i.imgur.com/VUNAXV2.png
![explained](https://i.imgur.com/VUNAXV2.png "explained")


## Contact
- support@rainclab.net

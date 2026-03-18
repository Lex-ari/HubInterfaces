# HubInterfaces

This is a shared submodule between ADeployment and BDeployment. 

This project consists of 3 repositories:
- [ADeployment](https://github.com/Lex-ari/HubA): A "primary" FSW
- [BDeployment](https://github.com/Lex-ari/HubB): A "secondary" FSW (ex. payload/sensor)
- [HubInterface](https://github.com/Lex-ari/HubInterfaces): Interface defining hub connections and shared ports

It contains:
- Port Indexing for both sides of the hub
- Port definitions that are used by components that invoke other components across the hub

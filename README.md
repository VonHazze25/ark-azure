![image](https://user-images.githubusercontent.com/8069294/37400960-781952be-277e-11e8-90a1-48d40bfb669a.png)

**Read full guide [here](https://blog.ark.io/ark-bridgechain-azure-guide-774f5fd63333) on how to setup ARK BridgeChain via Microsoft Azure**

# Deployment of Ark.io Bridgechain

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FArkEcosystem%2Fark-azure%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fdavepinkawa%2Fazure-quickstart-templates%2Fmaster%2Fark-sidechain-on-ubuntu%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

<p>This template creates a Ubuntu VM with user-specified credentials. It then sets the PublicDNS name, creates a network security group for all ark firewall settings, and leaves you with a fresh Ubuntu 16.04-LTS VM in less than 5 minutes.</p>
<p>FQDN:  PublicDNSname.datacenter-region.cloudapp.azure.com</p>
<p>Once the server is fully deployed, connect via SSH (PuTTY > PublicDNSName > Credentials) and then run: <p> 
<code>curl -o- https://raw.githubusercontent.com/ArkEcosystem/ark-azure/master/script/arkdefaultinstall.sh | bash </code>
<p> After approximately 10 minutes of the script running, your Ark Node Bridgechain and Ark Explorer will be viewable at:  HTTP://publicIP:4200 </p>

## Authors
- [@davepinkawa](https://github.com/davepinkawa)
- Alex Barnsley <alex@ark.io>

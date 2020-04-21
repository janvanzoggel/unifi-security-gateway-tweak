# unifi-security-gateway-tweak
My Unifi Security Gateway configuration for Tweak fiber to replace the standard Zyxel router. 

* ssh root@10.x.y.z to your Unifi Cloud Key
* vi /usr/lib/unifi/data/sites/default/config.gateway.json
* chown unifi:unifi /usr/lib/unifi/data/sites/default/config.gateway.json
* Through the Unifi Network controller perform a force provision of the USG

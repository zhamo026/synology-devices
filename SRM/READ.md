# Setup
Upon the initial setup, you can locate the device under
```bash
[192.168.1.1](http://192.168.1.1:8000/webman/index.cgi)

[10.0.4.1](http://10.0.4.1:8000/webman/index.cgi)

[router.synology.com](http://router.synology.com:8000/webman/index.cgi)
```
Please ensure that the gateway isn't assigned the same IP address.

During the first setup, the device offers two operation modes: wireless router or AP.

wireless router:
```bash
When set to wireless router mode, it automatically creates two subnets.
It's important to ensure these subnets don't conflict with your device
or the device you're connecting to. Refresh the DHCP leases,
disable and then enable your devices. Additionally, this mode allows you to create VLANs
within your LAN network and wireless connections.
```
wireless AP:

```bash
In wireless AP mode, the gateway IP is copied.
Please ensure it doesn't conflict with your devices.
This mode only permits the creation of VLANs with wireless connections.

```

Establish a static IP address for the router. Then, create users accounts with secure passwords 
and adjust login ports as needed for enhanced security

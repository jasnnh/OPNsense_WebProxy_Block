# OPNsense_WebProxy_Block
Using Web Proxy on OPNsense to block sites.

Lets setup OPNsense Web proxy to add sites to a black list to block users from accessing these sites.
Services > Web Proxy > Administration > General Settings & Forward Proxy
Make sure that under General settings it's enabled and you select the network that you want to apply the web proxy on.

![Screenshot](https://github.com/jasnnh/OPNsense_WebProxy_Block/blob/main/image18.png)

Now the web proxy should be working and our users won't be able to access any sites that we decide to block.

![Screenshot](https://github.com/jasnnh/OPNsense_WebProxy_Block/blob/main/image19.png)

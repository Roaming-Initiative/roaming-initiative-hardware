#Omnitik

An Omnitik is a radio with an integrated router and antenna made by MikroTik, it is weatherproof and has generally good coverage and power. Omnitiks can be had for around $30 on eBay or in group buys. 

##Hardware

The base model Omnitik includes 5 10/100mbps ethernet ports, and a MiMo 2x2 802.11n radio. It can accept 8v to 30v of DC power injected into the ethernet cable via PoE on the Uplink port. The model above the base model offers PoE Out on ports 2 thru 5, but due to firmware issues the Omnitik may randomly turn off PoE on those ports, hence why most mod the base model to add PoE into the Omnitik. The Omnitik also has a 400mhz MIPS based SoC and 32mb of ram, along with 64mb of flash.

##Software

Your average Omnitik comes with RouterOS v6, which is based on the Linux kernel and a mess of other utilities. OpenWRT and DD-WRT are not supported on the Omnitik yet, although it should be possible to support this platform.

##Modifications

###Omnitik DIY POE out

With this modification you can add POE out on all 4 ethernet ports that are available for other devices to plug into on your Omnitik. Check out a [completed POE out mod](http://www.flickr.com/photos/h2non/sets/72157627860401917/) & try it yourself.

##Relevant Links

[Manufacturer Page](http://routerboard.com/RBOmniTikU-5HnD)

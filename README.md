<h1># Configure-pfSense-on-vSphere</h1>

<h2>Install pfSense for use as firewall on homelab</h2>

Let's start by [downloading pfSense community edition here](https://www.pfsense.org/download/).

If you need help installing the VM on vSphere you can look at my [vSphere and vCenter Set Up lab](https://github.com/AustinGettel/vSphere-and-vCenter-setup/blob/main/README.md).

Before installing, we need to to do some basic networking set up to ensure pfSense will work. We need 2 virtual switchs, 1 for WAN and 1 for LAN; then we'll need two port groups, also 1 for WAN and 1 for LAN.

From the ESXi web client navigator, click on Networking and then click on Virtual switches tab. From there, click on “Add a new standard virtual switch”.


![Rockatansky](https://raw.githubusercontent.com/superDuperCyberTechno/rockatansky/master/header.png)

OpenVPN server installation script, suitable for tech savvy [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29)s. Compatible with Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

In addition, it automatically maintains an internal malware blocklist based on the [StevenBlack/hosts](https://github.com/StevenBlack/hosts) project, isolating you from a constantly tweaked list of potential threats.

Originally, this was an amalgamation of [Nyr/openvpn-install](https://github.com/Nyr/openvpn-install) and [BobNisco/adblocking-vpn](https://github.com/BobNisco/adblocking-vpn), but it has evolved beyond those.

### Installation
Run the script and follow the wizard:

`wget https://raw.githubusercontent.com/superDuperCyberTechno/rockatansky/master/rockatansky.sh -O rockatansky.sh && bash rockatansky.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely remove what constitutes Rockatansky.

### Client
Please be aware, this is only 50% of a VPN connection. You need a local client to hook up your machine to the server. A good example could be the [Pritunl Client](https://client.pritunl.com/).

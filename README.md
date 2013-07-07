# OpenVPN installer for Debian

Fork of [Nyr's openvpn-install](https://github.com/Nyr/openvpn-install)

OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian-based distros.

This script will let you setup your own VPN server in no more than one minute, even if you haven't used OpenVPN before. It isn't bulletproof but it has been designed to be as unobtrusive and universal as possible.

Prerequisites:
If on a VPS, make sure that you submit a ticket to enable TUN module for openvpn.

Installation
Run the script and follow the assistant:

Optional prerequisite for cloning git repo:
`apt-get install git`

`git clone https://github.com/droidzone/openvpn-install.git`
`bash openvpn-install/openvpn-install.sh`

Once it ends, you can run it again to add more users.


License
[Attribution-NonCommercial-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-nc-sa/3.0/)

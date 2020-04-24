# airgeddon deb packages

Useful related to airgeddon packages for Debian based Linux distributions.

Here is a collection of deb packages to be installed using `dpkg -i <package>` command.

__Missing packages for archs__

 - amd64

 amd64 package collection is complete at this moment.

 - armhf (Raspbian for Raspberry pi)

Missing some packages: hcxtools, bully, gawk or anything containing awk command, ruby-em-proxy, ruby-network-interface, beef-xss, bettercap, hashcat.

 - armel (Kali/Parrot for Raspberry pi)

Missing some packages: python-twisted-bin, sslstrip, ruby-em-proxy, ruby-network-interface, beef-xss, bettercap, hashcat.

____

__This is completely unofficial, so don't ask airgeddon staff about it. Don't request anything to be included and don't open any issue regarding this__. Just contact us if you have one of the missing deb packages.

How to create a deb package? pretty easy. Install dpkg-repack tool by `apt install dpkg-repack`, then create deb file from an installed package of your choice, for example: `dpkg-repack aircrack-ng`. So, if you have installed one of the missing packages for any of the architectures, please create it and contact us to try to complete the repo.

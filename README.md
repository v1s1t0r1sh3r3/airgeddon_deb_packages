# airgeddon deb packages

Useful related to airgeddon packages for Debian based Linux distributions.

Here is a collection of deb packages to be installed using `dpkg -i <package>` command.

__Missing packages for archs__

 - i386 <- Package collection is complete at this moment.

 - amd64 <- Package collection is complete at this moment.

 - armhf (32bits Raspbian for Raspberry pi) <- Missing only one package: _hashcat-utils_.

 - armel (32bits Kali/Parrot for Raspberry pi) <- Missing some packages: _hashcat_ and _hashcat-utils_.

 - arm64 (Any 64bits Linux for Raspberry pi) <- Missing some packages: _hashcat_ and _hashcat-utils_

____

__This is completely unofficial, so don't ask airgeddon staff about it. Don't request anything to be included and don't open any issue regarding this__. Just contact us if you have one of the missing deb packages.

How to create a deb package? pretty easy. Install dpkg-repack tool by `apt install dpkg-repack`, then create deb file from an installed package of your choice, for example: `dpkg-repack aircrack-ng`. So, if you have installed one of the missing packages for any of the architectures, please create it and contact us to try to complete the repo.

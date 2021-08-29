# Atomic-Pi-ROOTER

Atomic Pi ROOTER AP builds. Openwrt built for cellular modems.                                                                                  

Built with standard rooter repo (https://github.com/ofmodemsandmen/RooterSource) and UEFI Support (https://github.com/falafalafala1668/OpenWrt-UEFI-Support)

Dir /openwrt-atomicpi-rooter-goldenorb-19.07.6/ - build using heavily hand-edited config file.

Future builds will use the standard method below.

* git clone https://github.com/ofmodemsandmen/RooterSource rooter19076
* cd rooter19076
* git clone https://github.com/falafalafala1668/OpenWrt-UEFI-Support.git -b openwrt-19.07
* ./OpenWrt-UEFI-Support/RunMe.sh apply
* ./build X86-64

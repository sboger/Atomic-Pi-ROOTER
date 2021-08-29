# Rooter for Atomic Pi

USB ONLY FOR NOW. (I'm fighting with the mmc)

Use Etcher to flash openwrt-x86-64-uefi-gpt-ext4.img.gz onto 2gb+ usb stick

Boot from usb stick.

Connect via wifi network ROOter, password rooter2017 (this will work even without antennas)

open webpage: 192.168.1.1

wifi defaults to lan. wifi client mode with ap mode works pefectly.

wired defaults to lan. for wan, network -> interfaces -> create new interface -> dhcp -> name eth0, device eth0, put into wan firewall settings.

Runs very fast from usb. Everything SEEMS to work. This is a first run with a heavily customized config file. MMC to come.

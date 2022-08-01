# ZeroXploit-Screen-version
Install instructions :

1 - Flash on a microsd of at least 4gb <br>
2 - At the end of flashing in the microsd a new partition with name "boot" will appear, configure the file wpa-supplicant.conf
3 - In the windows disk manager create a new partition in the remaining space (unalocated) of type fat32
4 - Configure the ip of the console in the configuration page of the host (if it is done from the console the ip will be automatically recognized), this is for the binloader of the lcd screen menu
5 - Edit the file /etc/dnsmasq.conf and at the end of the file replace the word **RASPBERRY_IP** with the ip of your raspberry in your local network, then use this ip in your dns configuration to block sony servers

- Goldhen2b2+jailbreak autoload
- No error messages when emulating usb
- Light page for ps4 browser
- After loading golhen the page is able to detect if the golhen binloader is working so as not to load the jailbreak again
- Interactive menu for raspberry screen
- Bin launcher, database backup and restore via ftp (no bin, you need to have ftp enabled for this option), all from the raspberry screen

I leave the link available to buy the screen used in the mod:

https://es.aliexpress.com/item/32970035492.html?spm=a2g0o.order_list.0.0.7555194d6H2bfb&gatewayAdapt=glo2esp

# Yocto_Domotic_Project
Embadded project using yocto and raspberrypi to make Domotic

You need to install this layer in yocto folder and don't forget to add this layer in build/conf/bblayers.conf

first commit -> meta-ynov-master with wifi activated

follow this tutorial to remake this :
    https://hub.mender.io/t/how-to-configure-networking-using-systemd-in-yocto-project/1097

generate the wifi connection to your host with this command with the correct path don't forget to delete this file before git upload

    $: wpa_passphrase 'YOUR_SSID' >  meta-ynov-master/recipes-connectivity/wpa-supplicant/files/wpa_supplicant-nl80211-wlan0.conf

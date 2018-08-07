# wifilinux
Wifi No Searching Problem On Linux (Solved)

1. Open terminal and get root in terminal
2. Write in terminal --> nano /etc/NetworkManager/NetworkManager.conf
3. Modify this file where [ifupdown] managed=false
4. Set [ifupdown] managed=true
5. Save this file and exit
6. Restart network manager --> service network-manager restart

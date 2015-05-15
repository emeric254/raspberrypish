# raspberrypish



## dependencies
  - hostapd
  - dnsmasq
  - python-tornado

```bash
aptitude -y install hostapd dnsmasq python-tornado
```



## configuration

edit the _INSTALL.sh_ file as you wish

```bash
nano INSTALL.sh
```

Name  | explanation | default
----- | ----------- | -------
 INTERFACE | interface to use | wlan0
 DRIVER | driver to use | nl80211
 CHANNEL | wifi channel to use | 1
 SSID | SSID to use | test
 PAGE | html pages the server have to use | test



## install raspberryphish on your system

execute the _INSTALL.sh_ file

```bash
bash INSTALL.sh
```

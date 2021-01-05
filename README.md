# DuckDNS Updater

Python script to update DuckDNS IPv4 and IPv6 address. 
It uses the IPv6 address of the device instead of the Router.

## Crontab

```bash
(crontab -l ; echo "*/5 * * * * /usr/bin/python3 ~/duckdns-updater/duckdns-updater.py") | crontab -
crontab -l
```

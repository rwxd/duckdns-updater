# DuckDNS Updater
Python script to update DuckDNS IPv4 and IPv6 address.
It uses the IPv6 address of the device instead of the Router.

## Crontab
`crontab -e`
```bash
cd ~
git clone 
*/5 * * * * /usr/bin/python3 ~/duckdns-updater.py
```

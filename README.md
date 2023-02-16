# Godaddy_dns_update
A script for dynamically update GoDaddy DNS records using systemd timers and GoDaddy API.
`run` Run script every 10 minutes

- ## Installation :
- `/etc/systemd/system/update.timer`
- `/etc/systemd/system/update.service`
- sudo systemctl daemon-reload
- sudo systemctl enable update.timer
- sudo systemctl start update.timer

- ## Careful :
`update` he must have permission `sudo update chmod +x"

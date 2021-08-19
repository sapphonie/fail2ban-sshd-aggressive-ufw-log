# fail2ban-sshd-aggressive-ufw-log

Ban users with `fail2ban` that fail to ssh to a server after 3 failed attempts through `ufw` and log it to syslog with `logger`

# Usage

assuming you're in the git repo as root:


```
cp ./*.d /etc/fail2ban/ -rfv
systemctl restart fail2ban
fail2ban-client reload
```

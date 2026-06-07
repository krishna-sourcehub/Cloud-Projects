DNSMASQ Port 53 Conflict

Problem:

failed to create listening socket for port 53

Cause:

systemd-resolved already using port 53

Solution:

sudo systemctl disable systemd-resolved
Nextcloud Trusted Domains

Problem:

Please contact your administrator

Solution:

'trusted_domains' => [
  'nextcloud.local',
  '192.168.31.50'
]
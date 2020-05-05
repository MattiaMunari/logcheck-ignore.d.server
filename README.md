# logcheck-ignore.d.server

My modified logcheck ignore.d.server regexp.

I added
- pve (to include items in log marked as pve and its components)
- systemd-pve (to include items in log marked as systemd but related to pve and its components. I include only the modified files that works for my installation and the subsequent installation of the differential backup patches https://github.com/ayufan/pve-patches)
- systemd-quiet (to include additional regexp to silence systemd that is flooding syslogs. Some of these rules are due to stop recurring messages of zabbix checks e.g. connection closed or reset to ssh)
- ssh-quiet (to include additional rexexp to silence all warnings about connection closed and reset to ssh due to zabbix checks)
- rsyslog-extra (to be put aside to the standard rsyslog that is bugged in debian systems)

feel free to contribute and to give me your opinions and/or to contribute.

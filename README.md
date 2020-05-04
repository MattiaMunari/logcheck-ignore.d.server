# logcheck-ignore.d.server-pve
Modified logcheck rules to ignore normal messages of pve Proxmox Virtual Environment 6

I include only the modified files that works for my installation and the subsequent installation of the differential backup patches https://github.com/ayufan/pve-patches

I added
- pve (to include items in log marked as pve and its components)
- systemd-pve (to include items in log marked as systemd but related to pve and its components)
- systemd-quiet (to include additional regexp to silence systemd that is flooding syslogs)

feel free to contribute and to give me your opinions and/or to contribute.

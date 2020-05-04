# logcheck-ignore.d.server-pve
Modified logcheck rules to ignore normal messages of pve Proxmox Virtual Environment 6

I include only the modified files that works for my installation and the subsequent installation of the differential backup patches https://github.com/ayufan/pve-patches

I added
- pve
- systemd-pve

files to include items marked in log as pve or its components or items in logs marked as systemd but related to pve

feel free to contribute and to give me your opinions and/or to contribute.

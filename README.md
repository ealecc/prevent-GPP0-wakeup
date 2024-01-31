# prevent-GPP0-wakeup
Systemd service to prevent my linux desktop from waking immediately after suspending.

I've created this repository mostly because I will write this custom service, forget about it, rebuild my OS at some point and forget how I solved this issue.

Specifically for Linux on a gigabyte aorus B550 motherboard, my computer will immediately wake from suspend. I found [this reddit thread] (https://www.reddit.com/r/gigabyte/comments/p5ewjn/b550i_pro_ax_f13_bios_sleep_issue_on_linux/) which describes a one-time fix, and it links to [this askubuntu thread] (https://askubuntu.com/questions/1049178/suspend-instantly-restarting-editing-acpi-wakeup-with-systemd-service/1139215#1139215) describing how to make a similar systemd service.

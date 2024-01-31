# prevent-GPP0-wakeup
Systemd service to prevent my linux desktop from waking immediately after suspending.

I've created this repository mostly because I will write this custom service, forget about it, rebuild my OS at some point and forget how I solved this issue.

Specifically for Linux on a gigabyte aorus B550 motherboard, my computer will immediately wake from suspend. I found [this reddit thread] (https://www.reddit.com/r/gigabyte/comments/p5ewjn/b550i_pro_ax_f13_bios_sleep_issue_on_linux/) which describes a one-time fix, and [this comment] (https://www.reddit.com/r/gigabyte/comments/p5ewjn/comment/hb32elw/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) describing the exact system service to write.

# Installation

As per the comment above, create 'preventGPP0wakeup.service' in '/etc/systemd/system/' then run 'sudo systemctl daemon-reload && sudo systemctl enable preventGPP0wakeup'.

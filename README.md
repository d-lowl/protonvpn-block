# protonvpn

Show ProtonVPN status. 

Requires script to be run under root, since pronovpn-cli requires root permissions. (Consider adding an exception to /etc/sudoers for this script only)

Displays Public IP Address, Server Name and Server Load, if ProtonVPN is running

# Dependencies

* `protonvpn-cli`

# Config

```
[protonvpn]
label=VPN
command=sudo $SCRIPT_DIR/protonvpn
interval=30
```

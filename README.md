# windscribe-tmux
Windscribe VPN connection status for tmux status bar (and possibly others)

## Usage

Copy `vpnstatus` to `/usr/local/bin` then do `chmod 775 /usr/local/bin/vpnstatus`.

Afterwards, add something like this to your `.tmux.conf`:

```
set -g status-right '#(vpnstatus)'
```

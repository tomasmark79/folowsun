# FollowSun - GNOME theme switcher based on sunrise/sunset

# Usage

```bash
Usage: followsun.sh [OPTION]

Options:
  --help         Show this help
  --set-location LAT LON  Set your latitude and longitude
  --set-offset SUNRISE_OFFSET SUNSET_OFFSET  Set offsets in minutes
  --force-light  Force light theme
  --force-dark   Force dark theme
  --auto         Apply the appropriate theme based on current time
  --daemon       Run as daemon, changing themes at sunrise/sunset

Current configuration:
  Location: 49.8682576, 14.2626625
  Sunrise offset: 0 minutes
  Sunset offset: 0 minutes

```

# systemd service

Copy `followsun.service` to the destination `~/.config/systemd/user/`

and enable and start service

```bash
systemctl --user enable followsun.service
systemctl --user start followsun.service
```

status output

```bash

```

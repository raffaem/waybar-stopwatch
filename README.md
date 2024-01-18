# waybar-stopwatch

A simple stopwatch for waybar.

To configure it:

```
"custom/stopwatch": {
    "exec": "$HOME/.config/waybar/scripts/stopwatch start",
    "format": "{}",
    "interval": 1,
    "return-type": "json",
    "on-click": "$HOME/.config/waybar/scripts/stopwatch restart"
},
```

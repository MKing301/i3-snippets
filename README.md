# i3 Snippets

## Useful Notes

### Move workspaces between monitors

$mod+Ctrl+greater move workspace to output right
$mod+Ctrl+less move workspace to output left

## Exit i3 without using a mouse

Edit config file (*/home/$USER/.config/i3/config*)

1. bindsym $mod+Shift+e exec "i3-nagbar -t warning -m 'You pressed the exit shortcut. Do you really want to exit i3? This will end your X session.' -b 'Yes, exit i3' 'i3-msg exit'"
2. bindsym $mod+Shift+e exit
3. run i3-msg reload to reload the configuration file

## Links

[i3 Reference Card](https://i3wm.org/docs/refcard.html)

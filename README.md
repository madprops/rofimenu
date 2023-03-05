This reads a file and builds a rofi menu.

For example:

```
Players = python /home/yo/code/empris/empris.py
Clipboard = clipton
Screenshot (Region) = spectacle -r
Screenshot (Window) = spectacle -a
Screenshot (Monitor) = spectacle -m
```

`cat` that file into rofimenu.

Left portion are labels, right are commands to execute.
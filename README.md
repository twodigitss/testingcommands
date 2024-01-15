# KFetch
The purpose of this fetch alternative is creating a fetch tool that does not need to be "static" all the time, 
printing just one set of colors and ascii art staying as the same until you change it manually. <br>
This tool offers to randomize the color set, randomizes the ascii art (if you have not changed it manually of course)
each time the command is launched and some other functions found in the configuration file. <br>
You can customize the looks modifying some parameters in ` config.py ` <br>
<br>
![Colorschemes output example](/images/demonstration.png)<br>

Highly inspired in bunnyfetch by Rosettea. <br>
https://github.com/Rosettea/bunnyfetch.

## Dependencies
1. Python
2. Make

## Instructions
1. Clone the repo locally with ` git clone `
2. Change directory to the folder with ` cd `
3. Install with  `make install`
3.1.  Uninstall with `make uninstall`
4. Run as  `kfetch`

## What this fetch can do?
>   Set custom ascii arts
>   Enable/Disable default and custom ascii art
>   Randomize colors in both information and default ascii art 
>   Reorganize information to your like
>   Randomize expressions in bunnies faces
>   Customize (add or remove/ enable or disable) random phrases
>   Customize glyphs in information display

## Future plans
> - make a real aur package when it's stable

## author notes
This fetch tool uses colors of your system to colorize the output.
I recommend to use a colorscheme for your Xresources file, like rosepine, dracula, nord, etc. <br>
It also may look weird depending of the font, monospace looks weird. I recommend nerd fonts or some other.<br> 
https://www.nerdfonts.com/font-downloads

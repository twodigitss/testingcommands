# Bunnydelic
The purpose of this fetch alternative is creating a fetch tool that does not need to be "static" all the time, 
printing just one set of colors and ascii art staying as the same until you change it manually. <br>
This tool offers to randomize the color set, randomizes the ascii art (if you do not change it manually of course)
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
1. Clone the repo locally with ` git clone `<br>
2. Change directory to the folder with ` cd `<br>
3. Install as binary with  ` make install `<br>
4. Run as  ` bunnydelic `<br>
5. For uninstalling use ` make uninstall `<br>

## Supported distros
- Arch linux and derivated distros
- Debian and derivated distros
- Redhat and derivated distros (hopefully)

## What this fetch can do?
>   - Set custom ascii arts<br>
>   - Enable/Disable default and custom ascii art<br>
>   - Randomize colors in both information and default ascii art <br>
>   - Reorganize information to your like<br>
>   - Randomize expressions in bunnies faces<br>
>   - Customize (add or remove/ enable or disable) random phrases<br>
>   - Customize glyphs in information display<br>

## Future plans
+ make an aur package when it's stable
+ make an deb package when it's stable

## Author notes
why this name? well, it has bunnies and "delic" comes from "psychodelic", 
whose colors are always changing, and also match for an old username i had.<br>
This fetch uses colors of your system to colorize the output.
I recommend to use a colorscheme for your Xresources file, like rosepine, dracula, nord, etc. <br>
It also may look weird depending of the font, monospace looks weird. I recommend nerd fonts or some other.<br> 
https://www.nerdfonts.com/font-downloads




# Added more customization options to display the information!!
## this version added:<br>
- Indent the phrase to left instead right on custom ascii arts<br>
- Enable/disable color randomization<br>
- If color randomization is disabled, you can set the order of the colors manually<br>
<br>
## Previous (base) options:<br>
- Enables/disables random phrases at the top of the fetch<br>
- Enables/disables every ascii art<br>
- Enables/Disables icons from NerdFonts.com<br>
- Shows your distro icon instead the stock one in "icons" list<br>
- Selection of icons that are shown alsongside display variable<br>
- Select the order of the information that is displayed<br>
- Prioritize "custom" or "default" ascii art<br>


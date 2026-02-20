# sway-screenshot
Easily screenshot an area or the entire screen with a hotkey by adding a line to the sway config file located at ~/.config/sway/config.


## requirements
 slurp for selecting an area within the screen and grim for taking the screenshot  `sudo apt install slurp grim`
 


## instructions
Add `bindsym $mod+Shift+s exec grim -g "$(slurp)"` to your config file to take a screenshot of an area which saves to the home dir by default. 
  
uncomment or add the line `bindsym Print exec grim` to enable a full screen screenshot with PrtScn key, feel free to this key to whatever you prefer.

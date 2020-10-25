# fluxbox-dotfiles
 


#steps to clone my rice 

1. git clone https://github.com/siduck76/fluxbox-dotfiles.git

2. go to the cloned repo folder and you'll see a fluxbox folder which contains all the fluxbox config. put this folder in your home folder  and rename fluxbox to .fluxbox .

<img src = "https://raw.githubusercontent.com/siduck76/fluxbox-dotfiles/main/fluxbox-config.png">

3. go to the .fluxbox folder and the files startup / keys are important , be sure to chmod +x the startup file and remove all the uneeded bloat from it except exec-fluxbox thing .

<img src = "https://raw.githubusercontent.com/siduck76/fluxbox-dotfiles/main/keys.png">

4. go to the keys file and find this line , edit it for your use . 

5. I use nord gtk theme https://github.com/EliverLara/Nordic , you need to install these fonts https://github.com/siduck765/jwm-realdots/tree/main/material%20fonts for the icons to appear on the polybar , put those fonts in your ~/.local/share/fonts folder and do fc-cache -fv in terminal.

6. install polybar from your distro's repo and put my polybar folder into ~/.config folder , go to the polybar folder and be sure to chmod +x all the scripts in it.
  btw my systemtray on my poly is kinda messed up so goodluck in editing my dirty config.
  
7. copy the my rofi folder in ~/.config and install these icons for rofi https://github.com/OrancheloTeam/oranchelo-icon-theme .
  
<img src ="https://raw.githubusercontent.com/siduck76/fluxbox-dotfiles/main/e.png">

my ricing/linux community https://t.me/DE_WM (telegram group) 

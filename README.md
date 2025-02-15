# mpv_Livewallpaper
Simple Live Wallpaper 


1 . INSTALLATIONS 

    sudo snap install mpv

2 . FIND YOUR DESKTOP ID 

    xwininfo -name Desktop

3 . RUN 

    mpv --no-osc --no-osd-bar --quiet --screen=0 --wid=0x1400013 --loop yourfile.*

  * Replace --wid="your desktop id"
  * * Replace your file by the "name.mp4" 

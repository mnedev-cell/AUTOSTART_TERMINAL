# AUTOSTART_TERMINAL

## Setup autostart
```shell
  sudo chmod +x  /home/pi/dir/autostart
```
```shell
 sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
```
```shell
    @xset s noblank
    @xset s off
    @xset -dpms
    @lxterminal --command="/home/pi/dir/autostart"
```

# xfreeRDP-usage

Official code site: https://www.freerdp.com/

### Usage:
```bash
# in ubuntu install from official ubuntu repo with
sudo apt install freerdp2-x11
# or freerdp2-wayland ... depending on your OS setting

# use with:
# use /f for full screen or /m for multiple screen
xfreerdp /f /clipboard /u:myUserName /v:ipOrHostname /drive:Downloads,/home/myLinuxUser/Downloads /microphone:sys:pulse /sound:sys:pulse

# or add password directly to command NOT RECOMMENDED by adding /p:myPassword
```

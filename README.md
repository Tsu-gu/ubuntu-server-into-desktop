`sudo apt update && sudo apt upgrade`
I recomend installing the firefox snap first. and then running `sudo snap refresh --hold firefox`. This is broken but I kinda understand why nobody thought about servers being turned into desktops.
# Near the end it will try to restart the snapd service which will take 5 minutes. Let it do its thing.
`sudo apt install ubuntu-desktop`

# disables the server networking service, your first boot will take 2 minutes.
`systemctl disable systemd-networkd.service`

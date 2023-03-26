# Create nodejs-server user
```sh
sudo useradd --system --create-home --user-group nodejs-server
cat /etc/passwd

sudo usermod --append --groups nodejs-server mihai
sudo usermod --append --groups nodejs-server jenkins
cat /etc/group

sudo passwd --status nodejs-server
sudo passwd --lock nodejs-server
sudo passwd --status nodejs-server
sudo cat /etc/shadow

sudo reboot
```

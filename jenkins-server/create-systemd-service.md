# Create backend-app systemd service
```shell
cd /etc/systemd/system/
sudo touch nodejs-backend-app.service
```
- Open **/etc/systemd/system/nodejs-backend-app.service** and copy the content from local **resources/nodejs-backend-app.service** file. Command `sudo nano nodejs-backend-app.service`


# Start backend-app systemd service
```shell
sudo systemctl start nodejs-backend-app.service
systemctl status nodejs-backend-app.service
sudo systemctl stop nodejs-backend-app.service

sudo systemctl enable nodejs-backend-app.service
```

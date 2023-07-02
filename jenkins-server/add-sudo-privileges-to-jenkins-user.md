# Create a sudoer file for jenkins user
```sh
cd /etc/sudoers.d

sudo touch jenkins-user-privileges
sudo nano jenkins-user-privileges
```

- Open **jenkins-user-privileges** and copy the content from local **resources/jenkins-user-sudo-privileges** file.

# Apply sudo privileges
```sh
sudo chmod 440 jenkins-user-privileges
sudo visudo --check
```

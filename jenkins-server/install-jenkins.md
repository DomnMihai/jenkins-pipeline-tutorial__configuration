# Install Jenkins
Download pages:
- [Jenkins](https://www.jenkins.io/download)
- [Ubuntu/Debian](https://pkg.jenkins.io/debian-stable)

```sh
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee /usr/share/keyrings/jenkins-keyring.asc > /dev/null

echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt-get update
sudo apt-get install fontconfig
sudo apt-get install jenkins
```

# Add the user to the jenkins group
```sh
cd /var/lib/jenkins/
ls -l --almost-all

whoami
groups

sudo usermod --append --groups jenkins mihai
cat /etc/group

sudo reboot
groups
```

# Jenkins plugins
- Rebuilder

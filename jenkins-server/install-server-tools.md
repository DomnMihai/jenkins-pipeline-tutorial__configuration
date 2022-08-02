# Install java
```sh
sudo apt install openjdk-11-jdk
java --version
```

# Install git
Download [page](https://git-scm.com/download/linux)
```sh
sudo add-apt-repository ppa:git-core/ppa
sudo apt update
sudo apt install git

git --version
```

# Install Node.js
Download [page](https://nodejs.org/en/download/)
```sh
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs

node --version

npm --version
sudo npm install --location=global npm
npm --version
```

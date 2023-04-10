# Create folders for nodejs-backend app
```shell
cd /home
cd nodejs-server/

sudo mkdir backend-application
cd backend-application

sudo mkdir backups
```

# Clone nodejs-backend from GitHub
```shell
sudo git clone https://github.com/DomnMihai/jenkins-pipeline-tutorial__nodejs-backend.git
sudo mv jenkins-pipeline-tutorial__nodejs-backend nodejs-backend
```

# Change folders' owner
```shell
cd /home/nodejs-server/
sudo chown --recursive nodejs-server:nodejs-server backend-application
```

# Run the server
```shell
sudo npm install --omit=dev
cat package.json
npm run start
```

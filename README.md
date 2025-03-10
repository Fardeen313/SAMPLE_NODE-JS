# Node Hello World

Simple node.js app that servers "A Monk in Cloud"

Great for testing simple deployments on Cloud

## Step 1: Install NodeJS and NPM using nvm
Install node version manager (nvm) by typing the following at the command line.
sudo yum install curl -y
```bash

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
Activate nvm by typing the following at the command line.

```bash
source ~/.bash_profile
```

Use nvm to install the latest version of Node.js by typing the following at the command line.

```bash
nvm install node
```

Test that node and npm are installed and running correctly by typing the following at the terminal:

```bash
node -v
npm -v
```

## Step 2: Install Git and clone repository from GitHub
To install git, run below commands in the terminal window:

```bash

yum install git -y
```

Just to verify if system has git installed or not, please run below command in terminal:
```bash
git — version
```

This command will print the git version in the terminal.

Run below command to clone the code repository from Github:

```bash
git clone https://github.com/CloudTechDevOps/sample_nodejs_on_Ec2.git
```

Get inside the directory and Install Packages

```bash
cd nodejs-on-ec2
npm install
```

Start the application
To start the application, run the below command in the terminal:

```bash
npm start
```

or if we want to run application into process manager pm2
```bash
npm install -g pm2
pm2 start index.js --name node-app




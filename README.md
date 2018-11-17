


BASIC SETUP (needs Node8)

## installing Node

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash


## booting the server

npm install   (# See Note A)

npm run dev

npm run webpack #(to build the website files)

# 0xBitcoin Web

The uncompiled code for 0xbitcoin.org, 0xbitcoin.github.io

### Commands

npm run dev
    Starts a local dev server to serve the website as a test

npm run webpack
     Compiles the website and outputs the static files in  /public


###  Note A: If you have problems, install these dependencies


npm install -g node-gyp

sudo apt-get install build-essential

You may need to do..
sudo apt-get install python2.7
npm config set python python2.7

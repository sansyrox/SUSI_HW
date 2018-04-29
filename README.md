# SUSI_HW
<p>This is repo is made for the SUSI_HW that is to be run on a Raspberry Pi.</p>

## Getting Started
Login to your raspberry pi and do the following steps
<br>
To install NodeJS 
* cd /tmp
* wget https://nodejs.org/dist/v8.2.1/node-v8.2.1-linux-armv7l.tar.xz
* tar xfv node-v8.2.1-linux-armv7l.tar.xz
* cd node-v8.2.1-linux-armv7l
* sudo cp -R * /usr/local/
* Clone this repo
To test the app
* npm install
* export DISPLAY=:0
* npm run electron-dev
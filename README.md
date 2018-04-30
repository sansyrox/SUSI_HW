# SUSI_HW
<p>This is repo is made for the SUSI_HW that is to be run on a Raspberry Pi.</p>

## Hardware Requirements
* A RaspberryPi 3 model B (recommended) or any other with external wifi card
* Usb Mouse and keyboard
* Usb Mic
* External Speaker with 3.5 mm jack

## Tech Stack
* ReactJs
* ElectronJs
* Mocha
* Travis 
* Codacy

## Getting Started
Login to your raspberry pi and do the following steps
<br><br>
To install NodeJS 
* cd /tmp
* wget https://nodejs.org/dist/v8.2.1/node-v8.2.1-linux-armv7l.tar.xz
* tar xfv node-v8.2.1-linux-armv7l.tar.xz
* cd node-v8.2.1-linux-armv7l
* sudo cp -R * /usr/local/
* Clone this repo
<br><br>
To test the app
<br><br>
* npm install
* export DISPLAY=:0
* npm run electron-dev

## Viewing in Headless mode
* Enable VNC and SSH in your RasPi's settings.
* To emulate the complete environment:<br>
 Download [VNC](https://www.realvnc.com/en/connect/download/viewer/) on your phone/pc
* To just get SSH download [PUTTY](https://www.putty.org/) {only tested on Windows Platform}
* Install accordingly and enter your RaspPi's ip address in VNC viewer

## Viewing in Browser
* If you just want to view the app in your external device's browser 
* Start the RasPi app.
* You check it on your browser at `https://IP_ADDRESS/3000` <br>
where IP_ADDRESS is your internal IP Address
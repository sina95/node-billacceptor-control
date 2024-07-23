# Node.js EBDS Bill Acceptor Control

Script for testing and controlling an EBDS bill acceptor written in Node.js.

## Installation Procedure

##### 1. Download the script:
```sh
git clone https://github.com/sina95/node-billacceptor-control.git
```

##### 2. Install Node.js if you haven't installed:
Follow the instructions [here](https://nodejs.org/en/learn/getting-started/how-to-install-nodejs) to install Node.js.

##### 3. Go to the script directory and install packages:
```sh
cd node-billacceptor-control
npm install
```

##### 4. Connect the bill acceptor to your PC with a USB cable, and ensure the port is correct in `example.js` (default is `/dev/ttyUSB0`).

##### 5. Run:
```sh
node example.js
```

Modify scripts based on `/lib/commands`.

Happy testing! :)

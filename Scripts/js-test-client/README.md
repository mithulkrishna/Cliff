# JS Test Client

Acts as a GATT server and client for exchanging chat messages with real iOS nodes.

## Usage

First make sure to have Node.js 8.9.0 installed (you can use a version manager like `n` for this), then run

```
sudo apt-get install bluetooth bluez libbluetooth-dev libudev-dev
```

to install the system dependencies, finally

```
npm install
```

to install the npm dependencies. Now you can either...

* Launch the GATT server/peripheral using `sudo npm run server`
* Launch the GATT client/central using `sudo npm run client`






### Step 1) Install parity (or geth) and start (or continue) syncing


Make sure for this demonstration to open the Webpack's localhost port for CORS requests.

`parity --rpccorsdomain="http://localhost:3000"`


### Step 2) Start the web application first

```terminal
cd app
npm install
npm start
```

Webpack will run a local server of our React app.

### Step 3) Boot up Electron

```terminal
cd Electron
npm install
npm start
```



Overview:
![alt tag](https://github.com/CraigglesO/Parity-UI/blob/master/img/overview.png)

After five minutes (and eventually to login), you are required to enter a simple passcode [0 0 0 0 for now]:
![alt tag](https://github.com/CraigglesO/Parity-UI/blob/master/img/pass.png)

Syncing:
![alt tag](https://github.com/CraigglesO/Parity-UI/blob/master/img/syncScreen.png)

Syncing in the dock:
![alt tag](https://github.com/CraigglesO/Parity-UI/blob/master/img/downloadDock.png)

When the sync is complete:
![alt tag](https://github.com/CraigglesO/Parity-UI/blob/master/img/complete.gif)

Loading screen and failure to connect example:
![alt tag](https://github.com/CraigglesO/Parity-UI/blob/master/img/skeleton.gif)

License Page:
![alt tag](https://github.com/CraigglesO/Parity-UI/blob/master/img/license.png)

![web-bluetooth image](/assets/battery_service.png)

### Web-Bluetooth Demo: Battery Service

This simple demo uses the Web-Bluetooth library to connect to a device broadcasting a Battery Service characteristic and reads it's battery level.

#### Requirements
------------
Web-Bluetooth is behind an experimental flag in Chrome 45+. Go to `chrome://flags/#enable-web-bluetooth` to enable the flag. Restart Chrome and you should be good to go.

Experiment with web-bluetooth on the following devices.
  * Linux      
  * ChromeOS
  * Android

#### Installation
------------
First, fork this repo and then run:

```
$ npm install
$ npm run demo
$ open http://localhost:3000
```
#### Use
------------
Connect to any device by its Name or Name Prefix.
This demo uses four of the many methods in the [web-bluetooth](http://sabertooth-io.github.io/) library.

##### `new BluetoothDevice()`
##### `connect()`
##### `disconnect()`
##### `getValue()`

For more information, visit the web[web-bluetooth](http://sabertooth-io.github.io/) docs.

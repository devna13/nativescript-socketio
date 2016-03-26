# nativescript-socketio
# Usage
```
tns plugin add https://github.com/triniwiz/nativescript-socketio
```
Set connection string and options then connect
```js
var SocketIO = require('nativescript-socketio');
SocketIO.init(url,opts);
```

Send data to the server
```js
SocketIO.emit(event,data)
```
Listen for data 
```js
SocketIO.on(event,callback)
```

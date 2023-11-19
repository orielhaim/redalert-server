---
sidebar_position: 1
---

# Node.JS example
```js
const io = require('socket.io-client');
const socket = io('https://redalert.auto-host.xyz');

socket.on("alert", function(data) {
  console.log(data);
});
```
<h1>Display TCP/IP Network Configuration</h1>

<h3>Installation</h3> 

```javascript 
cd your_node_project
npm install network-info
```

<h3>Usage</h3>

```javascript
var network = require('network-info');

network.displayNetworkInfo();

//prints network info to console

//Network information...

//Network type: _____
//Local IP: _____
//IP Version: _____
//Mac address v6: _____
//Subnet Mask: _____

```

## License
[MIT](https://choosealicense.com/licenses/mit/)

<p align="center">
  <img src="https://github.com/ethereumjs/testrpc/blob/ganache-cli/resources/icons/ganache-cli-128x128.png?raw=true">
</p>

## mzStudio
Welcome to mzStudio

### Installation

create a package.json
```Bash
npm init
```

 install Express
```Bash
npm install express --save
```

create a nodeapp.js
```
const express = require('express')
const app = express()

app.get('/', (req, res) => res.send('Hello World!'))

app.listen(3000, () => console.log('Example app listening on port 3000!'))
```

<pre>
	node nodeapp.js
</pre>

express-generator
```Bash
npm install express-generator -g
```

```
express -h
```



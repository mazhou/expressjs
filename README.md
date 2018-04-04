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

```
express --view=pug myapp
cd myapp
npm install
DEBUG=myapp:* npm start
```

http://localhost:3000
```
.
├── app.js
├── bin
│   └── www
├── package.json
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets
│       └── style.css
├── routes
│   ├── index.js
│   └── users.js
└── views
    ├── error.pug
    ├── index.pug
    └── layout.pug

7 directories, 9 files
```

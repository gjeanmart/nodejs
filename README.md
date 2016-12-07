# nodejs

## Prerequisite
Install NodeJS and NPM

## Initialize a project
```
$ mkdir app

$ cd app

$ npm init .

$ npm install --save express
```


## First app
### REST API
1. Create a file *server.js*

```
var express = require('express')
 
var app = express()
 
app.get('/api', function(req, res) {
  res.json({api: "This is your api."})
})
 
app.listen(3000)
```


### Run the app
```
$ cd app

$ nodejs server,js
```



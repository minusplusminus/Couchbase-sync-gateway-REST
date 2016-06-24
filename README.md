#  [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]

> Couchbase Mobile Sync Gateway REST wrapper
Initial code from: https://github.com/luismanuel001/sync-gateway



## Install

```sh
$ npm install --save sync-gateway
```


## Usage

```js

var SyncGateway = new (require('sync-gateway'))('http://[USERNAME]:[PASSWORD]@[HOSTNAME]:[PORT]',[DATABASE]);

```

## functions 

### get([docId])
```js
SyncGateway.get(docId)
    .then(function (response) {

    })
    .catch(function (err) {
        
    })
```
### post([doc])
```js
SyncGateway.post(doc)
```

### put([doc])
```js
SyncGateway.put(doc)
```
### del([doc])
```js
SyncGateway.del(doc)
```

### purge([docIds],[channels])
```js
SyncGateway.purge(docIds,["*","info","!"])
```

## License

MIT © [Luis Manuel](https://github.com/luismanuel001)


[npm-image]: https://badge.fury.io/js/sync-gateway.svg
[npm-url]: https://npmjs.org/package/sync-gateway
[travis-image]: https://travis-ci.org/luismanuel001/sync-gateway.svg?branch=master
[travis-url]: https://travis-ci.org/luismanuel001/sync-gateway
[daviddm-image]: https://david-dm.org/luismanuel001/sync-gateway.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/luismanuel001/sync-gateway

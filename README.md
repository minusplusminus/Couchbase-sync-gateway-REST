#  [![Dependency Status][daviddm-image]][daviddm-url]

> Couchbase Mobile Sync Gateway REST wrapper
Initial code from: https://github.com/luismanuel001/sync-gateway



## Install

```sh
$ npm install Couchbase-sync-gateway-REST
```


## Usage

```js

var SyncGateway = new (require('sync-gateway'))('http://[USERNAME]:[PASSWORD]@[HOSTNAME]:[PORT]',[DATABASE]);

```

## functions 

### get(docId)
```js
SyncGateway.get(docId)
    .then(function (response) {

    })
    .catch(function (err) {
        
    })
```
### post({doc})
```js
SyncGateway.post(doc)
```

### put({doc})
```js
SyncGateway.put(doc)
```
### del({doc})
```js
SyncGateway.del(doc)
```

### purge([docIds],[channels])
```js
SyncGateway.purge(docIds,["*","info","!"])
```

## License

MIT © [Luis Manuel](https://github.com/luismanuel001)


[npm-image]: https://badge.fury.io/js/minusplusminus/Couchbase-sync-gateway-REST.svg
[npm-url]: https://npmjs.org/package/minusplusminus/Couchbase-sync-gateway-REST
[travis-image]: https://travis-ci.org/minusplusminus/Couchbase-sync-gateway-REST.svg?branch=master
[travis-url]: https://travis-ci.org/minusplusminus/Couchbase-sync-gateway-REST
[daviddm-image]: https://david-dm.org/minusplusminus/Couchbase-sync-gateway-REST.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/minusplusminus/Couchbase-sync-gateway-REST.svg

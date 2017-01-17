# bitty-tracker

#### Create http - udp - ws bittorrent tracker whitout database based on [![bittorrent-tracker][bittorrent-tracker]]

[bittorrent-tracker]: https://github.com/feross/bittorrent-tracker

![bittytracker](http://www.axlcash.com/wp-content/uploads/2014/09/torrent-trackers-300x300.png)

## install

```
npm install bitty-tracker
```

## usage

To start a BitTorrent tracker server, create index.js and add this:

```js
var bitty = require('bitty-tracker')
```

The http server will handle requests for the following paths: `/announce`, `/scrape`. Requests for other paths will not be handled.

## command line

Easily start a tracker server:

```sh
$ node index.js --start -h localhost
http server listening on 8000
udp server listening on 8000
ws server listening on 8000
```

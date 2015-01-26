# passport-memcached

[![Build Status](https://travis-ci.org/relekang/passport-memcached.svg)](https://travis-ci.org/relekang/passport-memcached)
[![Coverage Status](https://coveralls.io/repos/relekang/passport-memcached/badge.png)](https://coveralls.io/r/relekang/passport-memcached)

```bash
npm install --save passport-memcached
```

## Usage

If not any of the [MemJS environment variables](https://github.com/alevy/memjs/blob/master/README.md#configuration) are set `127.0.0.1:11211` will be used for memcached.

```javascript
var passportMemcached = require('passport-memcached');

passport.serializeUser(passportMemcached.memcachedSerializeUser);
passport.deserializeUser(passportMemcached.memcachedDeserializeUser);

```

--------
MIT © Rolf Erik Lekang

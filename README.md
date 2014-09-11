# passport-memcached

[![Build Status](https://travis-ci.org/relekang/passport-memcached.svg)](https://travis-ci.org/relekang/passport-memcached)
[![Coverage Status](https://coveralls.io/repos/relekang/passport-memcached/badge.png)](https://coveralls.io/r/relekang/passport-memcached)

```bash
npm install --save passport-memcached
```

## Usage

```javascript
var passportMemcached = require('passport-memcached');

passport.serializeUser(passportMemcached.memcachedSerializeUser());
passport.deserializeUser(passportMemcached.memcachedDeserializeUser());

```

--------
MIT © Rolf Erik Lekang

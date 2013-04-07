[![Build Status](https://secure.travis-ci.org/rkatic/p.png)](http://travis-ci.org/rkatic/p)

#P

A simple Promises/A+ library.

- Implements a subset of the the [Q](https://github.com/kriskowal/q) API.
- Passing the [Promises/A+ Compliance Test Suite](https://github.com/promises-aplus/promises-tests).
- Cross-Browser, Node.js and RequireJS ready.
- Small.
- [Fast](http://jsperf.com/wqfwewefewrw).

##API

P implements a subset of the [Q](https://github.com/kriskowal/q) API with few **differences**.

- `P(val)`
- `P.defer()`
- `P.all(promises)` (array **or object** of promises)
- `P.onerror`
- `P.nextTick(callback)`
- `deferred.promise`
- `deferred.resolve(value)`
- `deferred.reject(reason)`
- `promise.then(onFulfilled, onRejected)`
- `promise.done(onFulfilled, onRejected)`
- `promise.spread(onFulfilled, onRejected)`
- `promise.timeout(ms)`
- `promise.delay(ms)`

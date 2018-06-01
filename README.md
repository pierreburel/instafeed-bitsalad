instafeed.js
============

This is a fork of [instafeed.js](https://github.com/stevenschobert/instafeed.js) which uses [BitSalad.co](http://www.bitsalad.co) API instead of Instagram. User feed only.

**NOTE**: I created this fork to fix existing projects using Instafeed since Instagram changed their API. You'd better use [BitSalad.co](http://www.bitsalad.co)'s [salad-spinner](https://github.com/bitsalad/salad-spinner) if you're starting from scratch.

## Installation

Install this fork with NPM instead of the original `instafeed.js` package:

```sh
npm install https://github.com/pierreburel/instafeed.js
```

[See the original README](https://github.com/stevenschobert/instafeed.js) for more informations.

## Requirements

You need to create an account on [BitSalad.co](http://www.bitsalad.co).

## Basic Usage

[See the original README](https://github.com/stevenschobert/instafeed.js). Only notable changes :

* values for `clientId` and `userId` options can be found in your [BitSalad.co](http://www.bitsalad.co) feed url: `https://api2.bitsalad.co/feeds/<cliendId>?ids=<userId>` ;
* no more `accessToken` option since [bitsalad.co](http://www.bitsalad.co) doesn't need one ;
* no more `get` option (only user), same for `tagName`, `locationId` ;
* no more pagination (`next()` and `hasNext()` methods) ;
* no more tests since I'm too lazy.

## Credits

* [Steven Schobert](https://github.com/stevenschobert)

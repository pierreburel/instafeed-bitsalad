instafeed-bitsalad
============

A drop-in solution for using [Instafeed](https://github.com/stevenschobert/instafeed.js) with [BitSalad.co](http://www.bitsalad.co) API instead of Instagram. User feed only.

**NOTE**: I created this fork to fix existing projects using Instafeed since Instagram changed their API. You'd better should use [BitSalad.co](http://www.bitsalad.co)'s [salad-spinner](https://github.com/bitsalad/salad-spinner) if you're starting from scratch.

## Installation

instafeed-bitsalad is available on NPM:

```sh
npm install instafeed-bitsalad
```

[See the original README](https://github.com/stevenschobert/instafeed.js) fo more informations.

## Requirements

You need to create an account on [BitSalad.co](http://www.bitsalad.co).

## Basic Usage

[See the original README](https://github.com/stevenschobert/instafeed.js). Only notable changes :

* values for `clientId` and `userId` options can be found in your [BitSalad.co](http://www.bitsalad.co) feed url: `https://api2.bitsalad.co/feeds/<cliendId>?ids=<userId>` ;
* no more `accessToken` option since [bitsalad.co](http://www.bitsalad.co) doesn't need one ;
* no more `get` option (only user), same for `tagName`, `locationId` ;
* no more tests since I'm too lazy.

## Credits

* [Steven Schobert](https://github.com/stevenschobert)

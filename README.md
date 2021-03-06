socialshareprivacy-community
============================

This is a community version of the [Heise.de socialshareprivacy plugin](http://www.heise.de/extras/socialshareprivacy/).

Download
--------
Download the [latest build of socialshareprivacy-community](https://github.com/webmaster128/socialshareprivacy-community/blob/master/download.zip?raw=true).

Goal
----
The purpose of this community fork is to have a socialshareprivacy plugin
which is compatible with the current jQuery version.

Requirements
------------
* jQuery 1.7+

Features
--------
* Tested with jQuery 1.7 – 1.10
* Tested with jQuery 2.0
* Compatible with IE7 (In theory. Layout is broken and Facebook doesn't seem to support IE7 with their social plugin)
* Full support for German and English

Privacy Note
------------
* This plugin is pointless when you include jQuery via Google's CDN.

Changelog
---------

### Version 1.5 (to be released)
* Replace jQuery .live() calls by .on() calls. [e14a0a8d0d](https://github.com/webmaster128/socialshareprivacy-community/commit/e14a0a8d0d8a462d3e81377e2b6877b38d7952c5)
* Replace native JSON.parse call by jQuery.parseJSON in order to be able to remove browser switch.
  [8070ae54f3](https://github.com/webmaster128/socialshareprivacy-community/commit/8070ae54f391e9392b4979f82658746a08b70c98) and
  [dc35454a7c](https://github.com/webmaster128/socialshareprivacy-community/commit/dc35454a7c6d0bd14b1bc8335a8a1bcf29cdb8c6)
* Full support for German and English

### Version 1.4
* Use original source from [Heise](http://www.heise.de/extras/socialshareprivacy/)

Build download zip package
--------------------------
```
$ cd ./download
$ yui-compressor jquery.socialshareprivacy.js > jquery.socialshareprivacy.min.js
$ zip -9 --exclude *~ -r ../download.zip ./
$ cd ..
```


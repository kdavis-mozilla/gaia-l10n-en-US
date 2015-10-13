gaia-l10n-en-US
================

A locale for building the en-US speech model language package for Firefox OS.


Installation
------------

    git clone https://github.com/kdavis-mozilla/gaia-l10n-en-US.git


Usage
-----

First, checkout `gaia`

``kdaviss-MacBook-Pro:Code kdavis$ git https://github.com/mozilla-b2g/gaia.git``

then remove all apps from the gaia apps directory

```
  kdaviss-MacBook-Pro:Code kdavis$ cd gaia
  kdaviss-MacBook-Pro:gaia kdavis$ rm -fr apps/*
```

then checkout `langpack-builder`

```
  kdaviss-MacBook-Pro:gaia kdavis$ cd ..
  kdaviss-MacBook-Pro:Code kdavis$ git clone https://github.com/l20n/langpack-builder.git
```

and follow the installation instructions for `langpack-builder`

Finally, use the `langpack-builder` to build the en-US speech model language package for Firefox OS 

```
  kdaviss-MacBook-Pro:langpack-builder kdavis$ ./bin/lp-builder.js --gaia /path/to/gaia --locale en-US /path/to/gaia-l10n/gaia-l10n-en-US
```

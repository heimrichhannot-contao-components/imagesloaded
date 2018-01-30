# imagesLoaded Contao component

Shim repository for [imagesLoaded](https://github.com/desandro/imagesloaded) as [Contao Component](https://github.com/contao-components/installer).

## Install

```
composer require heimrichhannot-contao-components/imagesloaded
```

## Internal
 
Update Library:

```
svn export https://github.com/desandro/imagesloaded.git/trunk/imagesloaded.pkgd.min.js ./dist --force
svn export https://github.com/desandro/imagesloaded.git/trunk/imagesloaded.pkgd.js ./dist --force
```
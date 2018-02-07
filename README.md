# imagesLoaded Contao component

[![Latest Stable Version](https://poser.pugx.org/heimrichhannot-contao-components/imagesloaded/v/stable)](https://packagist.org/packages/heimrichhannot-contao-components/imagesloaded)
[![Total Downloads](https://poser.pugx.org/heimrichhannot-contao-components/imagesloaded/downloads)](https://packagist.org/packages/heimrichhannot-contao-components/imagesloaded)

Shim repository for [imagesLoaded](https://github.com/desandro/imagesloaded) as [Contao Component](https://github.com/contao-components/installer).

## Install

```
composer require heimrichhannot-contao-components/imagesloaded
```


## Config

Add the following to your config (keep keys to prevent double integration):

### Contao 4

```
$GLOBALS['TL_JAVASCRIPT']['huh_components_imagesloaded'] = 'assets/masonry/imagesloaded.pkgd.min.js|static';
```

### Contao 3
```
$GLOBALS['TL_JAVASCRIPT']['huh_components_imagesloaded'] = 'assets/components/masonry/imagesloaded.pkgd.min.js|static';
```


## Internal
 
Update Library:

```
svn export https://github.com/desandro/imagesloaded.git/trunk/imagesloaded.pkgd.min.js ./dist --force
svn export https://github.com/desandro/imagesloaded.git/trunk/imagesloaded.pkgd.js ./dist --force
```
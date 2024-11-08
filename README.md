<h1 align="left">Hyvä Compatibility Module for Mulberry Warranty Extension</h1>
This repository hold the module to add support for Mulberry Warranty extension to Hyvä. This module has a dependency on the Mulberry Warranty Magento 2 module.
https://github.com/mulberryHQ/mulberry-m2-extension/

## About Mulberry Warranty
The Mulberry Warranty extension allows the addition of an additional warranty product to an original Magento product.

## Installation

1. Install the module using composer:

```bash
composer config repositories.getmulberry/mulberry-m2-extension git git@github.com:MulberryHQ/mulberry-m2-extension-hyva-compatibility.git
composer require getmulberry/mulberry-m2-extension-hyva-compatibility
```

2. Enable the module:

```bash
bin/magento module:enable Mulberry_WarrantyHyvaCompatibility
```

3. Upgrade the database:

```bash
bin/magento setup:upgrade
```

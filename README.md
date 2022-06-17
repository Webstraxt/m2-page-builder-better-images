# Page Builder Better Images

Magento 2 module allowing you to specify explicit dimensions and loading behaviour on Page Builder images. Allows different dimensions to be specified for desktop and mobile images.

---

To install:  
* `composer require webstraxt/m2-page-builder-better-images`
* `php bin/magento module:enable Webstraxt_PageBuilderBetterImages`
* `php bin/magento setup:upgrade`

---

To use:
* Insert an image using Page Builder and populate the new fields for Explicit Width (Desktop), Explicit Height (Desktop), Explicit Width (Mobile), Explicit Height (Mobile), and Image Loading. These fields will be rendered as HTML `width`, `height`, and `loading` attributes on the image.

---

Copyright (C) 2022 Webstraxt Limited

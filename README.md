# OpenMage (Magento 1.9) - GDPR newsletter consent

Adds a GDPR consent checkbox with a popup (your own HTML text) to the newsletter subscription form in OpenMage / Magento 1.9. The subscribe button stays disabled until the visitor agrees. The consent is also shown in the admin newsletter subscriber grid.

A second template (`newsletter_quickshop.phtml`) adds the same popup next to the "Sign up for newsletter" checkbox in checkout.

No jQuery or other libraries are needed.

## Installation

```sh
composer require degriz/openmage-gdpr-newsletter
```

You need `magento-hackathon/magento-composer-installer` with `"magento-root-dir"` set in your shop's `composer.json`. Alternatively, copy the `app/` and `skin/` folders into your OpenMage root.

## Configuration

Go to System > Configuration > Degriz Gdpr Newsletter settings. There you set the checkbox text, the link text and the popup HTML.

Translations: en_US, sl_SI.

## License

MIT. Made by [Degriz](https://www.degriz.net).

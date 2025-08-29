# Product Generate Price Weight Barcode


Print product barcode stickers on ZPL printer
=============================================

This module adds a wizard on product.product form view which allows to generate and print a product barcode sticker on a ZPL printer (such as Zebra GC420, GK420, ...). It can print:

* regular product barcode stickers. These stickers will show:
  * product name
  * product price
  * EAN13 or EAN8 barcode

* price/weight barcode stickers. These stickers will show:
  * product name
  * weight (the wizard asks for this info)
  * price
  * price per kg
  * EAN13 barcode

It also allows to generate a private barcode for products without barcode. For that, you must configure the sequence "private.product.barcode". This sequence must be configured to produce 12 digits (for EAN13) or 7 digits (for EAN8) ; the checksum will be added automatically.

This module has been written by Alexis de Lattre from Akretion
<alexis.delattre@akretion.com>.
    

## Installation

```bash
pip install odoo-bringout-akretion-product_print_zpl_barcode
```

## Dependencies

This addon depends on:
- product
- barcodes
- stock

## Manifest Information

- **Name**: Product Generate Price Weight Barcode
- **Version**: 16.0.1.0.0
- **Category**: Extra Tools
- **License**: AGPL-3
- **Installable**: True

## Source

Custom addon from bringout-akretion vendor, addon `product_print_zpl_barcode`.

## License

This package maintains the original AGPL-3 license from the addon.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Reports: doc/REPORTS.md
- Security: doc/SECURITY.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md

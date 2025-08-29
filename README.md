# Akretion Odoo Packages

This repository contains **2** Odoo packages from Akretion vendor.

## About Akretion

Akretion is a recognized vendor in the Odoo ecosystem, providing specialized addons and customizations.

## Packages Included (2 packages)

- **odoo-bringout-akretion-account_invoice_margin** - Account Invoice Margin
- **odoo-bringout-akretion-product_print_zpl_barcode** - Product Print Zpl Barcode


## Installation

Install any package from this collection:

```bash
# Install from local directory
pip install packages/akretion/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/akretion/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/akretion/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
akretion/
├── odoo-bringout-akretion-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## License

Each package maintains its original license as specified by Akretion.

## Support

For support with these packages, please refer to the original Akretion documentation or community resources.

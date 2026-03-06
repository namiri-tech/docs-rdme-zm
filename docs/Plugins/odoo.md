---
title: DigiTax Zambia Odoo Plugin
hidden: true
---

# Odoo ZM plugin

## Prerequisites

1. An Odoo instance (that you can install a custom module).
    - Odoo.sh
    - Self-host Odoo
1. Sign up on [digitax.tech]
1. Create a ZM profile
1. Create a business
1. Create an API Key

[digitax.tech]: https://digitax.tech

## Set up

Install custom module on Odoo: DigiTax Smart Invoice Integration

![Odoo-custom-module]

Navigate to Settings

![Settings]

Navigate to Users & Companies > Companies

![Companies]

Select the company you want to integrate with

![Select company] 

Click "DigiTax Zambia" on the company page

![Company page]

Enter your API Key, then click "Save Manually" icon.

![Plugin settings]

After saving, you can start using the plugin.

## DigiTax Zambia Odoo plugin page

From the DigiTax Zambia Odoo plugin page, you can:

- Test Connection
- Fetch Items
- Fetch Imports
- Fetch Customers
- Fetch Suppliers
- Fetch Purchases

![Test Connection]

[Odoo-custom-module]: ../../docs-assets/install-zm-odoo-plugin.png
[Settings]: ../../docs-assets/select-settings.png
[Companies]: ../../docs-assets/select-companies.png
[Select company]: ../../docs-assets/select-company.png
[Company page]: ../../docs-assets/one-company.png
[Plugin settings]: ../../docs-assets/plugin-settings.png
[Test Connection]: ../../docs-assets/test-plugin-connection.png

## Invoice

To create an invoice, one needs one or more items and optionally a customer or supplier.

On Odoo, a customer or supplier is required. The plugin doesn't send customer or supplier information to DigiTax, hence to ZRA, if a TIN is not provided.

### Inventory (Items)

On Odoo, you can create items by fetching them from DigiTax. You can do this from the [DigiTax Zambia Odoo plugin page](#DigiTax-Zambia-Odoo-plugin-page).

You can create new items or manage them from the Inventory page.

Navigate to Inventory > Products > Products

![Inventory]

![Products]

Select one product

![Product]

![Product-Page]

Navigate to the Digitax Zambia module of the item

![Product-DigiTax-Zambia]

[Inventory]: ../../docs-assets/select-inventory.png
[Products]: ../../docs-assets/select-products.png
[Product]: ../../docs-assets/products.png
[Product-Page]: ../../docs-assets/product.png
[Product-DigiTax-Zambia]: ../../docs-assets/product-digitax.png

### Customers

On Odoo, you can create customers by fetching them from DigiTax. You can do this from the [DigiTax Zambia Odoo plugin page](#DigiTax-Zambia-Odoo-plugin-page).

You can create new customers or manage them from the Customers page, in Invoicing module.

Navigate to the Invoicing page.

![Invoicing]

Click Customers > Customers

![Customers]

Select one customer

![Customer]

Navigate to the Digitax Zambia module of the customer

![Customer-DigiTax-Zambia]

[Invoicing]: ../../docs-assets/select-invoicing.png
[Customers]: ../../docs-assets/select-customers.png
[Customer]: ../../docs-assets/customers.png
[Customer-Page]: ../../docs-assets/customer.png
[Customer-DigiTax-Zambia]: ../../docs-assets/customer-digitax.png

### Invoicing

Next, navigate to the Invoicing page.

![Invoicing]

Click New to create a new invoice.

![New-Invoice]

Add one or more products to the invoice.

![Add-Products]

After adding products, you may attempt to confirm the invoice without selecting a customer. This will result in an error.

![Attempt to confirm invoice without customer]

Add customer, then click "Confirm".

![Add-Customer]

The invoice will now be confirmed and saved.

![Invoice Confirmed]

Click "Post to DigiTax" to send the invoice to DigiTax.

![Invoice Posted]

[Invoicing]: ../../docs-assets/select-invoicing.png
[New-Invoice]: ../../docs-assets/new-invoice.png
[Add-Products]: ../../docs-assets/invoice-add-product.png
[Attempt to confirm invoice without customer]: ../../docs-assets/invoice-customer-required.png
[Add-Customer]: ../../docs-assets/invoice-add-customer.png
[Invoice Confirmed]: ../../docs-assets/invoice-confirmed.png
[Invoice Posted]: ../../docs-assets/invoice-posted.png

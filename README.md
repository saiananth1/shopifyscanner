# Shopify Store Scanner & Exporter

A Chrome extension to detect Shopify storefronts, count public products and collections, view searchable tables, and export store data to CSV.

## Overview

Shopify Store Scanner & Exporter helps ecommerce teams, SEO teams, developers, merchandisers, and auditors quickly inspect publicly available Shopify storefront data.

Open any Shopify storefront, click the extension, and view product and collection counts. You can also open detailed table views, search through results, export products or collections separately, and view scan activity logs.

## Features

* Detect Shopify storefronts
* Count public products
* Count public collections
* View products in a searchable table
* View collections in a searchable table
* Export products to CSV
* Export collections to CSV
* Save the latest scan locally to avoid repeated rescanning
* View scan status and activity logs
* Handles slower stores and rate limits with safer retry behavior

## Use cases

* Ecommerce audits
* SEO research
* Shopify migration planning
* Product catalog checks
* Collection structure review
* Competitive storefront analysis
* Merchandising QA
* Storefront testing and validation

## Privacy

This extension only reads publicly available storefront information from the website selected by the user.

It does not access or collect:

* Passwords
* Payment information
* Checkout information
* Customer account information
* Private Shopify admin data
* Cookies
* Personal communications
* Email content
* Location data
* Health information
* Financial information

Scan results are stored locally in the user’s browser and are not sent to any external server controlled by the developer.

Privacy Policy: https://saiananth1.github.io/shopify-store-scanner-exporter.github.io/privacy.html

## Permissions

The extension uses the following Chrome permissions:

### activeTab

Used to identify the current tab when the user opens the extension. The extension scans only the website the user is currently viewing.

### tabs

Used to open the Products table, Collections table, and Status & Logs pages in a new browser tab when the user clicks those buttons.

### storage

Used to save the latest scan result locally in the user’s browser. This prevents the extension from rescanning the same store every time the popup is opened.

### host permissions

The extension requests access to `http://*/*` and `https://*/*` so it can scan Shopify storefronts on any user-selected domain.

The extension only reads publicly available storefront information. It does not access private admin pages, passwords, payment data, checkout information, cookies, or customer account data.

## Data handling

* Data is processed locally in the browser.
* Scan results are saved locally for convenience.
* CSV exports are downloaded directly by the user.
* No scanned data is sold, shared, rented, or transferred to third parties.
* No external analytics or tracking service is used.

## Chrome Web Store

This extension is designed for the Chrome Web Store as a Shopify storefront scanner and CSV export tool.

## Support

For support or questions, contact:

`sai@scribbleminds.com`

## License

All rights reserved.

# Snowdog Alpaca ACM

## Extension purposes

Add layouts and templates for custom content types of Blackbird ACM module used by Alpaca

## Installation

`composer require snowdog/module-alpaca-acm`

`blackbird/contentmanager` module is required, see the official site: https://www.advancedcontentmanager.com/

## Usage

We use custom content types for slider component and blog section based on layout and templates in this module.

After module installation, import 3 content types from `imports` folder via Magento 2 admin panel under `Content` > `Content Manager` > `Content Types` > `Import Content Types` button

You can overwrite templates and extend layout XML inside your theme (in `Snowdog_Acm` folder).

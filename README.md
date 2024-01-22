# madeofzero Shopify + Tailwind Boilerplate code

Simple Boilerplate code to get started with Shopify &amp; tailwind CSS

## How to run?

1. Extract your Shopify theme in `/theme` folder.
2. Run `npm install` in root folder.
3. Add new classes in your liquid file using the prefix `tw-`(in order to avoid confilicts however you can update this setting in `tailwind.config.js` > `prefix: false`).
4. Add `{{ 'styles.css' | asset_url | stylesheet_tag }}` in your `theme.liquid` in order to pull tailwind css file in your shopufy code.

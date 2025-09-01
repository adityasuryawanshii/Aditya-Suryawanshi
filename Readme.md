# Shopify Custom Theme Test - Aditya Suryawanshi

This repository contains my submission for the Ecomexperts Shopify developer hiring test.  
The task was to create custom Shopify theme sections based on provided Figma designs and implement dynamic product display and popup functionality.


## Custom Section Descriptions

### Banner Section 
- Displays a promotional banner with editable heading, subheading, button text, and link.
- Fully built from scratch with Liquid schema for dynamic content editing.
- Includes CSS styling and vanilla JavaScript for button hover animations.

### Product Grid Section
- Shows a grid of up to 6 selectable products.
- Each product displays image, title, price, and links to its page.
- Configured using blocks in the Liquid schema for easy product selection from admin.

## Methods and Shopify Schema

- Used Shopify Liquid templating language to build sections.
- Created **schema** JSON blocks with `"name"`, `"settings"`, and `"blocks"` fields for user-editable options.
- Used Liquid objects and filters to dynamically render product information.
- Applied vanilla JavaScript inside sections for interactivity, avoiding jQuery per test instructions.


## Troubleshooting and Issues Faced

- Restarted Shopify CLI multiple times to ensure theme changes were synced.
- Cleared browser cache and used incognito mode to avoid stale data in theme editor.
- Validated JSON schema with online validators to prevent syntax errors.
- Despite correct code and schema, custom sections did not appear in Shopify theme editor due to an unknown issue.


## Final Notes

- All required sections were implemented following the test requirements and pushed to this public GitHub repo.
- Due to Shopify theme editor caching or schema recognition issues, custom sections could not be added visually in the admin interface.
- As a fallback, code can be integrated manually or previewed via Shopify CLI locally.
- I am available to provide further explanation or live demo if needed.


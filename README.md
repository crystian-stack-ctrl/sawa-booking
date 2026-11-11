# Sawa — booking requests made simple

A responsive product landing page, working WhatsApp booking handoff, and local demo dashboard for an early-stage booking product.

## Preview

Open `index.html` in a browser. Select **Business dashboard** in the navigation to customize the demo business and see booking requests. No build tools or packages are needed. Google Fonts need internet; system font fallbacks are included.

## Configure and try it

1. Open `dashboard.html` and set a business name, business type/location, WhatsApp number, and services (one per line).
2. Save the profile.
3. Return to `index.html`, submit a booking request, and continue to WhatsApp.
4. Open the dashboard in the same browser to see the saved request.

The WhatsApp phone value must be international digits only (Kenya example: `2547...`). The Join the pilot form prepares a signup request for the founder WhatsApp number in the page script. The owner must press Send in WhatsApp; this prototype does not store leads centrally.

## Prototype limits

This is a browser-only prototype. Settings and requests are saved in local storage on one browser/device; they do not sync across devices, create separate public links for each business, verify availability, or send reminders. It is not ready for real customer records. A production version needs a backend, accounts, a database, secure access controls, and an approved messaging integration.


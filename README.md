# homelocator-media

Website listing and article images for https://www.homelocator.net, already branded with the Home Locator logo.

- Public on purpose: every image here is already public on the website.
- Nothing else goes in this repo. No customer data, no documents, no config.
- The site does not link here directly. It loads `https://homelocator-gateway-production.up.railway.app/img/gh/<name>.jpg`, and the gateway caches the file from this repo.
- Listing images are written by `scripts/brand-images.mjs` in the AIOS repo. Article covers also use its shared `brand-images-filter.mjs` stamp. Do not rename or delete files: the site's database points at them by name.

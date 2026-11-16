# BENGALVOLT store website

A responsive Bengali storefront based on the supplied homepage reference. The reference image supplies the hero, category, product, and family photos in `assets/`. The site includes product search, category filters, price display, photo upload, add/edit/delete controls, and JSON product backup and restore.

## Run locally

Open `index.html` in a recent browser. Product edits are stored in that browser's local storage.

## Publish with GitHub Pages

1. Create a GitHub repository and upload `index.html`, `README.md`, and the `assets` folder (keep the folder structure intact).
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and `/ (root)`, then save.
4. GitHub will show the published site URL in the Pages settings.

You can update the site by editing these files and pushing the changes to the repository. GitHub Pages serves the website, but it does not provide a product database or secure admin login. Product changes made in the browser are local to that browser/device. Use **পণ্য ব্যাকআপ ডাউনলোড** to export a JSON backup, then **ব্যাকআপ থেকে আনুন** to restore it in the same browser or another browser. To share live product updates across devices and visitors, connect the page to a database and add authenticated admin access.

## Before launch

- The business contact number in `index.html` is +8801707944636.
- Replace demo products, prices, and descriptions with the real catalog using **⚙ পণ্য পরিচালনা**.
- Product photos uploaded in the page are saved in that browser, not committed to the GitHub repository.


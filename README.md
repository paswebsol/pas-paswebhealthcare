# Pas and Pasweb Healthcare — GitHub Pages

This is a static website. The homepage is `index.html`; no build step, package manager, or server-side runtime is required.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload **all files in this folder** (`index.html` and `.nojekyll`) to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. The public address will appear in the Pages settings.

## Contact form

The enquiry form currently sends through FormSubmit to the email address already configured in the page. FormSubmit may require the recipient to confirm/activate the address the first time a message is sent. Test the form after deployment.

## Images and fonts

The African-user pulse-oximeter image is embedded directly in `index.html`. Other product photographs and Google Fonts are loaded from their external hosts, so visitors need an internet connection to see those resources. If you want a fully self-contained/offline site, download and store those assets in this repository and update their paths.

## Local preview

Open `index.html` in a browser. The contact form is designed to send from the deployed website; test actual delivery after publishing.

# VPC Peering Live Demo (Static Website)

This is a static interactive website for the local AWS VPC Peering simulation. It does not deploy AWS resources or send real network packets.

## Publish for free with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `vpc-peering-live-demo`.
2. Upload `index.html` to the repository root and commit the file.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. The Pages screen will show the website URL.

The URL will usually look like `https://YOUR-USERNAME.github.io/vpc-peering-live-demo/`. Replace `YOUR-USERNAME` with your GitHub username and use the actual URL shown by GitHub Pages.

GitHub Pages supports static HTML websites. It does not run Python backend code; this demo's interactive behavior is implemented in browser JavaScript.

## Important disclosure
Label this as a local simulation in your submission. The interactive ping results are illustrative, not real AWS connectivity evidence.

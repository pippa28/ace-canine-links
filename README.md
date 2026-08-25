# Ace Canine Instagram Bio Page

A simple static landing page for GitHub Pages.

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `ace-canine-links`.
2. Upload `index.html` and the `assets` folder from this package.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will give you a public URL such as `https://yourusername.github.io/ace-canine-links/`.

## Use a subdomain such as links.ace-canine.com

In GitHub Pages settings, enter `links.ace-canine.com` as the custom domain.
Then, at the DNS provider for ace-canine.com, create a CNAME record:

- Name/Host: `links`
- Target/Value: `YOUR-GITHUB-USERNAME.github.io`

After DNS has propagated, enable **Enforce HTTPS** in GitHub Pages.

## Editing products

Each product is a card in `index.html`. Update the product name, description, image URL and destination link as needed.

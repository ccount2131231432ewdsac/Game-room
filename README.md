# Ready Room

A small game night lobby for seeing who is around, setting your status, chatting, and using voice while you play on another device.

## Files

- `index.html` — the complete website. Its HTML, styles, and app code are in one file.
- `assets/` — a place for local CSS, JavaScript, or other files if you add them later.
- `images/` — a place for local pictures if you add them later.

The current site does not need local images or extra CSS/JavaScript files. It loads its fonts from Google Fonts and PeerJS from a public CDN, so those features need an internet connection.

## Publish with GitHub Pages

1. Put the contents of this folder in the top level of your GitHub repository. Keep `index.html` at the top level.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select your branch and `/(root)` and save.

GitHub's current instructions are in [Configuring a publishing source for GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

The site uses browser storage to remember your display name on that device. It does not have user accounts or a server-side sign-in system.

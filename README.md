# Hatirla Developer Site

This folder is a minimal static developer site for Google Play and AdMob verification.

Required public URLs after hosting:

- `https://YOUR_GITHUB_USERNAME.github.io/app-ads.txt`
- `https://YOUR_GITHUB_USERNAME.github.io/privacy-policy.html`

For AdMob app-ads.txt verification, set the same GitHub Pages URL as the developer website in Google Play Console.

Recommended free hosting:

1. Create a public GitHub repository named `YOUR_GITHUB_USERNAME.github.io`.
2. Upload the contents of this `developer-site` folder to the repository root.
3. Open repository Settings > Pages.
4. Set Source to `Deploy from a branch`.
5. Select branch `main` and folder `/root`, then save.
6. Use the published GitHub Pages URL in Play Console as the developer website.

app-ads.txt content:

```txt
google.com, pub-5607392451920269, DIRECT, f08c47fec0942fa0
```

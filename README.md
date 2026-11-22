# plannerytemplates.github.io

The Plannery Templates website: home page, privacy policy (needed for the Pinterest developer app), and image hosting for Pinterest pins.

## Put it online (about 15 minutes, once)

1. Create a GitHub account with the username **plannerytemplates**.
2. Create a new **public** repository named exactly **plannerytemplates.github.io**.
3. On the repository page click **Add file → Upload files**, drag in everything from this folder (index.html, privacy.html, style.css, README.md and the fonts, img and pins folders), and click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment" choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
5. After a minute or two, open https://plannerytemplates.github.io and https://plannerytemplates.github.io/privacy.html to check both load.

Before uploading, replace `YOUR-EMAIL@example.com` in privacy.html (two places) with the email you want people to contact.

If the username plannerytemplates is taken, use another name and change every address below to match.

## Addresses for the Pinterest developer form

- Company website: https://plannerytemplates.github.io
- Privacy policy: https://plannerytemplates.github.io/privacy.html

## Hosting pin images

Upload pin images into the **pins** folder (Add file → Upload files, then open the pins folder first). Each image is then online at:

    https://plannerytemplates.github.io/pins/<file name>.jpg

In pins.py set:

    BASE_URL = "https://plannerytemplates.github.io/pins/"

Open one image address in your browser before uploading pins.csv to Pinterest, to check it loads. New uploads can take a minute or two to appear.

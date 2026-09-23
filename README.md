# Tangent

A free, installable learning feed. There are no accounts, ads or servers: progress is saved on each person's phone, and the app works offline once it's opened.

## What's in the folder

- `index.html` — the whole app
- `cards.js` — the card library (81 cards). Edit this file to add more.
- `sw.js` — the service worker, which makes the app work offline and installable
- `manifest.webmanifest` — the app name, colours and icons
- the `.png` files — the app icons

## Put it online from your phone (GitHub Pages, free)

1. Tap the zip in Claude to download it, then open it in the Files app. Tapping the zip unzips it into a folder.
2. In Safari, go to github.com and create a free account.
3. Tap **+**, then **New repository**. Name it `tangent`, set it to **Public**, and tap **Create repository**.
4. Tap **uploading an existing file**. Select all 9 files from the unzipped folder (not the folder itself), then tap **Commit changes**.
5. Go to **Settings**, then **Pages**. Under Branch, choose **main** and **/ (root)**, then tap **Save**. If Settings is hidden, use the **aA** button in Safari and choose **Request Desktop Website**.
6. After a minute or two, the app is live at `https://YOUR-USERNAME.github.io/tangent/`.

## Install it on a phone

- **iPhone:** open the link in Safari, tap Share, then tap **Add to Home Screen**.
- **Android:** Chrome shows an **Install** prompt, or you can install from the Topics button in the app.

## Add cards or push an update

Edit `cards.js` on GitHub by tapping the file, then the pencil icon. The comment at the top explains each field. After any change, also edit `sw.js` and bump `tangent-v1` to `tangent-v2`, or installed copies will keep showing the old cards.

## Later: app stores

Wrap this same set of files with Capacitor (capacitorjs.com). You'll need a computer, or a cloud build service, at that stage.

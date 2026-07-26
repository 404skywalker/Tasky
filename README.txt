TASKY — Install as an app on your phone
========================================

This folder is a complete, installable web app (PWA). Once it's online at a
link, you can add it to your iPhone or Android home screen and it behaves like
a native app: its own icon, full screen, and it works offline.

WHAT'S IN HERE (don't rename these files):
  index.html            the app
  manifest.webmanifest  makes it installable
  sw.js                 offline support
  icon-192.png / icon-512.png / apple-touch-icon.png / favicon.png  the app icons

------------------------------------------------------------
STEP 1 — Put it online (free, ~2 minutes)
------------------------------------------------------------
Easiest option — Netlify Drop:
  1. On a computer, go to:  https://app.netlify.com/drop
  2. Sign in (free — you can use email or a Google/GitHub login).
  3. Drag THIS WHOLE FOLDER (the unzipped "tasky-app" folder) onto the page.
  4. Wait a few seconds. You'll get a link like  https://something.netlify.app
  5. That link is your app. Open it to check it works.

Alternative — GitHub Pages (if you already use GitHub):
  1. Create a new repository, upload all the files in this folder.
  2. Settings > Pages > Deploy from branch > main > /(root) > Save.
  3. Your app appears at  https://YOURNAME.github.io/REPO/

------------------------------------------------------------
STEP 2 — Install on your phone
------------------------------------------------------------
iPhone / iPad (use Safari):
  1. Open your link in Safari.
  2. Tap the Share button (square with an up arrow).
  3. Tap "Add to Home Screen", then "Add".
  4. Tasky now has an icon on your home screen and opens full screen.

Android (use Chrome):
  1. Open your link in Chrome.
  2. Tap the three-dot menu (top right).
  3. Tap "Install app" (or "Add to Home screen"), then confirm.
  4. Tasky is installed like a normal app.

------------------------------------------------------------
GOOD TO KNOW
------------------------------------------------------------
- Works offline after the first load.
- Your tasks are stored privately on each device. Adding a task on your phone
  won't show up on your computer automatically.
- To move data between devices: on one device use the (…) menu > Export backup,
  then Import backup on the other.
- Want your phone and computer always in sync automatically? That needs a small
  cloud account added to the app — just ask.

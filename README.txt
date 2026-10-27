Narwhal's Favorite Teams — Android PWA files

Upload these files to the ROOT of your existing GitHub Pages repository, keeping the icons folder:
- index.html (replace the current page)
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

After GitHub Pages deploys the commit, open the HTTPS site in Chrome on Android. Use ⋮ > Install app (or Install and create shortcut) > Install.

The app shell can open from cache, but live records, schedules, and remote photos need an internet connection. The page refreshes sports data while it is open; it does not run updates in the background.

PlantPower installable PWA package

Upload the contents of this folder to the ROOT of your GitHub repository:
- index.html
- manifest.webmanifest
- sw.js
- icons/plantpower-192.png
- icons/plantpower-512.png

Keep the folder structure exactly as shown. GitHub Pages must be enabled for the main branch and / (root).
Then open https://sash-based.github.io/plantpower-dev/ in a supported browser.

Install:
- Chrome/Edge on desktop or Android: use the Install PlantPower button or browser install icon/menu.
- iPhone/iPad: open in Safari, tap Share, then Add to Home Screen. iOS uses Apple's web-app installation flow.

This is an installable Progressive Web App (PWA), not a native App Store application. The PWA icon and standalone display are provided by the manifest. The service worker caches the app shell for repeat/offline loading.

Security:
The HTML contains API integration placeholders/configuration. Never publish real API secrets in a public repository. Browser-visible keys can be copied. Use a secure server-side proxy for private keys.

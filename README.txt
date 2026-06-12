NETWORK iPhone offline package

Use on iPhone:
1. Host this folder at an HTTPS URL. GitHub Pages, Netlify, Cloudflare Pages, or any private HTTPS server is enough.
2. Open the HTTPS URL in Safari on the iPhone while online.
3. Tap Share -> Add to Home Screen -> Add.
4. Launch it once from the Home Screen while still online. This lets sw.js cache the app.
5. Turn on Airplane Mode and open it again from the Home Screen.

Important:
- Do not open index.html from the Files app and expect reliable offline app behavior. iOS file preview is not a PWA runtime.
- Data is stored in Safari/WebKit localStorage for this exact origin. Changing the URL/domain creates a separate database.
- Use Export (encrypted) regularly. iOS can remove website storage under pressure or if site data is cleared.
- The Google Fonts dependency was removed so the app has no network dependency after install.

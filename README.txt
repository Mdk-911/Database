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


UPDATE: This version adds Sources → Bulk. Paste names separated by spaces, commas, or new lines, choose shared defaults, then tap Add all.


Update: Excel-safe bulk paste
- Bulk add now defaults to Excel cells / rows mode.
- First-name + last-name values stay together.
- Split-by-spaces mode is still available only when you want one-word codenames.


Update (v6): Tap a name in Places to re-root the tree to that branch (shows only it and its descendants). Use "Full tree" in the selection bar to return to the whole network. Expand all / Collapse now keep the current root. Pinch or the -/+ buttons zoom in to read crowded names.


Update (v8): Per-principal balances. Each principal source now has its own purse. Deposits are made to a chosen principal. Main balance on Command = sum of all principal balances (plus any Unallocated legacy deposits). Payments to a source draw from its principal's purse, and over-spend warnings now reference that principal. Older deposits made before this update show under "Unallocated" until you re-deposit them to a principal.


Update (v9): Multi-select pay. On Sources, tap "Select" to enter select mode (all branches auto-expand and a checkbox appears on every member). Tick any members, then "Pay selected" in the bottom bar pays them all at once — either each member's monthly amount or one flat amount to each. Per-principal purses are checked and you're warned before any purse goes negative. Tap "Done" to leave select mode.

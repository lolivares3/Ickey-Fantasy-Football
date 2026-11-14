# Fantasy Football Central — GitHub Pages website

A complete static multi-page fantasy football league website. No subscriptions, database, build tools, or paid hosting needed. **All included team and score data is fictional demo content.**

## Pages
- `index.html` — homepage, leaders, standings preview, announcements
- `standings.html` — full league standings
- `matchups.html` — weekly matchups
- `teams.html` — team profiles
- `news.html` — announcements
- `rules.html` — league rules

## Customize
1. Open `data.js` in a text editor.
2. Change `name`, `season`, `week`, and `announcement`.
3. Replace the demo `teams`, `matchups`, `news`, and `rules` entries with your real league details.
4. Each team needs a unique `id`; matchup `home` and `away` values must match team IDs.
5. Save and upload the updated `data.js` to GitHub. Changes will appear on all pages after GitHub Pages deploys.
6. For appearance, edit `style.css` (the `--accent` variable changes the yellow highlight).

## Publish free with GitHub Pages
1. Sign in at https://github.com and create a **public** repository, e.g. `fantasy-football`.
2. Choose **Add file → Upload files** and upload the **contents** of this folder (not the ZIP and not the enclosing folder). Commit the changes.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**; select `main` and `/ (root)`, then Save.
5. After deployment, visit `https://YOUR-USERNAME.github.io/fantasy-football/`.
6. Share the link with anyone. Visitors don't need GitHub accounts.

For a repository named `YOUR-USERNAME.github.io`, the site instead uses `https://YOUR-USERNAME.github.io/`.

## Preview locally
Open `index.html` in a browser; the links work without a server.

## Notes
- This is a **read-only public site**. There is no login, commissioner editor, live ESPN/Yahoo sync, or automatic score refresh.
- Data is updated by editing `data.js` and committing it to GitHub.
- Do not publish private league information without permission.

# ⚾ Blue Crew Showdown — GitHub Pages setup

Get your league live in about 2 minutes:

1. Go to **github.com** and sign in, then tap **+ → New repository**.
2. Name it `blue-crew-showdown`, keep it **Public**, and create it.
3. On the new repo page, tap **Add file → Upload files**, upload **index.html**, and commit.
4. Go to the repo's **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then **Save**.
5. Wait a minute or two, then your league is live at:

   `https://YOUR-USERNAME.github.io/blue-crew-showdown/`

Send that link to your friends — that's it. Everyone joins on their own phone, drafts a $100 squad of 6 Dodgers, and the leaderboard scores automatically from real MLB games (July 30 through the end of the regular season).

Notes:

- All picks and standings are stored in a shared cloud database, so it doesn't matter who hosts the page — everyone sees the same league.
- The page remembers who you are on your own phone. If someone switches devices, they can type their same name and tap "resume."
- Scoring updates live from MLB's public stats API every time someone opens the Leaderboard tab.

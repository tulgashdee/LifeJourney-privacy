# LifeJourney: privacy policy

The public privacy policy page of the LifeJourney Android app, served by GitHub Pages at https://tulgashdee.github.io/LifeJourney-privacy/

The app's code lives in `D:\Aaw\LifeJourney` (github.com/tulgashdee/LifeJourney); its `docs/PLAY_STORE.md` gives this address to Google Play.

## Files

- `index.html`: the policy, one page with no scripts, readable on phones and in dark mode.
- `icon.png`, `favicon.png`: the app icon (from `brand/icon-512.png` in the app's repo).

## Publish it (first time)

The GitHub repository `tulgashdee/LifeJourney-privacy` exists and this folder is its clone (`D:\Aaw\LifeJourney-privacy\LifeJourney-privacy`).

1. Fill in the contact email: replace both `REPLACE-WITH-CONTACT-EMAIL` in `index.html` with the address people should write to (the same one as the Play listing), and commit.
2. Push with GitHub Desktop (or `git push -u origin main`).
3. On GitHub: the repository's **Settings → Pages → Build and deployment**: Source "Deploy from a branch", branch **main**, folder **/ (root)**, Save. The repository must be public (or Pages enabled for it).
4. After a minute or two, open https://tulgashdee.github.io/LifeJourney-privacy/ on a phone and check it shows the policy.

## Changing it

Edit `index.html`, change the effective date at the top, commit and push; Pages updates by itself. If the app ever sends anything new off the phone (crash reports, analytics, an account), change this page and the Data safety answers in Play before that version ships.

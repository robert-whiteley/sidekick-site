# sidekick-site

Static website for the Sidekick Android app: https://sidekick.sashy.ai, served by GitHub Pages (`CNAME`). Licence: Apache-2.0, like the app.

Pages are generated from the app repo — do not edit the HTML by hand:

    cd ../sidekick && node scripts/build-site.mjs ../sidekick-site

The privacy page comes from `sidekick/docs/privacy-policy.md` (the same text the app shows). Commit and push; Pages redeploys.

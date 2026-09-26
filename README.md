# atmchat

SubX room #20 — Find a nearby ATM. Public map data · Maps outbound. (preview).

Static site. `siteId` is `atmchat`. Custom domain in `CNAME` is `atmchat.com`. Preview banner and `noindex` stay on.

Deploy `main` from `/` on GitHub Pages (Cloudflare DNS next). Factory shell talks to Firebase project `subx-skins` (fetches `firebase-web-config.json`; no API keys in this repo).

## Outside this repo

- Firestore allowlist for `siteId` `atmchat` (CTO).
- Cloudflare zone + NS flip for `atmchat.com` (CTO).

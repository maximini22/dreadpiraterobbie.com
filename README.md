# dreadpiraterobbie.com

Static landing page for the Dread Pirate Robbie album site.

## Publish later (not done from this workspace)

- GitHub account: `maximini22`
- New repo: `maximini22/dreadpiraterobbie.com`
- Enable GitHub Pages from the repository root (default branch, `/`)
- Custom domain: `dreadpiraterobbie.com` (`CNAME` in this folder)
- Point the domain's DNS at GitHub Pages after the repo exists

This folder was built locally only. Nothing here has been pushed.

## Sources

Stream buttons, socials, and the press release are taken from the HTTrack
capture of dreadpiraterobbie.com. HTTrack rewrote external links into local
paths and appended a 4-character hash to some filenames (`playlist772c.html`,
`187006495244ba.html`). Those hashes were removed when restoring the https
URL. Query strings that were still in the saved `href` were kept.

Known issues left as captured, not guessed:

- Spotify on this page is album `01mIow264j4s7H4sNDfPPr` plus the `si` parameter
  from the capture. That album id is the known-wrong release (If It Wasn't For
  Satoshi). It is not used on the robbiep.net music-links page.
- Apple Music keeps the truncated `?ls` query from the capture.
- The only Instagram `href` in the capture is the login wall
  (`/accounts/login/`), not a profile.
- Email is `team@jeremylegalrecords.com`, decoded from the Cloudflare
  email-protection link in the capture.

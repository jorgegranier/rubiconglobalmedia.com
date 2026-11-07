# rubiconglobalmedia.com — static site (not published)
1. Create a public GitHub repo (e.g. rubicon-site), push index.html, style.css, CNAME.
2. Settings → Pages → Deploy from branch `main` / root. Custom domain: rubiconglobalmedia.com. Tick "Enforce HTTPS" once the cert issues.
3. GoDaddy → Domains → rubiconglobalmedia.com → DNS:
   - A records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 (delete GoDaddy parking A record / forwarding)
   - CNAME `www` → <github-username>.github.io
   - Keep existing MX records (email) untouched.
4. Optional: verify the domain in GitHub Settings → Pages (TXT record) to prevent takeover.
Before launch: no public email on the site by design (contact routes to the LinkedIn company page). Chris Albrecht's bio approved; Secuoya confirmed active; BTF Media copy kept minimal.

## Design source
The look comes from the Rubicon deck "IP Play - Main 3.4.25": Instrument Serif and Instrument Sans (Google Fonts), white/black with orange #FE5D2F, yellow #EEFF41, teal #228AAC, maroon #890E17 and amber #FFB441. The two abstract stripe artworks in assets/ are taken from the deck. There's no logo file in the deck; the wordmark is set in Instrument Serif.

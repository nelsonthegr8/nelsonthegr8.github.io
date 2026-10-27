# Website (GitHub Pages)

Source for **https://nelsonthegr8.github.io/** — the support, privacy and
marketing pages App Store Connect and AdMob need.

| URL | Used for |
|---|---|
| `/idle-trader-tycoon/` | App Store "Marketing URL" |
| `/idle-trader-tycoon/support/` | App Store "Support URL" (required) |
| `/idle-trader-tycoon/privacy/` | App Store "Privacy Policy URL" (required) and in-app Settings |
| `/app-ads.txt` | AdMob seller verification — must be at the domain root |

## Publishing

`app-ads.txt` only counts at the root of the domain, so this must be a GitHub
**user site**: a repo named `nelsonthegr8.github.io` whose `main` branch root
holds these files (Settings → Pages → Deploy from branch → `main` / root).

Published to the `nelsonthegr8/nelsonthegr8.github.io` repo (copy these files to
its root). Support currently goes to that repo's GitHub Issues; swap in an
email address on the support page when there is one. `app-ads.txt` isn't
published yet — put the real line from AdMob (Apps → app-ads.txt) in it first.

The in-app links live in `lib/core/config/app_links.dart`.

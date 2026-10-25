# my-mobile-apps-links.github.io

Developer website for apps by NAZLIM, published with GitHub Pages at <https://my-mobile-apps-links.github.io/>.

- `app-ads.txt` – authorized ad sellers ([IAB app-ads.txt](https://iabtechlab.com/app-ads-txt/)). AdMob crawls it
  from the root of the developer website listed in the App Store / Google Play, so it must stay at
  <https://my-mobile-apps-links.github.io/app-ads.txt>. Add one `google.com, pub-…, DIRECT, f08c47fec0942fa0` line per AdMob
  publisher account (one line covers every app in that account).
- `privacy-policies/` – app privacy policies, served at <https://my-mobile-apps-links.github.io/privacy-policies/>:

  | App | Policy |
  |---|---|
  | Live Cameras (iOS & Android) | <https://my-mobile-apps-links.github.io/privacy-policies/live-cameras/> |
  | Shake to DND (Android) | <https://my-mobile-apps-links.github.io/privacy-policies/shake-to-dnd/> |
  | Walkie Talkie Pro (iOS & Android) | <https://my-mobile-apps-links.github.io/privacy-policies/walkie-talkie-pro/> |

  To add an app: create `privacy-policies/<app-name>/index.html` (copy an existing one, it uses `../style.css`)
  and link it from `privacy-policies/index.html` and the root `index.html`.

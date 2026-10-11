# starnova-io.github.io

Root GitHub Pages site for the `starnova-io` organisation.

## Why this repo exists

AdMob requires `app-ads.txt` at the **root of the developer-website domain** listed
on each app's store page. Project pages such as
`starnova-io.github.io/sayly-legal/`, `starnova-io.github.io/sentenceray-legal/`
and `starnova-io.github.io/hearth-island/` all share this domain, so this single
file at the domain root authorises every app in the organisation:

```
google.com, pub-3847722511208491, DIRECT, f08c47fec0942fa0
```

Without it AdMob leaves those apps on "Yêu cầu xem xét / Verify app to lift limit"
and ad serving stays limited.

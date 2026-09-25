# D7 Labs

D7 Labs is my indie label for publishing Android apps on Google Play. This repo is the D7 Labs public website: an app page, a privacy policy and terms of service for each app, plus a support contact.

**Live site:** https://darsh-7.github.io/d7labs/

## Apps

Both apps are in testing on Google Play and haven't been publicly released yet.

| App | Package | Pages |
|-----|---------|-------|
| **XO Game**: tic-tac-toe with an AI opponent and a two-player mode, offline | `com.d7labs.xo` | [About](https://darsh-7.github.io/d7labs/xo-game/) · [Privacy](https://darsh-7.github.io/d7labs/xo-game/privacy/) · [Terms](https://darsh-7.github.io/d7labs/xo-game/terms/) |
| **Financify**: tracks income, expenses and savings goals, with on-device receipt scanning | `com.d7labs.financify` | [About](https://darsh-7.github.io/d7labs/financify/) · [Privacy](https://darsh-7.github.io/d7labs/financify/privacy/) · [Terms](https://darsh-7.github.io/d7labs/financify/terms/) |

## Site structure

```
index.html                 Home page: app cards and contact
style.css                  Shared stylesheet (light and dark themes)
xo-game/index.html         XO Game app page
xo-game/privacy/index.html XO Game privacy policy
xo-game/terms/index.html   XO Game terms of service
financify/index.html       Financify app page
financify/privacy/...      Financify privacy policy
financify/terms/...        Financify terms of service
```

The site is plain static HTML and CSS with no build step. GitHub Pages redeploys it on every push to the default branch. Each page lives in its own folder as `index.html`, so every URL ends in a clean `/`, and the Play Console can link straight to the policy URLs.

## Contact

Questions, bug reports and privacy requests: [d7labs77@gmail.com](mailto:d7labs77@gmail.com)

---
Maintained by [Mostafa Ahmed (darsh-7)](https://github.com/darsh-7)

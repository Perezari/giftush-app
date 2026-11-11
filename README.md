# giftush-app

The web pages of Giftush, the iPhone wallet for gift cards (the app is in the private repository Giftush), served by
GitHub Pages at https://perezari.github.io/giftush-app/:

- `index.html`: the support page, which App Store Connect asks for and the app's settings link to.
- `privacy.html`: the privacy policy.
- `stores.json`: where each provider's gift cards are taken. The app ships a copy and fetches this one once a day, so a
  change here reaches every iPhone without a new version; its `updated` date must be later than the copy in the app.

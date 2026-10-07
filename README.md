# Banking-App-UI
# Aura Bank

An interactive mobile banking prototype: welcome, sign-in and dashboard screens in plain HTML, CSS and JavaScript. No build step and no dependencies.

## Demo credentials

- PIN: `482915`
- SMS code: `123456` (tap "Use SMS code")
- Face ID: tap the button, it verifies after a short scan

## What works

- Tap the card stack on the welcome screen to shuffle cards
- Six-digit PIN pad (on-screen or keyboard), show/hide, shake on a wrong code
- Face ID and SMS code simulations
- Dashboard with animated balance, hide balance, and recent activity
- Send money: validates the amount, updates the balance and adds a transaction
- High contrast mode (remembered between visits) and reduced-motion support

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Aura Bank prototype"
git branch -M main
git remote add origin https://github.com/<your-username>/aura-bank.git
git push -u origin main
```

Then in the repository go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. The site appears at `https://<your-username>.github.io/aura-bank/`.

## Structure

```
index.html
css/styles.css
js/app.js
```

Fonts (Plus Jakarta Sans, Material Symbols) load from Google Fonts, so an internet connection is needed on first load. All data is fictional and nothing is sent anywhere.


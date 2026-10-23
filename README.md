# I-FIT Gym & Fitness Club

Single-page website for I-FIT Gym & Fitness Club, a premium unisex gym in Bankimpally, Sodepur, Kolkata.

## Live

- **Vercel:** https://i-fit-gym.vercel.app
- **GitHub:** https://github.com/kushik12debnath-bit/i-fit-gym

## Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Google Fonts
- Instagram photography embedded as base64 so the page stays self-contained

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8766
```

Then visit `http://localhost:8766`.

## Deploy

This is a static site with no build step.

```bash
vercel --prod
```

Or import the GitHub repository in the Vercel dashboard.

The first production deploy was created with the Vercel CLI. To enable automatic deploys on every push, connect the repo under **Vercel → Project → Settings → Git**.

## Business details used

- 4.6★ from 83 Google reviews
- Bankimpally, Amarabati, Sodepur, Kolkata, West Bengal 700110
- Open until 11 PM
- Premium unisex gym · imported equipment · certified trainers
- Strength training · fat loss · personal training · open gym

## Notes before launch

- All photography comes from the gym's public Instagram profile (`@i_fit_gym`). Some images are cropped from public post/video thumbnails, so replace them with the gym's originals for maximum sharpness.
- The free-tour form currently simulates a successful submission. Connect it to a booking endpoint or WhatsApp before going live.
- No phone number is published because none could be verified.
- Social preview image is intentionally omitted to keep stock imagery out. Add a hosted 1200×630 photo if link previews matter.

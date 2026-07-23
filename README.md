# Ante Vinum — WSET Level 2 study companion

Study notes, grape profiles, flashcards and a timed mock examination for the WSET Level 2 Award in Wines. One HTML file, no build step, no accounts, no tracking.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site |
| `og-image.png` | Preview image shown when the link is shared |
| `apple-touch-icon.png` | Home screen icon on iOS |
| `icon-192.png`, `icon-512.png` | Icons for Android / installed app |
| `manifest.webmanifest` | Lets the site be installed to a phone home screen |

Upload all of them to the repository root, side by side.

## Before you share the link

`index.html` has two URLs near the top that assume the repository is called **ante-vinum**:

```html
<link rel="canonical" href="https://joelucadooley.github.io/ante-vinum/">
<meta property="og:image" content="https://joelucadooley.github.io/ante-vinum/og-image.png">
```

If the repository has a different name, change `ante-vinum` in every line of that block to match. Social previews need absolute URLs, so a relative path will not work.

Already shared it somewhere and the old preview is stuck? Paste the URL into the relevant debugger to clear the cache: [Facebook](https://developers.facebook.com/tools/debug/), [X](https://cards-dev.twitter.com/validator), [LinkedIn](https://www.linkedin.com/post-inspector/).

## Two different previews

- Sharing the **site** (`joelucadooley.github.io/ante-vinum`) uses the tags in `index.html`.
- Sharing the **repository** (`github.com/joelucadooley/ante-vinum`) uses GitHub's own image, set under Settings → General → Social preview. Upload `og-image.png` there too.

## Hosting

Settings → Pages → Branch `main`, folder `/ (root)`. Live in a minute at `https://joelucadooley.github.io/<repo>/`.

## The exam it prepares you for

50 multiple-choice questions, 60 minutes, closed book. 55% passes, 70% is a merit, 85% a distinction. The mock paper mirrors the real weighting across the six learning outcomes.

Independent study aid, not affiliated with WSET.

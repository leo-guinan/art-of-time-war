# The Art of Time War

The Entropy Press site for *The Art of Time War*, a meta-commentary layered over Sun Tzu’s *The Art of War*.

Live target: https://war.entropypress.xyz

## Site

- `/` — Entropy Press landing page
- `/reader.html` — complete book reader
- `/reader.html?chapter=1` through `?chapter=13` — deep links into each chapter
- `/reader.html?chapter=coda` — deep link to the coda

The complete manuscript is included in `content/book.html`. The paywall is visible but non-enforcing: readers can read the whole book without subscribing, while the site still offers a clear route to support the press.

This is deliberate readership-first publishing. A reader who cannot afford the platform or subscription should still be able to read the work.

## Local preview

```bash
python3 -m http.server 8899
open http://localhost:8899/
```

## Deployment

This repository is deployed as a Cloudflare Pages project with the custom domain `war.entropypress.xyz`.

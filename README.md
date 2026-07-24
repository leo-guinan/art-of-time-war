# The Art of Time War

The Entropy Press site for *The Art of Time War*, a meta-commentary layered over Sun Tzu’s *The Art of War*.

Live target: https://war.entropypress.xyz

## Site

- `/` — Entropy Press landing page
- `/reader.html?chapter=1` — free Chapter 1
- `/reader.html?chapter=2` through `/reader.html?chapter=13` — subscriber gate

Only Chapter 1 is included in this static repository. The paid chapters are deliberately not shipped to the public artifact. A client-side unlock would be theatre wearing a security badge.

Paid access still requires a production entitlement boundary: a canonical Hitchhiker’s Guide checkout/login URL, a verified subscriber session or signed reader token, and a server-side chapter delivery endpoint.

## Local preview

```bash
python3 -m http.server 8899
open http://localhost:8899/
```

## Deployment

This repository is deployed as a Cloudflare Pages project with the custom domain `war.entropypress.xyz`.

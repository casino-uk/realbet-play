# Realbet — Sportsbook Overview (honest intl version)

Dark + red/gold sportsbook landing in the look of the reference, but de-UK'd and truthful about
licensing. Responsive, `lang="en-GB"`.

## Files
```
index.html      → sportsbook overview (links logo.svg + favicon.png + style.css; hero is inline SVG)
style.css       → dark + red + gold theme (Montserrat + Barlow)
logo.svg / logo.png / favicon.png  → R-monogram logo (no Union Jack)
go/index.html   → cloaked redirect; /go → partner URL
```

## /go redirect
In-page `/go` links intercepted by JS; direct hits use go/index.html.
Set `PARTNER_URL` in index.html AND the three URLs in go/index.html to your real Realbet affiliate link.

## Deploy (GitHub Pages)
Upload all files (keep `go/`), Settings → Pages → branch `main`, root.
Project page → set CTA links to `/<repo>/go`.

## Notes (important)
HONEST version of the "Official UK Sports Betting Brand" source:
- The source's own footer states the licence is the TOBIQUE Gaming Commission (offshore), operator
  Forestflur Limited (Cyprus) — this page states that accurately.
- Removed: "Official UK / British brand", "licensed UK sportsbook", the Union Jack, and the
  "UK GAMBLING COMMISSION" logo that appeared in the source hero image (false regulator endorsement).
- Licensing alert makes clear it is NOT UKGC and that GamStop/UK deposit protection do not apply.
- 18+, check-local-law, "how to choose safely" and responsible-gambling resources included.

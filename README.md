# PU „Veseli pužić“ — demo sajt

Jednostranični sajt (desktop + mobilni, prilagođava se širini ekrana).

## Objava na GitHub Pages
1. Napravite novi repozitorijum, npr. `veseli-puzic` (Public).
2. Otpremite SAV sadržaj ovog foldera u koren repozitorijuma (Add file > Upload files) — `index.html` mora biti u korenu.
3. Settings > Pages > Source: **Deploy from a branch**, Branch: `main` / `(root)` > Save.
4. Posle 1–2 minuta sajt je na: `https://KORISNIK.github.io/veseli-puzic/`

## Pre slanja linka
- U `index.html` zamenite **KORISNIK** svojim GitHub imenom (og:url, og:image, canonical) — inače pregled linka neće imati sliku.
- Proverite pregled: Facebook Sharing Debugger (`Scrape Again`) ili opengraph.xyz.
- Viber/WhatsApp keširaju pregled — za novi pregled dodajte `?v=2` na kraj linka.

## Demo zaštita
`index.html` sadrži `<meta name="robots" content="noindex, nofollow">`, a `robots.txt` zabranjuje indeksiranje. **Obrišite oba pre prave objave.**

## Sadržaj
- `index.html` — sajt
- `support.js` — runtime (mora biti pored index.html)
- `images/` — fotografije (privremene, sa Instagrama)
- `og-image-*.jpg`, `favicon*`, `webclip-256.png` — pregled linka i ikonice

Napomena: sajt učitava React i Google Fonts sa interneta (CDN), pa radi samo online.

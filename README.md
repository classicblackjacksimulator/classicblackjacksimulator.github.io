# Classic Blackjack Simulator

Gratis blackjack in je browser, met speelgeld. Speel op maximaal drie handen tegelijk, met splitsen, verdubbelen, verzekering, opgeven en de sidebets Pair, Dealer pair en 21+3. Met hints, een strategietabel, instelbare huisregels, statistieken en sneltoetsen.

Er wordt geen echt geld ingezet of uitbetaald.

## Online zetten met GitHub Pages

1. Maak een account op github.com (als je die nog niet hebt).
2. Klik rechtsboven op **+** en kies **New repository**.
   - Naam: `classic-blackjack-simulator`
   - Zet hem op **Public**.
   - Klik op **Create repository**.
3. Klik op **uploading an existing file** en sleep alle bestanden uit deze map erin:
   `index.html`, `favicon.svg`, `sitemap.xml` en `README.md`. Klik op **Commit changes**.
4. Ga naar **Settings** → **Pages**. Kies bij *Branch* `main` en de map `/ (root)` en klik op **Save**.
5. Na een minuut of twee staat het spel op
   `https://oledevries693-byte.github.io/classic-blackjack-simulator/`

## Vindbaar maken in Google

1. Ga naar search.google.com/search-console en log in met een Google-account.
2. Kies **Voorvoegsel van URL** en vul het adres van je spel in.
3. Kies als verificatie **HTML-tag**. Google geeft je een regel als
   `<meta name="google-site-verification" content="...">`.
   Zet die in `index.html` direct onder de regel met `<meta charset="utf-8">`, upload het bestand opnieuw en klik op **Verifiëren**.
4. Ga naar **Sitemaps**, vul `sitemap.xml` in en klik op **Indienen**.
5. Gebruik bij **URL-inspectie** de knop **Indexering aanvragen**.

Het duurt meestal een paar dagen tot een paar weken voordat het spel in Google verschijnt. Zoek dan op **Classic Blackjack Simulator**.

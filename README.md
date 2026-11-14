Projekt koncepcyjny do portfolio – fikcyjna marka

# Kowal-Bud

**Problem.** Osoba planująca remont potrzebuje zrozumieć zakres prac i przygotować dane do wyceny.

**Rozwiązanie.** Pięć podstron porządkuje zakres, proces i kontakt, a ilustracje pokazują obie wersje wnętrza.

**Sekcje.** Start, Usługi, Realizacje, O nas, Kontakt.

**Technologie.** HTML, Tailwind CSS, CSS, JavaScript bez frameworków. Font Instrument Sans z Google Fonts.

**Grafiki.** Własne SVG i zrzuty interfejsu.

**GitHub Pages.** [Adres demo](https://andriu-tsap.github.io/kowal-bud/).

**Lokalnie.** Uruchom serwer statyczny w katalogu projektu poleceniem python3 -m http.server 8000. Treść jest w HTML, motyw w style.css, zachowanie w app.js. Aby ponownie skompilować Tailwind, zainstaluj tailwindcss@4 i @tailwindcss/cli@4 i uruchom npx @tailwindcss/cli -i tailwind.input.css -o tailwind.css --minify.

## Zrzuty ekranu

[Desktop](screenshots/desktop.png) · [Mobile](screenshots/mobile.png)

## Lighthouse

<!-- AUDIT:START -->
Pomiar strony głównej na lokalnym serwerze statycznym w GitHub Actions (Chromium · Lighthouse 12).

| Tryb | Wydajność | Dostępność | Dobre praktyki | SEO |
| --- | ---: | ---: | ---: | ---: |
| desktop | 100 | 100 | 100 | 100 |
| mobile | 100 | 100 | 100 | 100 |
<!-- AUDIT:END -->


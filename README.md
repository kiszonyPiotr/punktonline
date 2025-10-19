# Punkt Online — statyczna strona (HTML + Tailwind CDN)

Gotowy landing sprzedażowy: e‑booki + merch. Działa bez żadnego builda.

## Szybki podgląd lokalnie
Po prostu otwórz `index.html` w przeglądarce.

## Wdrożenie na GitHub Pages
1. Stwórz publiczne repo (np. `punktonline`).
2. Wgraj pliki z tego folderu (`index.html`, `assets/`).
3. W repo: **Settings → Pages** → Source: `Deploy from branch`, Branch: `main /(root)`.
4. Po chwili strona będzie pod adresem: `https://TWOJE_GITHUB_USERNAME.github.io/punktonline/`

## Podmiana grafik
- W `index.html` znajdziesz obrazki w sekcjach HERO i SKLEP.
- Zmień ich atrybut `src` na:
  - własne linki HTTPS (np. Cloudinary/Unsplash/host własny), albo
  - ścieżki względne do plików w folderze `assets/` (np. `assets/ebook-airfryer.jpg`).

## Zmiana kolorów/brandingu
- Kolor brandu: `#F5C542` (złoto) — używany jako `text-brand`, `bg-brand`.
- Tło: `#0b0b0f` (ciemny). Zmienisz je w tailwind.config (sekcja `<script>tailwind.config=...`).

## SEO/OG
- Ustaw tytuł, opis i obraz OG w `<head>`.

## Płatności
- CTA kierują do: `https://buycoffee.to/punktonline` — podmień według potrzeb.

© 2025 Punkt Online

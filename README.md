# GPS Lab Navigator - PWA iPhone

Varianta v3 are un template nou de tip navigator/radar, cu paleta negru grafit, verde GPS si cyan.

## Fisiere

- `index.html` - interfata si logica aplicatiei GPS
- `manifest.webmanifest` - configuratie PWA pentru instalare pe Home Screen
- `sw.js` - service worker pentru PWA/cache
- `icon-192.png` si `icon-512.png` - iconite pentru aplicatie

## Instalare

1. Incarca toate fisierele direct in radacina repository-ului GitHub.
2. Activeaza GitHub Pages din `Settings -> Pages -> Deploy from a branch -> main -> /(root)`.
3. Deschide linkul in Safari pe iPhone.
4. Alege `Share -> Add to Home Screen`.
5. Porneste aplicatia si apasa `Porneste GPS`.

## Nota tehnica

Pe iOS/PWA numarul brut de sateliti GPS nu este disponibil prin API-ul public al browserului. Aplicatia marcheaza campul ca `N/A iOS` si afiseaza informatii GPS suplimentare: acuratete, altitudine, viteza, directie, coordonate DMS si harta.

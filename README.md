# GPS Custom App - PWA v5

Variantă finală echilibrată: template modern, fără elemente inutile, dar cu viteză și direcție păstrate.

## Afișează

- Latitudine
- Longitudine
- Ora
- Data
- Acuratețe GPS
- Altitudine
- Viteză estimată
- Direcție de deplasare
- Număr sateliți: N/A iOS
- Ultima actualizare
- Coordonate pentru copiere
- Deschidere hartă

## Observații iOS

Pe iPhone, browserul nu oferă prin API public numărul brut de sateliți GPS. Din acest motiv, aplicația afișează `N/A iOS` și folosește acuratețea GPS ca indicator al calității poziției.

Viteza și direcția sunt valori estimate de telefon/browser. Ele pot lipsi sau pot fluctua, mai ales când utilizatorul stă pe loc, este în interior sau semnalul GPS este slab.

## Update pe GitHub Pages

Încarcă toate fișierele direct în root-ul repository-ului:

- index.html
- manifest.webmanifest
- sw.js
- README.md
- icon-192.png
- icon-512.png

După commit, deschide linkul cu `?v=5` la final pentru a evita cache-ul.

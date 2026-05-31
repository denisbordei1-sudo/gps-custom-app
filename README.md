# GPS Custom App - PWA v6

Variantă echilibrată pentru laborator: template modern, câmpuri GPS principale, viteză și direcție păstrate, hartă integrată direct în aplicație.

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
- Moment măsurare
- Coordonate pentru copiere
- Hartă integrată în aplicație

## Observații iOS

Pe iPhone, browserul nu oferă prin API public numărul brut de sateliți GPS. Din acest motiv, aplicația afișează `N/A iOS` și folosește acuratețea GPS ca indicator al calității poziției.

Viteza și direcția sunt valori estimate de telefon/browser. Ele pot lipsi sau pot fluctua, mai ales când utilizatorul stă pe loc, este în interior sau semnalul GPS este slab. Direcția reprezintă direcția deplasării.

Altitudinea este afișată când dispozitivul returnează această informație. Dacă nu este disponibilă, aplicația afișează `Nedisponibilă`.

## Update pe GitHub Pages

Încarcă toate fișierele direct în root-ul repository-ului:

- index.html
- manifest.webmanifest
- sw.js
- README.md
- icon-192.png
- icon-512.png

După commit, deschide linkul cu `?v=6` la final pentru a evita cache-ul.

# Cijene lijekova

Mala web-aplikacija za pretragu cijena lijekova. Radi offline kad se jednom otvori s interneta i doda na početni ekran.

## Postavljanje na GitHub Pages

1. Na github.com napravi novi repozitorij (npr. `cijene-lijekova`), javni (public).
2. Dodaj sve fajlove iz ovog foldera: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-*.png`.
3. Settings → Pages → Source: **Deploy from a branch** → branch `main`, folder `/ (root)` → Save.
4. Za minutu-dvije adresa je `https://TVOJ-USERNAME.github.io/cijene-lijekova/`.

## Na iPhoneu (obavezno u Safariju)

1. Otvori adresu u **Safariju** dok ima internet.
2. Dodirni dugme za dijeljenje → **Dodaj na početni ekran** → Dodaj.
3. Otvaraj aplikaciju samo preko te ikonice. Prvi put je baza prazna, unesi lijekove (ili zalijepi listu kroz "Unos više lijekova odjednom").
4. Isključi internet i provjeri da radi.

Napomene:
- Baza koju vidi u Safariju i baza u ikonici na početnom ekranu su **odvojene**. Unos podataka radi tek nakon što otvori aplikaciju preko ikone.
- Povremeno neka klikne "Preuzmi kopiju" (sigurnosna kopija).
- Kad mijenjaš `index.html`, u `sw.js` povećaj broj verzije (`cijene-lijekova-v1` → `v2`), da telefon povuče novu verziju.

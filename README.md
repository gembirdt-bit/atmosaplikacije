# Atmos aplikacije

Stranica sa svim besplatnim Atmos aplikacijama: **https://gembirdt-bit.github.io/atmosaplikacije/**

| Aplikacija | Za šta je | Adresa |
|---|---|---|
| Atmos Dom | troškovi domaćinstva, računi, rokovi, garancije | https://gembirdt-bit.github.io/atmosdom/ |
| Atmos Ishrana | kalorije i nutrijenti, barkod, tablica namirnica | https://gembirdt-bit.github.io/atmos-ishrana/ |
| Atmos Personalni trener | za trenere: klijenti, termini, podsetnici, treninzi, napredak | https://gembirdt-bit.github.io/atmos-personalnitrener/ |
| Atmos Auto — servisna knjižica | servisi, gorivo, podsetnici za vozilo | https://gembirdt-bit.github.io/atmos-auto-servisna-knjizica/ |
| Atmos Dashboard | sat, prognoza, radio, kalendar, alarm | https://gembirdt-bit.github.io/atmos/ |
| Atmos Radionica | program za auto servise (Android / Windows) | https://github.com/gembirdt-bit/atmosradionica/releases/latest |

## Motivacione poruke (`poruke.json`)

Atmos Ishrana prikazuje u dnevniku motivacionu poruku koja se menja na 2 dana. Spisak poruka aplikacija preuzima iz fajla
[`poruke.json`](poruke.json) jednom u 2 dana; ako nema interneta, koristi ugrađeni spisak.

Da dodaš ili promeniš poruke, izmeni `poruke.json` na GitHub-u (olovka ✏️ → *Commit changes*). Format:

```json
{ "v": 1, "azurirano": "2026-11-13", "poruke": ["Prva poruka.", "Druga poruka."] }
```

Potrebno je bar 10 poruka; svaka u navodnicima, odvojene zarezom.

Podrška: vasserviserbgd@gmail.com

# Atmos aplikacije

Stranica sa svim Atmos aplikacijama: **https://gembirdt-bit.github.io/atmosaplikacije/**

| Aplikacija | Za šta je | Adresa |
|---|---|---|
| Atmos Dom | troškovi domaćinstva, računi, rokovi, garancije | https://gembirdt-bit.github.io/atmosdom/ |
| Atmos Ishrana | kalorije i nutrijenti, barkod, tablica namirnica | https://gembirdt-bit.github.io/atmos-ishrana/ |
| Atmos Personalni trener | za trenere: klijenti, termini, podsetnici, treninzi, napredak | https://gembirdt-bit.github.io/atmos-personalnitrener/ |
| Atmos Auto — servisna knjižica | servisi, gorivo, podsetnici za vozilo | https://gembirdt-bit.github.io/atmos-auto-servisna-knjizica/ |
| Atmos Dashboard | sat, prognoza, radio, kalendar, alarm | https://gembirdt-bit.github.io/atmos/ |
| Atmos Studio | za salone: termini, klijenti, usluge, paketi (Android / Windows, 30 dana besplatno) | https://gembirdt-bit.github.io/atmosstudio/ |
| Atmos Radionica | za auto servise: radni nalozi, vozila, predračun i račun (Android / Windows, 30 dana besplatno) | https://gembirdt-bit.github.io/atmosradionica/ |
| Atmos Magacin | šta se gde nalazi: kuća, garaža, vikendica, magacin, QR nalepnice | https://gembirdt-bit.github.io/atmos-magacin/ |
| Atmos Sentinel | zdravlje HDD i SSD diskova preko USB OTG (Android) | https://github.com/gembirdt-bit/gembirdt-bit-atmos-sentinel/releases/latest |
| Atmos Format | brisanje i formatiranje diskova (Windows / Android) | https://github.com/gembirdt-bit/atmos-format/releases/latest |
| Atmos IP kamere | pretraga i pregled IP kamera na mreži, RTSP / MJPEG strimovi (Windows / Android) | https://github.com/gembirdt-bit/Atmos-ipkamere/releases/latest |

Atmos Studio i Atmos Radionica rade kao Android i Windows aplikacije. Na njihovoj stranici su dugmad za preuzimanje (APK i Windows instalacija). Na ekranu za prijavu je taster **„Isprobaj besplatno“**: probna verzija traje 30 dana, sa najviše 10 klijenata (Studio) odnosno 10 vozila (Radionica), bez izvoza i sinhronizacije. Za stalni rad potrebna je licenca.

## Motivacione poruke (`poruke.json`)

Atmos Ishrana prikazuje u dnevniku motivacionu poruku koja se menja na 2 dana. Spisak poruka aplikacija preuzima iz fajla
[`poruke.json`](poruke.json) jednom u 2 dana; ako nema interneta, koristi ugrađeni spisak.

Da dodaš ili promeniš poruke, izmeni `poruke.json` na GitHub-u (olovka ✏️ → *Commit changes*). Format:

```json
{ "v": 1, "azurirano": "2026-11-13", "poruke": ["Prva poruka.", "Druga poruka."] }
```

Potrebno je bar 10 poruka; svaka u navodnicima, odvojene zarezom.

Podrška: vasserviserbgd@gmail.com

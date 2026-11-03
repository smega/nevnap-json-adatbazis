# Névnap JSON-adatbázis

A repó két JSON-fájlt tartalmaz a magyar névnapokról:

- `nap_nev.json`: dátum szerint (pl. `"01-02"`), az adott nap összes névnapjával,
- `nev_nap.json`: név szerint, az adott név összes névnapjával.

Ezekből veszi az adatokat a https://api.nevnapok.eu is.

Az adatok forrása: [Magyar névnapok listája betűrendben](https://hu.wikipedia.org/wiki/Magyar_n%C3%A9vnapok_list%C3%A1ja_bet%C5%B1rendben) (Wikipédia).

Frissítve: 2026.11.03.

## Változások

- **2026.11.03.** A `nap_nev.json`-ból (dátum -> nevek) majdnem minden napról
  hiányzott egy név (az eredeti generálásnál elcsúszott az első elem), összesen
  362 név. Ezeket visszaraktam a teljes `nev_nap.json` alapján, így a két fájl
  most pontosan ugyanazokat a név-dátum párokat tartalmazza. Új nevek: Gerzson
  (02-22), Bendegúz (05-07), Ádám (09-09), Naren (10-19).
- **2019.11.17.** Első változat.

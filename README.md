# Nevnap-json-adatbazis

A repo tartalmaz ket json file-t, melyek nev es nap alapjan tartalmazzak a nevnapokat. 
Ezekbol veszi az adatokat a https://api.nevnapok.eu oldal is.

Frissitve: 2026.11.03.

## Valtozasok

- **2026.11.03.** A `nap_nev.json`-bol (datum -> nevek) majdnem minden naprol
  hianyzott egy nev (az eredeti generalasnal elcsuszott az elso elem), osszesen
  362 nev. Ezeket visszaraktam a teljes `nev_nap.json` alapjan, igy a ket fajl
  most pontosan ugyanazokat a nev-datum parokat tartalmazza. Uj nevek: Gerzson
  (02-22), Bendeguz (05-07), Adam (09-09), Naren (10-19).
- **2019.11.17.** Elso valtozat.
Adatok: https://hu.wikipedia.org/wiki/Magyar_n%C3%A9vnapok_list%C3%A1ja_bet%C5%B1rendben oldalrol szarmaznak. 

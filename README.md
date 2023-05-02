# Házi feladat specifikáció
## Feladat informális leírása
A feladat célja egy olyan oldal létrehozása, amelyre fel lehet vinni Forma 1-es futamok eredményeit, majd az eredmények alapján kiszámolja és megjeleníti a pilóták és a konstruktőrök világbajonkságának állását.
## Elérhető funkciók
Az alkalmazás a következő funkciókat biztosítja
* Pilóták kezelése 
  * Új pilóták hozzáadása
  * Felvitt pilóták adatainak szerkesztése
* Csapatok kezelése
  * Új csapatok hozzáadása
  * Felvitt csapatok adatainak szerkesztése
* Pilóták hozzárendelése csapatokhoz
* Versenyeredmények felvitele
* Versenyeredmények pontokká való átszámítása, és ezeknek kilistázása
## Adatbázis séma
Az adatbázisban a következő entitásokat és attribútumokat tároljuk:
* Pilóta: Név, Csapat
* Csapat: Csapatnév
* Verseny: Dátum, Helyszín, Hivatalos körök száma, Teljesített körök száma, Leggyorsabb kört teljesítő pilóta
* Eredmény: Verseny dátuma, Pilóta, Pozíció
* Átváltás: Segéd tábla előre felvitt adatokkal, a pozíciók és pontok közötti átváltáshoz

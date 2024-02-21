# CarsAppProject1
CarsAppProject/asp.netMVC
Minta példa:
SQL rész: Hozzon létre 3 táblát és 1 tárolt eljárást mssql-ben.
Az első tábla (tulajdonosok)
azonosító (elsődleges kulcs)
vezeték
keresztnév
születési dátum
Második tábla (autók)
azonosító (elsődleges kulcs)
autómárka
típus
rendszám
gyártás ideje
Harmadik tábla
azonosító (elsődleges kulcs)
tulajdonos azonosító (külső kulcs)
autó azonosító (külső kulcs)
Tárolt eljárás Adja vissza a megadott tulajdonos azonosítóhoz tartozó autók adatait.
C# rész:
Egy asp.net MVC vagy Blazor projekt keretében hozzon létre egy programot, ami lehetőséget biztosít az autók és tulajdonos táblák megjelenítésére, az ott található sorok módosítására, illetve új elem felvételére. Minden funkció külön oldalon is megjelenhet. A tulajdonosok kilistázásánál minden sor végén jelenjen meg egy gomb, amit megnyomva megjelenik az adott tulajdonoshoz tartozó autók listája. Ennek lekérdezéséhez használja a fentebb említett tárolt eljárást.

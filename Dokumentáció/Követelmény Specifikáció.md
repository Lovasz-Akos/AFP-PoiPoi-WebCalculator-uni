# Áttekintés

A csapatunk célja egy olyan web alapú számológép fejlesztése, ami elsősorban ingyenes és reklám mentes.
Ezen felül pedig rendelkezik minden olyan funkcióval ami ki tudja elégíteni mind egy diák, mind egy informatikai hallgató igényeit is számítások tekintetében, viszont kellőképpen letisztult és felhasználóbarát a felülettel rendelkezik, ahhoz, hogy intuitív legyen a használata.
Különböző számolási feladtok megoldását teszi majd lehetővé, legyen az akár sima összeadás, kivonás vagy számrendszerek közötti átváltás.
Természetesen nem csak számítógépen lesz elérhető, hanem minél több platformon, tehát tableten és telefonon is.
Használatához semmilyen regisztráció nem szükséges, bárki hozzáférhet.
A projektünk html-ből, css-ből, javascript-ből fog összetevődni.

# Jelenlegi helyzet

Bár rengeteg számológép alkalmazás található a piacon, viszont ezek nagyrésze általában rengeteg zavaró reklámot tartalmaz, vagy esetleg bizonyos funkciók csak fizetés ellenében használhatóak.
Akár az is előfordulhat, hogy csak egyetlen platformon érhető el.
Pontosan ezekből az okokból kifolyólag döntöttünk úgy, hogy meg alkotunk egy teljesen ingyenes és reklámmentes számológépet, amit akár több platformon is lehet használni.

# Vágyálom rendszer

A projekt célja egy olyan web alapú számológép fejlesztése, amely teljesen ingyenes, és reklám mentes.
A rendszer elérhető több platformon, weben és androidon is egyaránt.
Látványos felülettel rendelkezik a program, hogy felkeltse a felhasználók
figyelmét.
A rendszernek van egy háttere amit csak a fejlesztő tud kezelni.
Itt a háttérben fejleszti, és tartja karban a programot a fejlesztő.

# Funkcionális követelmények

Kijelző -> Kijelző : A felhasználó által elvégzett műveletek és számolások itt jelennek meg.

Gomb -> Összeadás : Két vagy akár több szám összeadása.

Gomb -> Kivonás : Két vagy akár több szám kivonása egymásból.

Gomb -> Szorzás : Két vagy akár több szám összeszorzása.

Gomb -> Osztás : Két szám osztása egymással.

Gomb -> Eredmény : A számítások befejezése, az erdemények kiíratása.

Gomb -> Tizedes vessző : Megadhatjuk egy szának a tizedes vessző után levő értékeit.

Gomb -> Előjel változtatás : Egy szám előjelének megváltoztatását teszi lehetővé.

Gomb -> Visszavonás : Az utolsó számjegy törlése.

Gomb -> C : Az éppen aktuálisan felvitt szám nullázása, a részeredmény is nulázásra kerül.

Gomb -> CE : Az éppen aktuálisan felvitt szám nullázása, ha van részeredmény az megmarad.

Gomb -> Számok : A számok gombjai, ezek 1-9-ig terjednek, ezekkel tudjuk felvinni a kívánt számokat a számoláshoz.

Gomb -> Négyzet : Az éppen aktuálisan felvitt szám négyzetre emelése.

Gomb -> Négyzetgyök : Az éppen aktuálisan felvitt szám négyzetgyökének kiírása.

# Rendszerre vonatkozó törvények, szabványok, ajánlások

A programunk teljesen ingyenes, bárki használhatja.
Az alábbi böngészők közül bármelyiket lehet használni a programohoz:
 - Google Chrome
 - Mozilla Firefox
 - Opera
 - Safari
 
 Fogalmak:
- HTML: (angolul: HyperText Markup Language = hiperszöveges jelölőnyelv) egy leíró nyelv, melyet weboldalak készítéséhez fejlesztettek ki, miden weboldal alappillére.
- CSS: (Cascading Style Sheets, magyarul: lépcsőzetes stíluslapok)  egy stílusleíró nyelv, mely a HTML típusú strukturált dokumentumok megjelenését írja le.
- JavaScript: Programozási nyelv egy objektumorientált, prototípus-alapú szkriptnyelv, amelyet weboldalakon elterjedten használnak.


# Jelenlegi üzleti folyamatok modellje

Manapság egyre többen használunk számológépet, akár iskolában, akár otthon a házi feladatok megírására, vagy akár akkor is ha hirtelen kiakarunk valamit számolni.
A csapat több tagja is szembesült már azzal a problémával, amikor hiretelen számológépre volt szüksége, ám a rendelkezésre álló számológép alkalmazás nem volt megfelelő, vagy nem volt több platformon elérhető, vagy nem rendelkezett a megfelelő funkciókkal és ezáltal nem volt képes a megfelelő műveleteket elvégezni, vagy pedig a rengeteg reklám zavarta a feladat megoldását, és még egy olyan kezelőfelülettel is összefuthatunk ami abszolút nem felhasználó barát.
Pontosan ezek miatt fogalmazódott meg az ötlet csapatunkban, hogy fejlesszünk egy olyan számológépet ami több platformon elérhető, ingyenes és reklámmentes.
Megvizsgáltuk több számológép alkalmazásnak a kezelőfelületét és funkcióit, és ezekből próbáljuk megalkotni a megfelelő számológép alkalmazást.

# Igényelt üzleti folyamatok

- A felhasználónak semmilyen regisztráció nem szükséges a számológép használatához
- A felület mobilon lesz natív, de a reszponzív kialakítás miatt máson is használható lesz
- A felhasználó képes lesz a 4 alapművelet elvégzésére konkatenált módon
- A számológép gyökvonásra és négyzetre emelésre is képes lesz
- A felhasználónak, amennyiben rendelkezik az "alkalmazással" nincs szükségre internetkapcsolatra a használathoz
- Az informatikai hallgatók részére pedig képes lesz számrendszerek közötti átváltásra is

# Követelménylista

Modul 		| ID 	| Név 					| v. 	| Kifejtés
------------|-------|-----------------------|-------|-----------------------------------------------------------------------------------------------------
Jogosultság	|	1	| Jogosultsági szintek	| 1.0	| Admin : Rendszerhozzáférés, rendszer karbantartás, rendszerfejlesztés, program használata. Felhasználó : Program használata.
Felület		|	2	| Előnézeti felület		|		| Ez a felület lesz az, amit a felhasználó használni tud, azaz itt tudja igénybe venni a számológépet
			
# Riportok

A rendszer teljesen átlagosan működik akár egy átlagos számológép.
Az összeadás, kivonás, szorzás, osztás, négyzetre emelés, négyzetgyökre hozás műveletekre képes a számológép.
Továbbfejlesztési lehetőségként számos opció van.
Ilyen opció például:
 - Nevezetes szögfüggvények kezelése
 - X-edik hatványra hozás
 - stb.
 
# Fogalomtár

- HTML: (angolul: HyperText Markup Language = hiperszöveges jelölőnyelv) egy leíró nyelv, melyet weboldalak készítéséhez fejlesztettek ki, miden weboldal alappillére.
- CSS: (Cascading Style Sheets, magyarul: lépcsőzetes stíluslapok)  egy stílusleíró nyelv, mely a HTML típusú strukturált dokumentumok megjelenését írja le.
- JavaScript: Programozási nyelv egy objektumorientált, prototípus-alapú szkriptnyelv, amelyet weboldalakon elterjedten használnak.
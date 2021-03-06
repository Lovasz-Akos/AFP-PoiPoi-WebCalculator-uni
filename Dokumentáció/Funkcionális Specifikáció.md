# Áttekintés
A csapatunk célja egy olyan web alapú számológép fejlesztése, ami elsősorban ingyenes és reklám mentes. Ezen felül pedig rendelkezik minden olyan funkcióval ami ki tudja elégíteni mind egy diák, mind egy informatikai hallgató igényeit is számítások tekintetében, viszont kellőképpen letisztult és felhasználóbarát a felülettel rendelkezik, ahhoz, hogy intuitív legyen a használata. Különböző számolási feladtok megoldását teszi majd lehetővé, legyen az akár sima összeadás, kivonás vagy számrendszerek közötti átváltás. Természetesen nem csak számítógépen lesz elérhető, hanem minél több platformon, tehát tableten és telefonon is. Használatához semmilyen regisztráció nem szükséges, bárki hozzáférhet.

# Jelenlegi helyzet
Bár rengeteg számológép alkalmazás található a piacon, viszont ezek nagyrésze általában rengeteg zavaró reklámot tartalmaz, vagy esetleg bizonyos funkciók csak fizetés ellenében használhatóak. Akár az is előfordulhat, hogy csak egyetlen platformon érhető el. Pontosan ezekből az okokból kifolyólag döntöttünk úgy, hogy meg alkotunk egy teljesen ingyenes és reklámmentes számológépet, amit akár több platformon is lehet használni.

# Követelménylista
Modul | Név | Kifejtés
-|-|-
Kijelző | Kijelző | A felhasználó által elvégzett műveletek és számolások itt jelennek meg.
Gomb | Összeadás | Két vagy akár több szám összeadása.
Gomb | Kivonás | Két vagy akár több szám kivonása egymásból.
Gomb | Szorzás | Két vagy akár több szám összeszorzása.
Gomb | Osztás | Két szám osztása egymással.
Gomb | Eredmény | A számítások befejezése, az erdemények kiíratása.
Gomb | Tizedes vessző | Megadhatjuk egy szának a tizedes vessző után levő értékeit.
Gomb | Előjel változtatás | Egy szám előjelének megváltoztatását teszi lehetővé.
Gomb | Visszavonás | Az utolsó számjegy törlése.
Gomb | C | Az éppen aktuálisan felvitt szám nullázása, a részeredmény is nulázásra kerül.
Gomb | CE | Az éppen aktuálisan felvitt szám nullázása, ha van részeredmény az megmarad.
Gomb | Számok | A számok gombjai, ezek 1-9-ig terjednek, ezekkel tudjuk felvinni a kívánt számokat a számoláshoz.
Gomb | Négyzet | Az éppen aktuálisan felvitt szám négyzetre emelése.
Gomb | Négyzetgyök | Az éppen aktuálisan felvitt szám négyzetgyökének kiírása.

# Jelenlegi üzleti folyamatok modellje
Manapság egyre többen használunk számológépet, akár iskolában, akár otthon a házi feladatok megírására, vagy akár akkor is ha hirtelen kiakarunk valamit számolni. A csapat több tagja is szembesült már azzal a problémával, amikor hiretelen számológépre volt szüksége, ám a rendelkezésre álló számológép alkalmazás nem volt megfelelő, vagy nem volt több platformon elérhető, vagy nem rendelkezett a megfelelő funkciókkal és ezáltal nem volt képes a megfelelő műveleteket elvégezni, vagy pedig a rengeteg reklám zavarta a feladat megoldását, és még egy olyan kezelőfelülettel is összefuthatunk ami abszolút nem felhasználó barát. Pontosan ezek miatt fogalmazódott meg az ötlet csapatunkban, hogy fejlesszünk egy olyan számológépet ami több platformon elérhető, ingyenes és reklámmentes. Megvizsgáltuk több számológép alkalmazásnak a kezelőfelületét és funkcióit, és ezekből próbáljuk megalkotni a megfelelő számológép alkalmazást.

# Igényelt üzleti folyamatok modellje
 - A felhasználónak semmilyen regisztráció nem szükséges a számológép használatához
 - A felület mobilon lesz natív, de a reszponzív kialakítás miatt máson is használható lesz
 - A felhasználó képes lesz a 4 alapművelet elvégzésére konkatenált módon
 - A számológép gyökvonásra és négyzetre emelésre is képes lesz
 - A felhasználónak, amennyiben rendelkezik az "alkalmazással" nincs szükségre internetkapcsolatra a használathoz
 - Az informatikai hallgatók részére pedig képes lesz számrendszerek közötti átváltásra is


# Használati esetek

A felhasználó legfőképpen alapműveletek elvégzésére tudja használni a számológépet.
Abban az esetben tudja használni a számológépet, amennyiben szeretné az alábbi műveletek valamelyikét elvégezni:

- Összeadás gomb: Két vagy akár több szám összeadása. 
- Kivonás gomb: Két vagy akár több szám kivonása egymásból. 
- Szorzás gomb: Két vagy akár több szám összeszorzása.
- Osztás gomb: Két szám osztása egymással.
- Négyzetre emelés gomb: Az éppen aktuálisan felvitt szám négyzetre emelése. 
- Négyzetgyök gomb: Az éppen aktuálisan felvitt szám négyzetgyökének kiírása.
- Eredmény gomb: A számítások befejezése, az erdemények kiíratása. 
- Tizedes vessző gomb: Megadhatjuk egy szának a tizedes vessző után levő értékeit. 
- Előjel változtatás gomb: Egy szám előjelének megváltoztatását teszi lehetővé. 
- Visszavonás gomb: Az utolsó számjegy törlése. 
- C gomb: Az éppen aktuálisan felvitt szám nullázása, a részeredmény is nulázásra kerül. 
- CE gomb: Az éppen aktuálisan felvitt szám nullázása, ha van részeredmény az megmarad.

A fejlesztő ezeken kívűl egyetemhez szükséges műveleteket, és további elemeket is hozzá tudja adni:

- Logaritmus
- Trigonometria
- Pi értéke
- Stb.

# Képernyőterv
![Képernyőterv](/Dokumentáció/Képek/design.PNG)

# Fogalomszótár
 - HTML: (angolul: HyperText Markup Language=hiperszöveges jelölőnyelv) egy leíró nyelv, melyet weboldalak készítéséhez fejlesztettek ki, miden weboldal alappillére.
 - CSS: (Cascading Style Sheets, magyarul: lépcsőzetes stíluslapok)  egy stílusleíró nyelv, mely a HTML típusú strukturált dokumentumok megjelenését írja le.
 - JavaScript: Programozási nyelv egy objektumorientált, prototípus-alapú szkriptnyelv, amelyet weboldalakon elterjedten használnak.

# Forgatókönyvek
 Célja: segítse a felhasználót a számítási feladatok kiszámításában: összeadás, kivonás, szorzás, osztás, gyökvonás, négyzetre emelés.
 Összeadás: Elsőnek megnyomod azt a számgombot, amit össze akarsz adni valamivel. Ezután rákattintasz a + jelre, ami az összeadást szolgálja. Utána arra a számra kell kattintanod, amit hozzá akarsz adni az előző számhoz. Végül rákattintasz az egyenlőség jelre, és a számológép kijelzőjén leolvasod az eredményt.

 Kivonás: Elsőnek megnyomod azt a számgombot, amiből ki akarsz vonni egy másik számot. Ezután rákattintasz a - jelre, ami a kivonást szolgálja. Utána arra a számra kell kattintanod, amit ki akarsz vonni az előző számból. Végül rákattintasz az egyenlőség jelre, és a számológép kijelzőjén leolvasod az eredményt.

 Szorzás: Elsőnek megnyomod azt a számgombot, amit össze akarsz szorozni valamivel. Ezután rákattintasz a × jelre, ami a szorzást szolgálja. Utána arra a számra kell kattintanod, amit össze akarsz szorozni az előző számmal. Végül rákattintasz az egyenlőség jelre, és a számológép kijelzőjén leolvasod az eredményt.

 Osztás: Elsőnek megnyomod azt a számgombot, amit osztani akarsz valamivel. Ezután rákattintasz a / jelre, ami az osztást szolgálja. Utána arra a számra kell kattintanod, amivel osztani akarod az előző számot. Végül rákattintasz az egyenlőség jelre, és a számológép kijelzőjén leolvasod az eredményt.

 Tizedes vessző: Ha olyan számmal akarsz műveletet végezni, ami nem egész szám (tört szám), akkor először rákattintasz az egész részt jelző számjegyre/számjegyekre, majd a tizedes vesszőre, és utána arra a számjegyre/számjegyekre, ami/amik a tört részben jelenik/jelennek meg.

 Előjel változtatás: Ha negatív számmal szeretnél műveletet végezni, akkor először rákattintasz a +/- gombra, majd a számjegyre/számjegyekre.

 Visszavonás: Ha rossz számot írtál be, akkor a visszavonás gombra kattintva kitörölheted az utolsó számjegyet. A gomb többszöre megnyomásával az mindig aktuális utolsó számjegy kerül törlésre.

 C: Ha ki akarod törölni az összes számítást, kattints a C gombra. Ezzel kitörlődik az összes számjegy, amit felvittél, valamint a részeredmények sem maradnak meg.

 CE: Ha rosszul vitted fel a számjegyet/számjegyeket, akkor a CE gomb egyszeri megnyomásával tudod kitörölni a számjegyet/számjegyeket amnélkül, hogy a részeredmény elveszne.

 Négyzet: Először megnyomod azt a számgombot, amit négyzetre szeretnél emelni, majd rákattintasz a Négyzet gombra, ami az általad felvitt számjegyet/számjegyeket megszorozza önmagával.
 Négyzetgyök: Először megnyomod azt a számgombot, amiből gyököt szeretnél vonni, majd rákattintasz a Négyzetgyök gombra, ami az általad felvitt számjegyen négyzetgyökvonási műveletet végez el.
 
 Egyéb: Ha rossz műveleti jelre kattintasz, ki tudod cserélni a következőnek leütött műveleti jellel. Pl.: Ha a +, azaz az összeadás jelre kattintottál rá, és még a számjegy bevitele előtt rákattintasz a ×, azaz a szorzás jelre, akkor a műveleti jel a ×, azaz a szorzás lesz.
 

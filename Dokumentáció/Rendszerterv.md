# Követelmények
 Funcionális követelmények:
 - A program a következő számításokat helyesen végezze el:
   - Összeadás gomb: a beírt számokat összeadja.
   - Kivonás gomb: a beírt számokat kivonja egymásból.
   - Szorzás gomb: a beírt számokat összeszorozza.
   - Osztás gomb: a beírt számot elosztja az általad beírt másik számmal.
   - Tizedes vessző: lehetővé teszi a tört számok bevitelét.
   - Előjel változatás gomb: megváltoztatja a beírt szám előjelét.
   - Visszavonás: az éppen aktuális utolsó számjegyet kitörli.
   - C: a számjegyek és a részeredmények nullázása.
   - CE: az aktuálisan felvitt számot nullázza, a részeredmények megmaradnak.
   - Négyzet: az általad bevitt számot emeli négyzetre, szorozza meg önmagával.
   - Négyzetgyök: az általad bevitt számnak veszi a négyzetgyökét.
   
# Implementációs terv
 A Webes felület főként HTML, CSS, és Javascript nyelven fog készülni. Ezeket a technológiákat amennyire csak lehet külön fájlokba írva készítjük, és úgy fogjuk egymáshoz csatolni a jobb átláthatóság, könnyebb változtathatóság, és könnyebb bővítés érdekében

# Telepítési terv
 A program eléréséhez csak egy böngésző telepítésére lesz szükség (Google Crome, Firefox, Opera, Safari), amelyet a Google áruházból lehet letölteni. Adja meg a szükséges engedélyeket és telepítse a böngészőt. Ezt követően a megfelelő URL cím beírását követően van lehetőség a program elérésére.

# Karbantartási terv
 A jövőben felmerülő esetleg további igények kielégítése érdekében fenntartjuk a program üzemeltetését és karbantartását, valamint ha hiba/probléma merülne fel a program használata közben. Ezenkívül a későbbiekben beépíthetünk egy olyan plusz lehetőséget is, mely engedélyezi a program letöltését/telepítését, a gyakran használt képletek tárolását, a kinézet alakítását.

# Projektterv

Alapvetően a dokumentum megírását nagyjából egyenlően próbáltuk elosztani.
A program kódot szintén nagyjából felosztottuk egymás között, némelyik témakörben közösen dolgozunk majd.

Tag|Felelősség
-|-
Farkas Erik|Logika fejlesztő, Dokumentáció
Zöldi Tóth István|Design fejlesztő, Dokumentáció
Karsai Petra|Design tervező, Dokumentáció
Maka Bettina|Rendszerszervező, Dokumentáció
  
# A rendszer célja

A felhasználó a számológép segítségével képes legyen alapvető műveleteket elvégezni.
Mindemelett a négyzetre emelést és a négyzetgyökvonást is eltudja végezni.
Fontos, hogy a felhasználó el tudjon igazodni a számológépen.
A rendszert a felhasználók csak webes felületen, tehát valamelyik böngészőben tudják majd használni (Google Crome, Firefox, Opera, Safari, stb.).

# Fizikai környezet

A program csak webes felületen működik. 
A számológépen elérhető az összes funkció amit látni fog a felhasználó. Fejlesztői eszközként az alábbiakat használjuk: 
 - Html
 - css
 - javascript  
 
# Architekturális terv

A programhoz nem szükséges semmit telepíteni, hiszen az egész webes felületen lesz elérhető. Mindezek mellett html-t, css-t, és javascriptet használunk. 

# Funkcionális terv

Rendszerszereplők:
 - Felhasználó
 - Fejlesztők

Rendszerhasználati esetek és lefutásaik:

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
 
# Teszt terv

Unit teszt:

Minden egyes műveletnél (például: összeadás, kivonás, stb.) érdemes tesztelni már a fejlesztési idő alatt is.

Alfa teszt:

Ezt a tesztet, mi fejlesztők végezzük. Az alapvető, és az összes műveleteket leteszteljük hogy megfelelően működik-e. Ezt minél több böngészőben próbáljuk kivitelezni.

Beta teszt:

Ezt a tesztet már nem mi, fejlesztők végezzük, hanem véletlenszerűen kiválasztott ismerősöknek/embereknek a setgítségét kérjük.
A felhasználó a maga, sajátos módján tesztelheti a programot.
Ha hiba lép fel, akkor a fejlesztők kijavítják a probléma gyökerét.

Tesztelendő funkciók:
 - Összeadás
 - Kivonás 
 - Szorzás
 - Osztás
 - Előjel változtatás 
 - Négyzetre emelés 
 - Négyzetgyök
 - Eredmény
 - Tizedes vessző 
 - Visszavonás
 - C 
 - CE

# Üzleti folyamatok modellje

Felhasználók:

Alapvetően csak a számológép felületéhez és a használatához fér hozzá.

Fejlesztők:

Szintén hozzá tudnak férni a számológép felületéhez és használatához, viszont a karbantartást és a fejlesztést is ők végzik.

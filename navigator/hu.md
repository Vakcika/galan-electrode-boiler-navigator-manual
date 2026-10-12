# „Navigator” hőmérséklet-szabályozó. Kezelési útmutató

<!-- page 1 -->

![Borító](images/p01_cover.jpg)

**GALAN ™ GALAN**
WARMWORLD · A MELEG VILÁGA

**ÚTMUTATÓ**
alkalmazáshoz és üzemeltetéshez

**Kétcsatornás elektronikus hőmérséklet-szabályozó, „NAVIGATOR”**

Kivitel: ______ *(kézzel beírva: „B”, azaz Bázis/Alap)*

RST megfelelőségi jel, ME 69

---

<!-- page 2 -->

# Tartalom

Rendeltetés ........................................................ 3
Leírás és működési elv ............................................. 4
Szállítási terjedelem .............................................. 6
Biztonsági előírások ............................................... 6
Szerelés, üzembe helyezésre való felkészítés ....................... 7
A Navigator bekapcsolása, üzemmódjainak beállítása ................ 12
Karbantartás ...................................................... 12
Tárolási szabályok ................................................ 13
A lehetséges hibák és elhárításuk módszerei ........................ 14

---

<!-- page 3 -->

# 1. Rendeltetés

1.1. A „Navigator” kétcsatornás elektronikus hőmérséklet-szabályozó (a továbbiakban: hőmérséklet-szabályozó) elektromos fűtőberendezések (elektródás típusú elektromos vízmelegítők, fűtőbetétes kazánok, hőlégágyúk, hőlégfüggönyök, konvektorok és egyéb berendezések) adott hőmérsékleti üzemmódjának fenntartására és a fűtési rendszer keringtető szivattyújának vezérlésére szolgál.

1.2. A hőmérséklet fő szabályozása két csatornán történik: az előremenő és a visszatérő csővezeték hőmérséklete alapján. Kiegészítően a helyiség levegőjének hőmérséklete szerint is szabályozás valósítható meg az „Istopnik” vezérlővel vagy a „Galan GSM” cellás felügyeleti rendszerrel.

1.3. A hőmérséklet-szabályozó alkalmazása csökkenti az elektromos energia-fogyasztást, és a fűtött helyiségben a legkedvezőbb hőmérsékleti viszonyokat biztosítja.

1.4. A gyártó jogosult a hőmérséklet-szabályozó szerkezetének és kapcsolási rajzainak olyan módosítására, amely nem rontja annak mérési és műszaki jellemzőit.

---

<!-- page 4 -->

# 2. Leírás és működési elv

A „Navigator” digitális hőmérséklet-szabályozó házból (1. ábra), a hozzá csatlakoztatott hőmérséklet-érzékelőkkel rendelkező elektronikus egységből (3) áll (piros: előremenő csővezeték, kék: visszatérő csővezeték). Részei továbbá: a fűtési fokozatok működését jelző kijelzők (2); a keringtető szivattyú bekapcsolását jelző kijelző (4); a külső szobatermosztát bekapcsolását jelző kijelző (5); a visszatérő (kék) és az előremenő (piros) csatorna kijelzői (6); a hőmérséklet-kijelző (7); a kezelőgombok (8); a kapcsoló (9); a keringtető szivattyú csatlakoztatására és a vezérlőegység 220 V-os tápellátására szolgáló átmeneti kapocssor (10); a relé-kontaktor (11) (H2 változatban két, H3 változatban három kontaktor); az áramszabályzó (12) (NKT változathoz); valamint a nullsín (13).

![1. ábra. A „Navigator” hőmérséklet-szabályozó kezelő- és jelzőelemei](images/p04_control_panel_diagram.jpg)

*1. ábra. A „Navigator” hőmérséklet-szabályozó kezelő- és jelzőelemei*

Az ábra számozott elemeinek magyarázata:
- 1: a készülék háza (a szövegben számozás nélkül, „ház” néven szerepel)
- 2: fűtési fokozatok működését jelző LED-ek
- 3: elektronikus egység, a hőmérséklet-érzékelők csatlakoztatásával
- 4: a keringtető szivattyú bekapcsolását jelző LED
- 5: a külső szobatermosztát bekapcsolását jelző LED
- 6: a visszatérő (kék) és az előremenő (piros) csatorna LED-jei
- 7: hőmérséklet-kijelző
- 8: kezelőgomb
- 9: kapcsoló
- 10: átmeneti kapocssor (keringtető szivattyú csatlakoztatása, a vezérlőblokk 220 V-os tápellátása)
- 11: relé-kontaktor (H2 változat: két kontaktor, H3 változat: három kontaktor)
- 12: áramszabályzó (NKT változat)
- 13: nullsín

A hőmérséklet szabályozása két csatornán történik: az előremenő (piros) és a visszatérő (kék) csővezetékhez tartozó érzékelőkről. A visszatérő érzékelő a fő szabályozó érzékelő. Az előremenő érzékelő vészérzékelő, amely a felforrás megelőzését szolgálja, és tartalékként működik a visszatérő érzékelő meghibásodása esetén.

---

<!-- page 5 -->

| **Beállítási tartomány:** | **Ajánlott értékek:** |
|---|---|
| Visszatérő: 10–80°C. | Visszatérő: 35–40°C. |
| Előremenő: 10–85°C. | Előremenő: 70–75°C. |
| Hiszterézis: 1–9°C | Hiszterézis: 3–5°C |

A jelen útmutatóban hiszterézisen a kikapcsolás és a kazán későbbi újra bekapcsolása közötti hőmérséklet-különbséget értjük.

A blokk bekapcsolásakor a 7-es kijelzőn megjelenik az aktuális visszatérő hőmérséklet, és a kék 6-os LED világít. Az indikátor bal felső sarkában lévő pont világítása jelzi a keringtető szivattyú bekapcsolására adott jelet. A csúcsterhelés csökkentése érdekében a fűtési fokozatok egymás után kapcsolnak be. A szivattyú bekapcsolása után 30 másodperccel az első fokozat kapcsol be, az első fokozat bekapcsolása után 10 másodperccel a második, majd további 10 másodperccel a harmadik fűtési fokozat. A fűtési rendszer felmelegedésével a gazdaságos működés érdekében a fűtési fokozatok fokozatosan kikapcsolnak. Ha a beállított hőmérséklet mínusz a hiszterézis értékét eléri, a harmadik fokozat kikapcsol, a beállított hőmérséklet mínusz a hiszterézis fele értéknél pedig a második fokozat. A beállított hőmérséklet elérésekor a fűtés teljesen kikapcsol. A kazán hűtéséhez a keringtető szivattyú a fűtés kikapcsolása után még 30 másodpercig üzemel, majd leáll. A fűtési rendszer hűlése közben a hőmérséklet-egyenletesség érdekében a keringtető szivattyú 5 percenként 30 másodpercre bekapcsol. A rendszer hűlésekor a fűtési fokozatok szintén egymás után kapcsolnak be.

Ha az előremenő hőmérséklet elérte a beállított maximális értéket, a fűtés teljesen kikapcsol, amíg a hőmérséklet 9°C-kal nem csökken. A hőmérséklet-érzékelőket a fűtési rendszer fémes részeire, a kazántól 30–50 cm távolságra kell felszerelni.

---

<!-- page 6 -->

A szabályozó két csatlakozóaljzattal rendelkezik külső, a helyiség levegőjének hőmérsékletét szabályozó eszközök csatlakoztatásához. Ezen eszközök csatlakoztatása és a beállított levegő-hőmérséklet elérése esetén a fűtés teljesen kikapcsol, és a kijelző felső középső részén jelzőpont világít.

A KT szabályozósorozat elektródás kazánokhoz készült, és áramszabályzót tartalmaz, amely a névleges áramerősség túllépésekor 3 percre kikapcsolja a fűtést, majd a fűtési ciklus megismétlődik. Az áramszabályzó működésekor a LED fénye zöldről pirosra vált.

A keringtető szivattyú legnagyobb megengedett teljesítménye a „szivattyú” kimeneten legfeljebb 200 W. Nagyobb teljesítményű keringtető szivattyú esetén a csatlakoztatást kapcsolóberendezésen keresztül kell megoldani.

# 3. Szállítási terjedelem

1. Többcsatornás elektronikus szabályozó-kijelző „Navigator” hőmérséklet-szabályozóhoz – 1 db
2. Digitális integrált hőmérséklet-érzékelő (2 db)
3. Használati útmutató – 1 db
4. Csomagolás – 1 db

# 4. Biztonsági előírások

4.1. Az áramütés elleni védelem módja szerint a hőmérséklet-szabályozó a GOST 12.2.007.075 szerinti 0. osztálynak felel meg.

4.2. A hőmérséklet-szabályozóban életveszélyes feszültség van. Hibaelhárítás, karbantartás és szerelési munkák előtt a hőmérséklet-szabályozót és a hozzá csatlakoztatott eszközöket le kell választani a hálózatról.

---

<!-- page 7 -->

4.3. A hőmérséklet-szabályozó robbanásveszélyes helyiségekben való használatra készült.

4.4. A nedvesség nem juthat a kapocssorok kivezetéseire és a hőmérséklet-szabályozó belső elektronikus elemeire. Tilos a hőmérséklet-szabályozót olyan agresszív környezetben használni, ahol a levegő savakat, lúgokat, olajokat stb. tartalmaz.

4.5. A hőmérséklet-szabályozó üzemeltethető olyan helyiségben, ahol a hőmérséklet nem alacsonyabb +5°C-nál és nem magasabb +40°C-nál, a relatív páratartalom pedig legfeljebb 85%.)

4.6. A hőmérséklet-szabályozó szerelését és karbantartását csak a jelen használati útmutatót ismerő, képesített szakemberek végezhetik.

4.7. Üzemeltetés és karbantartás során be kell tartani az „Elektromos berendezések és fogyasztók műszaki üzemeltetésének szabályai” és az „Elektromos berendezések és fogyasztók üzemeltetése során alkalmazandó műszaki biztonsági szabályok” előírásait.

# 5. Szerelés, üzembe helyezésre való felkészítés

5.1. A blokkot száraz, szellőztethető helyiségben, falra függőlegesen, önmetsző csavarokkal rögzítse.

Vegye le a 8-as kezelőgombot (1. ábra), csavarozza ki a két csavart, és vegye le a „Navigator” blokk fedelét, majd vezesse be a bekötő kábeleket a kapcsolási rajznak megfelelően.

5.2. Vezesse be a hőmérséklet-érzékelők, a 220 V-os modul tápellátása, a keringtető szivattyú vezérlése és a külső eszközök vezérlése összekötő vezetékeit. A hőmérséklet-érzékelőket a fűtési rendszer fémes csővezeték-szakaszaira, a kazántól 30–50 cm távolságra kell felszerelni.

5.3. A külső csatlakozások szerelésekor gondoskodni kell arról, hogy azok megbízhatóan érintkezzenek a hőmérséklet-szabályozó kapcsaival.

A vezérlőkábelek szereléséhez réz vezetéket használjon, amelynek keresztmetszete 0,5–2,5 mm².

---

<!-- page 8 -->

A vezérlőáramkörök csatlakoztatásához a kábel végét 7+0,5 mm hosszúságban vezesse le. A túl hosszú vég rövidzárlat okozója lehet, a túl rövid vég pedig megbízhatatlan csatlakozást eredményez. Csavarja ki a kapocs csavarját, és helyezze be a lecsupaszított kábelvéget a kapocsba.

A vezérlőáramkörök kapcsát 0,5 N·m ajánlott nyomatékkal húzza meg.

A gyenge meghúzás a csatlakozás lazulásához és hibás működéshez vezethet, a túlzott meghúzás pedig rövidzárlatot vagy a kapocssor sérülését okozhatja.

**Figyelem!**

Többeres vezeték használata esetén csavarja össze az ereket a lecsupaszított kábelvégen, vagy a rögzítés előtt használjon présözött kábelvéghüvelyt. Ne ónozza a vezeték végét, mert az rossz érintkezést okozhat.

5.4. A szabályozóblokk vezérlőmodulja és a teljesítményelemei hálózati tápellátásának csatlakoztatását a 2–7. ábrán látható kapcsolási rajzok szerint kell elvégezni. A teljesítményvezetékek keresztmetszetét és a kapcsolóeszközök teljesítményét a kazán teljesítménye alapján kell megválasztani. A „Navigator” blokk elé kötelezően automata védelmi kismegszakítót kell szerelni.

5.5. Figyelem! A feszültséget csak az összes eszköz csatlakozásának és az összes menetes elektromos kötés meghúzásának ellenőrzése után szabad rákapcsolni. A feszültség rákapcsolása után a digitális kijelzőn megjelenik az információ, amely jellemzi azt az üzemmódot, amelyben a hőmérséklet-szabályozó van.

---

<!-- page 9 -->

![2. ábra. A „Navigator Alap” blokkok csatlakoztatási sémája.](images/p09_wiring_diagram_base.jpg)

*2. ábra. Blokkok csatlakoztatási sémája: „Navigator Alap”.*

A 2. ábra feliratainak magyarázata:
- 380 V-os hálózat
- N, A, B, C: változatlanul (N: nulla, A, B, C: fázisvezetők)
- védőautomaták (nem tartozékai a blokknak)
- kontaktor
- elektronikus vezérlőmodul
- hőmérséklet-érzékelők
- a kazánhoz a használati útmutató szerint
- a keringtető szivattyúhoz, <200 W
- 220 V 2 A tápellátás

![3. ábra. A „Navigator Alap KT” blokkok csatlakoztatási sémája.](images/p09_wiring_diagram_base_kt.jpg)

*3. ábra. Blokkok csatlakoztatási sémája: „Navigator Alap KT”.*

A 3. ábra feliratainak magyarázata:
- 380 V-os hálózat
- N, A, B, C: változatlanul (N: nulla, A, B, C: fázisvezetők)
- védőautomaták (nem tartozékai a blokknak)
- kontaktor
- KTSZ-1 (típusjelzés, változatlanul)
- elektronikus vezérlőmodul
- hőmérséklet-érzékelők
- a kazánhoz a használati útmutató szerint
- a keringtető szivattyúhoz, <200 W
- 220 V 2 A tápellátás

---

<!-- page 10 -->

![4. ábra: A „Navigator Alap +” egységek csatlakoztatási sémája](images/p10_fig4_wiring_base_plus.jpg)

*4. ábra: A „Navigator Alap +” egységek csatlakoztatási sémája.*

**Jelmagyarázat a 4. ábrához:**
- 380 V-os hálózat
- védőautomaták (a blokk szállítási terjedelmében nincsenek benne)
- kontaktor
- elektronikus vezérlőmodul
- hőmérséklet-érzékelők
- a keringetőszivattyúhoz, <200 W
- táplálás 220 V, 2 A
- a kazánhoz, a kézikönyv szerint
- N, A, B, C: nulla és fázisvezetékek

![5. ábra: A „Navigator Alap KT +” egységek csatlakoztatási sémája](images/p10_fig5_wiring_base_kt_plus.jpg)

*5. ábra: A „Navigator Alap KT +” egységek csatlakoztatási sémája.*

**Jelmagyarázat az 5. ábrához:**
- 380 V-os hálózat
- védőautomaták (a blokk szállítási terjedelmében nincsenek benne)
- KTSZ-1 modul
- kontaktor
- elektronikus vezérlőmodul
- hőmérséklet-érzékelők
- „FN”, táplálás 220 V, 2 A (az „FN” jelölést a kézikönyv nem magyarázza, az eredeti jelölést megtartottam)
- „FN”, a keringetőszivattyúhoz
- a kazánhoz, annak kézikönyve szerint
- A1 B1 C1, A2 B2 C2, N: kimeneti és bemeneti fázisok, nulla

---

<!-- page 11 -->

![6. ábra: A „Navigator T” egység csatlakoztatási sémája](images/p11_fig6_wiring_t.jpg)

*6. ábra: A „Navigator T” egység csatlakoztatási sémája.*

**Jelmagyarázat a 6. ábrához:**
- 220 V-os hálózat
- fázis
- védőautomaták (a blokk szállítási terjedelmében nincsenek benne)
- 1. fokozat, 2. fokozat, 3. fokozat
- kontaktor
- elektronikus vezérlőmodul
- hőmérséklet-érzékelők
- a keringetőszivattyúhoz, <200 W
- táplálás 220 V, 2 A
- N: nulla

![7. ábra: A „Navigator TT” egységek csatlakoztatási sémája](images/p11_fig7_wiring_tt.jpg)

*7. ábra: A „Navigator TT” egységek csatlakoztatási sémája.*

**Jelmagyarázat a 7. ábrához:**
- 380 V-os hálózat
- védőautomaták (a blokk szállítási terjedelmében nincsenek benne)
- kontaktor
- elektronikus vezérlőmodul
- hőmérséklet-érzékelők
- a kazánhoz, a kézikönyv szerint
- a keringetőszivattyúhoz, <200 W
- táplálás 220 V, 2 A
- N, A, B, C: nulla és fázisvezetékek

---

<!-- page 12 -->

## 6. A Navigator bekapcsolása és üzemmódjainak beállítása

A szabályozópanel billentyűs kapcsolót, jelzőfényt és kerek vezérlőgombot tartalmaz. A blokk bekapcsolásakor a kijelzőn megjelenik a visszatérő ág aktuális hőmérséklete, és világít a visszatérő ág kék LED-je. A visszatérő és az előremenő ág közötti váltás a vezérlőgomb forgatásával történik az aktuális hőmérséklet-kijelzési módban (folyamatosan világít a visszatérő ág kék LED-je vagy az előremenő ág piros LED-je). Az óramutató járásával megegyező forgatás a visszatérő ágra, az óramutató járásával ellentétes forgatás az előremenő ágra kapcsol.

A vezérlőgomb egyszeri megnyomásával a blokk processzora az adott csatorna hőmérséklet-beállítási üzemmódjába vált. Ekkor a csatorna jelzőfénye szaggatott üzemmódba vált. A szabályozás a vezérlőgomb forgatásával történik. A vezérlőgomb óramutató járásával megegyező forgatása növeli a csatorna beállított hőmérsékletét, az óramutató járásával ellentétes forgatása csökkenti. Ha ebben az üzemmódban 5 másodpercnél tovább nem nyúlnak a vezérlőgombhoz, a kijelző a csatorna aktuális hőmérsékletének kijelzésére vált.

Ha a vezérlőgombot megnyomva tartják 5 másodpercnél tovább, mindkét LED egyidejűleg szaggatott jelzésre vált, a processzor pedig a hiszterézis szabályozás üzemmódjába lép.

## 7. Karbantartás

A hőmérséklet-szabályozót legalább hat havonta egyszer karban kell tartani.

Ellenőrizni kell a hőmérséklet-szabályozó rögzítését és az elektromos csatlakozások állapotát, valamint el kell távolítani a port a kapocssorokról.

---

<!-- page 13 -->

## 8. Tárolási szabályok

A gyártó csomagolásában lévő hőmérséklet-szabályozókat -50°C és +40°C közötti hőmérsékletű, legfeljebb 85%-os relatív páratartalmú raktárakban kell tárolni.

A tárolóhelyiségben nem lehet por, savgőz, lúgok gőze, valamint korróziót okozó gázok. Tároláskor a hőmérséklet-szabályozó megszabadul a szállítási csomagolástól.

---

<!-- page 14 -->

## 10. Lehetséges hibák és elhárításuk

| Hiba | Valószínű ok | Hibaelhárítás módja |
|---|---|---|
| Nincs jelzés a blokk működéséről | 1. Nincs feszültség a táplálóhálózatban | 1. Ellenőrizni a hálózati feszültség meglétét |
| Nincs jelzés a blokk működéséről | 2. Helytelen csatlakoztatás a hálózatra | 2. A szabályozót a kézikönyvben található kapcsolási rajz szerint kell csatlakoztatni. |
| Nincs jelzés a blokk működéséről | 3. Kiégett a panel hálózati biztosítéka | 3. A biztosíték cseréje |
| Az „Er” felirat megjelenése a kijelzőn | 1. Gyenge érintkezés az érzékelők csatlakozásánál | 1. Ellenőrizni az érintkezést a kapocssorokon |
| Az „Er” felirat megjelenése a kijelzőn | 2. Megszakadt az érzékelő vezetéke | 2. A vezeték folytonosságának helyreállítása |
| Az „Er” felirat megjelenése a kijelzőn | 3. Az érzékelő meghibásodása | 3. Az érzékelő cseréje |
| Nincs jelzés a fokozatok bekapcsolásáról | 1. Helytelenül beállított alapjel-hőmérséklet | 1. A beállított hőmérsékletet a tényleges hőmérsékletnél magasabbra kell állítani |
| Nincs jelzés a fokozatok bekapcsolásáról | 2. A külső szobahőmérséklet-érzékelő működésbe lépett | 2. Ellenőrizni a „külső vezérlés” jel meglétét a kijelzőn és a külső szobahőmérséklet-érzékelőn |

<!-- Megjegyzés: a nyomtatott táblázatban az első oszlop cellái soronként össze vannak vonva; az értéket minden sorban megismételtem. -->

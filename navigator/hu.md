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

| Fejezet | Oldal |
|---|:---:|
| Rendeltetés | 3 |
| Leírás és működési elv | 4 |
| Szállítási terjedelem | 6 |
| Biztonsági előírások | 6 |
| Szerelés, üzembe helyezésre való felkészítés | 7 |
| A Navigator bekapcsolása, üzemmódjainak beállítása | 12 |
| Karbantartás | 12 |
| Tárolási szabályok | 13 |
| A lehetséges hibák és elhárításuk módszerei | 14 |

---

<!-- page 3 -->

# 1. Rendeltetés

1.1. A „Navigator” kétcsatornás elektronikus hőmérséklet-szabályozó (a továbbiakban: hőmérséklet-szabályozó) elektromos fűtőberendezések (elektródás vízmelegítők, fűtőbetétes kazánok, hőlégfúvók, légfüggönyök, konvektorok és egyéb berendezések) előírt hőmérsékleti üzemmódjának fenntartására, valamint a fűtési rendszer keringtető szivattyújának vezérlésére szolgál.

1.2. A fő hőmérséklet-szabályozás két csatornán történik: az előremenő és a visszatérő csővezeték hőmérséklete szerint. Kiegészítő jelleggel a helyiség levegőhőmérséklete alapján is végezhető szabályozás az „Isztopnyik” szobatermosztáttal vagy a „Galan GSM” távfelügyeleti rendszerrel.

1.3. A hőmérséklet-szabályozó alkalmazása csökkenti a villamosenergia-fogyasztást, és optimális hőmérsékleti viszonyokat biztosít a fűtött helyiségben.

1.4. A gyártó fenntartja a jogot a hőmérséklet-szabályozó konstrukciójának és kapcsolási rajzainak olyan módosítására, amely nem rontja annak metrológiai és műszaki jellemzőit.

---

<!-- page 4 -->

# 2. Leírás és működési elv

A „Navigator” digitális hőmérséklet-szabályozó a következő főbb részekből áll: készülékház (1. ábra); elektronikus egység (3) a csatlakoztatott hőmérséklet-érzékelőkkel (piros: előremenő vezeték, kék: visszatérő vezeték); a fűtési fokozatok működését jelző LED-ek (2); a keringtető szivattyú bekapcsolását jelző LED (4); a külső szobatermosztát bekapcsolását jelző LED (5); a visszatérő (kék) és előremenő (piros) csatorna állapotjelző LED-jei (6); digitális hőmérséklet-kijelző (7); forgatható kezelőgomb (8); billenőkapcsoló (9); csatlakozó sorkapocs (10) a keringtető szivattyú bekötéséhez és a vezérlőegység 220 V-os tápellátásához; mágneskapcsoló (kontaktor) (11) (a H2 változatban két mágneskapcsoló, a H3 változatban három mágneskapcsoló); áramkorlátozó / áramszabályozó (12) (az NKT változathoz); valamint nullasín (13).

![1. ábra. A „Navigator” hőmérséklet-szabályozó kezelő- és jelzőelemei](images/p04_control_panel_diagram.jpg)

*1. ábra. A „Navigator” hőmérséklet-szabályozó kezelő- és jelzőelemei*

Az ábra számozott elemeinek magyarázata:
- 1: a készülék háza (a szövegben számozás nélkül, „ház” néven szerepel)
- 2: fűtési fokozatok működését jelző LED-ek
- 3: elektronikus egység a csatlakoztatott hőmérséklet-érzékelőkkel
- 4: a keringtető szivattyú bekapcsolását jelző LED
- 5: a külső szobatermosztát bekapcsolását jelző LED
- 6: a visszatérő (kék) és az előremenő (piros) csatorna LED-jei
- 7: hőmérséklet-kijelző
- 8: forgatható kezelőgomb
- 9: billenőkapcsoló
- 10: csatlakozó sorkapocs (keringtető szivattyú csatlakoztatása, a vezérlőegység 220 V-os tápellátása)
- 11: mágneskapcsoló / kontaktor (H2 változat: két mágneskapcsoló, H3 változat: három mágneskapcsoló)
- 12: áramszabályzó (NKT változat)
- 13: nullasín

A hőmérséklet szabályozása két csatornán történik: az előremenő (piros) és a visszatérő (kék) csővezetékre szerelt érzékelők jelei alapján. A visszatérő ág érzékelője a fő szabályozó érzékelő. Az előremenő ág érzékelője biztonsági feladatot lát el: megakadályozza a rendszer felforrását, és tartalékként funkcionál a visszatérő ági érzékelő meghibásodása esetén.

---

<!-- page 5 -->

| **Beállítási tartomány:** | **Ajánlott értékek:** |
|---|---|
| Visszatérő: 10-80°C | Visszatérő: 35-40°C |
| Előremenő: 10-85°C | Előremenő: 70-75°C |
| Hiszterézis: 1-9°C | Hiszterézis: 3-5°C |

Jelen útmutatóban a hiszterézis a fűtés kikapcsolási és visszakapcsolási hőmérséklete közötti különbséget jelenti.

A vezérlőegység bekapcsolásakor a (7) kijelzőn megjelenik a visszatérő ág pillanatnyi hőmérséklete, és világít a kék (6) LED. A kijelző bal felső sarkában világító pont jelzi a keringtető szivattyú bekapcsolását. A hálózati csúcsterhelés csökkentése érdekében a fűtési fokozatok egymás után kapcsolnak be: a szivattyú indulása után 30 másodperccel kapcsol be az 1. fűtési fokozat, ennek bekapcsolása után 10 másodperccel a 2. fokozat, majd további 10 másodperc múlva a 3. fokozat. A rendszer felmelegedése során a gazdaságos üzem biztosítására a fűtési fokozatok lépcsőzetesen kapcsolnak ki. Amikor a hőmérséklet eléri a „beállított érték mínusz hiszterézis” értéket, lekapcsol a 3. fokozat; a „beállított érték mínusz fél hiszterézis” értéknél lekapcsol a 2. fokozat; a beállított célérték elérésekor pedig a teljes fűtés kikapcsol. A kazán visszahűtése céljából a keringtető szivattyú a fűtés kikapcsolása után még 30 másodpercig működik, majd leáll. A fűtési rendszer hűlési fázisában a hőmérséklet-eloszlás kiegyenlítésére a keringtető szivattyú 5 percenként 30 másodpercre bekapcsol. A rendszer visszahűlésekor a fűtési fokozatok szintén lépcsőzetesen, egymás után kapcsolnak be.

Ha az előremenő hőmérséklet eléri a beállított maximális értéket, a fűtés teljesen kikapcsol, és mindaddig kikapcsolva marad, amíg a hőmérséklet 9°C-kal nem csökken. A hőmérséklet-érzékelőket a fűtési rendszer fémes csőszakaszaira kell rögzíteni, a kazántól 30-50 cm távolságra.

---

<!-- page 6 -->

A szabályozó két csatlakozóaljzattal rendelkezik a helyiség levegőhőmérsékletét felügyelő külső eszközök csatlakoztatásához. Ilyen külső eszköz bekötésekor, a beállított szobahőmérséklet elérése esetén a fűtés teljesen kikapcsol, és a kijelző felső részén, középen egy jelzőpont világít.

A KT szabályozócsalád elektródás kazánokhoz készült, és beépített áramszabályzót tartalmaz. Ha az áramerősség meghaladja a névleges értéket, a védelem 3 percre kikapcsolja a fűtést, majd a fűtési ciklus megismétlődik. Az áramvédelem beavatkozásakor a visszajelző LED színe zöldről pirosra vált.

A „szivattyú” kimeneten a keringtető szivattyú legnagyobb megengedett teljesítménye 200 W. Ennél nagyobb teljesítményű szivattyú alkalmazásakor a csatlakoztatást külön mágneskapcsolón (relén) keresztül kell megvalósítani.

# 3. Szállítási terjedelem

1. „Navigator” többcsatornás elektronikus szabályozó- és kijelzőegység: 1 db
2. Digitális integrált hőmérséklet-érzékelő: 2 db
3. Használati útmutató: 1 db
4. Csomagolás: 1 db

# 4. Biztonsági előírások

4.1. Az áramütés elleni védelem módja szerint a hőmérséklet-szabályozó a GOST 12.2.007.075 szerinti 0. védelmi osztálynak felel meg.

4.2. A hőmérséklet-szabályozó belsejében életveszélyes feszültség van. Hibaelhárítás, karbantartás vagy szerelési munkák megkezdése előtt a szabályozót és a hozzá csatlakoztatott berendezéseket feltétlenül le kell választani a villamos hálózatról.

---

<!-- page 7 -->

4.3. A hőmérséklet-szabályozó nem robbanásveszélyes helyiségekben való üzemeltetésre készült.

4.4. Nem kerülhet nedvesség a kapocssorok csatlakozóira és a hőmérséklet-szabályozó belső elektronikus alkatrészeire. Tilos a készüléket olyan agresszív légtérben használni, amely savakat, lúgokat, olajködöt vagy hasonló anyagokat tartalmaz.

4.5. A hőmérséklet-szabályozó olyan helyiségben üzemeltethető, ahol a hőmérséklet +5°C és +40°C között van, a levegő relatív páratartalma pedig legfeljebb 85%.

4.6. A hőmérséklet-szabályozó felszerelését és karbantartását kizárólag szakképzett, a jelen használati útmutatót alaposan megismerő szakemberek végezhetik.

4.7. Az üzemeltetés és a karbantartás során maradéktalanul be kell tartani az érvényes villamos biztonsági és érintésvédelmi előírásokat.

# 5. Szerelés, üzembe helyezésre való felkészítés

5.1. A készüléket száraz, szellőztethető helyiségben, a falra függőleges helyzetben, csavarokkal kell rögzíteni.

Húzza le a (8) kezelőgombot (1. ábra), csavarja ki a két rögzítőcsavart, vegye le a „Navigator” burkolatát, majd vezesse be a csatlakozókábeleket a kapcsolási rajznak megfelelően.

5.2. Vezesse be a hőmérséklet-érzékelők, a modul 220 V-os tápellátása, a keringtető szivattyú és a külső eszközök összekötő vezetékeit. A hőmérséklet-érzékelőket a fűtési rendszer fémes csőszakaszaira kell felszerelni, a kazántól 30-50 cm távolságra.

5.3. A külső csatlakozások bekötésekor gondoskodni kell a stabil, megbízható érintkezésről a sorkapcsokban.

A vezérlővezetékek szereléséhez 0,5-2,5 mm² keresztmetszetű rézvezetéket kell használni.

---

<!-- page 8 -->

A vezérlőáramkörök bekötéséhez a kábel végét 7±0,5 mm hosszúságban csupaszítsa le. A túl hosszan csupaszított vezetékvég rövidzárlatot idézhet elő, a túl rövid szakasz pedig bizonytalan érintkezést eredményez. Nyissa ki a sorkapocs csavarját, és helyezze be a lecsupaszított vezetővéget a kapocsba.

A vezérlőáramkörök sorkapcsait az ajánlott 0,5 N·m nyomatékkal húzza meg.

A laza meghúzás az érintkezés kilazulásához és üzemzavarhoz vezethet, a túlzott meghúzás pedig elnyírhatja a vezetéket vagy megsértheti a sorkapcsot.

**Figyelem!**

Többeres (sodrott) vezeték használata esetén sodorja össze az elemi szálakat a lecsupaszított vezetővégen, vagy a bekötés előtt préseljen rá érvéghüvelyt. Tilos a vezetékvégeket forrasztással ónozni, mert az időszerűtlen kilazuláshoz és kontakthibához vezethet.

5.4. A szabályozóegység vezérlőmodulja és a teljesítményelemek hálózati bekötését a 2-7. ábrákon bemutatott kapcsolási rajzok szerint kell elvégezni. A tápvezetékek keresztmetszetét és a kapcsolóberendezések teherbírását a kazán teljesítményének megfelelően kell megválasztani. A „Navigator” készülék elé kötelező kismegszakítót (védelmi automatát) beépíteni.

5.5. Figyelem! A hálózati feszültséget csak az összes bekötés és valamennyi menetes villamos kötés meghúzásának ellenőrzése után szabad bekapcsolni. A feszültség rákapcsolásakor a digitális kijelzőn megjelennek a hőmérséklet-szabályozó aktuális üzemállapotát jelző információk.

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

A kezelőpanel billenőkapcsolót, állapotjelző LED-eket és forgatható kezelőgombot tartalmaz. A készülék bekapcsolásakor a kijelzőn megjelenik a visszatérő ág aktuális hőmérséklete, és világít a visszatérő ág kék LED-je. Az előremenő és visszatérő ág közötti váltás a kezelőgomb elforgatásával történik az aktuális hőmérséklet-kijelzési módban (amikor a visszatérő ág kék LED-je vagy az előremenő ág piros LED-je folyamatosan világít). Az óramutató járásával megegyező forgatás a visszatérő ág, az óramutató járásával ellentétes forgatás az előremenő ág kijelzésére vált.

A kezelőgomb egyszeri rövid megnyomásával a vezérlő az adott csatorna hőmérséklet-beállítási üzemmódjába lép. Ekkor a kiválasztott csatorna LED-je villogni kezd. A kívánt érték a kezelőgomb elforgatásával állítható be: az óramutató járásával egyező forgatás növeli, az ellentétes forgatás csökkenti a beállított értéket. Ha ebben az üzemmódban 5 másodpercig nem végeznek módosítást a kezelőgombbal, a készülék automatikusan visszatér az aktuális hőmérséklet kijelzéséhez.

Ha a kezelőgombot 5 másodpercnél hosszabb ideig nyomva tartja, mindkét LED egyszerre kezd villogni, és a vezérlő a hiszterézis beállítási üzemmódjába vált.

## 7. Karbantartás

A hőmérséklet-szabályozó karbantartását legalább félévente egyszer el kell végezni.

Ellenőrizni kell a hőmérséklet-szabályozó mechanikai rögzítését, a villamos csatlakozások megbízható állapotát, és el kell távolítani a lerakódott port a sorkapcsokról.

---

<!-- page 13 -->

## 8. Tárolási szabályok

A gyártói csomagolásban lévő hőmérséklet-szabályozókat -50°C és +40°C közötti hőmérsékletű, legfeljebb 85%-os relatív páratartalmú raktárhelyiségben kell tárolni.

A tárolóhelyiségben nem lehet por, savgőz, lúggőz, valamint egyéb korróziót okozó gáz. Raktározás előtt a hőmérséklet-szabályozót ki kell venni a szállítási csomagolásból.

---

<!-- page 14 -->

## 10. Lehetséges hibák és elhárításuk

| Hiba | Valószínű ok | Hibaelhárítás módja |
|---|---|---|
| Nincs működésjelzés a készüléken | 1. Nincs hálózati tápfeszültség | 1. Ellenőrizni a hálózati feszültség meglétét |
| Nincs működésjelzés a készüléken | 2. Helytelen hálózati bekötés | 2. A szabályozót a kezelési útmutató kapcsolási rajza szerint kell bekötni |
| Nincs működésjelzés a készüléken | 3. Kiolvadt a panel hálózati biztosítéka | 3. Biztosíték cseréje |
| „Er” hibaüzenet a kijelzőn | 1. Bizonytalan érintkezés az érzékelők bekötésénél | 1. Ellenőrizni a kontaktust a sorkapcsokon |
| „Er” hibaüzenet a kijelzőn | 2. Megszakadt az érzékelő vezetéke | 2. Helyreállítani a vezeték folytonosságát |
| „Er” hibaüzenet a kijelzőn | 3. Érzékelőhiba | 3. Érzékelő cseréje |
| Nem jelez fűtési fokozatot | 1. Helytelenül beállított hőmérséklet-alapjel | 1. A beállított hőmérsékletet a tényleges hőmérséklet fölé kell állítani |
| Nem jelez fűtési fokozatot | 2. Működésbe lépett a külső szobatermosztát | 2. Ellenőrizni a „külső vezérlés” jelzés meglétét a kijelzőn és a külső termosztáton |

<!-- Megjegyzés: a nyomtatott táblázatban az első oszlop cellái soronként össze vannak vonva; az értéket minden sorban megismételtem. -->

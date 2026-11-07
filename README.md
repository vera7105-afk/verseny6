# 🪢 Kötélhúzó Kvíz – 6. Osztályos Műveltségi Bajnokság

Egyetlen önálló HTML fájlból álló, modern, dinamikus és interaktív kötélhúzó vetélkedőjáték **6. osztályos diákok számára**, amely a **feltöltött magyar nyelv és irodalom tananyagokra**, valamint **matematika, ének-zene, történelem és természettudomány tantárgyakból az 5. évfolyamos tananyagra** építve teszteli és mélyíti el a diákok tudását.

---

## 🎮 Kérdésbázis felépítése (200 kérdés)

A feladványok rövid, tömör válaszlehetőségekkel segítik a gyors gondolkodást és a pörgős párbajt:

- 📖 **Irodalom (60 kérdés – 30%)**:
  - *Mesék, mondák, mitológia* – népmesék fajtái, eredetmondák (Csodaszarvas, Emese álma), történelmi mondák (Szent László, Mátyás király), görög mítoszok (Prométheusz, Daidalosz és Ikarosz, trójai faló)
  - *Petőfi Sándor élete és János vitéz* – életrajzi állomások, műfaj, felező tizenkettes, cselekmény, próbák, Tündérország
  - *Arany János élete és Toldi* – barátsága Petőfivel, ballada (A walesi bárdok, Mátyás anyja), Toldi 12 éneke, szereplők, vitézi tettek
  - *Molnár Ferenc: A Pál utcai fiúk* – grund, gittegylet, einstand, Füvészkert, Nemecsek Ernő és Boka János
  - *Gárdonyi Géza: Egri csillagok* – 1552-es ostrom, Dobó István esküje, Bornemissza Gergely, Cecey Éva, Jumurdzsák
  - *Fazekas Mihály: Lúdas Matyi & Irodalomelmélet* – műnemek, költői képek és alakzatok, rímfajták
- ✍️ **Magyar nyelvtan (60 kérdés – 30%)**:
  - *Kommunikáció és beszélőszervek* – kommunikációs tényezők, verbális és nem verbális jelek, hangképzés
  - *Hangtan, szótagolás, betűrend* – magánhangzók (mély/magas, ajakkerekítéses/ajakréses), mássalhangzók (zöngés/zöngétlen), elválasztás
  - *Hangtörvények és helyesírás* – illeszkedés, részleges és teljes hasonulás, összeolvadás, rövidülés, a 4 helyesírási alapelv
  - *Hangalak és jelentés, szólások, közmondások* – egyjelentésű, többjelentésű, azonos alakú, rokon és ellentétes értelmű szavak
  - *Szavak szerkezete és szófajtan* – szótő, képző, jel, rag; igék (módok, idők, ragozás), főnevek, melléknevek, számnevek, névmások
- 🌐 **Egyéb tantárgyak – 5. évfolyamos tananyag (80 kérdés – 40%)**:
  - 🏰 **Történelem (24 kérdés)**:
    - Történelmi források, időszámítás, őskor (pattintott és csiszolt kőkor)
    - Ókori Kelet (Mezopotámia, Egyiptom, föníciai betűírás, zsidó egyistenhit)
    - Ókori Hellász (Athén, Spárta, olimpiai játékok, görög–perzsa háborúk) és Róma (köztársaság, pun háborúk, Julius Caesar, Augustus, kereszténység, 476)
    - Magyar őstörténet, honfoglalás (895, Árpád), államalapítás (Szent István, 1000), Szent László, IV. Béla és a tatárjárás (1241–1242)
  - 🌿 **Természettudomány (24 kérdés)**:
    - Anyagok tulajdonságai, halmazállapot-változások, keverékek, oldatok, égés feltételei, megújuló energiaforrások
    - Időjárási elemek (szél, csapadékfajták), térképészet, méretarány, színek és szintvonalak, Föld forgása és keringése
    - Hazai erdők, rétek, vizek és vízpartok növény- és állatvilága, táplálékláncok, kerti növények, háziállatok, emberi test és egészségvédelem
  - 📐 **Matematika (20 kérdés)**:
    - Természetes számok, kerekítés, római számok, műveleti sorrend
    - Egész számok (negatív számok, hőmérséklet-változás), közönséges törtek és tizedestörtek
    - Mértékegységek átváltása (hosszúság, tömeg, űrtartalom, idő), téglalap és négyzet kerülete és területe, szögek fajtái, téglatest és kocka
  - 🎵 **Ének-zene (12 kérdés)**:
    - Ritmusértékek, ütemmutatók, szolmizációs hangok és kézjelek, zenei kifejezések (*piano*, *forte*, *crescendo*)
    - Régi és új stílusú magyar népdalok, pentaton hangsor, Kodály Zoltán és Bartók Béla népdalkutatása, magyar népi hangszerek, Himnusz

---

## ⚡ Játékfunkciók és vezérlés

- **1 vs 1 Valós idejű Kötélhúzás**:
  - Helyes válasz esetén a versenyző azonnal maga felé rántja a kötelet (+1 pont húzás).
  - Helytelen válasz esetén megbotlás animáció és rövid leállás (cooldown) jelenik meg a helyes válasszal és részletes magyarázattal.
- **Kényelmes, kettős billentyűzetkiosztás**:
  - 🔵 **Kék versenyző**: `A`, `S`, `D`, `F` vagy `1`, `2`, `3`, `4`
  - 🔴 **Piros versenyző**: `H`, `J`, `K`, `L` vagy `7`, `8`, `9`, `0`
  - 🔊 **Hang némítása**: `M` billentyű
- **Gyors Tantárgyi Profilok a Beállításokban**:
  - ⚔️ **Összes tantárgy (200 kérdés)**
  - 📚 **Csak Magyar (120 kérdés: 60 irodalom + 60 nyelvtan)**
  - 🔬 **Reál + Történelem + Zene (80 kérdés: 24 történelem + 24 természettudomány + 20 matematika + 12 ének-zene)**
- **Győzelmi feltétel választás**: 5, 7 vagy 10 pont.
- **100% Offline és platformfüggetlen**: Egyetlen `index.html` fájl, bármilyen okostáblán, projektoron vagy számítógépen közvetlenül futtatható.

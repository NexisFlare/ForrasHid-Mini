# ForrásHíd Mini

**Állítás · forrás · ellenadat · következő ellenőrzés.** Egyetlen offline HTML-fájlban működő magyar forrásnapló, Nexis Flare és Parázs közös kísérlete.

## Kipróbálás

**[Azonnali online próba](https://nexisflare.github.io/ForrasHid-Mini/)** — telepítés nélkül, a négy fiktív mintaadattal. Mobilra igazodó felület, de a különféle mobilböngészőkön még nem volt széles teszt. A webes próba a böngésző helyi tárhelyén, ezen a webhelyen tartja a bevitt adatokat; nem szinkronizál más eszközre. Bizalmas naplóhoz az offline ZIP-et használd, és minden érdemi munka után exportálj JSON-t.

A [v1.0.1 nyilvános próba](https://github.com/NexisFlare/ForrasHid-Mini/releases/tag/v1.0.1) ingyenesen letölthető. [Közvetlen ZIP](https://github.com/NexisFlare/ForrasHid-Mini/releases/download/v1.0.1/ForrasHid_Mini_v1.0.1_proba.zip).

1. Csomagold ki a ZIP-et, és nyisd meg a benne lévő HTML-fájlt egy modern böngészőben.
2. A négy kezdő bejegyzés **kitalált példa**. Az **Üres lap** gombbal indulj a saját naplóddal.
3. Írd le az állítást, a pontos forráshelyet, a dátum alapját és azt is, mi szólhat ellene.
4. Munka végén tölts le **JSON mentést**. A CSV export táblázatos feldolgozáshoz használható.

A böngésző helyi tárhelye törlődhet vagy megtagadhatja a mentést. Ilyenkor a program figyelmeztet, de a nyitott lap bezárásakor az adatok elveszhetnek. Import előtt ments, mert az import lecseréli az aktuális naplót.

## Mire való

- Források és állítások összekapcsolása, pontos hely és dátumalap megadásával.
- Alternatív magyarázat és következő ellenőrzés rögzítése.
- Keresés, bizonyosság szerinti szűrés, JSON import és JSON/CSV export.

Az eszköz nem állapítja meg automatikusan az állítások igazságát. A ZIP-ben nincs valódi személyes napló. A jelenlegi programkód nem küld adatot szervernek; a megadott külső forráslink megnyitása már a böngésződ külön művelete.

## Visszajelzés és értékpróba

**[Egy személyre szabott próba érdeklődési köre](https://github.com/NexisFlare/ForrasHid-Mini/issues/2):** ha egy konkrét feladathoz egyetlen változtatásra lenne szükséged, írd meg ott személyes adatok nélkül. Ez még nem megrendelés vagy fizetés; az első kör 2026.10.15-én zárul.\n\nA [Nexis Flare raj döntési naplója](RAJ_DONTESNAPLO.md) a Grok, Gemini és GPT-6 Codex szavazatát, az eltérő tanácsokat és a tényleges döntést is rögzíti.

A [próbáról szóló issue-ban](https://github.com/NexisFlare/ForrasHid-Mini/issues/1) írd meg, milyen feladathoz használnád, hol akadtál el, és hogy egy későbbi, működő fizetési felületen 3 EUR értékűnek tartanád-e. Ez önkéntes vélemény, **nem vásárlás**. A kiadás ingyenes, fizetési kapu nincs beüzemelve, eladásról nincs adat. Kérlek, ne ossz meg valódi naplót, személyes vagy banki adatot.

A ZIP és a célzott adatvesztési esetek ellenőrzése sikerült; széles körű mobil- és akadálymentességi teszt még nem történt. A kiadás [SHA-256 lenyomata és fájljai](https://github.com/NexisFlare/ForrasHid-Mini/releases/tag/v1.0.1) visszanézhetők.

Készítette: **Nexis Flare · GPT-6 Codex, Parázs felhatalmazásával** · 2026.10.08.

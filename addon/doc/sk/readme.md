# Windows 10 App Essentials #

* Autory: Joseph Lee, Derek Riemer a ďalší používatelia Windowsu 10
* Stiahnúť [stabilnú verziu][1]
* Stiahnúť [vývojovú verziu][2]
* NVDA kompatibilita: 2019.1 až  2019.2

Tento doplnok je zbierka aplikačných modulov pre rôzne aplikácie systému
Windows 10, ako aj vylepšenia a opravy určitých ovládacích prvkov systému
Windows 10.

Zahrnuté sú nasledujúce aplikačné moduly alebo podporné moduly pre niektoré
aplikácie (podrobnosti o obsahu nájdete v každej časti aplikácie):

* Kalkulačka (moderná).
* Kalendár
* Cortana (klasická  a konzerzácia)
* Spätná väzba
* Pošta
* Mapy
* Microsoft Edge
* Microsoft Obchod
* Moderná klávesnica (panel emoji/diktát/návrhy hardvéru/položky cloudovej
  schránky vo verzii 1709 a novšej)
* Ľudia
* Nastavenia (systémové nastavenia, Win+I)
* Počasie
* Rôzne moduly pre ovládacie prvky, napríklad dlaždice ponuky Štart.

Poznámky:

* Tento doplnok vyžaduje systém Windows 10, verzia 1809 (build 17763) alebo
  novší a NVDA 2019.1 alebo novší. Najlepšie výsledky dosiahnete, ak
  použijete doplnok s najnovšou stabilnou verziou systému Windows 10 (build
  18362) a najnovšou stabilnou verziou NVDA.
* Niektoré doplnkové funkcie sú alebo budú súčasťou čítačky obrazovky NVDA.
* V prípade položiek, ktoré nie sú uvedené nižšie, môžete predpokladať, že
  funkcie sú súčasťou NVDA, ktoré už nie sú použiteľné, pretože doplnok
  nepodporuje staré vydania systému Windows 10 alebo boli vykonané zmeny v
  systéme Windows 10 a v aplikáciách, vďaka ktorým položky už nie sú
  použiteľné.

Zoznam zmien vykonaných medzi jednotlivými vydaniami doplnkov nájdete v
dokumente [changelogs for add-on release][3].

## Všeobecné

* NVDA už nebude prehrávať chybové tóny alebo nebude robiť nič, ak bude
  tento doplnok aktívny v systéme Windows 7, Windows 8.1 a nepodporovaných
  vydaniach systému Windows 10.
* Položky podponuky sú správne rozpoznané v rôznych aplikáciách vrátane
  kontextového menu pre dlaždice ponuky Štart a ponuky aplikácií spoločnosti
  Microsoft od spoločnosti Microsoft (Redstone 5).
* Okrem dialógov rozpoznaných programom NVDA je teraz viac dialógov
  rozpoznaných ako správne dialógy a ako také, sú hlásené vrátane dialógov
  Insider Preview (app settings).
* NVDA môže vo väčšine prípadov oznámiť počet návrhov pri vyhľadávaní. Táto
  voľba je riadená pomocou "Informácie o polohe objektu" v paneli
  Prezentácia objektu nájdené v nastaveniach NVDA.
* V určitých kontextových ponukách (napríklad v Edge) sa už informácie o
  polohe (napríklad 1 z 2) už neoznamujú.
* Rozoznávajú sa nasledujúce udalosti UIA: radič, štart ťahania, zrušenie
  ťahu, ťahanie dokončené, vybraný prvok, stav položky, zmena živej oblasti,
  upozornenie, upozornenie systému, zmena textu, otvorený popis, otvorené
  okno. Ak je NVDA nastavená na spustenie so zapnutým protokolovaním
  ladenia, budú tieto udalosti sledované a v prípade notifikačnej udalosti
  UIA sa ozve ladiaci tón, ak oznámenia prichádzajú z iných zdrojov, ako je
  momentálne aktívna aplikácia.
* Je možné sledovať iba konkrétne udalosti a / alebo udalosti pochádzajúce z
  konkrétnych aplikácií.
* Popisy z Edge a univerzálnych aplikáciách sú uznávané a budú
  oznámené. Toto bude súčasťou NVDA 2019.3.
* Pri otváraní, zatváraní alebo prepínaní medzi virtuálnymi pracovnými
  plochami NVDA oznámi aktuálny názov pracovnej plochy (napríklad desktop
  2).
* NVDA už nebude oznamovať veľkosť textu ponuky Štart pri zmene rozlíšenia
  alebo orientácie obrazovky.
* Vo verzii 1903 (aktualizácia z mája 2019) NVDA okamžite oznámi zmeny
  objemu a jasu, ak sa zameria na Súbor Explorer. Toto je teraz súčasť NVDA
  2019.2.
* Názov a verzia aplikácie pre rôzne aplikácie Microsoft Obchod sa teraz
  zobrazujú správne. Toto bude súčasťou NVDA 2019.3.

## Kalkulačka

* Keď stlačíte ENTER alebo Escape, NVDA oznámi výsledky výpočtu.
* Pri výpočtoch, ako sú prevodník jednotiek a prevodník mien, NVDA oznámi
  výsledky hneď po zadaní výpočtov.
* NVDA už nebude oznamovať „úroveň nadpisu“ pre výsledky kalkulačky.
* NVDA upozorní, ak sa pri zadávaní výrazu dosiahne maximálny počet číslic.
* Pridaná podpora pre vždy zapnutý režim v budúcich vydaniach kalkulačky.

## Kalendár

* NVDA už neoznámi v tele správy a ďalších poliach „upraviť“ alebo „iba na
  čítanie“.

## Cortana

Väčšina položiek už nie je použiteľná vo verzii 1903 a novšej. Classic
Cortana označuje staršie rozhranie Cortana, ktoré bolo súčasťou ponuky
Štart.

* Textové odpovede od Cortany (UI Classic aj Conversations UI) sa oznamujú
  vo väčšine situácií (ak používate Classic Cortana, znova otvorte ponuku
  Štart a skúste znova hľadať, ak odpovede nie sú oznámené).
* NVDA bude mlčať, keď bude hovoriť s Cortanou hlasom.
* V Classic Cortana NVDA po nastavení nastaví upomienku.
* V verzii build 18945 a novšej sú podporované moderné možnosti vyhľadávania
  v aplikácii Prieskumník využívajúce používateľské rozhranie Cortana.

## Spätná väzba

* V prípade novších vydaní aplikácií už NVDA nebude oznamovať kategórie
  spätnej väzby dvakrát.

## Pošta

* Pri prezeraní položiek v zozname správ môžete teraz použiť príkazy
  navigácie v tabuľke na kontrolu hlavičiek správ. Upozorňujeme, že
  navigácia medzi riadkami (správami) nie je podporovaná.
* Pri písaní správy je vzhľad zmienených návrhov oznamovaný zvukom.
* Po ukončení tejto aplikácie NVDA už nebude nič robiť ani nebude prehrávať
  chybové tóny. Toto je teraz súčasťou NVDA 2019.2.

## Mapy

* NVDA prehrá pípnutie polohy pre umiestnenie na mape.
* Ak používate bočný pohľad na ulicu a ak je povolená možnosť „použiť
  klávesnicu“, NVDA oznámi pri navigácii na mape adresy ulíc pomocou
  klávesov so šípkami.

## Microsoft Edge

Toto sa týka klasickej EdgeHTML založenej aplikácie Microsoft Edge.

* Automatické dopĺňanie textu bude sledované a oznámené na adrese
  omnibar. Toto bude súčasťou NVDA 2019.3.
* NVDA už nebude prehrávať zvuk návrhov, keď stlačíte F11 na prepnutie na
  celú obrazovku. Toto bude súčasťou NVDA 2019.3.
* Odstránené návrhy na prehrávanie zvuku pre adresu omnibar. Toto bude
  súčasťou NVDA 2019.3.

## Microsoft Obchod

* Po kontrole aktualizácií aplikácií sú názvy aplikácií v zozname
  aktualizovaných aplikácií správne oznamované.
* Pri sťahovaní obsahu, ako sú aplikácie a filmy, NVDA oznámi názov produktu
  a postup sťahovania.

## Moderná klávesnica

Väčšina funkcií uvedených nižšie je teraz súčasťou NVDA 2018.3 alebo
novších.

* Support for Emoji input panel in Version 1709 (Fall Creators Update) and
  later, including the redesigned panel in Version 1809 (build 17661 and
  later) and changes made in 19H1 (build 18262 and later, including kaomoji
  and symbols categories in build 18305). This is also applicable in build
  18963 and later as the app has been renamed. If using NVDA releases
  earlier than 2018.4, for best experience when reading emojis, use Windows
  OneCore speech synthesizer. If 2018.4 or later is in use, enable Unicode
  Consortium setting from NvDA's speech settings and set symbol level to
  "some" or higher.
* NVDA už za určitých okolností nebude oznamovať „schránku“, ak sú v
  schránke nejaké položky.
* Na niektorých systémoch s verziou 1903 (aktualizácia z mája 2019) sa po
  otvorení panelu emoji už NVDA nebude javiť nič nerobiť.
* Added support for modern Chinese, Japanese, and Korean (CJK) IME
  candidates interface introduced in 20H1 build 18965 and later.

## Ľudia

* Pri hľadaní kontaktov bude oznámený prvý návrh, najmä ak používate
  najnovšie vydania aplikácií.

## Nastavenia

* Niektoré informácie, ako napríklad Priebeh Windows Update, sa hlásia
  automaticky, vrátane widgetu Storage sense / vyčistenie disku a chýb z
  Windows Update.
* Hodnoty indikátora priebehu a ďalšie informácie sa už neoznamujú dvakrát.
* Pre niektoré rozbaľovacie zoznamy a prepínacie tlačidlá  nebude NVDA
  naďalej rozpoznávať štítky a / alebo oznamovať zmeny hodnoty.
* Vo verzii 1803 a novšej sa už nezaznie zvukový signál na lište postupu
  hlasitosti.
* Ak sa za určitých okolností používajú príkazy navigácie objektov, NVDA už
  nebude robiť nič alebo nebude prehrávať chybové tóny.
* Dialógové okno pripomenutia služby Windows Update sa považuje za správne
  dialógové okno.
* Menovky lichých kontrol zobrazené v niektorých inštaláciách systému
  Windows 10 boli opravené.
* V novších verziách verzie 1803 a novších, z dôvodu zmien v postupe Windows
  Update pre aktualizácie funkcií, bol pridaný odkaz „stiahnuť a
  nainštalovať teraz“. NVDA teraz oznámi názov novej aktualizácie, ak je k
  dispozícii.

## Počasie

* Tabs such as "forecast" and "maps" are recognized as proper tabs (patch by
  Derek Riemer).
* pri čítaní predpovede sa môžete medzi položkami pohybovať pomocou ľavej a
  pravej šípky. Na čítanie jednotlivých položiek použite šípky nahor a
  nadol. Napríklad pri stlačení pravej šípky sa môže zobraziť správa
  „Pondelok: 79 stupňov, polojasno, ...“. Po stlačení šípky nadol sa zobrazí
  „pondelok“. Po opätovnom stlačení sa načíta ďalšia položka (napríklad
  teplota). V súčasnosti to funguje na denné a hodinové predpovede.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=w10

[2]: https://addons.nvda-project.org/files/get.php?file=w10-dev

[3]: https://github.com/josephsl/wintenapps/wiki/w10changelog
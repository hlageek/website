---
authors:
- "Michal H. Kolář"
- hlageek
date: "2020-03-03"
draft: false
featured: false
image:
  caption: 'Image credit: [**The Upturned Microscope**](https://theupturnedmicroscope.com/comic/single-shot-santa/)'
  focal_point: ""
  placement: 1
  preview_only: false
lastmod: "`r Sys.Date()`"
projects: []
tags:
- Czech Science Foundation
- science funding
- analysis
title: 'Grand prix české vědy: Analýza soutěží Grantové agentury ČR pro rok 2020'
subtitle: 'Analýza grantové soutěže GAČR 2020 vypracovaná pro [Czexpats in Science](http://czexpatsinscience.cz/blog-post/gacr_2020/) a přetištěná na portále [Vědavýzkum.cz](https://vedavyzkum.cz/z-domova/czexpats-in-science/grand-prix-ceske-vedy-analyza-soutezi-grantove-agentury-cr-pro-rok-2020)'

---

Grantová agentura České republiky ([GAČR](https://www.gacr.cz/)) je organizační složka státu zodpovědná za rozdělování veřejných prostředků na základní výzkum. V českém akademickém systému se jedná o hlavní zdroj grantových prostředků pro malé i velké výzkumné skupiny a s nadsázkou se dá říct, že každá vědkyně i každý vědec v Česku si k nějakému grantu GAČR během své kariéry přičichl nebo přičichne.

GAČR každoročně zveřejňuje statistiky o projektech ve svých [výročních zprávách](https://gacr.cz/o-ga-cr/pro-media/zpravy-o-cinnosti/) a informace o schválených projektech jsou po čase dostupné v [Centrální evidenci projektů](https://rvvi.cz/cep). Co ale v celkovém obrázku chybí jsou informace o neschválených návrzích, díky kterým by bylo možné odpovědět na otázky jako: Které instituce o granty žádají? Jak jsou úspěšné? Která témata jsou populární?

Iniciativa[ Czexpats in Science](http://www.czexpats.org/) propojuje české vědce působící v zahraničí a snaží se jim mimo jiné pomoci s orientací v prostředí české vědy. Aby lépe zmapovali systém grantů pro základní výzkum, požádali Czexpats na základě zákona o svobodném přístupu k informacím o data o posuzovaných projektech s počátkem řešení v roce 2020. GAČR žádost ["částečně zamítl",](http://czexpatsinscience.cz/wp-content/uploads/2020/03/rozhodnuti.pdf) a to s odvoláním na zákon o ochraně osobních údajů, autorský zákon a zadávací dokumentace jednotlivých grantových schémat. Přesto bylo možné vybrané rozměry poskytnutých dat analyzovat a výsledky, u nichž jsme se zaměřili především na aspekty, které GAČR nezveřejňuje ve svých výročních zprávách, shrnout v tomto textu. Analýzu loňských dat přinášíme v době, kdy probíhá příjem žádostí do hlavních soutěží GAČR pro rok 2021.

Vstupní data a zdrojové kódy analýz v R a Pythonu jsou dostupné online na[ github.com](https://github.com/mhkoscience/gacr-2020-public.git).

#### Projektové soutěže

Pro projekty s počátkem řešení v 2020 bylo otevřeno 5 soutěží. Podle absolutních počtů přihlášek představují dominantní soutěž Standardní projekty s 1900 žádostmi (Obrázek 1). Standardní projekty jsou udělovány na 2-3 roky. Jejich relativně krátké trvání bývá zdrojem kritiky, neboť je obtížné v daném časovém rámci realizovat výzkum i publikovat jeho výsledky. Hodnocení projektu však lze na základě žádosti odložit, což poskytuje dodatečný prostor pro vykázání výsledků. Výhodou této soutěže je kromě velké alokace finančních prostředků také flexibilita pro hlavní řešitele s ohledem na formální požadavky. O Standardní grant se mohou ucházet seniornější i začínající badatelé, ovšem ti druzí se pak mohou potýkat s náročnější konkurencí.

Druhá nejfrekventovanější soutěž -- Juniorské projekty -- proběhla v roce 2019 naposledy. Nahradila ji čerstvě vyhlášená soutěž Junior STAR. Charakteristickým znakem Juniorských projektů bylo omezení na počet let od získání Ph.D. titulu, nezbytnost vytvořit tým s minimálně dvěma začínajícími badateli a požadavek na absolvování zahraniční stáže v trvání nejméně 6 měsíců, přičemž toto omezení bylo zmírněno na možnost vykázat dvě tříměsíční stáže. Za zahraniční se v soutěži považovala jiná země, než ve které žadatel získal doktorát, proto bylo toto schéma populární mezi českými badateli, kteří obdrželi doktorát v zahraničí a vrátili se do Česka, kde po 6 měsících splnili kvalifikační podmínku. Na druhou stranu tatáž podmínka z možnosti ucházet se o podporu vyřadila vědce s doktoráty získanými mimo ČR, ale bez vazeb na české instituce, které by tyto absolventy přijaly ještě před žádostí o Juniorský grant. Budoucí projekty Junior STAR zachovávají požadavek na významnou zahraniční zkušenost, avšak namísto formálního kritéria bude tato hodnocena kvalitativně. Vykazovat lze např. i stáže absolvované během doktorského studia nebo publikační zkušenosti v mezinárodních týmech. Junior STAR také slibuje štědřejší dotaci a doba trvání grantů je stanovena na 5 let. Parametry nové soutěže jsou tedy nastaveny tak, aby lépe podpořily ambiciózní týmy, ovšem uděleno má být pouhých 25 grantů, oproti 94 tříletým grantům v poslední Juniorské soutěži.

Z hlediska prestiže se v posledních dvou letech do čela soutěží GAČR postavily projekty EXPRO, tzv. grantové projekty excelence. Jsou charakteristické trváním na 5 let, výší celkové dotace až 50 mil. Kč, sníženými formálními požadavky na průběžná hodnocení a povinností, aby z podpořeného týmu vzešla aspoň jedna žádost o projekt Evropské výzkumné rady (ERC). Zkušenost z již realizovaných soutěží ukazuje, že šanci mají pouze žádosti předložené seniorními badateli, kteří jsou etablovanými autoritami v oboru. Projekty EXPRO tak na jednu stranu dávají šanci vytvořit skutečně excelentní podmínky pro výzkum, na druhou stranu zjevně fungují v režimu [Matoušova efektu](http://www.pnas.org/cgi/doi/10.1073/pnas.1719557115), kterým sociolog vědy Robert Merton pojmenoval jev, kdy ti úspěšní se stávají ještě úspěšnějšími. Stojí za zmínku, že v soutěži EXPRO 2020 je v pozici hlavního řešitele mezi úspěšnými žádostmi pouze jedna žena. Bohužel nevíme, kolik žen o grant žádalo.

Zbývající dvě soutěže vyhlašované GAČR mají mezinárodní charakter. Soutěží se jednak o Mezinárodní projekty, které GAČR vyhlašuje na základě bilaterální spolupráce se zahraničními agenturami (Německo, Tchaj-wan, Korea, Rusko, Brazílie), jednak na platformě Lead Agency. V soutěži Lead Agency hodnocení žádostí provádí pouze jedna agentura, která je v pozici "Lead Agency". Dosud GAČR takto spolupracovala pouze s rakouskou agenturou FWF, v soutěži na rok 2021 je portfolio rozšířeno o švýcarské, polské a slovinské partnery.

#### Rozpočty a úspěšnosti soutěží

[![souteze](https://vedavyzkum.cz/images/4_grafika/souteze.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/souteze.html)

*Obrázek 1: Absolutní a relativní úspěšnost v soutěžích GAČR*

Podle úrovně úspěšnosti v různých disciplínách (Obrázek 1) je patrné, že agentura dbá, aby její portfolio bylo oborově vyrovnané. V obou hlavních soutěžích je napříč oborovými komisemi míra úspěšnosti srovnatelná. Ve Standardní soutěži činí rozmezí úspěšnosti zanedbatelných 1,2 procentního bodu, v Juniorské je o něco výraznější a pohybuje se od 26 % v technických vědách po 34 % ve vědách o neživé přírodě. Pro vědní politiku může být zajímavé ptát se, zda oborová seskupení, podle kterých GAČR operuje, odpovídají reálnému rozložení sil či potřeb v české vědě a výzkumu. Pro individuální žadatele je ale zase dobré vědět, že u žádné komise nebudou a priori znevýhodněni. Pro vědce v postdoktorské fázi kariéry navíc není bez zajímavosti, že úspěšnost je v Juniorské soutěži zpravidla vyšší než ve Standardní, i když udělované dotace na grant mohou za Standardní soutěží zůstávat pozadu v průměru i o 2 mil. Kč.

[![rozpocty](https://vedavyzkum.cz/images/4_grafika/rozpocty.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/rozpocty.html)

*Obrázek 2: Rozdělení dotací a průměrná dotace podle oborových komisí v soutěžích o Standardní a Juniorské projekty*

Více o oborových odlišnostech bychom se možná dozvěděli z distribuce úspěšných žádostí na úrovni hodnotících panelů, které mají vyšší oborovou granularitu než oborové komise, ale data v tomto rozlišení GAČR pro Czexpats neuvolnila. Že je oborová perspektiva v grantových soutěžích důležitá, lze aspoň v náznaku vypozorovat z dat o počtech udělených grantů a o oborově příslušných částkách. Zde se projevuje především rozdíl mezi vědami společenskými a humanitními (SSH) a ostatními disciplínami. Zatímco badatelé v SSH podávají zdaleka nejvíc žádostí (celkem 587 ve standardní souteži, druhé v pořadí jsou vědy o neživé přírodě s 369 přihláškami, Obrázek 2), jejich oborová komise rozdělila pro rok 2020 nejmenší absolutní částku a průměrná dotace na grant (3,73 mil. Kč) je v SSH téměř dvaapůlkrát nižší než u grantů v nejštědřejších komisi lékařských a biologických věd (9,08 mil. Kč).

Z oborové perspektivy stojí za zmínku také nulová úspěšnost společenskovědních projektů v kategorii Mezinárodních projektů. Co do počtu přihlášek (232) představují Mezinárodní projekty třetí největší soutěž GAČR, ale s průměrnými 9 % podpořených žádostí je to soutěž nejnáročnější. V této soutěži se navíc úspěšnost mezi komisemi liší velmi výrazně a sahá od již zmiňované nuly až po úspěšnost 24,5 % v lékařských a biologických vědách. I v soutěži EXPRO bývají projekty vyhodnocovány oborovými panely, ale výsledky jsou vyhlašovány za celou soutěž a na základě poskytnutých dat tak nelze oborové hledisko hodnotit.

#### Ideální název grantu

Analýza textu není tolik exaktní jako tvrdá data o udělených dotacích a úspěšnostech přihlášek. Na rozdíl od nich však rozbor slov vyskytujících se v projektových žádostech nabízí neotřelý úhel pohledu na grantové soutěže a poskytuje více prostoru pro interpretaci. Bohužel, textová data v sadě od GAČR neobsahují abstrakty neúspěšných žádostí. Zde jsme proto za obě hlavní soutěže GAČR porovnali na základní tvar převedené termíny z názvů přihlášek a klíčových slov.

[![slova](https://vedavyzkum.cz/images/4_grafika/slova.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/slova.html)

*Obrázek 3: Relativní výskyt 100 nejčastějších slov v záhlaví návrhů projektů podle výsledku žádosti*

Frekvenční jazyková analýza ukázala 100 nejčastěji se vyskytujících slov v grantových žádostech, která jsou navíc porovnána podle svých relativních četností v podpořených a zamítnutých projektech (Obrázek 3). Podle očekávání ta vskutku nejčastější slova leží kolem diagonály a nepřináleží preferenčně do žádné z obou skupin přihlášek. Tvar grafu však naznačuje, že čím více se slovník specializuje a frekvence slov se odpovídajícím způsobem snižuje, tím více se u jednotlivých slov projevuje relativní příklon k jedné či druhé skupině projektů. Na základě těchto výsledků lze s nezbytnou mírou nadsázky odvodit tato dvě doporučení pro budoucí žadatele: Chcete-li uspět, napište si žádost na téma "Nová role evoluce v chemické charakterizaci a regulaci proteinů"; naopak, pokud byste raději chtěli jen zlomyslně přidělávat zbytečnou práci hodnotitelům, vhodným názvem projektu by mohl být "Vliv zdrojů politické aktivity na chování sociálních vrstev".

Díky textovým údajům můžeme zachytit také sémantické vazby mezi jednotlivými návrhy projektů (Obrázek 4). V tomto případě uvažujeme o návrzích projektů v podobě sítě, v níž každý návrh představuje uzel (vrchol) síťového grafu a každé slovo, které sdílí s aspoň jedním dalším návrhem, zakládá vazbu (hranu) mezi návrhy. Počet hran dopadajících na konkrétní uzel lze vyjádřit jako tzv. stupeň uzlu, tedy jako míru centrality, která zachycuje sílu propojení konkrétního návrhu s ostatními. Projekt obsahující v názvu či klíčových slovech termíny, které se často vyskytují i v jiných návrzích, bude uzlem s vysokým stupněm.

[![sit](https://vedavyzkum.cz/images/4_grafika/sit.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/sit.png)

*Obrázek 4: Síť přihlášek na základě sdílených slov podle oborů a výsledků žádosti*

Nejdříve jsme vytvořili síť ze všech projektů ve Standardní a Juniorské soutěži a spočítali hrany na základě názvů a klíčových slov. Výsledná síť všech návrhů projektů je protkána statisíci vazeb, k její vizualizaci jsme tedy použili specializovaný nástroj [Gephi](https://gephi.org/). Velikost uzlů vypovídá o jejich stupňové centralitě. Barvu uzlů v případě Obrázku 4 vlevo odpovídá oborové komisi, do níž byl návrh podán, ve druhém případě barva označuje schválené a zamítnuté návrhy projektů. Obraz oborových skupin ukazuje, že přestože síť návrhů projektů není jako celek s výjimkou společenských a humanitních věd výrazně modularizovaná, sdílená slova celkem zdařile rekonstruují oborové rozlišení projektů. Pouze mezi technickými vědami a vědami o neživé přírodě, zdá se, dochází k výraznějším sémantickým překryvům.

Druhá varianta vizualizace v Obrázku 4 vpravo ukazuje, jak jsou v síti rozloženy schválené a zamítnuté žádosti. Úspěšné přihlášky se nekoncentrují ani na okrajích sítě (což by napovídalo preferenci projektů s ojedinělou terminologií), ani nevytvářejí žádné výrazné shluky sémanticky spřízněných projektů. Jelikož posláním GAČR je podporovat základní, nikoliv orientovaný výzkum, absence jasných vzorců zde představuje dobrou zprávu, stejně jako skutečnost, že schválen může být i projekt v podobě uzlu s nízkým stupněm a na okraji sítě. Na druhou stranu výsledný obrázek ani nenaznačuje, že by se u GAČR nějak zvlášť dařilo interdisciplinárním projektům. Pokud má síť hluchá místa, kde je úspěšných návrhů méně, je tomu tak právě v oblastech, kde se oborové skupiny navzájem setkávají.

Ani rozbor na úrovni oborových komisí nevykázal žádné výrazné vzory, které by na základě sémantických vazeb vznikaly mezi úspěšnými a neúspěšnými projekty. Pro větší přehlednost zde pracujeme pouze s vazbami mezi klíčovými slovy. Čtenáři se mohou na konkrétní klíčová slova podívat v interaktivních grafech pro [humanitní a společenské vědy](http://czexpatsinscience.cz/wp-content/uploads/2020/03/sit-hum.html), [vědy o neživé přírodě](http://czexpatsinscience.cz/wp-content/uploads/2020/03/sit-nez.html),[technické vědy](http://czexpatsinscience.cz/wp-content/uploads/2020/03/sit-tec.html), [zemědělské a biologicko-environmentální vědy](http://czexpatsinscience.cz/wp-content/uploads/2020/03/sit-zem.html) a[ lékařské a biologické vědy](http://czexpatsinscience.cz/wp-content/uploads/2020/03/sit-lek.html).

Velikost uzlů opět vyjadřuje jejich stupňovou centralitu. Pokud by oborové komise výrazně upřednostňovaly vybraná témata, vazby by se kumulovaly zvlášť mezi podpořenými a zamítnutými žádostmi. Ve skutečnosti však probíhají celým prostorem. Pouze u některých oborových komisí je při bližším pohledu patrné, že některé vrcholy tvořené neúspěšnými žádostmi jsou propojené intenzivněji. Nejzřetelnější je tento jev v humanitních a společenských vědách a v komisi zemědělských a biologicko-environmentálních věd. Na základě explorativních vizualizací však můžeme nanejvýš vyslovit hypotézu, že grantové žádosti nejsou kvůli své tematické orientaci systematicky zvýhodňovány, ale některá témata mohou být v soutěži znevýhodněna. Tento signál je však slabý a není tedy vůbec jisté, zda by obstál jako závěr ve formálním testu této hypotézy.

#### Vítězové a poražení

Data umožnila analyzovat grantové chování jednotlivých institucí na úrovni fakult vysokých škol a ústavů Akademie věd ČR. Do některé ze soutěží se zapojilo 234 institucí, přičemž v množství podaných návrhů jsou až řádové rozdíly. Nejvíce návrhů -- 118 -- poslala Přírodovědecká fakulta UK v Praze, naproti tomu 34 institucí poslalo jedinou žádost. Asi dvě třetiny institucí podaly méně než 10 návrhů do všech soutěží.

Tak jako se instituce liší v množství podaných návrhů, liší se i množství schválených projektů respektive v poměru schválených vůči podaným. Za úspěšné lze považovat instituce, které mají vysoký poměr a/nebo velké množství schválených návrhů. Z dat zároveň plyne, že čím víc projektů instituce podá, tím víc jich bude v průměru schváleno.[Spearmanův koeficient rS](https://cs.wikipedia.org/wiki/Spearman%C5%AFv_koeficient_po%C5%99adov%C3%A9_korelace) má pro Standardní projekty a instituce s více než 5 návrhy hodnotu 0,73 (ideální pořadovou korelaci mají data s rS=1).

V dalším textu se budeme zabývat Standardní, Juniorskou a EXPRO soutěží. O Standardní granty žádá zdaleka nejvíce institucí, Juniorské z našeho pohledu reprezentují pokrokovost instituce a příslib budoucnosti české vědy a EXPRO granty spojuje kvalitní a drahá věda. Lead Agency granty si dovolíme vynechat, neboť každá instituce získala buď jeden, nebo žádný grant. Mezinárodní projekty se dají shrnout do sdělení, že se 4 schválenými projekty v nich pomyslně zvítězil pražský Matfyz, tři instituce získaly po dvou grantech a 11 institucí jediný.

[![navrhy s](https://vedavyzkum.cz/images/4_grafika/navrhy-s.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/navrhy-s.png)

 *Obrázek 5: Instituce ve Standardní soutěži*

Obrázek 5 znázorňuje množství přijatých a zamítnutých návrhů na Standardní granty pro ústavy AV ČR (vlevo) a pro instituce mimo AV ČR (vpravo) seřazené podle celkového počtu návrhů a s uvedenou procentuální úspěšností návrhů. Pro přehlednost jsou instituce mimo AV ČR zobrazeny pouze pokud podaly alespoň 7 návrhů.

Nejvíce návrhů na Standardní projekt ze všech institucí bylo schváleno Přírodovědecké fakultě UK v Praze (21). Ta ale zároveň podala nejvíce žádostí a úspěšností 26 % byla slabě nad průměrem 24 %. Matematicko-fyzikální fakulta UK v Praze se umístila na pomyslné druhé příčce s 19 schválenými granty při úspěšnosti 31 %. Mezi ústavy AV ČR dominovalo Biologické centrum v Českých Budějovicích s 18 Standardními granty a nadprůměrnou úspěšností 36 %. Ústav organické chemie a biochemie, veřejně známý díky antivirotikům Antonína Holého, získal 12 grantů z 29 (úspěšnost 41 %). Pomineme-li instituce s méně než 10 podanými žádostmi, mírou úspěšnosti 44 % dominovala, pro nás překvapivě, Fakulta stavební ČVUT (12 schválených grantů).

[![navrhy j](https://vedavyzkum.cz/images/4_grafika/navrhy-j.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/navrhy-j.png)

*Obrázek 6: Instituce v Juniorské soutěži*

Obrázek 6 znázorňuje množství přijatých a zamítnutých návrhů v Juniorské soutěži pro ústavy AV ČR (vlevo) a pro instituce mimo AV ČR (vpravo) seřazené podle celkového počtu návrhů a s uvedenou procentuální úspěšností. Pro přehlednost jsou instituce mimo AV ČR zobrazeny pouze pokud podaly alespoň 2 návrhy. Se 7 získanými granty zvítězilo Biologické centrum AV ČR v Českých Budějovicích a pražský Matfyz. Čtyři instituce získaly po 5 grantech. Nad průměrnou úspěšnost 30 % v Juniorské soutěži výrazně vyčnívají Přírodovědecká fakulta Jihočeské univerzity v Českých Budějovicích (4 granty, úspěšnost 67 %), Fyzikální ústav (5 grantů, úspěšnost 50 %) nebo Přírodovědecká fakulta MU (5 grantů, úspěšnost 45 %). Stojí za zmínku, že Juniorské granty mířily ve velké většině na přírodovědně a technicky zaměřené instituce. Žádná sociálně a humanitně zaměřená instituce nezískala více jak dva.

[![navrhy e](https://vedavyzkum.cz/images/4_grafika/navrhy-e.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/navrhy-e.png)

*Obrázek 7: Instituce v soutěži EXPRO*

Kategorie pětiletých grantů EXPRO je na Obrázku 7, vlevo pro ústavy AV ČR a vpravo pro instituce mimo AV ČR, z nichž jsou pro přehlednost zobrazené pouze ty, které podaly dvě a více žádostí. Nejvíce grantů -- tři -- získala Matematicko-fyzikální fakulta UK v Praze. Další 4 instituce získaly granty dva, přičemž instituce AV ČR a mimo ni si rozdělily shodně po 11 grantech.

[![zamitnute](https://vedavyzkum.cz/images/4_grafika/zamitnute.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/allRejected.png)

*Obrázek 8: Instituce s nulovou úspěšností*

Na opačném konci úspěšnosti se umístily instituce shrnuté na Obrázku 8. Ten zobrazuje ty instituce (společně AV ČR i mimo ni), které nezískaly ani jeden grant, seřazené podle počtu návrhů. Celkem 95 institucím byly všechny jejich návrhy zamítnuty. Z toho 21 institucí podalo víc než 5 návrhů.

Ve Standardních grantech si Černého Petra vytáhla Fakulta strojní ČVUT v Praze, u které ani jeden ze 17 návrhů nebyl schválen. Napadá nás několik důvodů, např. procesních nebo formálních, které by 0% úspěšnost při vysokém množství návrhů dokázaly vysvětlit. Nedostatečnou kvalitu návrhů ovšem nelze vyloučit. Kontaktovali jsme fakultní Oddělení pro vědu a výzkum, ale jejich vyjádření se nám získat nepodařilo. V Juniorských grantech se nedařilo Agronomické fakultě Mendelovy univerzity v Brně, která podala 7 žádostí, a v EXPRO grantech pak Středoevropskému technologickému institutu VUT s 10 žádostmi.

Dle našeho názoru z grafů a dat krystalizují instituce, které jsou, alespoň z hlediska schopnosti získávat granty GAČR, úspěšné. Dokonce bychom se neostýchali tuto úspěšnost zobecnit a např. Matematicko-fyzikální fakultu UK, Biologické centrum AV ČR nebo Fyzikální ústav AV ČR, které uspěly napříč grantovými soutěžemi, považovat v českém prostředí za prokazatelně špičkové výzkumné instituce. Nutno zmínit, že Biologickému centru se mimořádně daří navzdory tomu, že nemůže využívat výhody, kterých se dostává institucím v Praze a Brně, např. v podobě sousedství velkých univerzit či dopravní dostupnosti.

[![fakulty fil](https://vedavyzkum.cz/images/4_grafika/fakulty-fil.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/fakulty-fil.png)

*Obrázek 9: Filozofické fakulty univerzit*

[![fakulty pri](https://vedavyzkum.cz/images/4_grafika/fakulty-pri.png)](http://czexpatsinscience.cz/wp-content/uploads/2020/03/fakulty-pri.png)

*Obrázek 10: Přírodovědecké fakulty univerzit*

Z profesní zvědavosti jsme se podrobněji také podívali na přírodovědecké (PřF) a filozofické fakulty (FF), které jsou součástí mnoha českých univerzit. Výsledky jsou shrnuté na Obrázcích 9 a 10 pro každou soutěž zvlášť, seřazené podle počtu podaných návrhů a s uvedenou procentuální úspěšností. Mezi filozofickými fakultami se nejvíce dařilo FF MU, která ve Standardní soutěží získala nejvíc grantů a nadprůměrnou úspěšností 39 % se zařadila těsně za Filosofický ústav AV ČR -- nejúspěšnější instituci společenskovědních disciplín (Obrázek 5). Juniorských a EXPRO grantů bylo filozofickým fakultám uděleno příliš málo na to, abychom výsledky mohli komentovat.

Přírodovědecké fakulty se co do počtu žádostí rozdělily na ty velké (UK, MU, UP a JU) a malé (Ostrava, UJEP a Hradec Králové). Obecně se jim dařilo. Mezi velkými univerzitami byly v úspěšnosti značně nad průměrem PřF MU a JU v Českých Budějovicích. Hodnoty úspěšnosti u malých univerzit jsou zatíženy malým počtem žádostí. Znatelně pod průměrnou úspěšností 24 % se ve Standardních grantech umístila přírodověda v Olomouci s 19 % úspěšností. PřF v Olomouci se letos nedařilo ani v Juniorské soutěži, kde získala jediný grant, což odpovídá úspěšnosti 17 %. Ostatní přírodovědecké fakulty měly vyšší než průměrnou úspěšnost 30 %, nejvyšší pak PřF JU s 67 %.

#### Shrnutí a výhled

Představili jsme základní statistické informace o projektech GAČR s počátkem řešení v lednu 2020, které jsme zjistili z dat získaných na žádost Czexpats in Science. Dle našeho názoru by GAČR měla data a podrobné statistiky zveřejňovat z vlastní iniciativy, ať už pro zvýšení své transparentnosti a důvěryhodnosti, nebo aby napomohla vnitřní reflexi českých vědeckých institucí. GAČR by se mohla inspirovat (nebo přímo spolupracovat) s portálem [STARFOS ](https://starfos.tacr.cz/)Technologické agentury ČR, která nabízí o svých grantových soutěžích podobné informace, které prezentujeme v této analýze. Za jednoznačně pozitivní posun ve výročních zprávách GAČR považujeme např. zahrnutí aspoň základních statistik o rozdělení žadatelů podle genderu a oborů. V naší analýze jsme genderovou perspektivu nemohli zohlednit, neboť potřebné údaje o žadatelích nebyly v poskytnutých datech k dispozici.

Bylo by zajímavé, a pro některé naše závěry možná i vhodné, analyzovat data za delší časový úsek a tím odpovědět např. na otázku, zda-li je pražský Matfyz úspěšný dlouhodobě. Meziroční výkyvy úspěšnosti mohou být významné zvlášť u institucí s malým množstvím návrhů. Srovnání by na druhou stranu bylo komplikované podmínkami jednotlivých soutěží, které se mění z roku na rok a např. u Juniorských grantů mohou mít velký vliv na průběh soutěže. Podobná analýza však přesahuje naše stávající možnosti.

Dalšími rozměry, kterými je náš současný pohled limitován, jsou velikosti jednotlivých institucí reprezentované počtem akademických pracovníků, studentů, případně rozpočtem. Nelze tedy říci, jaká je motivace uchazečů o granty žádat (mají malý rozpočet a mnoho zaměstnanců?). Některé závěry by bylo také vhodné normalizovat vůči velikosti instituce. Podává Přírodovědecká fakulta UK nejvíce grantů, protože má oproti ostatním institucím proporčně nejvíce zaměstnanců? Nevíme. Obecně bychom ale za nejúspěšnější instituci považovali tu, která má nejvyšší poměr přijetí vůči počtu zaměstnanců.

Při optimálním nastavení hodnoticích procesů by grantové soutěže měly vědě prospívat výběrem nejlepších kandidátů a témat k mimořádné podpoře. Kevin Gross a Carl T. Bergstrom však ve svém loňském [článku ](https://doi.org/10.1371/journal.pbio.3000065)*"Contest models highlight inherent inefficiencies of scientific funding competitions"* postulují existenci kritického bodu, po jehož překonání začínají grantové soutěže vědě spíše škodit. Reálná pozice tohoto bodu se odvíjí od průměrné úspěšnosti v grantových soutěžích, která má historicky sestupný trend. Pokud úspěšnost klesne pod určitou hladinu, čas a práce investované do přípravy grantové žádosti se sice stále vyplatí vítězům soutěže, ale věda jako celek začíná strádat, neboť malá množina podpořených badatelů již nedokáže vykompenzovat množství úsilí, které do přípravy často i vysoce kvalitních projektů vložili neúspěšní žadatelé. Naše analýza např. poukazuje na vysoké množství institucí s úspěšností 0 %. Pokud GAČR udrží nebo zvýší ve svých hlavních soutěžích aktuální míry úspěšnosti, může české vědě prospívat. Jestliže se však potvrdí trend, v němž některé obory mají v Mezinárodních projektech GAČR úspěšnost hluboko pod 10 %, pak lze pochybovat o tom, zda je existence takového schématu pro rozvoj těchto oborů prospěšná. Grossův a Bergstromův argument také tvoří rub současné snahy GAČR o rozvíjení programů EXPRO a STAR, jejichž parametry sice vycházejí vstříc reálným potřebám vědců pro rozvíjení excelentních týmů (především pětiletá doba řešení), avšak děje se tak na úkor průměrné úspěšnosti žádostí, která v EXPRO aktuálně klesá pod 20 %. Pokud toto dilema nerozetne navýšení rozpočtu GAČR, mohlo by hrozit, že dobře míněné snahy o vylepšování českých grantových schémat se minou účinkem.

*Autoři:*

*Michal H. Kolář, Vysoká škola chemicko-technologická v Praze a Czexpats in Science*

*Radim Hladík, Filosofický ústav AV ČR a Česká asociace pro digitální humanitní vědy (CzADH)*

*Zdroj:[Czexpats in Science](http://czexpatsinscience.cz/blog-post/gacr_2020/)*

* * * * *

**RNDr. Michal H. Kolář, Ph.D.**

[Michal](http://mhko.science/)(*1985) vystudoval chemii a molekulové modelování na Přírodovědecké fakultě UK a Ústavu organické chemie a biochemie AV ČR. Za podpory Nadace Alexandera von Humboldta působil ve Výzkumném centru Jülich v Německu, odkud se přesunul do Ústavu Maxe Plancka pro biofyzikální chemii v Göttingenu. Od roku 2018 je odborným asistentem na Vysoké škole chemicko-technologické v Praze, kde mj. v rámci Juniorského projektu GAČR z loňského roku studuje detaily syntézu proteinů na ribozomech.

**PhDr. Radim Hladík, Ph.D.**

[Radim](https://twitter.com/hlageek)(*1980) vystudoval sociologii na Fakultě sociálních věd UK. Od roku 2008 působí na Filosofickém ústavu AV ČR v Kabinetu pro studium vědy, techniky a společnosti. Během doktorského studia absolvoval jako nositel Fulbrightova stipendia roční pobyt na Columbia University v USA, v letech 2017-2019 realizoval s podporou Japan Society for the Promotion of Science postdoktorskou stáž na National Institute of Informatics v Japonsku. V Juniorské soutěži GAČR 2020 uspěl s projektem "Funded and Unfunded Research in the Czech Republic". V České asociaci pro digitální humanitní vědy se zasazuje o využívání digitálních a kvantitativních metod v sociálních a humanitních vědách.
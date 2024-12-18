---
title: "Mapa české vědy"
subtitle: "V dynamickém světě vědy se hranice mezi jednotlivými disciplínami stále více prolínají. Tradiční oborové klasifikace často nedokážou zachytit komplexnost a propojenost současného vědeckého poznání. Metoda mapování vědy, kterou jsme vyvinuli nad daty z českého výzkumného prostředí, nabízí nový přístup, jak tento problém překonat."
summary: "V dynamickém světě vědy se hranice mezi jednotlivými disciplínami stále více prolínají. Tradiční oborové klasifikace často nedokážou zachytit komplexnost a propojenost současného vědeckého poznání. Metoda mapování vědy, kterou jsme vyvinuli nad daty z českého výzkumného prostředí, nabízí nový přístup, jak tento problém překonat."
authors: 
- hlageek
tags:
- Czech science
- scientific knowledge
- disciplines
- analysis
categories:
- Czech
- Vedavyzkum.cz
date: 2024-12-18
lastmod: 2024-12-18
featured: false
draft: false
image:
  caption: 'Image credit: [Radim Hladík]'
  focal_point: ""
  placement: 1
  preview_only: false
projects: []
---

Snahy přehledně uspořádat různé oblasti lidského poznání a nacházet mezi nimi vzájemné souvislosti mají kořeny ve starověkých filosofických systémech. 
Tradiční přístupy jako svůj hlavní nástroj využívají klasifikaci, tedy hierarchické členění jednotlivých druhů poznání dle stanovených kritérií, jejíž výsledek lze zobrazit jako tabulku nebo stromovou strukturu.
Původně tyto snahy plnily primárně didaktické účely, ale s nástupem moderních vědeckých disciplín na přelomu 18. a 19. století začala klasifikace poznání výrazněji prostupovat i způsoby organizace odborné komunity.
Třídění vědy do oborových kategorií tak dodnes zůstává pevnou součástí vědních politik, statistik, institucionálních struktur, ale i profesní identity a odborného vzdělání badatelů.
Současné mapování vědy se však od těchto tradičních modelů vědění odklání tím, že místo fixních hierarchií využívá dynamické vizualizace založené na empirických datech. 
Tento přístup lépe odráží komplexitu a propojenost současného vědeckého poznání, což má význam například pro pochopení interdisciplinární spolupráce v dnešní vědě.

<figure>
<img src="https://atlas-disciplines.unige.ch/Images/Source_images/Park_Roswell_1841_Pantology_or_A_systematic_survey_of_human_knowledge_p_iii.jpg" width="400">
<figcaption>Strom "pantologie". Klasifikace lidského poznání dle Roswella Parka z roku 1841. Zdroj: <a href="https://atlas-disciplines.unige.ch/">Historical Atlas of the Disciplines</a></figcaption>
</figure>

Moderní kartografie vědy vychází převážně z bibliometrických technik.
Výchozím předpokladem je existence vztahů mezi jednotlivými publikacemi, jejichž zmapování poskytuje obraz vědy jako propojené sítě, ať už z globální perspektivy, nebo z pohledu vybraných oborových skupin.
Vazby mezi publikacemi se zpravidla určují prostřednictvím citačních odkazů, kdy spolu dvě publikace souvisejí tehdy, pokud jedna obsahuje referenci k druhé, nebo když se společně vyskytují v seznamu literatury třetí publikace.
Spojitosti lze hledat také na základě textové podobnosti či spoluvýskytu odkazů v odborných časopisech.
Alternativně je možné spíše než na publikace zaměřit se na vědce, kdy výsledná síť reflektuje společné vazby podle údajů o spoluautorství.
Tyto postupy nejenže dobře odrážejí komplexitu vědy, ale nabízejí i vysoké rozlišení až na úroveň [stovky tisíc odborných specializací](https://doi.org/10.1002/asi.22990). 

<figure>
<img src="https://cset.georgetown.edu/wp-content/uploads/Figure-1-5-700x349.png" height="300">
<figcaption>Bibliometrická mapa vědy sestavená na základě citačních vazeb. Zdroj: <a href="https://cset.georgetown.edu">Center for Security and Emerging Technology, Georgetown University</a></figcaption>
</figure>

Mapy vědy založené na bibliometrických sítích však i přes své nepopiratelné přednosti trpí některými nedostatky.
Především pro ně neexistuje žádný kompas.
Orientace bibliometrické mapy a lokalizace jednotlivých bodů, ať už představují publikace, časopisy nebo autory, jsou výsledkem nastavení parametrů pro vybraný algoritmus grafického rozvržení sítě. 
To znamená, že z těchto map můžeme vyčíst pouze informaci o relativní blízkosti či vzdálenosti mezi body a shluky síťového grafu, ale jejich konkrétní pozice v prostoru žádný význam nenese.
Oproti rozvětveným klasifikačním systémům bibliometrické sítě také postrádají vícerozměrnou soustavu mapovacích kritérií.
Vždy zachycují jen jeden organizační princip, který se odvíjí od prvotní definice sledované síťové vazby.

Vlastnosti bibliometrických map omezují jejich využitelnost pro následné aplikace.
Konkrétně jsme se například v rámci projektu GAČR zabývali otázkou, do jaké míry projektové financování vykazuje sklon preferovat či upozaďovat různé typy vědeckého poznání.
Pro takový sociologický výzkum však bibliometrické sítě nemohou nabídnout více než alternativní variantu oborového členění.
Abychom mohli zkoumat vztahy mezi znalostním a sociálním prostorem vědy na kontinuální škále, potřebovali jsme zcela nový postup.
Kombinaci analytických postupů vypůjčených z různých vědních oblastí se nám nakonec podařilo vypracovat nový protokol pro mapování vědy, jenž překonává stávající omezení klasifikačních i empiricky založených metod a zároveň zachovává jejich přednosti.

Výchozí myšlenkou nové mapovací techniky je rozklad oborů do dílčích témat. 
Pro tento účel textové anotace publikací zpracováváme algoritmem pro tzv. tematické modelování.
Tematické modely redukují slovní zásobu ve sbírce textů na omezený počet syntetických témat, které představují uspořádané sady spoluvyskytujících se termínů.
Každá publikace se tedy jeví jako unikátní tematická směs, což nám umožňuje spočítat průměrné rozložení témat v oborech.
Tematický rozptyl pak lze studovat postupy geometrické analýzy, která nám na rozdíl od sítí poskytuje vícerozměrnou soustavu souřadnic.
Poté, co z dat odvodíme základní rozlišovací principy vymezující prostor vědění, promítneme do připravených koordinát tematická portfolia jednotlivých autorů. 
Výsledkem je mapa české vědy, která se opírá o data z více než 800 tisíc publikačních výstupů evidovaných v databázi RIV a lokalizuje epistemologické pozice takřka 60 tisíc vědců a vědkyň.

<figure>
<img src="map1x2.png" width="700">
<figcaption>Mapa české vědy s osami Kultura–Příroda, Život–Ne-život. Každý bod představuje projekci individuálního výzkumníka nebo výzkumnice z celkem 58 466 tematických portfolií s pěti nebo více publikacemi. Barvy odpovídají nejčastější oborové skupině. Průměrné pozice oborů na úrovni FORD jsou vyznačeny příslušným textem. Zdroj: Autor.</figcaption>
</figure>

Jak tedy vypadá česká věda?
Místo přehledného rozdělení do úhledných oborových škatulek nacházíme ve výsledné vizualizaci tvar připomínající nakousnutou koblihu s barevnou posypkou.
Na jednu stranu spirálovitá struktura ukazuje, jak úzce jsou některé disciplíny provázané. 
Neizolují se v jasně vymezených doménách, nýbrž jsou rozprostřeny do vzájemně se prolínajících ploch, jejichž hranice jsou rozmlžené a nejednoznačné.
Zároveň je ale patrné, že tato propojenost není zcela rovnoměrná. 
Řídce obydlené centrum kruhu odhaluje, že některé oblasti vědy si zůstávají navzájem vzdálené.
Zatímco sousední disciplíny, jako třeba lékařství a biologie, mají více styčných bodů, mezi humanitními a přírodovědnými obory zeje větší propast. 
Mapa tedy simultánně ukazuje jak celkové propojení vědy, tak i přetrvávající oborové bariéry a rozdíly.

Do jaké míry takto prezentovaná struktura české vědy koresponduje se situací v jiných zemích či s mezinárodní úrovní nelze říci bez dalších komparativních výzkumů.
Zdá se ale, že základní obrysy české mapy odráží obecné vlastnosti vědeckého poznání.
Zajímavým aspektem je totiž podobnost mapy s teoretickými modely, které se pokoušely uspořádat vědní oblasti do nelineárních struktur. 
Například slavný švýcarský psycholog Jean Piaget navrhl [koncept kruhového uspořádání vědeckého poznání](https://atlas-disciplines.unige.ch/#Jean%20Piaget), kde jednotlivé disciplíny tvoří součásti většího celku.
V jeho pojetí je vědecké poznání rozloženo do kruhové formy hodinového ciferníku, který ve 12 odbíjí logiku a matematiku, ve 3 ukazuje na fyzikální vědy, v 6 hlásí čas biologie a kolem 9. přichází okamžik společenských věd.
Takřka totožnou konfiguraci vidíme i na naší mapě a podobné [opakující se vzorce nalezneme i v bibliometrických sítích](https://doi.org/10.1002/asi.20991).

Unikátnost mapy spočívá v tom, že díky jejímu sémantickému podkladu můžeme interpretovat nevyřčené principy klasifikace v prostoru vědění podle koncentrace témat a oborů na protilehlých pólech souřadnicového systému.
To znamená, že v mapě lze smysluplně navigovat.
Hlavní osa v naší interpretaci zachycuje protiklad mezi kulturou a přírodou, zatímco druhá je postavena na kontrastu živých a neživých objektů výzkumu.

Geometrická technika mapování má navíc tu výhodu, že dovoluje prozkoumávat i další dimenze prostoru vědění.
Řez daty sestavený ze druhé a třetí osy tak nabízí zcela jiný pohled, který vedle toho, zda jsou předměty výzkumu životné, či neživotné, zohledňuje i to, do jaké míry se badatelé soustředí na jejich popis, nebo nakolik vyzdvihují jejich zpracování pomocí vědeckých metod.
Zde se ukazuje, že kromě humanitních věd převažují v tematickém zaměření vědců metodologické akcenty, přičemž nejvíce jsou zdůrazňovány v medicínských a inženýrských oborech. 
Střed mapy je tentokrát zaplněn především sociálněvědními výzkumníky, což v kontextu geometrické – na rozdíl od síťové – mapy musíme vnímat tak, že jsou pro ně tyto rozdíly méně významné. 

<figure>
<img src="map2x3.png" width="700">
<figcaption>Mapa české vědy s osami Život–Ne-život, Materiál–Metody. Každý bod představuje projekci individuálního výzkumníka nebo výzkumnice z celkem 58 466 tematických portfolií s pěti nebo více publikacemi. Barvy odpovídají nejčastější oborové skupině. Průměrné pozice oborů na úrovni FORD jsou vyznačeny příslušným textem. Zdroj: Autor.</figcaption>
</figure>

Namísto jedné mapy tedy můžeme pracovat s malým atlasem, jehož jednotlivé stránky zachycují empirickou verzi filosofie vědy. Jako další určující dimenze vědeckého poznání totiž detekujeme rozdíly mezi syntetickými a analytickými tématy, aplikovaným a základním výzkumem či mezi pozorováním a experimentem (tato poslední dichotomie se v humanitních a společenských vědách projevuje v jejich deskriptivním, respektive preskriptivním zaměření). 

Rozličné aplikace, ke kterým lze data získaná mapováním využít, ponechme pro tentokrát stranou.
Na závěr se soustřeďme jen na několik úvah, které se odvíjejí od samotných vizualizací.
Prvním nápadným momentem je velmi řídké propojení mezi medicínskými a sociálněvědními či humanitními obory v české vědě.
Je vcelku dobře možné, že nedostatek expertízy v tomto kvadrantu, kde bychom intuitivně očekávali uzavření znalostní spirály, přímo souvisí s nedostatkem skutečných vzdělávacích a výzkumných kapacit.
Této interpretaci by napovídala i anekdotická zkušenost České republiky v éře pandemie covid-19, kdy byl pociťován nedostatek jak medicínských expertů kvalifikovaných pro sociální zvládání pandemie, tak sociálních a humanitních vědců s dostatečnou kompetencí pro medicínská témata.  
Vezmeme-li ale v potaz mapu vykreslenou na podružných osách – kde se lékařství a humanitní obory nacházejí v téměř absolutní opozici – stává se zřejmým, že sbližování těchto oblastí objektivně brání i podstatné epistemologické rozdíly. 

Mapa české vědy nás také přivádí ke kritice nevhodných způsobů práce s tradičními oborovými klasifikacemi. 
Ty mohou být velmi nepřesným měřítkem například při posuzování interdisciplinarity.
S pomocí mapy lze dovodit, že některá interdisciplinární partnerství mohou mít čistě formální charakter tam, kde se obory víceméně překrývají, zatímco jiné zdánlivě ekvivalentní případy spolupráce musí překonávat značné rozdíly v tematické orientaci. 
Na základě mapy je také možné vyhodnotit, zda organizační schéma výzkumné instituce či grantové agentury vhodně reflektuje empiricky doložené rozdělení vědců v tematických oblastech.
Mapování vědy tedy nemusí zůstávat pouze akademickým cvičením, ale může reálně podporovat vědní politiku s dopady na to, jak chápeme a organizujeme vědecký výzkum.

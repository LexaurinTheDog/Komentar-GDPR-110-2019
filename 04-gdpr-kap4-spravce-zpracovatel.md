# 04 — Kapitola IV GDPR: Správce a zpracovatel (čl. 24–43)

Kapitola IV tvoří organizační a technické jádro GDPR: stanoví, jak mají správci a zpracovatelé zavést, udržovat a prokazovat soulad s nařízením. Oproti předchozím kapitolám se zaměřuje nikoliv na práva subjektů údajů, ale na **povinnosti** osob, které s osobními údaji nakládají — od principu odpovědnosti (accountability) přes záznamy o činnostech zpracování, bezpečnostní opatření, hlášení porušení, posouzení vlivu na ochranu osobních údajů až po institut pověřence pro ochranu osobních údajů a nástroje soft-law (kodexy chování, certifikace). Zákon č. 110/2019 Sb. na tuto kapitolu navazuje zejména v §§ 9, 10, 12 (výjimky z DPIA a oznámení), § 14 (jmenování pověřence) a § 15 (akreditace pro vydávání osvědčení).

---

## Oddíl 1 — Obecné povinnosti (čl. 24–31)

### Čl. 24 — Odpovědnost správce

> **Čl. 24 odst. 1**
> *S přihlédnutím k povaze, rozsahu, kontextu a účelům zpracování i k různě pravděpodobným a různě závažným rizikům pro práva a svobody fyzických osob provede správce vhodná technická a organizační opatření, aby zajistil a byl schopen doložit, že zpracování je prováděno v souladu s tímto nařízením. Tato opatření musí být podle potřeby přezkoumána a aktualizována.*

> **Čl. 24 odst. 2**
> *Pokud je to přiměřené s ohledem na zpracování prováděné správcem, zahrnují opatření uvedená v odstavci 1 zavedení vhodných zásad ochrany osobních údajů.*

> **Čl. 24 odst. 3**
> *Přistoupení ke schváleným kodexům chování uvedeným v článku 40 nebo ke schváleným mechanismům pro vydávání osvědčení uvedeným v článku 42 lze využít jako prvek pro doložení souladu s povinnostmi správce.*

**Výklad:** Článek 24 kodifikuje zásadu **odpovědnosti** (*accountability*), jež prostupuje celým GDPR (srov. čl. 5 odst. 2). Správce není pouhým příjemcem pravidel — musí aktivně prokázat, že je dodržuje. Výraz „být schopen doložit" má zásadní praktický dosah: v případě šetření dozorového úřadu nebo soudního sporu leží důkazní břemeno na správci. Recitál 74 zdůrazňuje, že správce by měl nést odpovědnost za veškeré zpracování, k němuž dochází jím nebo jeho jménem.

Volba konkrétních technických a organizačních opatření je funkcí **rizika**: zásada proporcionality se projevuje v tom, že malý e-shop zpracovávající kontaktní informace zákazníků potřebuje jiné záruky než nemocnice zpracovávající zdravotní záznamy. Opatření musí být přezkoumávána a aktualizována — jde tedy o kontinuální proces, nikoliv jednorázový úkon.

Odstavec 2 předpokládá vydávání vnitřních **zásad ochrany osobních údajů** (privacy policy / GDPR policy). Ty jsou interním nástrojem správce; nenahrazují povinné informování subjektů údajů dle čl. 13–14, ale tvoří vnitřní rámec pro implementaci GDPR.

Odstavec 3 umožňuje využít **kodexy chování** (čl. 40) a **certifikaci** (čl. 42) jako dokladový nástroj — nikoli jako liberaci z odpovědnosti. ÚOOÚ ani jiný dozorový úřad není kodexem nebo certifikátem vázán, avšak v praxi jim přikládá při posuzování souladu značnou váhu.

---

### Čl. 25 — Záměrná a standardní ochrana osobních údajů

> **Čl. 25 odst. 1**
> *S přihlédnutím ke stavu techniky, nákladům na provedení a k povaze, rozsahu, kontextu a účelům zpracování i k různě pravděpodobným a různě závažným rizikům pro práva a svobody fyzických osob, která jsou s ním spojena, provede správce jak v době stanovení prostředků zpracování, tak v době zpracování samotného vhodná technická a organizační opatření, jako je pseudonymizace, jejichž cílem je účinně provádět zásady ochrany osobních údajů, jako je minimalizace údajů, a začlenit do zpracování nezbytné záruky za účelem splnění požadavků tohoto nařízení a ochrany práv subjektů údajů.*

> **Čl. 25 odst. 2**
> *Správce zavede vhodná technická a organizační opatření, aby bylo ve výchozím nastavení zpracováváno pouze takové množství osobních údajů, které je nezbytné pro každý konkrétní účel zpracování. Tato povinnost se vztahuje na množství shromažďovaných osobních údajů, rozsah jejich zpracování, dobu jejich uložení a jejich dostupnost. Tato opatření zejména zajistí, aby osobní údaje nebyly bez zásahu fyzické osoby ve výchozím nastavení zpřístupněny neomezenému počtu fyzických osob.*

> **Čl. 25 odst. 3**
> *Schválený mechanismus pro vydávání osvědčení podle článku 42 lze použít jako prvek doložení souladu s požadavky odstavců 1 a 2 tohoto článku.*

**Výklad:** Článek 25 zakotvuje dvě spolu úzce propojené zásady:

**Privacy by design (záměrná ochrana)** — odst. 1 vyžaduje, aby správce zohlednil ochranu osobních údajů **již při návrhu** systémů, produktů a procesů, nikoliv dodatečně. Klíčový je pojem „v době stanovení prostředků zpracování": výběr technologie, nastavení databázové architektury, vývoj mobilní aplikace — to vše musí probíhat s přihlédnutím k ochraně údajů. Příkladem technického opatření je **pseudonymizace** (oddělení klíče od datové sady), příkladem organizačního opatření je nastavení workflow tak, aby k citlivým kategoriím měli přístup jen oprávnění zaměstnanci.

**Privacy by default (standardní ochrana)** — odst. 2 stanoví, že výchozí nastavení systémů nebo služeb musí být nastaveno na maximálně ochranné. Sociální síť, která ve výchozím stavu veřejně sdílí profil uživatele, nebo cloudová služba, která ve výchozím stavu uchovává data po dobu delší, než je nezbytné, porušují tuto zásadu. Recitál 78 upřesňuje, že zásada se vztahuje na celý životní cyklus — od shromažďování po výmaz.

Vztah k zákonu č. 110/2019 Sb.: zákon neobsahuje zvláštní prováděcí ustanovení k čl. 25; obecný rámec odpovědnosti správce pokrývá zákon v kontextu § 3 (použití nařízení) a výjimek pro veřejný sektor v §§ 6–9.

---

### Čl. 26 — Společní správci

> **Čl. 26 odst. 1**
> *Pokud dva nebo více správců společně určují účely a prostředky zpracování, jsou společnými správci. Tito správci transparentním způsobem určí, co přísluší každému z nich při plnění povinností vyplývajících z tohoto nařízení, zejména pokud jde o výkon práv subjektu údajů, a při plnění povinností poskytnout informace uvedené v článcích 13 a 14, a to pomocí dohody, pokud a v rozsahu, ve kterém příslušné povinnosti každého z nich nejsou vymezeny právem Unie nebo právem členského státu, jemuž jsou správci podřízeni. V této dohodě může být určeno kontaktní místo pro subjekty údajů.*

> **Čl. 26 odst. 2**
> *Tato dohoda náležitě odráží příslušné úlohy a vztahy společných správců vůči subjektům údajů. Podstata dohody je subjektům údajů zpřístupněna.*

> **Čl. 26 odst. 3**
> *Bez ohledu na podmínky dohody uvedené v odstavci 1 může subjekt údajů svá práva podle tohoto nařízení uplatňovat vůči každému ze správců a ve vztahu ke každému z nich.*

**Výklad:** Institut společných správců (*joint controllers*) zachycuje situace, kdy více subjektů společně rozhoduje o **účelech a prostředcích** zpracování. Kritériem je faktická kontrola nad cíli zpracování, nikoliv formální smluvní označení. Soudní dvůr EU ve svých rozhodnutích (ve věci správy fanouškovských stránek na sociálních sítích — rozsudky ve věci Wirtschaftsakademie a Fashion ID) potvrdil extenzivní výklad: pokud platforma sbírá osobní údaje návštěvníků i v zájmu provozovatele stránky, mohou být oba společnými správci.

Povinnou náležitostí je **dohoda** mezi společnými správci, jež určí, kdo nese jakou povinnost — zejména ohledně informační povinnosti a vyřizování práv subjektů. Podstatou dohody (nikoliv nutně celým jejím textem) musí být zpřístupněna subjektům údajů. Absence dohody nebo formální dohoda, která neodpovídá skutečnému rozdělení rolí, zakládá porušení čl. 26.

Odstavec 3 zaručuje, že subjekt údajů může kdykoli uplatňovat práva vůči **každému** ze společných správců, bez ohledu na vnitřní dohodu. Případné vymáhání plnění dohody je věcí vztahu mezi správci navzájem (občanskoprávní odpovědnost), nikoli obranou vůči subjektu údajů.

---

### Čl. 27 — Zástupci správců nebo zpracovatelů usazených mimo EU

> **Čl. 27 odst. 1**
> *Pokud se použije čl. 3 odst. 2, určí správce nebo zpracovatel písemně svého zástupce v Unii.*

> **Čl. 27 odst. 2**
> *Povinnost stanovená v odstavci 1 tohoto článku se nevztahuje na: a) zpracování, které je příležitostné, nezahrnuje ve velkém měřítku zpracování zvláštních kategorií údajů uvedených v čl. 9 odst. 1 nebo zpracování osobních údajů týkajících se rozsudků v trestních věcech a trestných činů uvedených v článku 10 a je nepravděpodobné, že by v důsledku tohoto zpracování vzniklo riziko pro práva a svobody fyzických osob, s přihlédnutím k povaze, kontextu, rozsahu a účelům zpracování; nebo b) orgán veřejné moci nebo veřejný subjekt.*

> **Čl. 27 odst. 3**
> *Zástupce se usadí v jednom z členských států, kde se nacházejí subjekty údajů, jejichž osobní údaje jsou zpracovávány v rámci nabídky zboží nebo služeb nebo jejichž chování je sledováno.*

> **Čl. 27 odst. 4**
> *Zástupce je správcem nebo zpracovatelem pověřen, aby byl kontaktován vedle správce nebo zpracovatele nebo namísto nich dozorovými úřady a subjekty údajů ve všech záležitostech týkajících se zpracování pro účely zajištění souladu s tímto nařízením.*

> **Čl. 27 odst. 5**
> *Určení zástupce správcem nebo zpracovatelem nemá vliv na právní kroky, jež lze podniknout vůči samotnému správci nebo zpracovateli.*

**Výklad:** Článek 27 doplňuje extrateritoriální dosah GDPR zakotveného v čl. 3 odst. 2 (nabídka zboží/služeb subjektům v EU nebo monitorování jejich chování). Správci a zpracovatelé mimo EU, kteří spadají pod GDPR, musejí jmenovat **zástupce** (fyzickou nebo právnickou osobu) usazeného v EU. Zástupce není pověřencem pro ochranu osobních údajů — jde o odlišný institut; tatáž osoba může teoreticky obě funkce kumulovat, pokud jsou splněny podmínky pro obě role.

Výjimky z odst. 2 jsou dvě: příležitostné zpracování bez zvláštních kategorií údajů s nízkou mírou rizika, a orgány veřejné moci (ty nemají extrateritoriální povinnost jmenovat zástupce v EU, protože k nim nelze dozorovým úřadem přistupovat jako k soukromým subjektům). Porušení povinnosti jmenovat zástupce je pokutovatelné dle čl. 83 odst. 4, přičemž zástupce nese odpovědnost v rozsahu svého pověření, ale samotný správce/zpracovatel zůstává primárně odpovědný (odst. 5).

---

### Čl. 28 — Zpracovatel

> **Čl. 28 odst. 1**
> *Pokud má být zpracování prováděno pro správce, využívá správce pouze ty zpracovatele, kteří poskytují dostatečné záruky zavedení vhodných technických a organizačních opatření takovým způsobem, aby zpracování splňovalo požadavky tohoto nařízení a aby byla zajištěna ochrana práv subjektu údajů.*

> **Čl. 28 odst. 2**
> *Zpracovatel nezapojí žádného dalšího zpracovatele bez předchozího konkrétního nebo obecného písemného povolení správce. V případě obecného písemného povolení informuje zpracovatel správce o veškerých zamýšlených změnách týkajících se přijetí dalších zpracovatelů nebo jejich nahrazení, a tím dává správci příležitost vyslovit vůči takovým změnám námitky.*

> **Čl. 28 odst. 3**
> *Zpracování prováděné zpracovatelem se řídí smlouvou nebo jiným právním aktem podle práva Unie nebo členského státu, který je pro zpracovatele závazný a týká se správce, v níž je vymezen předmět a doba trvání zpracování, povaha a účel zpracování, typ osobních údajů a kategorie subjektů údajů a povinnosti a práva správce. Tato smlouva nebo jiný právní akt zejména stanoví, že zpracovatel: a) zpracovává osobní údaje pouze na základě doložených pokynů správce, včetně pokynů týkajících se předání osobních údajů třetí zemi nebo mezinárodní organizaci, pokud mu tato povinnost nevyplývá z práva Unie nebo členského státu, jemuž zpracovatel podléhá; v takovém případě uvědomí zpracovatel správce o tomto právním požadavku před zpracováním, ledaže by bylo toto uvědomění v důležitém veřejném zájmu zakázáno; b) zajistí, aby se osoby oprávněné zpracovávat osobní údaje zavázaly k zachování mlčenlivosti nebo aby se na ně vztahovala zákonná povinnost zachovávat mlčenlivost; c) přijme veškerá opatření požadovaná podle článku 32; d) dodržuje podmínky pro zapojení jiného zpracovatele uvedené v odstavcích 2 a 4; e) zohledňuje povahu zpracování a pomáhá správci prostřednictvím vhodných technických a organizačních opatření, pokud je to možné, při plnění povinnosti správce reagovat na žádosti o výkon práv subjektu údajů stanovených v kapitole III; f) pomáhá správci při zajišťování souladu s povinnostmi podle článků 32 až 36 s přihlédnutím k povaze zpracování a informacím, jež má zpracovatel k dispozici; g) v závislosti na rozhodnutí správce vymaže nebo vrátí veškeré osobní údaje po ukončení poskytování služeb zpracování a vymaže existující kopie, pokud právo Unie nebo členského státu nepožaduje jejich uložení; h) poskytne správci veškeré informace nezbytné k doložení toho, že jsou plněny povinnosti stanovené v tomto článku, a umožní audity, včetně inspekcí, prováděné správcem nebo jiným auditorem, kterého správce pověřil, a k těmto auditům přispěje. Pokud jde o písm. h) prvního pododstavce, zpracovatel ihned informuje správce, je-li podle jeho názoru určitý pokyn v rozporu s tímto nařízením nebo jinými předpisy Unie nebo členského státu v oblasti ochrany osobních údajů.*

> **Čl. 28 odst. 4**
> *Pokud zpracovatel zapojí dalšího zpracovatele k provádění určitých činností zpracování jménem správce, jsou tomuto dalšímu zpracovateli na základě smlouvy nebo jiného právního aktu podle práva Unie nebo členského státu uloženy stejné povinnosti na ochranu osobních údajů, jaké jsou obsaženy ve smlouvě nebo jiném právním aktu mezi správcem a zpracovatelem, jak je uvedeno v odstavci 3, zejména s ohledem na to, aby byly poskytnuty dostatečné záruky zavedení vhodných technických a organizačních opatření takovým způsobem, aby zpracování splňovalo požadavky tohoto nařízení. Nesplní-li takový další zpracovatel své povinnosti v oblasti ochrany osobních údajů, odpovídá za plnění povinností tohoto dalšího zpracovatele nadále plně počáteční zpracovatel vůči správci.*

> **Čl. 28 odst. 9**
> *Smlouva nebo jiný právní akt uvedené v odstavcích 3 a 4 musí mít písemnou formu, včetně formy elektronické.*

**Výklad:** Článek 28 je jedním z nejprakticky frekventovanějších ustanovení GDPR. Upravuje vztah správce a **zpracovatele** — subjektu, který zpracovává osobní údaje nikoliv pro vlastní účely, ale na pokyn správce (srov. definici čl. 4 bod 8). Klíčová povinnost správce je výběrová due diligence: musí zajistit, že zpracovatel poskytuje **dostatečné záruky** (odst. 1). Záruky se posuzují před uzavřením smlouvy a průběžně.

Jádrem čl. 28 je **zpracovatelská smlouva** (*Data Processing Agreement*, DPA) nebo jiný právní akt. Povinné obsahové náležitosti jsou vymezeny v odst. 3 písm. a)–h). Praxe ÚOOÚ i evropských dozorových úřadů ukazuje, že chybějící nebo neúplná DPA je jednou z nejčastějších zjišťovaných nedostatků. Bez platné DPA nelze zákonně svěřit zpracování třetí straně (cloudové službě, marketingové agentuře, IT dodavateli apod.).

Subdodavatelský řetězec upravuje odst. 4: každý sub-zpracovatel musí mít se zpracovatelem smlouvu se stejnými povinnostmi, jako má zpracovatel vůči správci. Odpovědnost zpracovatele za sub-zpracovatele je plná — správce se vůči sub-zpracovateli nezprostí. Odst. 2 rozlišuje mezi **konkrétním** (pro každého sub-zpracovatele zvlášť) a **obecným** (seznam sub-zpracovatelů se zákazem namítat) písemným souhlasem správce.

Odstavce 6–8 umožňují, aby smlouva vycházela ze standardních smluvních doložek (*Standard Contractual Clauses*, SCC) vydaných Komisí nebo dozorovým úřadem. Komise vydala v roce 2021 prováděcí rozhodnutí se standardními doložkami pro zpracovatelské smlouvy (C(2021) 3190).

Odst. 10 obsahuje **„zpracovatelskou přeměnu"**: pokud zpracovatel překročí pokyny správce a sám určuje účely a prostředky zpracování, stává se pro toto zpracování správcem. Důsledek je právní odpovědnost zpracovatele jako správce, včetně možných sankcí dle čl. 83 odst. 4.

---

### Čl. 29 — Zpracování pod pravomocí správce nebo zpracovatele

> **Čl. 29**
> *Zpracovatel a každá fyzická osoba jednající z pověření správce nebo zpracovatele, jež má přístup k osobním údajům, zpracovává tyto údaje pouze na základě pokynů správce, pokud jí tato povinnost nevyplývá z práva Unie nebo členského státu.*

**Výklad:** Článek 29 vymezuje základní subordinační pravidlo: zaměstnanci zpracovatele (i sami zaměstnanci správce) zpracovávají osobní údaje výhradně na pokyn správce. Ustanovení je stručné, ale zásadní — je základem pro vnitřní interní pokyny (instructions to employees), roli pověřence při monitorování dodržování těchto pokynů (čl. 39 odst. 1 písm. b)) a pro posuzování odpovědnosti, pokud zaměstnanec jedná nad rámec svého pověření.

---

### Čl. 30 — Záznamy o činnostech zpracování

> **Čl. 30 odst. 1**
> *Každý správce a, v příslušných případech, zástupce správce vedou záznamy o činnostech zpracování, které jsou v jejich odpovědnosti. Tyto záznamy musí obsahovat všechny tyto informace: a) jméno a kontaktní údaje správce a případně společného správce, zástupce správce a pověřence pro ochranu osobních údajů; b) účely zpracování; c) popis kategorií subjektů údajů a kategorií osobních údajů; d) kategorie příjemců, jimž byly nebo budou osobní údaje zpřístupněny, včetně příjemců ve třetích zemích nebo mezinárodních organizacích; e) případně předání osobních údajů třetí zemi nebo mezinárodní organizaci, včetně identifikace příslušné třetí země nebo mezinárodní organizace, a v případě předání uvedených v čl. 49 odst. 1 druhém pododstavci i doložení vhodných záruk; f) pokud je to možné, plánované lhůty pro vymazání jednotlivých kategorií údajů; g) pokud je to možné, obecný popis technických a organizačních bezpečnostních opatření uvedených v čl. 32 odst. 1.*

> **Čl. 30 odst. 2**
> *Každý zpracovatel a, v příslušných případech, zástupce zpracovatele vedou záznamy o všech kategoriích činností zpracování prováděných jménem správce obsahující: a) jméno a kontaktní údaje zpracovatele nebo zpracovatelů a každého správce, jehož jménem zpracovatel jedná, a případně zástupce správce nebo zpracovatele a pověřence pro ochranu osobních údajů; b) kategorie zpracování prováděného jménem každého správce; c) případné předávání osobních údajů třetí zemi nebo mezinárodní organizaci, včetně identifikace příslušné třetí země nebo mezinárodní organizace, a v případě předání uvedených v čl. 49 odst. 1 druhém pododstavci i doložení vhodných záruk; d) pokud je to možné, obecný popis technických a organizačních bezpečnostních opatření uvedených v čl. 32 odst. 1.*

> **Čl. 30 odst. 3**
> *Záznamy uvedené v odstavcích 1 a 2 musí mít písemnou formu, včetně formy elektronické.*

> **Čl. 30 odst. 4**
> *Správce nebo zpracovatel a případně jejich zástupci poskytnou záznamy dozorovému úřadu na jeho žádost.*

> **Čl. 30 odst. 5**
> *Povinnosti uvedené v odstavcích 1 a 2 se nevztahují na podniky nebo organizace zaměstnávající méně než 250 osob, pokud jimi prováděné zpracování pravděpodobně nepovede k riziku pro práva a svobody subjektů údajů, zpracování není příležitostné nebo zahrnuje zvláštní kategorie údajů uvedené v čl. 9 odst. 1 nebo osobní údaje týkající se rozsudků v trestních věcech a trestných činů uvedených v článku 10.*

**Výklad:** Záznamy o činnostech zpracování (*Records of Processing Activities*, RoPA) nahradily oznamovací povinnost vůči dozorovému úřadu, jež existovala pod směrnicí 95/46/ES a v ČR pod zákonem č. 101/2000 Sb. Jde o interní dokumentaci správce nebo zpracovatele, která musí být na žádost poskytnuta ÚOOÚ.

Obsah záznamu správce (odst. 1) a záznamu zpracovatele (odst. 2) se liší: správce uvádí komplexnější informace (účely, kategorie subjektů, plánované lhůty výmazu), zpracovatel uvádí zejména kategorie zpracování prováděné pro jednotlivé správce.

**Výjimka pro organizace s méně než 250 zaměstnanci** (odst. 5) je v praxi velmi omezená: tři kumulativní podmínky zpracování bez rizika, příležitostnosti a zvláštních kategorií údajů nebo trestněprávních údajů se splňují jen výjimečně. Fakticky většina zaměstnavatelů (i malých) vede personální agendu (mzdy, pracovní smlouvy), čímž zpracování přestává být „příležitostné" — výjimka se tedy nevztahuje. Povinnost vést záznamy se tudíž v praxi dotýká naprosté většiny správců.

---

### Čl. 31 — Spolupráce s dozorovým úřadem

> **Čl. 31**
> *Správce a zpracovatel a případně jejich zástupci spolupracují na žádost s dozorovým úřadem při plnění jeho úkolů.*

**Výklad:** Stručné, ale závazné ustanovení, jež povinnost spolupráce s ÚOOÚ zakotvuje jako obecný princip. Konkrétní projevy spolupráce jsou pak upraveny v kapitolách VI a VII (kontrolní pravomoci úřadu, věcná příslušnost). Odmítnutí spolupráce je přestupkem dle čl. 83 odst. 4.

---

## Oddíl 2 — Bezpečnost osobních údajů (čl. 32–34)

### Čl. 32 — Zabezpečení zpracování

> **Čl. 32 odst. 1**
> *Správce a zpracovatel s přihlédnutím ke stavu techniky, nákladům na provedení, povaze, rozsahu, kontextu a účelům zpracování i k různě pravděpodobným a různě závažným rizikům pro práva a svobody fyzických osob provedou vhodná technická a organizační opatření, aby zajistili úroveň zabezpečení odpovídající danému riziku, přičemž tato opatření zahrnují podle potřeby mimo jiné: a) pseudonymizaci a šifrování osobních údajů; b) schopnost zajistit trvalou důvěrnost, integritu, dostupnost a odolnost systémů a služeb zpracování; c) schopnost obnovit dostupnost osobních údajů a přístup k nim včas v případě fyzického či technického incidentu; d) proces pravidelného testování, posuzování a hodnocení účinnosti technických a organizačních opatření pro zajištění bezpečnosti zpracování.*

> **Čl. 32 odst. 2**
> *Při posuzování přiměřené úrovně zabezpečení se zohlední zejména rizika, která zpracování představuje, zejména náhodné nebo protiprávní zničení, ztráta, pozměňování, neoprávněné zpřístupnění osobních údajů, které jsou přenášeny, uchovávány nebo jinak zpracovávány, nebo neoprávněný přístup k nim.*

> **Čl. 32 odst. 3**
> *Dodržování schválených kodexů chování uvedených v článku 40 nebo schváleného mechanismu pro vydávání osvědčení uvedeného v článku 42 může být použito jako prvek pro doložení souladu s požadavky stanovenými v odstavci 1 tohoto článku.*

**Výklad:** Článek 32 stanoví **povinnost zabezpečení** pro správce i zpracovatele — jde o jednu z mála ustanovení kapitoly IV, kde jsou obě strany postaveny na roveň. Úroveň zabezpečení je vždy relativní: hodnotí se vůči stavu techniky, nákladové přiměřenosti a zejména riziku pro práva a svobody fyzických osob.

Výčet v odst. 1 písm. a)–d) je demonstrativní. Pseudonymizace a šifrování jsou zmíněny jako příklady technických opatření. Pojmy důvěrnost, integrita, dostupnost a odolnost (*confidentiality, integrity, availability, resilience*) odpovídají standardním principům informační bezpečnosti (ISO/IEC 27001). Schopnost obnovit dostupnost dat po incidentu (písm. c)) implikuje povinnost zálohování a disaster recovery plánů. Pravidelné testování (písm. d)) zahrnuje penetrační testy, bezpečnostní audity a hodnocení zranitelností.

Zákon č. 110/2019 Sb. zvláštní prováděcí pravidla k čl. 32 neobsahuje; v oblasti kybernetické bezpečnosti může přijít v úvahu souběh s zákonem č. 181/2014 Sb., o kybernetické bezpečnosti, resp. novými pravidly dle NIS2 (zákon č. 124/2024 Sb.).

---

### Čl. 33 — Ohlášení porušení zabezpečení osobních údajů dozorovému úřadu

> **Čl. 33 odst. 1**
> *V případě porušení zabezpečení osobních údajů ohlásí správce bez zbytečného odkladu, a pokud možno nejpozději do 72 hodin od okamžiku, kdy se o něm dozvěděl, příslušnému dozorovému úřadu toto porušení v souladu s článkem 55, pokud není pravděpodobné, že by toto porušení zabezpečení osobních údajů mělo za následek riziko pro práva a svobody fyzických osob. Pokud ohlášení dozorovému úřadu není provedeno do 72 hodin, musí být doprovázeno uvedením důvodů prodlení.*

> **Čl. 33 odst. 2**
> *Zpracovatel ohlásí porušení zabezpečení osobních údajů správci bez zbytečného odkladu poté, co se o tomto porušení dozvěděl.*

> **Čl. 33 odst. 3**
> *Ohlášení uvedené v odstavci 1 musí přinejmenším: a) popisovat povahu daného porušení zabezpečení osobních údajů, včetně, pokud je to možné, kategorií a přibližného počtu dotčených subjektů údajů a kategorií a přibližného počtu dotčených záznamů osobních údajů; b) sdělovat jméno a kontaktní údaje pověřence pro ochranu osobních údajů nebo jiného kontaktního místa, kde lze získat bližší informace; c) popisovat pravděpodobné důsledky porušení zabezpečení osobních údajů; d) popisovat opatření, která správce přijal nebo navrhuje přijmout k řešení daného porušení zabezpečení osobních údajů, případně včetně opatření ke zmírnění případných nepříznivých dopadů.*

> **Čl. 33 odst. 4**
> *Pokud a v rozsahu, v němž není možné poskytnout informace ve stejnou dobu, mohou být informace poskytnuty postupně bez zbytečného dalšího odkladu.*

> **Čl. 33 odst. 5**
> *Správce zdokumentuje veškerá porušení zabezpečení osobních údajů, včetně skutečností s nimi souvisejících, jejich dopadů a přijatých nápravných opatření. Tato dokumentace musí dozorovému úřadu umožnit ověření souladu s tímto článkem.*

**Výklad:** Lhůta **72 hodin** od okamžiku, kdy se správce o porušení dozvěděl, je jedním z nejznámějších a nejčastěji diskutovaných prvků GDPR. Porušení zabezpečení (*personal data breach*) je definováno v čl. 4 bod 12 jako narušení bezpečnosti vedoucí k náhodnému nebo protiprávnímu zničení, ztrátě, pozměnění, neoprávněnému zpřístupnění nebo přístupu k osobním údajům. Kategoriemi jsou breache důvěrnosti, integrity a dostupnosti.

Oznámení ÚOOÚ se nevyžaduje, **pokud** je nepravděpodobné, že by porušení představovalo riziko pro práva a svobody fyzických osob — to je sám správce povinen posoudit a posouzení zdokumentovat (odst. 5). Pokud risk není zanedbatelný, ohlašuje správce sám; zpracovatel hlásí správci (odst. 2), a správce pak ÚOOÚ. Fázovité hlášení (odst. 4) je výslovně přípustné — první notifikace může obsahovat dostupné údaje a doplňují se postupně.

Zákon č. 110/2019 Sb. v § 12 umožňuje ÚOOÚ stanovit prováděcím předpisem bližší podmínky ohlašování; k vydání takové vyhlášky nedošlo, platí tedy přímo GDPR. ÚOOÚ přijal obecné pokyny pro ohlašování porušení a online formulář pro notifikaci.

---

### Čl. 34 — Oznámení porušení zabezpečení osobních údajů subjektu údajů

> **Čl. 34 odst. 1**
> *Pokud je pravděpodobné, že porušení zabezpečení osobních údajů bude mít za následek vysoké riziko pro práva a svobody fyzických osob, oznámí správce toto porušení bez zbytečného odkladu subjektu údajů.*

> **Čl. 34 odst. 2**
> *Oznámení subjektu údajů uvedené v odstavci 1 tohoto článku popisuje srozumitelným a přehledným jazykem povahu daného porušení zabezpečení osobních údajů a obsahuje přinejmenším informace a opatření uvedená v čl. 33 odst. 3 písm. b), c) a d).*

> **Čl. 34 odst. 3**
> *Oznámení subjektu údajů uvedené v odstavci 1 se nevyžaduje, je-li splněna kteroukoli z těchto podmínek: a) správce zavedl vhodná technická a organizační ochranná opatření a tato opatření byla na osobní údaje dotčené porušením zabezpečení uplatněna, a to zejména opatření, díky nimž jsou osobní údaje nesrozumitelné pro každého, kdo k nim nemá oprávněný přístup, jako je šifrování; b) správce přijal následná opatření, která zajistí, že vysoké riziko pro práva a svobody subjektů údajů uvedené v odstavci 1 se s největší pravděpodobností již neprojeví; c) oznámení by vyžadovalo nepřiměřené úsilí. V takovém případě je místo toho vydáno veřejné sdělení nebo je přijato podobné opatření, při němž jsou subjekty údajů informovány stejně účinným způsobem.*

> **Čl. 34 odst. 4**
> *Pokud správce dosud neoznámil porušení zabezpečení osobních údajů subjektu údajů, může dozorový úřad po zvážení pravděpodobnosti, že porušení zabezpečení bude mít za následek vysoké riziko, toto oznámení požadovat nebo rozhodnout, že je splněna jedna z podmínek uvedených v odstavci 3.*

**Výklad:** Oznámení subjektu údajů (čl. 34) je kvalifikovanější povinností než oznámení ÚOOÚ (čl. 33): vyžaduje se až při **vysokém riziku** (nikoli jen riziku). Jde o dvoustupňový mechanismus: nejprve se posuzuje, zda riziko vůbec existuje (pro oznamovací povinnost vůči ÚOOÚ stačí obecné „riziko"), a teprve pak, zda jde o riziko vysoké (pro přímé informování subjektů).

Výjimky v odst. 3 mají praktický smysl: šifrování dat (písm. a)) zbavuje správce povinnosti informovat subjekty, protože pro neoprávněné osoby jsou data nečitelná. Analogicky, pokud správce situaci rychle zhojí a vysoké riziko se již nevznikne (písm. b)), nebo pokud je počet dotčených osob tak velký, že individuální kontakt je nepřiměřený — pak lze přistoupit k veřejnému sdělení (písm. c)), například tiskové zprávě nebo banneru na webu.

ÚOOÚ je oprávněn nařídit oznámení subjektům, i pokud správce tuto povinnost nevyhodnotil jako nutnou (odst. 4).

---

## Oddíl 3 — Posouzení vlivu na ochranu osobních údajů a předchozí konzultace (čl. 35–36)

### Čl. 35 — Posouzení vlivu na ochranu osobních údajů (DPIA)

> **Čl. 35 odst. 1**
> *Pokud je pravděpodobné, že určitý druh zpracování, zejména s využitím nových technologií, s přihlédnutím k povaze, rozsahu, kontextu a účelům zpracování, bude mít za následek vysoké riziko pro práva a svobody fyzických osob, provede správce před zahájením zpracování posouzení vlivu zamýšlených operací zpracování na ochranu osobních údajů. Jedno posouzení se může týkat souboru podobných operací zpracování, které představují podobná vysoká rizika.*

> **Čl. 35 odst. 2**
> *Správce při provádění posouzení vlivu na ochranu osobních údajů vyhledá radu pověřence pro ochranu osobních údajů, byl-li jmenován.*

> **Čl. 35 odst. 3**
> *Posouzení vlivu na ochranu osobních údajů uvedené v odstavci 1 je vyžadováno zejména v případě: a) systematického a rozsáhlého vyhodnocování osobních aspektů fyzických osob, které je prováděno automatizovaně, včetně profilování, a na jehož základě se přijímají rozhodnutí, která mají pro fyzické osoby právní účinky nebo která je obdobně závažně ovlivňují; b) rozsáhlého zpracování zvláštních kategorií údajů uvedených v čl. 9 odst. 1 nebo osobních údajů týkajících se rozsudků v trestních věcech a trestných činů uvedených v článku 10; nebo c) systematického sledování veřejně přístupného prostoru ve velkém měřítku.*

> **Čl. 35 odst. 7**
> *Posouzení musí obsahovat přinejmenším: a) systematický popis zamýšlených operací zpracování a účelů zpracování, případně včetně oprávněného zájmu sledovaného správcem; b) posouzení nezbytnosti a přiměřenosti operací zpracování z hlediska účelů; c) posouzení rizik pro práva a svobody subjektů údajů uvedených v odstavci 1; d) opatření zamýšlená k řešení těchto rizik, včetně záruk, bezpečnostních opatření a mechanismů zajišťujících ochranu osobních údajů a doložení souladu s tímto nařízením, s přihlédnutím k právům a oprávněným zájmům subjektů údajů a dalších dotčených osob.*

**Výklad:** DPIA (*Data Protection Impact Assessment*) je preventivní nástroj řízení rizik: správce jej provádí **před zahájením** zpracování, nikoli ex post. Odstavec 3 vyjmenovává tři kategorie zpracování, u nichž je DPIA vždy povinná; výčet není taxativní — ÚOOÚ zveřejnil seznam dalších typů zpracování, u nichž DPIA vyžaduje (čl. 35 odst. 4). EDPB vydal pokyny k metodologii DPIA (WP248, Guidelines on DPIA).

Konzultace s pověřencem (odst. 2) má doporučující charakter; zákon č. 110/2019 Sb. v § 9 umožňuje výjimky z povinnosti DPIA, pokud zpracování probíhá na základě zákona, který sám provedl odpovídající posouzení. V § 10 je pak zakotvena možnost ÚOOÚ stanovit seznam zpracování nevyžadujících DPIA.

Obsahové náležitosti DPIA (odst. 7 písm. a)–d)) jsou minimální — praxe vyžaduje i zapracování výsledků konzultace se subjekty údajů nebo jejich zástupci (odst. 9) a zhodnocení alternativních scénářů. Výsledek DPIA (reziduum rizika) rozhoduje o tom, zda je nutná předchozí konzultace dle čl. 36.

---

### Čl. 36 — Předchozí konzultace

> **Čl. 36 odst. 1**
> *Správce konzultuje dozorový úřad před zahájením zpracování v případě, kdy posouzení vlivu na ochranu osobních údajů provedené podle článku 35 ukazuje, že zpracování by mělo za následek vysoké riziko v případě, že by správce nepřijal opatření ke zmírnění tohoto rizika.*

> **Čl. 36 odst. 2**
> *Pokud dozorový úřad dospěje k názoru, že zamýšlené zpracování uvedené v odstavci 1 by bylo v rozporu s tímto nařízením, a to zejména tehdy, pokud správce dostatečně neidentifikoval nebo nesnížil riziko, poskytne dozorový úřad ve lhůtě do osmi týdnů od obdržení žádosti o konzultaci písemné doporučení správci a případně zpracovateli a může využít veškerých svých pravomocí uvedených v článku 58. Tato lhůta může být prodloužena o šest týdnů s přihlédnutím ke složitosti zamýšleného zpracování. Dozorový úřad informuje správce a případně zpracovatele o takovém prodloužení do jednoho měsíce od obdržení žádosti o konzultaci spolu s důvody prodlení. Tyto lhůty mohou být pozastaveny, dokud dozorový úřad nezíská informace, o které požádal pro účely konzultace.*

**Výklad:** Předchozí konzultace s ÚOOÚ je povinná tehdy, kdy DPIA prokáže **vysoké reziduum rizika** i po zavedení zmírňujících opatření. Jde tedy o zvláštní proceduru, nikoli rutinní záležitost. ÚOOÚ v rámci konzultace hodnotí soulad s GDPR a může využít veškerá oprávnění dle čl. 58, včetně vydání závazného příkazu k pozastavení nebo úpravě zpracování.

Lhůta 8 týdnů (s možností prodloužení o 6 týdnů) je poměrně dlouhá; zákon č. 110/2019 Sb. v § 10 odst. 2 upřesňuje, že ÚOOÚ může v rámci konzultace vydat i předběžné opatření.

---

## Oddíl 4 — Pověřenec pro ochranu osobních údajů (čl. 37–39)

### Čl. 37 — Jmenování pověřence pro ochranu osobních údajů

> **Čl. 37 odst. 1**
> *Správce a zpracovatel jmenují pověřence pro ochranu osobních údajů v každém případě, kde: a) zpracování provádí orgán veřejné moci nebo veřejný subjekt, s výjimkou soudů jednajících v rámci svých soudních pravomocí; b) hlavní činnosti správce nebo zpracovatele spočívají v operacích zpracování, které ze své podstaty, svého rozsahu nebo svých účelů vyžadují rozsáhlé pravidelné a systematické monitorování subjektů údajů; nebo c) hlavní činnosti správce nebo zpracovatele spočívají v rozsáhlém zpracování zvláštních kategorií údajů uvedených v článku 9 nebo osobních údajů týkajících se rozsudků v trestních věcech a trestných činů uvedených v článku 10.*

> **Čl. 37 odst. 5**
> *Pověřenec pro ochranu osobních údajů je jmenován na základě profesních kvalit, a zejména na základě odborných znalostí práva a praxe v oblasti ochrany osobních údajů a schopnosti plnit úkoly uvedené v článku 39.*

> **Čl. 37 odst. 6**
> *Pověřenec pro ochranu osobních údajů může být zaměstnancem správce nebo zpracovatele nebo plnit své úkoly na základě smlouvy o poskytování služeb.*

> **Čl. 37 odst. 7**
> *Správce nebo zpracovatel zveřejní kontaktní údaje pověřence pro ochranu osobních údajů a sdělí je dozorovému úřadu.*

**Výklad:** Pověřenec pro ochranu osobních údajů (DPO — *Data Protection Officer*) je institutionalizovaným vnitřním kontrolorem souladu správce/zpracovatele s GDPR. Podmínky jmenování v odst. 1 jsou pro orgány veřejné moci bezvýjimečné (všechny musejí DPO jmenovat, vyjma soudů v soudních věcech); pro soukromý sektor závisejí na kritériích rozsáhlého monitorování nebo zpracování zvláštních kategorií.

Zákon č. 110/2019 Sb. v **§ 14** stanoví podrobnosti jmenování DPO pro potřeby adaptace GDPR v českém právním řádu — zejména pro subjekty veřejného sektoru a skupiny podniků. Správci mohou jmenovat externího DPO (na základě smlouvy o poskytování služeb), skupiny podniků mohou jmenovat jednoho společného DPO (čl. 37 odst. 2), a pro veřejný sektor lze jednoho DPO sdílet mezi více orgány (odst. 3).

Odst. 5 formuluje profesní požadavky: jde o kombinaci právních znalostí (GDPR, zákon č. 110/2019 Sb., sektorové předpisy) a provozní způsobilosti (schopnost provádět audity, školit zaměstnance, komunikovat s ÚOOÚ). GDPR nestanoví formální certifikaci jako podmínku, ale EDPB doporučuje doložení odbornosti například prostřednictvím uznávané certifikace nebo prokazatelné praxe.

---

### Čl. 38 — Postavení pověřence pro ochranu osobních údajů

> **Čl. 38 odst. 1**
> *Správce a zpracovatel zajistí, aby byl pověřenec pro ochranu osobních údajů řádně a včas zapojen do veškerých záležitostí souvisejících s ochranou osobních údajů.*

> **Čl. 38 odst. 3**
> *Správce a zpracovatel zajistí, aby pověřenec pro ochranu osobních údajů nedostával žádné pokyny týkající se výkonu těchto úkolů. Nesmí být správcem ani zpracovatelem odvolán ani postižen za výkon svých úkolů. Pověřenec pro ochranu osobních údajů je přímo podřízen nejvyšší úrovni vedení správce nebo zpracovatele.*

> **Čl. 38 odst. 5**
> *Pověřenec pro ochranu osobních údajů je při výkonu svých úkolů vázán povinností zachovávat mlčenlivost nebo důvěrnost v souladu s právem Unie nebo členského státu.*

> **Čl. 38 odst. 6**
> *Pověřenec pro ochranu osobních údajů může plnit i jiné úkoly. Správce nebo zpracovatel zajistí, aby žádný z těchto úkolů nevyvolával střet zájmů.*

**Výklad:** Nezávislost DPO je klíčovým předpokladem smysluplného výkonu funkce. Trojice záruk z odst. 3 — zákaz instrukcí, zákaz odvolání pro výkon funkce a přímá podřízenost nejvyššímu vedení — má za cíl vyloučit situace, kdy je DPO formálně jmenován, ale fakticky marginalizován. Zákaz střetu zájmů (odst. 6) brání tomu, aby DPO zároveň plnil funkce, u nichž by sám rozhodoval o zpracování (např. ředitel IT, vedoucí HR). EDPB vydal pokyny k funkci DPO (WP243).

Mlčenlivost DPO (odst. 5) je specifická: DPO zachovává mlčenlivost i vůči svému zaměstnavateli (správci) ohledně totožnosti zaměstnance, který se na DPO obrátil s podnětem. Tím je chráněn efektivní přístup subjektů a zaměstnanců k DPO (srov. čl. 38 odst. 4).

---

### Čl. 39 — Úkoly pověřence pro ochranu osobních údajů

> **Čl. 39 odst. 1**
> *Pověřenec pro ochranu osobních údajů plní přinejmenším tyto úkoly: a) informuje a poskytuje poradenství správci, zpracovateli a zaměstnancům, kteří provádějí zpracování, o jejich povinnostech vyplývajících z tohoto nařízení a z jiných ustanovení práva Unie nebo členského státu v oblasti ochrany osobních údajů; b) monitoruje soulad s tímto nařízením, s jinými předpisy Unie nebo členského státu v oblasti ochrany osobních údajů a se zásadami správce nebo zpracovatele v oblasti ochrany osobních údajů, včetně přidělení odpovědností, zvyšování povědomí a školení pracovníků zapojených do operací zpracování a příslušných auditů; c) poskytuje na požádání poradenství, pokud jde o posouzení vlivu na ochranu osobních údajů, a monitoruje jeho provádění v souladu s článkem 35; d) spolupracuje s dozorovým úřadem; e) plní úlohu kontaktního místa pro dozorový úřad v záležitostech týkajících se zpracování, včetně předchozí konzultace podle článku 36, a případně konzultuje záležitosti, které se k nim vztahují.*

> **Čl. 39 odst. 2**
> *Pověřenec pro ochranu osobních údajů při výkonu svých úkolů náležitě zohledňuje rizika spojená s operacemi zpracování, přičemž bere v úvahu povahu, rozsah, kontext a účely zpracování.*

**Výklad:** Úkoly DPO jsou minimálním zákonným rámcem — správce může DPO svěřit i rozsáhlejší kompetence (audit, dokumentace RoPA, řízení DPIA, komunikace se subjekty údajů). Pět zákonných úkolů lze strukturovat do čtyř oblastí: (1) poradenství a vzdělávání (písm. a)), (2) monitoring souladu (písm. b)), (3) podpora DPIA (písm. c)) a (4) styk s ÚOOÚ (písm. d)–e)).

DPO není rozhodovacím orgánem — neprovádí sám zpracování, nerozhoduje o zákonnosti zpracování. Je **poradním a monitorovacím** subjektem; konečná odpovědnost zůstává na správci. To je klíčové z hlediska odpovědnosti: SDEU v rozsudku ve věci správce jako správce osobních údajů (obecně) potvrdil, že přidělení funkce DPO nezbavuje správce vlastní odpovědnosti.

---

## Oddíl 5 — Kodexy chování a certifikace (čl. 40–43)

### Čl. 40 — Kodexy chování

> **Čl. 40 odst. 1**
> *Členské státy, dozorové úřady, sbor a Komise podporují vypracovávání kodexů chování, jejichž cílem je přispět k řádnému uplatňování tohoto nařízení s přihlédnutím ke specifickým znakům různých odvětví, v nichž probíhá zpracování, a ke specifickým potřebám mikropodniků a malých a středních podniků.*

> **Čl. 40 odst. 2**
> *Sdružení a jiné subjekty zastupující kategorie správců nebo zpracovatelů mohou připravovat kodexy chování, nebo měnit nebo rozšiřovat takové kodexy, za účelem upřesnění uplatňování tohoto nařízení, například pokud jde o: a) spravedlivé a transparentní zpracování; b) oprávněné zájmy sledované správci v konkrétních kontextech; c) shromažďování osobních údajů; d) pseudonymizaci osobních údajů; e) informace poskytované veřejnosti a subjektům údajů; f) výkon práv subjektů údajů; g) informace poskytované dětem a jejich ochranu a způsob, jakým má být získán souhlas osob nesoucích rodičovskou odpovědnost za děti; h) opatření a postupy uvedené v článcích 24 a 25 a opatření k zajištění bezpečnosti zpracování uvedená v článku 32; i) oznamování porušení zabezpečení osobních údajů dozorovým úřadům a sdělování takových porušení zabezpečení osobních údajů subjektům údajů; j) předávání osobních údajů třetím zemím nebo mezinárodním organizacím; nebo k) mimosoudní řízení a jiné postupy pro řešení sporů mezi správci a subjekty údajů týkajících se zpracování, aniž jsou dotčena práva subjektů údajů podle článků 77 a 79.*

> **Čl. 40 odst. 5**
> *Sdružení a jiné subjekty uvedené v odstavci 2 tohoto článku, jež mají v úmyslu připravit kodex chování nebo měnit nebo rozšiřovat existující kodex, předkládají návrh kodexu, změny nebo rozšíření dozorovému úřadu příslušnému podle článku 55. Dozorový úřad vydá stanovisko k tomu, zda je návrh kodexu, změny nebo rozšíření v souladu s tímto nařízením, a schválí jej, pokud dospěje k závěru, že poskytuje dostatečné vhodné záruky.*

**Výklad:** Kodexy chování jsou **sektorovými samoregulačními nástroji** přijímanými odvětvovými sdruženími — například zdravotnictvím, pojišťovnictvím, telekomunikacemi nebo HR. Schválený kodex (schválený ÚOOÚ nebo pro přeshraniční zpracování přes mechanismus konzistence EDPB a Komisí s obecnou platností dle odst. 9) slouží správci jako dokladový prostředek souladu s GDPR (čl. 24 odst. 3, čl. 28 odst. 5, čl. 32 odst. 3, čl. 40 odst. 3).

Zákon č. 110/2019 Sb. v **§ 54a** (vloženém novelou) upravuje řízení o rozhodnutí ÚOOÚ o kodexu chování, které navazuje na schvalovací proceduru dle čl. 40 odst. 5.

Kodex musí obsahovat mechanismy pro monitorování dodržování (odst. 4) — v tom spočívá funkce akreditovaného monitorovacího subjektu dle čl. 41.

---

### Čl. 41 — Monitorování schválených kodexů chování

> **Čl. 41 odst. 1**
> *Aniž jsou dotčeny úkoly a pravomoci příslušného dozorového úřadu podle článků 57 a 58, může být monitorování dodržování kodexu chování podle článku 40 prováděno subjektem, který má vhodnou úroveň odborných znalostí v oblasti předmětu kodexu a který je za tím účelem akreditován příslušným dozorovým úřadem.*

> **Čl. 41 odst. 4**
> *Aniž jsou dotčeny úkoly a pravomoci příslušného dozorového úřadu a ustanovení kapitoly VIII, přijme subjekt uvedený v odstavci 1 tohoto článku při porušení kodexu správcem nebo zpracovatelem, s přihlédnutím k vhodným zárukám, vhodná opatření, včetně pozastavení nebo vyloučení daného správce nebo zpracovatele z kodexu. Informuje o těchto opatřeních a jejich důvodech příslušný dozorový úřad.*

**Výklad:** Monitorovací subjekt (*Code Owner Body*) je soukromoprávní entita akreditovaná ÚOOÚ, jež průběžně kontroluje, zda signatáři kodexu dodržují jeho pravidla. Tím se odděluje každodenní dohled (monitorovací subjekt) od zákonného dozoru (ÚOOÚ). Akreditace monitorovacího subjektu podléhá kritériím nezávislosti, odbornosti a konfliktů zájmů (odst. 2). Článek 41 se nevztahuje na veřejné orgány (odst. 6).

---

### Čl. 42 — Vydávání osvědčení (certifikace)

> **Čl. 42 odst. 1**
> *Členské státy, dozorové úřady, sbor a Komise podporují, zejména na úrovni Unie, vytváření mechanismů pro vydávání osvědčení v oblasti ochrany osobních údajů a pečetí a značek ochrany osobních údajů, jejichž cílem je prokázat, že operace zpracování správců a zpracovatelů jsou v souladu s tímto nařízením. Přihlíží se ke specifickým potřebám mikropodniků a malých a středních podniků.*

> **Čl. 42 odst. 3**
> *Vydávání osvědčení je dobrovolné a probíhá prostřednictvím transparentního procesu.*

> **Čl. 42 odst. 4**
> *Vydáním osvědčení podle tohoto článku se nesnižuje odpovědnost správce nebo zpracovatele za soulad s tímto nařízením a tím nejsou dotčeny úkoly a pravomoci dozorových úřadů příslušných podle článku 55 nebo 56.*

> **Čl. 42 odst. 7**
> *Osvědčení je vydáváno správci nebo zpracovateli na dobu nejvýše tří let a může být za stejných podmínek obnoveno, jsou-li i nadále splňovány příslušné požadavky. Osvědčení je odebráno, případně certifikačními subjekty uvedenými v článku 43 nebo příslušným dozorovým úřadem, pokud požadavky pro vydání osvědčení nejsou nebo přestaly být splňovány.*

**Výklad:** Certifikace GDPR je dobrovolná a má demonstrační funkci — umožňuje správci nebo zpracovateli prokázat třetím stranám (klientům, partnerům, ÚOOÚ) soulad s GDPR pro konkrétní operace zpracování. Klíčovým příslibem je potenciální vznik **Evropské pečeti ochrany osobních údajů** (*European Data Protection Seal*) jako jednotného unijního certifikátu (čl. 42 odst. 5). EDPB schválil kritéria pro certifikaci; vydávaná osvědčení jsou platná po dobu nejvýše tří let.

Certifikace se může vztahovat i na zpracovatele mimo EU jako alternativní záruka pro předávání osobních údajů do třetích zemí (čl. 42 odst. 2, čl. 46 odst. 2 písm. f)).

Zákon č. 110/2019 Sb. v **§ 15** upravuje akreditaci subjektů pro vydávání osvědčení v ČR — příslušnost má ÚOOÚ nebo Český institut pro akreditaci.

---

### Čl. 43 — Certifikační subjekty

> **Čl. 43 odst. 1**
> *Aniž jsou dotčeny úkoly a pravomoci příslušného dozorového úřadu podle článků 57 a 58, vydávají certifikační subjekty, jež mají vhodnou úroveň odborných znalostí v oblasti ochrany osobních údajů, po sdělení dozorovému úřadu, aby mohl uplatňovat pravomoci podle čl. 58 odst. 2 písm. h) v případě nutnosti, osvědčení a tato osvědčení obnovují. Členské státy zajistí, aby tyto certifikační subjekty byly akreditovány jedním nebo oběma z těchto subjektů: a) dozorový úřad příslušný podle článku 55 nebo 56; b) vnitrostátní akreditační orgán jmenovaný v souladu s nařízením Evropského parlamentu a Rady (ES) č. 765/2008 v souladu s normou EN-ISO/IEC 17065/2012 a s dodatečnými požadavky stanoveného dozorovým úřadem příslušným podle článku 55 nebo 56.*

> **Čl. 43 odst. 4**
> *Certifikační subjekty uvedené v odstavci 1 odpovídají za náležité posouzení vedoucí k vydání osvědčení nebo jeho odebrání, aniž je dotčena odpovědnost správce nebo zpracovatele za soulad s tímto nařízením. Akreditace je vydávána na dobu nejvýše pěti let a může být za stejných podmínek obnovena za předpokladu, že certifikační subjekt splňuje požadavky stanovené v tomto článku.*

**Výklad:** Certifikační subjekty jsou akreditovány buď přímo ÚOOÚ, nebo národním akreditačním orgánem (v ČR Český institut pro akreditaci, o.p.s.) dle normy EN-ISO/IEC 17065. Zákon č. 110/2019 Sb. § 15 stanoví, že ÚOOÚ vydává pravidla pro akreditaci a vede seznam akreditovaných certifikačních subjektů. Certifikační subjekt odpovídá za náležité provedení certifikačního auditu, avšak odpovědnost správce/zpracovatele za soulad s GDPR tím není dotčena (čl. 43 odst. 4) — certifikát není absolutní zárukou souladu ani liberací z odpovědnosti.

---

*Konec kapitoly IV.*

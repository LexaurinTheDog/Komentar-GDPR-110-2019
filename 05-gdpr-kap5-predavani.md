# 05 — Kapitola V GDPR: Předávání osobních údajů do třetích zemí nebo mezinárodním organizacím

Kapitola V GDPR (čl. 44–50) zavádí ucelený, hierarchicky strukturovaný systém pravidel pro předávání osobních údajů mimo území Evropského hospodářského prostoru (EHP). Jde o jeden z nejcitlivějších aspektů nařízení: tok dat do třetích zemí je nezbytný pro mezinárodní obchod a spolupráci, avšak nesmí vést k obcházení ochrany zaručené GDPR. Celá kapitola stojí na základní myšlence, že úroveň ochrany fyzických osob zaručená nařízením musí být zachována bez ohledu na to, do jaké země se data přesouvají. Zákon č. 110/2019 Sb. (dále „ZZOÚ") sám předávání do třetích zemí specificky neupravuje — Česká republika v tomto bodě nevyužila žádnou otevřenou klauzuli GDPR —, takže pro praxi platí výhradně níže popsaná unijní pravidla.

---

### Čl. 44 — Obecná zásada pro předávání

> **Čl. 44**
> *Jakékoli předávání osobních údajů, jež jsou zpracovávány nebo jsou po předání určeny ke zpracování, do třetí země nebo mezinárodní organizaci se uskuteční pouze tehdy, jsou-li při dodržení ostatních ustanovení tohoto nařízení splněny podmínky stanovené v této kapitole správcem a zpracovatelem, a to i pro další předávání osobních údajů z dané třetí země nebo mezinárodní organizace do jiné třetí země nebo mezinárodní organizaci. Veškerá ustanovení této kapitoly se použijí tak, aby nebyla snížena úroveň ochrany fyzických osob zaručená tímto nařízením.*

**Výklad:** Článek 44 plní funkci obecné uzavírací klauzule pro celou kapitolu: předávání osobních údajů do třetí země nebo mezinárodní organizaci je podmíněno tím, že jsou splněny podmínky jednoho z titulů stanovených v čl. 45–49. Klíčovým pojmem je „předávání" (*transfer*), které GDPR nedefinuje výslovně, avšak judikatura Soudního dvora EU i stanoviska Evropského sboru pro ochranu osobních údajů (EDPB) vykládají tento pojem funkčně: zahrnuje jakékoli zpřístupnění nebo zpřístupnitelnost dat subjektu mimo EHP, ať již formou aktivního přenosu, či pasivního vzdáleného přístupu. Zásadní je také výslovný záchyt *dalšího předávání* (*onward transfer*): přijme-li třetí země data a hodlá je dále předat do jiné třetí země nebo mezinárodní organizaci, musí být i toto navazující předání pokryto vhodným titulem. Tím se uzavírá potenciální obcházení ochrany skrze „bezpečné tranzitní země". Recitál 101 zdůrazňuje, že pohyb dat mimo Unii nesmí vést ke snížení úrovně ochrany garantované nařízením — jde o tzv. princip ekvivalence. Pokud správce nebo zpracovatel nesplní podmínky kapitoly V, porušuje nejen čl. 44, ale zpravidla i příslušný konkrétní článek (čl. 46, 47, 49), na jehož titul se odvolával.

#### F. Kazuistika

**1. Modelová situace.** Česká společnost (správce) využívá cloudové úložiště provozované poskytovatelem se servery v třetí zemi a navíc tento poskytovatel data dále zrcadlí do jiné třetí země. Společnost se domnívá, že stačí smlouva o službě a o žádný titul kapitoly V se nestará. Důkazy: lokalizace serverů, popis dalšího předání (onward transfer), existence titulu předání, posouzení dopadu.

**2. Právní otázka.** Splnila společnost obecnou zásadu pro předávání dle čl. 44, včetně pokrytí dalšího předání vhodným titulem?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 44 (uzavírací klauzule, nutnost titulu, pokrytí onward transfer, princip ekvivalence).
- *Související ustanovení téhož zákona:* čl. 45 (adekvátnost), čl. 46 (záruky), čl. 49 (výjimky), čl. 5.
- *Související předpisy:* recitál 101; ZZOÚ (bez zvláštní úpravy předávání).
- *Judikatura:* SDEU Schrems II — funkční pojetí předání a nutnost reálné ekvivalence.

**4. Subsumpce.** Uložení dat na servery v třetí zemi i jejich zrcadlení jsou předáním. Každé předání (vč. dalšího) vyžaduje titul dle čl. 45–49. Pouhá smlouva o službě titulem není → porušení čl. 44.

**5. Řešení.** Společnost musí zvolit a doložit titul (adekvátnost / SCC / BCR / výjimka) pokrývající i onward transfer a případně přijmout dodatečná opatření. Procesně: TIA, sjednání SCC, šifrování. Bez titulu je předání nezákonné.

**6. Varianty.** (a) Pokud by se servery nacházely v zemi s rozhodnutím o adekvátnosti, postačil by čl. 45. (b) Pokud by data byla skutečně anonymizována, nešlo by o předání osobních údajů.

#### G. Protiargumenty a rizika

- *„Smlouva o cloudu stačí."* Smlouva o službě není titulem předání; nutný je titul dle kapitoly V.
- *„Onward transfer nás neřeší."* Čl. 44 výslovně pokrývá i další předání; bez titulu je nezákonné.
- *Slabé místo:* pojem „předání" není definován; rozhoduje funkční výklad (zpřístupnění mimo EHP), což může být sporné u pouhého vzdáleného přístupu.

#### H. Praktický závěr

Každé předání osobních údajů mimo EHP — včetně dalšího předání — musí být kryto některým titulem kapitoly V a nesmí snížit úroveň ochrany; smlouva o službě sama titulem není.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Dochází k předání/zpřístupnění mimo EHP (funkční výklad)?
- [ ] Je zvolen a doložen titul dle čl. 45–49?
- [ ] Je pokryto i další předání (onward transfer)?
- [ ] Nesnižuje předání úroveň ochrany (princip ekvivalence)?
- [ ] Bylo provedeno posouzení dopadu (TIA), je-li třeba?

**Typicky rozhodné důkazy / podklady:** mapa toků dat a lokalizace serverů, popis dalších předání, dokumentace titulu předání, TIA, dodatečná opatření.

---


<!-- LEGAL-REVISION:BEGIN id=97b4173bfc528a6534b7 generator=2026-07-17.4 source_sha256=064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea -->
#### Revizní doplnění k Čl. 44 — General principle for transfers

> Revize: 17. 7. 2026 | Znění předpisu k: datum dokumentu místního zdroje 27. 4. 2016 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-24/EU Law/Legal Acts-EN/Legal Acts/Regulations/2016/32016R0679.md`; identifikátor verze: `32016R0679`; SHA-256: `064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea`.

##### Znění ustanovení

>  Any transfer of personal data which are undergoing processing or are intended for processing after transfer to a third country or to an international organisation shall take place only if, subject to the other provisions of this Regulation, the conditions laid down in this Chapter are complied with by the controller and processor, including for onward transfers of personal data from the third country or an international organisation to another third country or to another international organisation. All provisions in this Chapter shall be applied in order to ensure that the level of protection of natural persons guaranteed by this Regulation is not undermined.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=97b4173bfc528a6534b7 -->

### Čl. 45 — Předávání na základě rozhodnutí o odpovídající ochraně

> **Čl. 45 odst. 1**
> *Předání osobních údajů do třetí země nebo mezinárodní organizaci může proběhnout, pokud Komise rozhodla, že daná třetí země, území nebo jedno nebo více konkrétních odvětví v dané třetí zemi nebo mezinárodní organizace zajišťují odpovídající úroveň ochrany. Takové předání nevyžaduje žádné zvláštní povolení.*

> **Čl. 45 odst. 2**
> *Při posuzování odpovídající úrovně ochrany Komise přihlíží zejména k těmto skutečnostem:*
> *(a) zásadám právního státu, respektování lidských práv a základních svobod, příslušné obecné a odvětvové právní předpisy, včetně těch týkajících se veřejné bezpečnosti, obrany, národní bezpečnosti a trestního práva a přístupu veřejných orgánů k osobním údajům, jakož i provádění těchto právních předpisů, pravidlům ochrany údajů, profesním pravidlům a bezpečnostním opatřením, včetně pravidel pro další předávání osobních údajů do jiné třetí země nebo mezinárodní organizace, jichž se v dané zemi nebo mezinárodní organizaci dodržuje, judikatuře, jakož i účinným a vymahatelným právům subjektu údajů a účinné správní a soudní ochraně pro subjekty údajů, jejichž osobní údaje jsou předávány;*
> *(b) existenci a účinnému fungování jednoho nebo více nezávislých dozorových úřadů ve třetí zemi nebo dozorových úřadů, jimž mezinárodní organizace podléhá a jež jsou pověřeny zajišťováním a prosazováním dodržování pravidel ochrany osobních údajů, včetně dostatečných pravomocí v oblasti prosazování, pomoci a poradenství subjektům údajů při výkonu jejich práv a spolupráce s dozorovými úřady členských států; a*
> *(c) mezinárodním závazkům, k nimž se příslušná třetí země nebo mezinárodní organizace zavázala, nebo jiným závazkům vyplývajícím z právně závazných úmluv nebo nástrojů, jakož i z účasti na mnohostranných nebo regionálních systémech, zejména ve vztahu k ochraně osobních údajů.*

> **Čl. 45 odst. 3**
> *Komise může po posouzení odpovídající úrovně ochrany rozhodnout prostřednictvím prováděcího aktu, že třetí země, území nebo jedno nebo více konkrétních odvětví třetí země nebo mezinárodní organizace zajišťují odpovídající úroveň ochrany ve smyslu odstavce 2 tohoto článku. Prováděcí akt stanoví mechanismus pravidelného přezkumu, alespoň jednou za čtyři roky, který zohlední veškerý příslušný vývoj ve třetí zemi nebo mezinárodní organizaci. Prováděcí akt upřesňuje svůj územní a odvětvový rozsah působnosti a v příslušných případech označí dozorový úřad nebo dozorové úřady uvedené v písm. b) odst. 2 tohoto článku. Prováděcí akt se přijme přezkumným postupem podle čl. 93 odst. 2.*

> **Čl. 45 odst. 4**
> *Komise průběžně sleduje vývoj ve třetích zemích a v mezinárodních organizacích, který by mohl ovlivnit fungování rozhodnutí přijatých podle odstavce 3 tohoto článku a rozhodnutí přijatých na základě čl. 25 odst. 6 směrnice 95/46/ES.*

> **Čl. 45 odst. 5**
> *Pokud dostupné informace ukáží, zejména po přezkumu uvedeném v odstavci 3 tohoto článku, že třetí země, území nebo jedno nebo více konkrétních odvětví třetí země nebo mezinárodní organizace již nezajišťují odpovídající úroveň ochrany ve smyslu odstavce 2 tohoto článku, Komise v nezbytném rozsahu zruší, změní nebo pozastaví rozhodnutí uvedené v odstavci 3 tohoto článku prostřednictvím prováděcích aktů bez retroaktivního účinku. Tyto prováděcí akty se přijmou přezkumným postupem podle čl. 93 odst. 2.*
> *Na náležitě odůvodněných závažných důvodech naléhavosti Komise přijme okamžitě použitelné prováděcí akty postupem podle čl. 93 odst. 3.*

> **Čl. 45 odst. 6**
> *Komise zahájí konzultace s třetí zemí nebo mezinárodní organizací s cílem napravit situaci, která vedla k rozhodnutí přijatému podle odstavce 5.*

> **Čl. 45 odst. 7**
> *Rozhodnutím podle odstavce 5 tohoto článku není dotčeno předávání osobních údajů do příslušné třetí země, území nebo jednoho nebo více konkrétních odvětví v dané třetí zemi nebo mezinárodní organizaci podle článků 46 až 49.*

> **Čl. 45 odst. 8**
> *Komise zveřejní v Úředním věstníku Evropské unie a na svém internetovém portálu seznam třetích zemí, území a konkrétních odvětví třetích zemí a mezinárodních organizací, ve vztahu k nimž rozhodla, že zajišťují nebo nezajišťují odpovídající úroveň ochrany.*

> **Čl. 45 odst. 9**
> *Rozhodnutí přijatá Komisí na základě čl. 25 odst. 6 směrnice 95/46/ES zůstávají v platnosti, dokud nejsou změněna, nahrazena nebo zrušena rozhodnutím Komise přijatým v souladu s odstavcem 3 nebo 5 tohoto článku.*

**Výklad:** Rozhodnutí o odpovídající ochraně (*adequacy decision*) je nejsilnějším a provozně nejpohodlnějším titulem pro předávání: správce ani zpracovatel nepotřebují žádné zvláštní povolení ani ad hoc záruky — stačí ověřit, zda se příjemce nachází v zemi nebo odvětví, na které se rozhodnutí vztahuje. Komise přijímá rozhodnutí prostřednictvím prováděcího aktu; proces schválení zahrnuje konzultaci s EDPB. Kritéria posuzování (odst. 2) jsou materiální a komplexní: zahrnují právní stát, lidská práva, trestní právo, přístup veřejných orgánů k datům, nezávislý dohled i mezinárodní závazky. Klíčovým standardem je „zásadní ekvivalence" (*essential equivalence*) s ochranou v EU — pouhá formální existence právní úpravy nestačí.

Historicky nejvýznamnějším předmětem judikatury SDEU v oblasti předávání je transatlantický přenos dat do USA. Věc *Schrems I* vedla ke zrušení rozhodnutí o tzv. Safe Harbour (rozhodnutí Komise, jímž byl Safe Harbour považován za odpovídající záruky) s poukazem na to, že masivní přístup amerických zpravodajských služeb k datům Evropanů je neslučitelný s principem ekvivalence a že vnitrostátní dozorové úřady nesmějí být zbaveny pravomoci přezkoumat platnost rozhodnutí Komise. Věc *Schrems II* poté vedla ke zrušení rozhodnutí o tzv. Privacy Shield, který Safe Harbour nahradil: Soudní dvůr EU dospěl k závěru, že legislativa USA — zejména pravomoci zpravodajských služeb podle příslušných zákonů — neumožňuje zajistit ekvivalentní úroveň ochrany a že subjekty údajů z EU nemají účinný soudní prostředek obrany. Tato judikatura zároveň potvrdila, že standardní smluvní doložky (čl. 46) mohou být i nadále používány, avšak správce je povinen v každém konkrétním případě posoudit, zda právo a praxe cílové země ve skutečnosti nedovolují respektovat obsah doložek — tzv. Transfer Impact Assessment (TIA).

V návaznosti na věc *Schrems II* přijaly USA a EU v roce 2022–2023 nový rámec — EU-US Data Privacy Framework (DPF). Komise přijala odpovídající rozhodnutí o odpovídající ochraně pro přenosy do organizací certifikovaných podle DPF. Tento rámec zavedl mechanismus soudní ochrany pro subjekty údajů z EU (Data Protection Review Court) s cílem odstranit námitky vytčené v *Schrems II*. Platnost tohoto rozhodnutí je opět předmětem diskuse a soudního přezkumu před SDEU. Odst. 3 výslovně ukládá povinný přezkum každé čtyři roky, odst. 4–5 pak umožňují pozastavení nebo zrušení rozhodnutí bez retroaktivního účinku (předávání uskutečněná za platnosti rozhodnutí nejsou zpětně protiprávní), avšak od okamžiku zrušení je třeba přejít na jiný titul. ZZOÚ nepřebírá a nedoplňuje tento mechanismus žádnými zvláštními pravidly; ÚOOÚ jako český dozorový úřad je zapojen prostřednictvím EDPB do procesu vydávání stanovisek k návrhu rozhodnutí (čl. 40 a násl. jednacího řádu EDPB).

#### F. Kazuistika

**1. Modelová situace.** Marketingová společnost (správce) předává data zákazníků do USA poskytovateli, který je certifikován v rámci EU-US Data Privacy Framework (DPF). Spoléhá výhradně na rozhodnutí o adekvátnosti, aniž ověřila, že příjemce je skutečně aktivně certifikován a že předání spadá do rozsahu rozhodnutí. Důkazy: doklad o aktivní certifikaci příjemce v DPF, rozsah rozhodnutí o adekvátnosti, kontrola statusu certifikace.

**2. Právní otázka.** Lze předání do USA opřít o rozhodnutí o adekvátnosti dle čl. 45 a jaké podmínky musí být splněny?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 45 odst. 1 (adekvátnost bez zvláštního povolení), odst. 3 (přezkum), odst. 5 (pozastavení/zrušení).
- *Související ustanovení téhož zákona:* čl. 44, čl. 46 (záložní titul), čl. 49.
- *Související předpisy:* rozhodnutí Komise o EU-US DPF; recitál 103.
- *Judikatura:* SDEU Schrems I a II — zrušení Safe Harbour a Privacy Shield; standard essential equivalence.

**4. Subsumpce.** Adekvátnost u DPF platí jen pro příjemce aktivně certifikované a v rozsahu rozhodnutí. Spoléhání bez ověření aktivní certifikace je rizikové; je-li příjemce necertifikovaný, titul chybí. Při zrušení rozhodnutí (riziko Schrems III) je nutný záložní titul (čl. 46).

**5. Řešení.** Správce ověří aktivní certifikaci příjemce a soulad předání s rozsahem rozhodnutí; připraví záložní titul (SCC) pro případ zrušení. Procesně: kontrola statusu DPF, monitoring vývoje.

**6. Varianty.** (a) Při necertifikovaném příjemci je nutné předání opřít o čl. 46 (SCC + dodatečná opatření). (b) Při pozastavení rozhodnutí (odst. 5) je třeba přejít na jiný titul od okamžiku zrušení (bez retroaktivity).

#### G. Protiargumenty a rizika

- *„DPF kryje všechny přenosy do USA."* Kryje jen aktivně certifikované příjemce v rozsahu rozhodnutí; ostatní vyžadují čl. 46/49.
- *„Adekvátnost je trvalá."* Rozhodnutí podléhá přezkumu a může být zrušeno (Schrems I, II); nutná příprava záložního titulu.
- *Slabé místo:* stabilita rozhodnutí o adekvátnosti USA je nejistá; spoléhání jen na ně bez zálohy je rizikové.

#### H. Praktický závěr

Adekvátnost je nejpohodlnější titul, ale jen v rozsahu a po dobu platnosti rozhodnutí a u skutečně certifikovaných příjemců; vždy měj připravený záložní titul pro případ zrušení.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Vztahuje se rozhodnutí o adekvátnosti na cílovou zemi/odvětví/příjemce?
- [ ] Je příjemce (u DPF) aktivně certifikován a v rozsahu rozhodnutí?
- [ ] Je sledován vývoj a platnost rozhodnutí (odst. 3, 5)?
- [ ] Je připraven záložní titul (SCC) pro případ zrušení?

**Typicky rozhodné důkazy / podklady:** doklad o aktivní certifikaci příjemce, rozsah rozhodnutí o adekvátnosti, monitoring statusu a vývoje, připravený záložní mechanismus.

---


<!-- LEGAL-REVISION:BEGIN id=6560b217cd90751b6750 generator=2026-07-17.4 source_sha256=064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea -->
#### Revizní doplnění k Čl. 45 — Transfers on the basis of an adequacy decision

> Revize: 17. 7. 2026 | Znění předpisu k: datum dokumentu místního zdroje 27. 4. 2016 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-24/EU Law/Legal Acts-EN/Legal Acts/Regulations/2016/32016R0679.md`; identifikátor verze: `32016R0679`; SHA-256: `064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea`.

##### Znění ustanovení

>  1.   A transfer of personal data to a third country or an international organisation may take place where the Commission has decided that the third country, a territory or one or more specified sectors within that third country, or the international organisation in question ensures an adequate level of protection. Such a transfer shall not require any specific authorisation.
>
>
>
>
>  2.   When assessing the adequacy of the level of protection, the Commission shall, in particular, take account of the following elements:
>
>
>
>
>
>
>
>  (a)
>
>
>
>  the rule of law, respect for human rights and fundamental freedoms, relevant legislation, both general and sectoral, including concerning public security, defence, national security and criminal law and the access of public authorities to personal data, as well as the implementation of such legislation, data protection rules, professional rules and security measures, including rules for the onward transfer of personal data to another third country or international organisation which are complied with in that country or international organisation, case-law, as well as effective and enforceable data subject rights and effective administrative and judicial redress for the data subjects whose personal data are being transferred;
>
>
>
>
>
>
>
>
>
>
>
>
>  (b)
>
>
>
>  the existence and effective functioning of one or more independent supervisory authorities in the third country or to which an international organisation is subject, with responsibility for ensuring and enforcing compliance with the data protection rules, including adequate enforcement powers, for assisting and advising the data subjects in exercising their rights and for cooperation with the supervisory authorities of the Member States; and
>
>
>
>
>
>
>
>
>
>
>
>
>  (c)
>
>
>
>  the international commitments the third country or international organisation concerned has entered into, or other obligations arising from legally binding conventions or instruments as well as from its participation in multilateral or regional systems, in particular in relation to the protection of personal data.
>
>
>
>
>
>
>
>
>
>  3.   The Commission, after assessing the adequacy of the level of protection, may decide, by means of implementing act, that a third country, a territory or one or more specified sectors within a third country, or an international organisation ensures an adequate level of protection within the meaning of paragraph 2 of this Article. The implementing act shall provide for a mechanism for a periodic review, at least every four years, which shall take into account all relevant developments in the third country or international organisation. The implementing act shall specify its territorial and sectoral application and, where applicable, identify the supervisory authority or authorities referred to in point (b) of paragraph 2 of this Article. The implementing act shall be adopted in accordance with the examination procedure referred to in Article 93(2).
>
>
>
>
>  4.   The Commission shall, on an ongoing basis, monitor developments in third countries and international organisations that could affect the functioning of decisions adopted pursuant to paragraph 3 of this Article and decisions adopted on the basis of Article 25(6) of Directive 95/46/EC.
>
>
>
>
>  5.   The Commission shall, where available information reveals, in particular following the review referred to in paragraph 3 of this Article, that a third country, a territory or one or more specified sectors within a third country, or an international organisation no longer ensures an adequate level of protection within the meaning of paragraph 2 of this Article, to the extent necessary, repeal, amend or suspend the decision referred to in paragraph 3 of this Article by means of implementing acts without retro-active effect. Those implementing acts shall be adopted in accordance with the examination procedure referred to in Article 93(2).
>
>  On duly justified imperative grounds of urgency, the Commission shall adopt immediately applicable implementing acts in accordance with the procedure referred to in Article 93(3).
>
>
>
>
>  6.   The Commission shall enter into consultations with the third country or international organisation with a view to remedying the situation giving rise to the decision made pursuant to paragraph 5.
>
>
>
>
>  7.   A decision pursuant to paragraph 5 of this Article is without prejudice to transfers of personal data to the third country, a territory or one or more specified sectors within that third country, or the international organisation in question pursuant to Articles 46 to 49.
>
>
>
>
>  8.   The Commission shall publish in the Official Journal of the European Union and on its website a list of the third countries, territories and specified sectors within a third country and international organisations for which it has decided that an adequate level of protection is or is no longer ensured.
>
>
>
>
>  9.   Decisions adopted by the Commission on the basis of Article 25(6) of Directive 95/46/EC shall remain in force until amended, replaced or repealed by a Commission Decision adopted in accordance with paragraph 3 or 5 of this Article.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: Čl. 93, Čl. 25

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=6560b217cd90751b6750 -->

### Čl. 46 — Předávání při poskytnutí vhodných záruk

> **Čl. 46 odst. 1**
> *Pokud nebylo vydáno rozhodnutí podle čl. 45 odst. 3, smí správce nebo zpracovatel předat osobní údaje do třetí země nebo mezinárodní organizaci, pouze pokud správce nebo zpracovatel poskytl vhodné záruky a pod podmínkou, že subjektům údajů jsou k dispozici vymahatelná práva a účinné právní prostředky ochrany.*

> **Čl. 46 odst. 2**
> *Vhodné záruky uvedené v odstavci 1 lze bez vyžadování zvláštního povolení od dozorového úřadu poskytnout prostřednictvím:*
> *(a) právně závazného a vynutitelného nástroje mezi veřejnými orgány nebo veřejnými subjekty;*
> *(b) závazných podnikových pravidel v souladu s článkem 47;*
> *(c) standardních doložek ochrany osobních údajů přijatých Komisí přezkumným postupem podle čl. 93 odst. 2;*
> *(d) standardních doložek ochrany osobních údajů přijatých dozorovým úřadem a schválených Komisí přezkumným postupem podle čl. 93 odst. 2;*
> *(e) schváleného kodexu chování podle článku 40 spolu s závaznými a vymahatelnými závazky správce nebo zpracovatele ve třetí zemi uplatňovat vhodné záruky, včetně záručného pro práva subjektů údajů; nebo*
> *(f) schváleného certifikačního mechanismu podle článku 42 spolu se závaznými a vymahatelnými závazky správce nebo zpracovatele ve třetí zemi uplatňovat vhodné záruky, včetně záručného pro práva subjektů údajů.*

> **Čl. 46 odst. 3**
> *S výhradou povolení příslušného dozorového úřadu lze vhodné záruky uvedené v odstavci 1 poskytnout zejména prostřednictvím:*
> *(a) smluvních doložek mezi správcem nebo zpracovatelem a správcem, zpracovatelem nebo příjemcem osobních údajů ve třetí zemi nebo mezinárodní organizaci; nebo*
> *(b) ustanovení vložených do správních ujednání mezi veřejnými orgány nebo veřejnými subjekty, která zahrnují vymahatelná a účinná práva subjektů údajů.*

> **Čl. 46 odst. 4**
> *Dozorový úřad uplatní mechanismus jednotnosti uvedený v článku 63 v případech uvedených v odstavci 3 tohoto článku.*

> **Čl. 46 odst. 5**
> *Povolení vydaná členským státem nebo dozorovým úřadem na základě čl. 26 odst. 2 směrnice 95/46/ES zůstávají v platnosti, dokud nejsou případně změněna, nahrazena nebo zrušena tímto dozorovým úřadem. Rozhodnutí přijatá Komisí na základě čl. 26 odst. 4 směrnice 95/46/ES zůstávají v platnosti, dokud nejsou případně změněna, nahrazena nebo zrušena rozhodnutím Komise přijatým v souladu s odstavcem 2 tohoto článku.*

**Výklad:** Článek 46 tvoří druhou vrstvu systému předávání: neexistuje-li rozhodnutí o odpovídající ochraně, může správce nebo zpracovatel předat data do třetí země na základě *vhodných záruk* (*appropriate safeguards*), jsou-li subjektům údajů k dispozici vymahatelná práva a účinné právní prostředky.

Prakticky nejrozšířenějším nástrojem jsou **standardní smluvní doložky** (*Standard Contractual Clauses*, SCC) přijaté Komisí podle odst. 2 písm. c). Komise v roce 2021 přijala nové moduly SCC (prováděcí rozhodnutí Komise 2021/914), které zahrnují čtyři konfigurační moduly: správce → správce, správce → zpracovatel, zpracovatel → zpracovatel a zpracovatel → správce. Tyto doložky jsou smluvně závazné, ale jejich účinnost v praxi závisí na tom, zda právo a faktická praxe cílové země umožňují jejich reálné dodržení — jak zdůraznil SDEU ve věci *Schrems II*. Proto EDPB přijal doporučení k tzv. supplementary measures (dodatečným opatřením), jako jsou šifrování, pseudonymizace nebo přísná selekce dat, která mají doložky doplnit tam, kde právo třetí země nedovoluje jejich plné respektování.

Odst. 2 dále uvádí: závazná podniková pravidla (čl. 47; viz níže), právně závazné a vynutitelné nástroje mezi veřejnými orgány (typicky mezivládní dohody), schválené kodexy chování (čl. 40) a certifikační mechanismy (čl. 42). Posledně jmenované jsou podmíněny tím, že správce nebo zpracovatel ve třetí zemi přijme závazné a vymahatelné závazky záruky uplatňovat — tedy pouhá certifikace nestačí, musí existovat mechanismus vymahatelnosti.

Odst. 3 upravuje záruky vyžadující individuální povolení dozorového úřadu: ad hoc smluvní doložky a správní ujednání. V těchto případech se uplatní mechanismus jednotnosti (čl. 63), aby se předešlo roztříštěnosti přístupů jednotlivých dozorových úřadů. ÚOOÚ v souladu s tím předkládá návrhy ad hoc doložek EDPB před vydáním povolení. ZZOÚ tento systém nepřebírá ani nedoplňuje; relevantní jsou výhradně unijní pravidla.

#### F. Kazuistika

**1. Modelová situace.** Společnost (správce) předává data zpracovateli v třetí zemi bez rozhodnutí o adekvátnosti na základě SCC z roku 2021. Spoléhá výhradně na text doložek, ale neprovedla posouzení, zda právo cílové země (rozsáhlé pravomoci tajných služeb) umožňuje doložky reálně dodržet, ani nepřijala dodatečná opatření. Důkazy: uzavřené SCC, TIA, dodatečná opatření (šifrování), právní analýza cílové země.

**2. Právní otázka.** Postačí pro předání dle čl. 46 samotné uzavření SCC, nebo je nutné posoudit reálnou účinnost záruk a přijmout dodatečná opatření?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 46 odst. 1 (vhodné záruky + vymahatelná práva), odst. 2 písm. c) (SCC), odst. 3 (ad hoc doložky s povolením).
- *Související ustanovení téhož zákona:* čl. 44, čl. 47 (BCR), čl. 49, čl. 32.
- *Související předpisy:* prováděcí rozhodnutí Komise 2021/914 (SCC); doporučení EDPB k dodatečným opatřením.
- *Judikatura:* SDEU Schrems II — nutnost TIA a případných supplementary measures.

**4. Subsumpce.** SCC jsou platným titulem jen tehdy, umožňuje-li právo a praxe cílové země jejich reálné dodržení. U země s rozsáhlým přístupem tajných služeb je nutné TIA a dodatečná opatření; jejich absence činí předání nezákonným i přes uzavřené SCC.

**5. Řešení.** Správce provede TIA, a je-li ochrana nedostatečná, přijme dodatečná opatření (silné šifrování, pseudonymizace, selekce dat) nebo od předání upustí. Procesně: dokumentace TIA, implementace opatření.

**6. Varianty.** (a) U ad hoc doložek (odst. 3) je nutné povolení dozorového úřadu a mechanismus jednotnosti (čl. 63). (b) Skupina podniků může využít BCR (čl. 47) místo opakovaných SCC.

#### G. Protiargumenty a rizika

- *„SCC samy o sobě stačí."* Po Schrems II je nutné posoudit reálnou účinnost a doplnit opatření; samotný text nestačí.
- *„TIA je formalita."* TIA je podmínkou zákonnosti; jeho absence vystavuje správce sankci a zákazu předání.
- *Slabé místo:* posouzení práva a praxe cílové země je náročné a nejisté; dostatečnost dodatečných opatření je sporná.

#### H. Praktický závěr

Vhodné záruky (zejm. SCC) jsou účinné jen tehdy, lze-li je v cílové zemi reálně dodržet; vždy proveď TIA a v rizikových zemích doplň silná dodatečná opatření, jinak od předání upusť.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je zvolen vhodný nástroj záruk (SCC / BCR / kodex / certifikace)?
- [ ] Jsou subjektům k dispozici vymahatelná práva a prostředky (odst. 1)?
- [ ] Bylo provedeno TIA (právo a praxe cílové země)?
- [ ] Byla přijata dodatečná opatření tam, kde je ochrana nedostatečná?
- [ ] Je u ad hoc doložek získáno povolení úřadu (odst. 3)?

**Typicky rozhodné důkazy / podklady:** uzavřené SCC/BCR, dokument TIA, právní analýza cílové země, popis dodatečných opatření (šifrování), případné povolení úřadu.

---


<!-- LEGAL-REVISION:BEGIN id=cebc2f1036a742a563d4 generator=2026-07-17.4 source_sha256=064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea -->
#### Revizní doplnění k Čl. 46 — Transfers subject to appropriate safeguards

> Revize: 17. 7. 2026 | Znění předpisu k: datum dokumentu místního zdroje 27. 4. 2016 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-24/EU Law/Legal Acts-EN/Legal Acts/Regulations/2016/32016R0679.md`; identifikátor verze: `32016R0679`; SHA-256: `064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea`.

##### Znění ustanovení

>  1.   In the absence of a decision pursuant to Article 45(3), a controller or processor may transfer personal data to a third country or an international organisation only if the controller or processor has provided appropriate safeguards, and on condition that enforceable data subject rights and effective legal remedies for data subjects are available.
>
>
>
>
>  2.   The appropriate safeguards referred to in paragraph 1 may be provided for, without requiring any specific authorisation from a supervisory authority, by:
>
>
>
>
>
>
>
>  (a)
>
>
>
>  a legally binding and enforceable instrument between public authorities or bodies;
>
>
>
>
>
>
>
>
>
>
>
>
>  (b)
>
>
>
>  binding corporate rules in accordance with Article 47;
>
>
>
>
>
>
>
>
>
>
>
>
>  (c)
>
>
>
>  standard data protection clauses adopted by the Commission in accordance with the examination procedure referred to in Article 93(2);
>
>
>
>
>
>
>
>
>
>
>
>
>  (d)
>
>
>
>  standard data protection clauses adopted by a supervisory authority and approved by the Commission pursuant to the examination procedure referred to in Article 93(2);
>
>
>
>
>
>
>
>
>
>
>
>
>  (e)
>
>
>
>  an approved code of conduct pursuant to Article 40 together with binding and enforceable commitments of the controller or processor in the third country to apply the appropriate safeguards, including as regards data subjects' rights; or
>
>
>
>
>
>
>
>
>
>
>
>
>  (f)
>
>
>
>  an approved certification mechanism pursuant to Article 42 together with binding and enforceable commitments of the controller or processor in the third country to apply the appropriate safeguards, including as regards data subjects' rights.
>
>
>
>
>
>
>
>
>
>  3.   Subject to the authorisation from the competent supervisory authority, the appropriate safeguards referred to in paragraph 1 may also be provided for, in particular, by:
>
>
>
>
>
>
>
>  (a)
>
>
>
>  contractual clauses between the controller or processor and the controller, processor or the recipient of the personal data in the third country or international organisation; or
>
>
>
>
>
>
>
>
>
>
>
>
>  (b)
>
>
>
>  provisions to be inserted into administrative arrangements between public authorities or bodies which include enforceable and effective data subject rights.
>
>
>
>
>
>
>
>
>
>  4.   The supervisory authority shall apply the consistency mechanism referred to in Article 63 in the cases referred to in paragraph 3 of this Article.
>
>
>
>
>  5.   Authorisations by a Member State or supervisory authority on the basis of Article 26(2) of Directive 95/46/EC shall remain valid until amended, replaced or repealed, if necessary, by that supervisory authority. Decisions adopted by the Commission on the basis of Article 26(4) of Directive 95/46/EC shall remain in force until amended, replaced or repealed, if necessary, by a Commission Decision adopted in accordance with paragraph 2 of this Article.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: Čl. 45, Čl. 47, Čl. 93, Čl. 40, Čl. 42, Čl. 63, Čl. 26

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=cebc2f1036a742a563d4 -->

### Čl. 47 — Závazná podniková pravidla

> **Čl. 47 odst. 1**
> *Příslušný dozorový úřad schválí závazná podniková pravidla v souladu s mechanismem jednotnosti stanoveným v článku 63 za předpokladu, že:*
> *(a) jsou právně závazná a platí a jsou vymáhána vůči každému příslušnému členu skupiny podniků nebo skupiny podniků zapojených do společné hospodářské činnosti, včetně jejich zaměstnanců;*
> *(b) výslovně přiznávají subjektům údajů vymahatelná práva s ohledem na zpracování jejich osobních údajů; a*
> *(c) splňují požadavky stanovené v odstavci 2.*

> **Čl. 47 odst. 2**
> *Závazná podniková pravidla uvedená v odstavci 1 upřesňují alespoň:*
> *(a) strukturu a kontaktní údaje skupiny podniků nebo skupiny podniků zapojených do společné hospodářské činnosti a každého z jejích členů;*
> *(b) předávání nebo soubory předávání údajů, včetně kategorií osobních údajů, druhu zpracování a jeho účelů, druhu dotčených subjektů údajů a identifikaci příslušné třetí země nebo zemí;*
> *(c) jejich právně závaznou povahu, a to jak interně, tak externě;*
> *(d) uplatňování obecných zásad ochrany osobních údajů, zejména omezení účelu, minimalizace údajů, omezené doby uchovávání, kvality údajů, záměrné a standardní ochrany osobních údajů, právního základu zpracování, zpracování zvláštních kategorií osobních údajů, opatření k zajištění bezpečnosti údajů a požadavků ohledně dalšího předávání subjektům, na které se závazná podniková pravidla nevztahují;*
> *(e) práva subjektů údajů ohledně zpracování a prostředky pro výkon těchto práv, včetně práva nebýt předmětem rozhodnutí založeného výhradně na automatizovaném zpracování, včetně profilování, v souladu s článkem 22, práva podat stížnost příslušnému dozorovému úřadu a příslušným soudům členských států v souladu s článkem 79 a práva na nápravu a případně na náhradu škody za porušení závazných podnikových pravidel;*
> *(f) přijetí odpovědnosti správcem nebo zpracovatelem usazeným na území členského státu za jakékoli porušení závazných podnikových pravidel jakýmkoli příslušným členem, který není usazen v Unii; správce nebo zpracovatel je z této odpovědnosti zcela nebo zčásti vyňat, pouze pokud prokáže, že daný člen za událost způsobující škodu odpovědnost nenese;*
> *(g) způsob, jakým jsou subjekty údajů nad rámec článků 13 a 14 informovány o závazných podnikových pravidlech, zejména o ustanoveních uvedených v písm. d), e) a f) tohoto odstavce;*
> *(h) úkoly pověřence pro ochranu osobních údajů jmenovaného v souladu s článkem 37 nebo jiné osoby nebo subjektu, které mají v rámci skupiny podniků nebo skupiny podniků zapojených do společné hospodářské činnosti za úkol sledovat dodržování závazných podnikových pravidel, jakož i sledovat odbornou přípravu a vyřizování stížností;*
> *(i) postupy pro podávání stížností;*
> *(j) mechanismy v rámci skupiny podniků nebo skupiny podniků zapojených do společné hospodářské činnosti k zajišťování ověření dodržování závazných podnikových pravidel. Tyto mechanismy zahrnují audity ochrany údajů a metody zajišťování nápravných opatření k ochraně práv subjektu údajů. Výsledky takového ověřování by měly být sděleny osobě nebo subjektu uvedenému v písmenu h) a správní radě kontrolního podniku skupiny podniků nebo skupiny podniků zapojených do společné hospodářské činnosti a na žádost by měly být k dispozici příslušnému dozorovému úřadu;*
> *(k) mechanismům pro hlášení a zaznamenávání změn pravidel a jejich oznamování dozorovému úřadu;*
> *(l) mechanismům spolupráce s dozorovým úřadem k zajišťování souladu ze strany každého člena skupiny podniků nebo skupiny podniků zapojených do společné hospodářské činnosti, a to zejména zpřístupňováním výsledků ověřování opatření uvedených v písmenu j) dozorovému úřadu;*
> *(m) mechanismům pro hlášení veškerých právních požadavků příslušnému dozorovému úřadu, jimž musí v třetí zemi člen skupiny podniků nebo skupiny podniků zapojených do společné hospodářské činnosti vyhovět a jež by mohly mít podstatný nepříznivý účinek na záruky poskytnuté závaznými podnikovými pravidly; a*
> *(n) vhodné odborné přípravě zaměstnanců, kteří mají trvalý nebo pravidelný přístup k osobním údajům.*

> **Čl. 47 odst. 3**
> *Komise může upřesnit formát a postupy pro výměnu informací mezi správci, zpracovateli a dozorovými úřady, pokud jde o závazná podniková pravidla ve smyslu tohoto článku. Tyto prováděcí akty se přijmou přezkumným postupem stanoveným v čl. 93 odst. 2.*

**Výklad:** Závazná podniková pravidla (*Binding Corporate Rules*, BCR) jsou interním právním nástrojem nadnárodních skupin podniků, který umožňuje přenosy osobních údajů uvnitř skupiny — mezi mateřskou společností a dceřinými podniky, pobočkami či přidruženými subjekty v různých zemích světa — bez potřeby uzavírat SCC ke každému konkrétnímu předání.

BCR musí být schválena příslušným dozorovým úřadem (v praxi vedoucím dozorovým úřadem dle pravidel one-stop-shop) v souladu s mechanismem jednotnosti (čl. 63 GDPR), takže schválení jednoho BCR platí pro celou skupinu bez nutnosti opakovat schvalovací řízení v každém členském státě. EDPB vydal doporučení upřesňující obsahové požadavky pro BCR správců a zvlášť pro BCR zpracovatelů.

Systém BCR je výhodný pro velké nadnárodní korporace (záruky jsou integrovány do interní politiky skupiny, jsou stabilnější než individuální SCC), avšak schvalovací řízení je časově i administrativně náročné. Zásadní charakteristikou je odpovědnost evropského subjektu skupiny (odst. 2 písm. f)): člen skupiny usazený v EU nese odpovědnost za porušení BCR způsobené členem mimo EU, ledaže prokáže jeho absenci zavinění. Tím je zajistitelnost práv subjektů údajů v Unii zachována i tehdy, když k pochybení dojde za hranicemi EHP. BCR musí pokrývat všechny obligatorní prvky taxativně vyjmenované v odst. 2 — zejména zásady GDPR, práva subjektů údajů, mechanismy stížností, audity, mechanismus hlášení konfliktních zahraničních právních požadavků (odst. 2 písm. m), který je přímou reakcí na problém legislativy třetích zemí nastolený judikaturou Schrems I a Schrems II) a pravidelnou odbornou přípravu zaměstnanců.

#### F. Kazuistika

**1. Modelová situace.** Nadnárodní skupina chce zjednodušit toky dat mezi mateřskou společností v EU a desítkami dceřiných společností po celém světě. Místo opakovaného uzavírání SCC zvažuje přijetí závazných podnikových pravidel (BCR). Jeden z členů mimo EU poruší pravidla a způsobí újmu subjektu. Důkazy: schválená BCR, struktura skupiny, doklad o vymahatelnosti vůči členům, odpovědnostní ujednání evropského subjektu.

**2. Právní otázka.** Splňují BCR podmínky čl. 47 (zejm. právní závaznost, vymahatelná práva subjektů, odpovědnost evropského subjektu) a kdo odpovídá za porušení členem mimo EU?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 47 odst. 1 (schválení, závaznost, vymahatelná práva), odst. 2 písm. f) (odpovědnost EU subjektu), písm. m) (hlášení konfliktních požadavků).
- *Související ustanovení téhož zákona:* čl. 46 odst. 2 písm. b), čl. 63 (jednotnost), čl. 22, čl. 79, čl. 82.
- *Související předpisy:* doporučení EDPB k BCR.
- *Judikatura:* Schrems I, II (důvod pro mechanismus hlášení dle písm. m)).

**4. Subsumpce.** BCR musí být schválena vedoucím dozorovým úřadem v rámci jednotnosti, právně závazná vůči všem členům a přiznávat subjektům vymahatelná práva. Za porušení členem mimo EU odpovídá evropský subjekt (odst. 2 písm. f)), ledaže prokáže absenci zavinění daného člena.

**5. Řešení.** Skupina nechá BCR schválit a zajistí všechny obligatorní prvky (odst. 2). Subjekt uplatní práva vůči evropskému subjektu, který odpovídá za škodu. Procesně: schvalovací řízení, audity, mechanismus hlášení konfliktů.

**6. Varianty.** (a) Pro zpracovatelské činnosti existují samostatné BCR zpracovatelů. (b) Bez schválení BCR nepředstavují platný titul a předání je nutné opřít o jiný nástroj.

#### G. Protiargumenty a rizika

- *„BCR platí automaticky po přijetí."* BCR musí schválit dozorový úřad v rámci jednotnosti; bez schválení nejsou titulem.
- *„Za zahraniční členy neodpovídáme."* Evropský subjekt odpovídá za porušení členy mimo EU (odst. 2 písm. f)).
- *Slabé místo:* schvalovací proces je zdlouhavý a administrativně náročný; konflikt s právem třetí země (písm. m)) zůstává rizikem.

#### H. Praktický závěr

BCR jsou stabilním vnitroskupinovým titulem pro předávání, vyžadují však schválení úřadem, úplnou sadu obligatorních prvků a odpovědnost evropského subjektu za porušení členy mimo EU.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Byla BCR schválena v rámci mechanismu jednotnosti (odst. 1)?
- [ ] Jsou právně závazná vůči všem členům i zaměstnancům?
- [ ] Přiznávají subjektům vymahatelná práva (odst. 1 písm. b))?
- [ ] Je upravena odpovědnost evropského subjektu (odst. 2 písm. f))?
- [ ] Existuje mechanismus hlášení konfliktních zahraničních požadavků (písm. m))?

**Typicky rozhodné důkazy / podklady:** schválená BCR, schvalovací rozhodnutí úřadu, struktura skupiny, doklady o auditech a školeních, odpovědnostní ujednání.

---


<!-- LEGAL-REVISION:BEGIN id=e5361ca9fb78b9fe531b generator=2026-07-17.4 source_sha256=064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea -->
#### Revizní doplnění k Čl. 47 — Binding corporate rules

> Revize: 17. 7. 2026 | Znění předpisu k: datum dokumentu místního zdroje 27. 4. 2016 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-24/EU Law/Legal Acts-EN/Legal Acts/Regulations/2016/32016R0679.md`; identifikátor verze: `32016R0679`; SHA-256: `064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea`.

##### Znění ustanovení

>  1.   The competent supervisory authority shall approve binding corporate rules in accordance with the consistency mechanism set out in Article 63, provided that they:
>
>
>
>
>
>
>
>  (a)
>
>
>
>  are legally binding and apply to and are enforced by every member concerned of the group of undertakings, or group of enterprises engaged in a joint economic activity, including their employees;
>
>
>
>
>
>
>
>
>
>
>
>
>  (b)
>
>
>
>  expressly confer enforceable rights on data subjects with regard to the processing of their personal data; and
>
>
>
>
>
>
>
>
>
>
>
>
>  (c)
>
>
>
>  fulfil the requirements laid down in paragraph 2.
>
>
>
>
>
>
>
>
>
>  2.   The binding corporate rules referred to in paragraph 1 shall specify at least:
>
>
>
>
>
>
>
>  (a)
>
>
>
>  the structure and contact details of the group of undertakings, or group of enterprises engaged in a joint economic activity and of each of its members;
>
>
>
>
>
>
>
>
>
>
>
>
>  (b)
>
>
>
>  the data transfers or set of transfers, including the categories of personal data, the type of processing and its purposes, the type of data subjects affected and the identification of the third country or countries in question;
>
>
>
>
>
>
>
>
>
>
>
>
>  (c)
>
>
>
>  their legally binding nature, both internally and externally;
>
>
>
>
>
>
>
>
>
>
>
>
>  (d)
>
>
>
>  the application of the general data protection principles, in particular purpose limitation, data minimisation, limited storage periods, data quality, data protection by design and by default, legal basis for processing, processing of special categories of personal data, measures to ensure data security, and the requirements in respect of onward transfers to bodies not bound by the binding corporate rules;
>
>
>
>
>
>
>
>
>
>
>
>
>  (e)
>
>
>
>  the rights of data subjects in regard to processing and the means to exercise those rights, including the right not to be subject to decisions based solely on automated processing, including profiling in accordance with Article 22, the right to lodge a complaint with the competent supervisory authority and before the competent courts of the Member States in accordance with Article 79, and to obtain redress and, where appropriate, compensation for a breach of the binding corporate rules;
>
>
>
>
>
>
>
>
>
>
>
>
>  (f)
>
>
>
>  the acceptance by the controller or processor established on the territory of a Member State of liability for any breaches of the binding corporate rules by any member concerned not established in the Union; the controller or the processor shall be exempt from that liability, in whole or in part, only if it proves that that member is not responsible for the event giving rise to the damage;
>
>
>
>
>
>
>
>
>
>
>
>
>  (g)
>
>
>
>  how the information on the binding corporate rules, in particular on the provisions referred to in points (d), (e) and (f) of this paragraph is provided to the data subjects in addition to Articles 13 and 14;
>
>
>
>
>
>
>
>
>
>
>
>
>  (h)
>
>
>
>  the tasks of any data protection officer designated in accordance with Article 37 or any other person or entity in charge of the monitoring compliance with the binding corporate rules within the group of undertakings, or group of enterprises engaged in a joint economic activity, as well as monitoring training and complaint-handling;
>
>
>
>
>
>
>
>
>
>
>
>
>  (i)
>
>
>
>  the complaint procedures;
>
>
>
>
>
>
>
>
>
>
>
>
>  (j)
>
>
>
>  the mechanisms within the group of undertakings, or group of enterprises engaged in a joint economic activity for ensuring the verification of compliance with the binding corporate rules. Such mechanisms shall include data protection audits and methods for ensuring corrective actions to protect the rights of the data subject. Results of such verification should be communicated to the person or entity referred to in point (h) and to the board of the controlling undertaking of a group of undertakings, or of the group of enterprises engaged in a joint economic activity, and should be available upon request to the competent supervisory authority;
>
>
>
>
>
>
>
>
>
>
>
>
>  (k)
>
>
>
>  the mechanisms for reporting and recording changes to the rules and reporting those changes to the supervisory authority;
>
>
>
>
>
>
>
>
>
>
>
>
>  (l)
>
>
>
>  the cooperation mechanism with the supervisory authority to ensure compliance by any member of the group of undertakings, or group of enterprises engaged in a joint economic activity, in particular by making available to the supervisory authority the results of verifications of the measures referred to in point (j);
>
>
>
>
>
>
>
>
>
>
>
>
>  (m)
>
>
>
>  the mechanisms for reporting to the competent supervisory authority any legal requirements to which a member of the group of undertakings, or group of enterprises engaged in a joint economic activity is subject in a third country which are likely to have a substantial adverse effect on the guarantees provided by the binding corporate rules; and
>
>
>
>
>
>
>
>
>
>
>
>
>  (n)
>
>
>
>  the appropriate data protection training to personnel having permanent or regular access to personal data.
>
>
>
>
>
>
>
>
>
>  3.   The Commission may specify the format and procedures for the exchange of information between controllers, processors and supervisory authorities for binding corporate rules within the meaning of this Article. Those implementing acts shall be adopted in accordance with the examination procedure set out in Article 93(2).

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: Čl. 63, Čl. 22, Čl. 79, Čl. 37, Čl. 93

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=e5361ca9fb78b9fe531b -->

### Čl. 48 — Předávání nebo zpřístupnění, která nejsou povolena právem Unie

> **Čl. 48**
> *Soudní rozsudek nebo rozhodnutí správního orgánu třetí země požadující od správce nebo zpracovatele předání nebo zpřístupnění osobních údajů může být uznáno nebo vykonatelné pouze tehdy, je-li založeno na mezinárodní dohodě, jako je smlouva o vzájemné právní pomoci, platná mezi žádající třetí zemí a Unií nebo členským státem, aniž jsou dotčeny jiné důvody pro předání podle této kapitoly.*

**Výklad:** Článek 48 řeší situaci, která je v globálním kontextu stále napínavější: orgány třetích zemí (soudy, správní úřady, zpravodajské služby) se snaží zavázat správce nebo zpracovatele se sídlem v EU k tomu, aby vydali nebo zpřístupnili osobní údaje osob nacházejících se v EU — a to zpravidla na základě vnitrostátního práva třetí země s extrateritoriálními účinky.

GDPR na tento fenomén reaguje jednoznačně: takový příkaz (ať soudní, či správní) je pro správce nebo zpracovatele v EU závazný pouze tehdy, pokud je podložen mezinárodní smlouvou platnou mezi třetí zemí a EU nebo členským státem — typicky smlouvou o vzájemné právní pomoci (*Mutual Legal Assistance Treaty*, MLAT) nebo obdobným instrumentem. Absence mezinárodní smlouvy znamená, že příkaz sám o sobě nepředstavuje platný právní titul k předání ve smyslu GDPR. Správce se tak ocitá ve střetu dvou právních řádů: GDPR mu předání zakazuje, zatímco cizí právní řád jej přikazuje. Tento střet je nutno řešit prostřednictvím příslušných procesních mechanismů (v EU typicky námitky a konzultace s dozorovým úřadem). Recitál 115 výslovně konstatuje, že extrateritoriální aplikace zákonů třetích zemí může být v rozporu s mezinárodním právem. Článek 48 se nevylučuje s ostatními tituly kapitoly V: pokud by zákonný požadavek třetí země mohl být splněn v rámci jiného titulu (např. výjimky pro důležité důvody veřejného zájmu dle čl. 49 odst. 1 písm. d), je-li tento zájem uznán v právu EU nebo členského státu), je takové předání přípustné.

#### F. Kazuistika

**1. Modelová situace.** Soud třetí země vydá příkaz adresovaný české dceřiné společnosti (zpracovatel), aby vydala osobní údaje zaměstnanců evropské matky pro účely tamního řízení. Mezi EU/ČR a danou zemí neexistuje smlouva o vzájemné právní pomoci. Společnost je v dilematu: vyhovět cizímu příkazu, nebo GDPR. Důkazy: znění zahraničního příkazu, existence/absence MLAT, konzultace s ÚOOÚ, posouzení jiných titulů.

**2. Právní otázka.** Je zahraniční soudní/správní příkaz sám o sobě platným titulem pro předání dle čl. 48, chybí-li mezinárodní smlouva?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 48 (uznání/vykonatelnost jen na základě mezinárodní dohody).
- *Související ustanovení téhož zákona:* čl. 44, čl. 49 odst. 1 písm. d), e) (možné jiné tituly), čl. 6.
- *Související předpisy:* recitál 115; smlouvy o vzájemné právní pomoci (MLAT).
- *Judikatura:* praxe a recitál 115 — extrateritoriální příkazy mohou být v rozporu s mezinárodním právem.

**4. Subsumpce.** Bez MLAT není zahraniční příkaz platným titulem k předání dle GDPR. Předání by bylo přípustné jen, pokud by je pokryl jiný titul (např. čl. 49 odst. 1 písm. e) pro právní nároky, je-li dán). Jinak je vyhovění příkazu porušením GDPR.

**5. Řešení.** Společnost příkazu bez MLAT nevyhoví automaticky; konzultuje ÚOOÚ a zváží jiné tituly kapitoly V. Procesně: právní analýza, námitka vůči cizímu orgánu, konzultace s úřadem.

**6. Varianty.** (a) Existuje-li MLAT, lze příkaz uznat a údaje předat v jeho rámci. (b) Pokud by předání kryl důležitý veřejný zájem uznaný právem EU/ČR (čl. 49 odst. 1 písm. d), odst. 4), bylo by přípustné.

#### G. Protiargumenty a rizika

- *„Cizí soudní příkaz musíme splnit."* Bez MLAT není příkaz platným titulem dle GDPR; jeho splnění může být porušením.
- *„GDPR neřeší cizí jurisdikci."* Čl. 48 výslovně podmiňuje uznání příkazu mezinárodní dohodou.
- *Slabé místo:* střet právních řádů je reálný a může vystavit společnost sankci v obou jurisdikcích; řešení vyžaduje konzultaci a procesní obranu.

#### H. Praktický závěr

Zahraniční soudní či správní příkaz k vydání dat je v EU titulem jen na základě mezinárodní dohody (MLAT); jinak je nutné hledat jiný titul kapitoly V nebo příkazu nevyhovět a konzultovat úřad.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Existuje mezinárodní dohoda (MLAT) krytí příkazu?
- [ ] Není-li, lze předání opřít o jiný titul kapitoly V?
- [ ] Byla věc konzultována s ÚOOÚ?
- [ ] Byla zvážena procesní obrana vůči cizímu orgánu?

**Typicky rozhodné důkazy / podklady:** znění zahraničního příkazu, doklad o (ne)existenci MLAT, právní analýza titulů, záznam konzultace s úřadem.

---


<!-- LEGAL-REVISION:BEGIN id=0e05242bd34ce30f739c generator=2026-07-17.4 source_sha256=064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea -->
#### Revizní doplnění k Čl. 48 — Transfers or disclosures not authorised by Union law

> Revize: 17. 7. 2026 | Znění předpisu k: datum dokumentu místního zdroje 27. 4. 2016 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-24/EU Law/Legal Acts-EN/Legal Acts/Regulations/2016/32016R0679.md`; identifikátor verze: `32016R0679`; SHA-256: `064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea`.

##### Znění ustanovení

>  Any judgment of a court or tribunal and any decision of an administrative authority of a third country requiring a controller or processor to transfer or disclose personal data may only be recognised or enforceable in any manner if based on an international agreement, such as a mutual legal assistance treaty, in force between the requesting third country and the Union or a Member State, without prejudice to other grounds for transfer pursuant to this Chapter.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=0e05242bd34ce30f739c -->

### Čl. 49 — Výjimky pro specifické situace

> **Čl. 49 odst. 1 pododstavec první**
> *Není-li vydáno rozhodnutí o odpovídající ochraně podle čl. 45 odst. 3 ani nejsou k dispozici vhodné záruky podle článku 46, včetně závazných podnikových pravidel, předání nebo soubor předání osobních údajů do třetí země nebo mezinárodní organizaci se uskuteční pouze za jedné z těchto podmínek:*
> *(a) subjekt údajů s navrženým předáním výslovně souhlasil poté, co byl informován o možných rizicích takových předání pro subjekt údajů vzhledem k absenci rozhodnutí o odpovídající ochraně a vhodných záruk;*
> *(b) předání je nezbytné pro plnění smlouvy uzavřené mezi subjektem údajů a správcem nebo provádění předsmluvních opatření přijatých na žádost subjektu údajů;*
> *(c) předání je nezbytné pro uzavření nebo plnění smlouvy uzavřené v zájmu subjektu údajů mezi správcem a jinou fyzickou nebo právnickou osobou;*
> *(d) předání je nezbytné z důležitých důvodů veřejného zájmu;*
> *(e) předání je nezbytné pro určení, výkon nebo obhajobu právních nároků;*
> *(f) předání je nezbytné k ochraně životně důležitých zájmů subjektu údajů nebo jiných osob, pokud subjekt údajů není fyzicky nebo právně způsobilý dát souhlas;*
> *(g) předání se uskuteční z rejstříku, který je podle unijního nebo členského práva určen k informování veřejnosti a který je veřejnosti nebo osobám, které prokáží oprávněný zájem, přístupný pro nahlédnutí, avšak pouze v rozsahu, v jakém jsou v daném případě splněny podmínky nahlédnutí stanovené unijním nebo členským právem.*

> **Čl. 49 odst. 1 pododstavec druhý**
> *Nemůže-li být předání založeno na ustanovení článku 45 nebo 46, včetně ustanovení o závazných podnikových pravidlech, a žádná z výjimek pro specifické situace uvedených v prvním pododstavci odstavce 1 se nevztahuje, lze předání do třetí země nebo mezinárodní organizaci uskutečnit, pouze pokud předání není opakované, týká se pouze omezeného počtu subjektů údajů, je nezbytné pro účely přesvědčivých oprávněných zájmů správce, které nepřevažují nad zájmy nebo právy a svobodami subjektu údajů, a pokud správce posoudil všechny okolnosti spojené s předáním údajů a na základě tohoto posouzení poskytl vhodné záruky ochrany osobních údajů. Správce informuje dozorový úřad o předání. Správce kromě poskytnutí informací uvedených v článcích 13 a 14 informuje subjekt údajů o předání a o přesvědčivých oprávněných zájmech, které sleduje.*

> **Čl. 49 odst. 2**
> *Předání podle písm. g) prvního pododstavce odstavce 1 se netýká veškerých osobních údajů nebo celých kategorií osobních údajů obsažených v rejstříku. Je-li rejstřík určen k nahlížení osobám, které mají oprávněný zájem, uskuteční se předání pouze na žádost těchto osob nebo tehdy, jsou-li příjemci.*

> **Čl. 49 odst. 3**
> *Písm. a), b) a c) prvního pododstavce odstavce 1 a druhý pododstavec odstavce 1 se nevztahují na činnosti prováděné veřejnými orgány při výkonu jejich veřejné moci.*

> **Čl. 49 odst. 4**
> *Veřejný zájem uvedený v písm. d) prvního pododstavce odstavce 1 musí být uznán v právu Unie nebo v právu členského státu, jemuž podléhá správce.*

> **Čl. 49 odst. 5**
> *Není-li vydáno rozhodnutí o odpovídající ochraně, mohou unijní nebo členské právo z důležitých důvodů veřejného zájmu výslovně stanovit meze pro předávání konkrétních kategorií osobních údajů do třetí země nebo mezinárodní organizaci. Členské státy takováto ustanovení oznámí Komisi.*

> **Čl. 49 odst. 6**
> *Správce nebo zpracovatel zaznamená posouzení a vhodné záruky uvedené v druhém pododstavci odstavce 1 tohoto článku do záznamů uvedených v článku 30.*

**Výklad:** Výjimky (*derogations*) v čl. 49 jsou záchrannou sítí třetí vrstvy — nastupují tehdy, kdy ani rozhodnutí o odpovídající ochraně, ani vhodné záruky nejsou k dispozici nebo je nelze v daném čase splnit. Mají být vykládány restriktivně a nesmějí sloužit jako trvalý náhražkový titul pro běžná opakovaná předávání; takový přístup opakovaně kritizoval EDPB (Pokyny č. 2/2018 k výjimkám z čl. 49 GDPR).

Souhlas dle písm. a) musí být *výslovný* a musí být předcházet předání; subjekt musí být informován o rizicích vyplývajících z absence standardní ochrany — což v praxi znamená výrazně posílenou informační povinnost oproti čl. 13 a 14 GDPR. Smluvní výjimky (písm. b) a c)) jsou podmíněny nezbytností — nelze jich použít jen proto, že je předání pohodlné nebo ekonomicky výhodné; musí být přímou podmínkou plnění smlouvy nebo nezbytnou součástí konkrétního smluvního vztahu. Výjimka veřejného zájmu (písm. d)) musí být uznána v právu EU nebo v právu členského státu (odst. 4) — nelze ji tedy opřít jen o vnitrostátní zájem třetí země. Výjimka pro právní nároky (písm. e)) pokrývá soudní, rozhodčí i správní řízení a mimosoudní postupy. Výjimka pro životně důležité zájmy (písm. f)) je aplikovatelná jen v případě neschopnosti subjektu souhlas udělit — nelze ji použít jako alternativu k souhlasu.

Druhý pododstavec odst. 1 zavádí tzv. residuální klauzuli přesvědčivých oprávněných zájmů (*compelling legitimate interests*): jde o výjimku ultima ratio, která vyžaduje nesystematičnost předání (nikoliv opakované přenosy), omezený okruh subjektů, přesvědčivý správcův zájem přesahující zájmy subjektů údajů, provedení posouzení (Transfer Impact Assessment) a jeho dokumentaci v záznamu zpracovatelských činností (čl. 30). Správce musí navíc informovat jak dozorový úřad, tak subjekt údajů.

Odst. 5 výslovně umožňuje, aby unijní nebo vnitrostátní právo *omezilo* předávání specifických kategorií údajů — jde o zrcadlový protipól výjimek: normotvůrce může zakázat předávání, kde by jinak mohla být výjimka použita. ZZOÚ neobsahuje takové výslovné zákazy předávání, avšak § 35 ZZOÚ omezuje přístup k osobním údajům zpracovávaným pro účely trestněprávní agendy, což má na předávání nepřímý dopad.

#### F. Kazuistika

**1. Modelová situace.** Cestovní kancelář (správce) jednorázově předá údaje jednoho klienta do třetí země bez adekvátnosti i bez SCC, aby mu zajistila ubytování, které si výslovně vyžádal. V jiném případě chce systematicky a opakovaně předávat databázi všech klientů do třetí země „na základě oprávněného zájmu". Důkazy: nezbytnost předání pro smlouvu, výslovný informovaný souhlas, rozsah a opakovanost předání, informování úřadu.

**2. Právní otázka.** Lze obě předání opřít o výjimky dle čl. 49 (smluvní nezbytnost, souhlas, residuální klauzule), a platí pro ně požadavek restriktivního výkladu?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 49 odst. 1 písm. a) (výslovný souhlas), písm. b) (smlouva), pododstavec druhý (residuální klauzule), odst. 6 (záznam).
- *Související ustanovení téhož zákona:* čl. 44–47, čl. 13/14, čl. 30.
- *Související předpisy:* pokyny EDPB č. 2/2018 k výjimkám čl. 49.
- *Judikatura:* praxe EDPB — výjimky jsou ultima ratio, ne trvalý titul.

**4. Subsumpce.** Jednorázové předání nezbytné pro klientem vyžádanou smlouvu spadá pod písm. b) (nebo výslovný informovaný souhlas dle písm. a)). Systematické opakované předávání celé databáze pod výjimky nespadá — vyžaduje čl. 45/46; residuální klauzule je vyloučena pro opakovaná předání.

**5. Řešení.** První předání je přípustné jako nezbytné pro smlouvu/se souhlasem. Pro druhé musí kancelář zavést SCC nebo jiný titul; výjimky nelze použít jako trvalý náhradní titul. Procesně: informovaný souhlas, záznam dle čl. 30.

**6. Varianty.** (a) Residuální klauzule (přesvědčivý oprávněný zájem) by připadala v úvahu jen u neopakovaného předání omezeného počtu subjektů s TIA a informováním úřadu. (b) U veřejných orgánů jsou některé výjimky vyloučeny (odst. 3).

#### G. Protiargumenty a rizika

- *„Oprávněný zájem kryje i opakovaná předání."* Residuální klauzule výslovně vylučuje opakovaná předání; pro ně je nutný čl. 45/46.
- *„Souhlas vyřeší vše."* Souhlas musí být výslovný a informovaný o rizicích absence záruk; nehodí se pro systematické toky.
- *Slabé místo:* hranice „nezbytnosti" a „neopakovanosti" je sporná; nesprávné použití výjimky vede k nezákonnosti.

#### H. Praktický závěr

Výjimky dle čl. 49 jsou záchrannou sítí pro nahodilá, nezbytná předání, vykládají se restriktivně a nesmí nahrazovat čl. 45/46 u systematických toků; vždy je dokumentuj v záznamech.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je dána konkrétní výjimka dle odst. 1 a je předání skutečně nezbytné?
- [ ] Je u souhlasu výslovný a informovaný o rizicích (písm. a))?
- [ ] Nejde o opakované/systematické předání (pak nutný čl. 45/46)?
- [ ] Je u residuální klauzule provedeno TIA a informován úřad?
- [ ] Je posouzení a záruky zaznamenáno dle čl. 30 (odst. 6)?

**Typicky rozhodné důkazy / podklady:** doklad o nezbytnosti pro smlouvu, znění výslovného souhlasu, rozsah a frekvence předání, záznam dle čl. 30, případné informování úřadu a subjektu.

---


<!-- LEGAL-REVISION:BEGIN id=7b1815e594e6df9591e8 generator=2026-07-17.4 source_sha256=064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea -->
#### Revizní doplnění k Čl. 49 — Derogations for specific situations

> Revize: 17. 7. 2026 | Znění předpisu k: datum dokumentu místního zdroje 27. 4. 2016 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-24/EU Law/Legal Acts-EN/Legal Acts/Regulations/2016/32016R0679.md`; identifikátor verze: `32016R0679`; SHA-256: `064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea`.

##### Znění ustanovení

>  1.   In the absence of an adequacy decision pursuant to Article 45(3), or of appropriate safeguards pursuant to Article 46, including binding corporate rules, a transfer or a set of transfers of personal data to a third country or an international organisation shall take place only on one of the following conditions:
>
>
>
>
>
>
>
>  (a)
>
>
>
>  the data subject has explicitly consented to the proposed transfer, after having been informed of the possible risks of such transfers for the data subject due to the absence of an adequacy decision and appropriate safeguards;
>
>
>
>
>
>
>
>
>
>
>
>
>  (b)
>
>
>
>  the transfer is necessary for the performance of a contract between the data subject and the controller or the implementation of pre-contractual measures taken at the data subject's request;
>
>
>
>
>
>
>
>
>
>
>
>
>  (c)
>
>
>
>  the transfer is necessary for the conclusion or performance of a contract concluded in the interest of the data subject between the controller and another natural or legal person;
>
>
>
>
>
>
>
>
>
>
>
>
>  (d)
>
>
>
>  the transfer is necessary for important reasons of public interest;
>
>
>
>
>
>
>
>
>
>
>
>
>  (e)
>
>
>
>  the transfer is necessary for the establishment, exercise or defence of legal claims;
>
>
>
>
>
>
>
>
>
>
>
>
>  (f)
>
>
>
>  the transfer is necessary in order to protect the vital interests of the data subject or of other persons, where the data subject is physically or legally incapable of giving consent;
>
>
>
>
>
>
>
>
>
>
>
>
>  (g)
>
>
>
>  the transfer is made from a register which according to Union or Member State law is intended to provide information to the public and which is open to consultation either by the public in general or by any person who can demonstrate a legitimate interest, but only to the extent that the conditions laid down by Union or Member State law for consultation are fulfilled in the particular case.
>
>
>
>
>
>
>  Where a transfer could not be based on a provision in Article 45 or 46, including the provisions on binding corporate rules, and none of the derogations for a specific situation referred to in the first subparagraph of this paragraph is applicable, a transfer to a third country or an international organisation may take place only if the transfer is not repetitive, concerns only a limited number of data subjects, is necessary for the purposes of compelling legitimate interests pursued by the controller which are not overridden by the interests or rights and freedoms of the data subject, and the controller has assessed all the circumstances surrounding the data transfer and has on the basis of that assessment provided suitable safeguards with regard to the protection of personal data. The controller shall inform the supervisory authority of the transfer. The controller shall, in addition to providing the information referred to in Articles 13 and 14, inform the data subject of the transfer and on the compelling legitimate interests pursued.
>
>
>
>
>  2.   A transfer pursuant to point (g) of the first subparagraph of paragraph 1 shall not involve the entirety of the personal data or entire categories of the personal data contained in the register. Where the register is intended for consultation by persons having a legitimate interest, the transfer shall be made only at the request of those persons or if they are to be the recipients.
>
>
>
>
>  3.   Points (a), (b) and (c) of the first subparagraph of paragraph 1 and the second subparagraph thereof shall not apply to activities carried out by public authorities in the exercise of their public powers.
>
>
>
>
>  4.   The public interest referred to in point (d) of the first subparagraph of paragraph 1 shall be recognised in Union law or in the law of the Member State to which the controller is subject.
>
>
>
>
>  5.   In the absence of an adequacy decision, Union or Member State law may, for important reasons of public interest, expressly set limits to the transfer of specific categories of personal data to a third country or an international organisation. Member States shall notify such provisions to the Commission.
>
>
>
>
>  6.   The controller or processor shall document the assessment as well as the suitable safeguards referred to in the second subparagraph of paragraph 1 of this Article in the records referred to in Article 30.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: Čl. 45, Čl. 46, Čl. 30

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=7b1815e594e6df9591e8 -->

### Čl. 50 — Mezinárodní spolupráce pro ochranu osobních údajů

> **Čl. 50**
> *Ve vztahu ke třetím zemím a mezinárodním organizacím přijmou Komise a dozorové úřady vhodná opatření s cílem:*
> *(a) rozvíjet mechanismy mezinárodní spolupráce pro usnadnění účinného prosazování právních předpisů o ochraně osobních údajů;*
> *(b) poskytovat si vzájemnou mezinárodní pomoc při prosazování právních předpisů o ochraně osobních údajů, a to i prostřednictvím oznámení, postoupení stížností, pomoci při šetřeních a výměny informací, s výhradou vhodných záruk ochrany osobních údajů a jiných základních práv a svobod;*
> *(c) zapojit příslušné zainteresované strany do diskusí a aktivit zaměřených na podporu mezinárodní spolupráce při prosazování právních předpisů o ochraně osobních údajů;*
> *(d) podporovat výměnu a dokumentaci právních předpisů o ochraně osobních údajů a praxe, zejména pokud jde o jurisdikční konflikty se třetími zeměmi.*

**Výklad:** Článek 50 má programový charakter — nestanoví konkrétní práva ani povinnosti pro správce, ale ukládá Komisi a dozorovým úřadům, aby aktivně budovaly infrastrukturu mezinárodní spolupráce v oblasti ochrany dat. Tento závazek je reakcí na realitu přeshraničního zpracování: porušení práv subjektů údajů se odehrává přes hranice, dozorové úřady jsou však omezeny vlastní jurisdikcí.

Opatření zahrnují uzavírání dohod o spolupráci (*Memoranda of Understanding* nebo formální dohody) s dozorovými úřady třetích zemí, vzájemnou pomoc při stížnostech a šetřeních, výměnu informací o legislativních confliktech a zapojení stakeholderů (akademická sféra, průmyslové asociace, mezinárodní organizace jako OECD, OSN či Rada Evropy). Recitál 116 zdůrazňuje, že bez mezinárodní spolupráce dozorových úřadů by přeshraniční prosazování GDPR bylo jen iluzorní. ÚOOÚ je zapojen prostřednictvím EDPB do mezinárodních fór (Global Privacy Assembly, Berlínská skupina) a uzavírá bilaterální ujednání o spolupráci s dozorovými úřady mimo EHP.

Vazba na zákon č. 110/2019 Sb.: § 54 a násl. ZZOÚ upravují pravomoci ÚOOÚ, přičemž mezinárodní spolupráce ÚOOÚ se opírá přímo o čl. 50 GDPR a o příslušná prováděcí pravidla EDPB; zvláštní vnitrostátní úprava pro předávání nebyla přijata.

#### F. Kazuistika

**1. Modelová situace.** Subjekt z ČR podá ÚOOÚ stížnost na správce usazeného mimo EHP, který sleduje jeho chování. ÚOOÚ k účinnému prošetření potřebuje součinnost dozorového úřadu třetí země (výměna informací, pomoc při šetření). Existuje jen omezený rámec spolupráce. Důkazy: dohody o spolupráci ÚOOÚ se zahraničními úřady, mechanismus vzájemné pomoci, rozsah sdílených informací.

**2. Právní otázka.** Jaký je dosah čl. 50 a zakládá adresátům normy (správcům) přímá práva či povinnosti?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 50 písm. a)–d) (mechanismy spolupráce, vzájemná pomoc, zapojení stran, výměna praxe).
- *Související ustanovení téhož zákona:* čl. 3 (územní působnost), čl. 57–58 (úkoly a pravomoci úřadu), čl. 60 a násl. (spolupráce v EU).
- *Související předpisy:* § 54, § 56 ZZOÚ (mezinárodní spolupráce ÚOOÚ); recitál 116.
- *Judikatura:* —

**4. Subsumpce.** Čl. 50 je programovým ustanovením adresovaným Komisi a dozorovým úřadům; nezakládá přímá práva ani povinnosti správců. Účinné přeshraniční prosazování závisí na dohodách o spolupráci a vzájemné pomoci, které ÚOOÚ uzavírá a využívá.

**5. Řešení.** ÚOOÚ využije existující mechanismy spolupráce (MoU, výměna informací) k prošetření stížnosti; účinnost je limitována rozsahem mezinárodní spolupráce. Pro subjekt to znamená, že vymahatelnost vůči zahraničnímu správci může být ztížená.

**6. Varianty.** (a) Má-li zahraniční správce zástupce v EU (čl. 27), je prosazování snazší. (b) Existuje-li dohoda o vzájemné pomoci s daným úřadem, je šetření efektivnější.

#### G. Protiargumenty a rizika

- *„Čl. 50 dává subjektu nárok na mezinárodní pomoc."* Jde o programové ustanovení pro orgány, nikoli o přímý nárok adresátů normy.
- *„ÚOOÚ vše vymůže i mimo EU."* Pravomoci úřadu jsou územně omezené; účinnost závisí na spolupráci se zahraničními úřady.
- *Slabé místo:* mezinárodní spolupráce je fakticky závislá na dobré vůli a dohodách; chybí přímá vynutitelnost.

#### H. Praktický závěr

Čl. 50 je programovým rámcem mezinárodní spolupráce dozorových úřadů; nezakládá povinnosti správců, ale ovlivňuje reálnou vymahatelnost práv vůči subjektům mimo EHP — proto je klíčový institut zástupce v EU (čl. 27).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Jde o přeshraniční prvek vyžadující součinnost zahraničního úřadu?
- [ ] Existuje dohoda o spolupráci/vzájemné pomoci (§ 54, § 56 ZZOÚ)?
- [ ] Má zahraniční správce zástupce v EU (čl. 27) usnadňující prosazování?
- [ ] Jsou využity dostupné mechanismy výměny informací?

**Typicky rozhodné důkazy / podklady:** dohody o spolupráci ÚOOÚ, doklad o existenci zástupce v EU, komunikace mezi dozorovými úřady, rozsah dostupné vzájemné pomoci.

---

*Komentář byl zpracován výhradně z lokálních materiálů (Obsidian vault s unijními předpisy z EUR-Lex; konsolidované anglické znění GDPR, CELEX 32016R0679). Na judikaturu SDEU (Schrems I, Schrems II) se odkazuje obecně podle názvů kauz; spisové značky nejsou uvedeny záměrně, aby nedocházelo k jejich vymýšlení. Aktuální přehledy rozhodnutí o odpovídající ochraně viz publikace Komise v Úředním věstníku EU.*

<!-- LEGAL-REVISION:BEGIN id=915f5e6b4791ea5f77f6 generator=2026-07-17.4 source_sha256=064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea -->
#### Revizní doplnění k Čl. 50 — International cooperation for the protection of personal data

> Revize: 17. 7. 2026 | Znění předpisu k: datum dokumentu místního zdroje 27. 4. 2016 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-24/EU Law/Legal Acts-EN/Legal Acts/Regulations/2016/32016R0679.md`; identifikátor verze: `32016R0679`; SHA-256: `064fd9c896af1d5d5b6dacdced0bc454afa4d8ba939b6b2cc12040d2a9a520ea`.

##### Znění ustanovení

>  In relation to third countries and international organisations, the Commission and supervisory authorities shall take appropriate steps to:
>
>
>
>
>
>
>
>  (a)
>
>
>
>  develop international cooperation mechanisms to facilitate the effective enforcement of legislation for the protection of personal data;
>
>
>
>
>
>
>
>
>
>
>
>
>  (b)
>
>
>
>  provide international mutual assistance in the enforcement of legislation for the protection of personal data, including through notification, complaint referral, investigative assistance and information exchange, subject to appropriate safeguards for the protection of personal data and other fundamental rights and freedoms;
>
>
>
>
>
>
>
>
>
>
>
>
>  (c)
>
>
>
>  engage relevant stakeholders in discussion and activities aimed at furthering international cooperation in the enforcement of legislation for the protection of personal data;
>
>
>
>
>
>
>
>
>
>
>
>
>  (d)
>
>
>
>  promote the exchange and documentation of personal data protection legislation and practice, including on jurisdictional conflicts with third countries.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=915f5e6b4791ea5f77f6 -->

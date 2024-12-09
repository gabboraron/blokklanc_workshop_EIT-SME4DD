# "Blockchain a kisvállalkozások számára" workshop by [EIT](https://professionalschool.eitdigital.eu/sme4dd-courses/blokklanc-projekttervezes-kisvallalatoknak)/[SME4DD](https://www.eitdigital.eu/eu-collaborations/sme4dd/)-[KIFÜ](https://kifu.gov.hu/sme4dd_blokklanc_kisvall/)

> **Mire készít fel a képzés?**
> - Blokklánc projektek magas szintű tervezése
> - Blokklánc megoldás kiválasztásának szempontrendszere
> - Blokklánc projekt javaslat megfogalmazása és kiértékelése
> - Blokklánc projektben előforduló tipikus feladatok ismerete

![hash függvények](https://miro.medium.com/v2/resize:fit:1199/1*m5hHny_ld5vmLy4Ip_7pEA.png)

A kriptográfiában az [X.509](https://en.wikipedia.org/wiki/X.509) a Nemzetközi Távközlési Unió (ITU) szabványa, amely meghatározza a nyilvános kulcsú tanúsítványok formátumát.

A [Hyperledger Fabric]( https://www.lfdecentralizedtrust.org/projects/fabric) a moduláris felépítésű alkalmazások vagy megoldások fejlesztésének alapjául szolgál. Lehetővé teszi a cserélhető komponenseket, beleértve a konszenzus és a tagsági szolgáltatásokat, lehetővé téve a plug-and-play környezetet. A Hyperledger Fabricot úgy tervezték, hogy megfeleljen a különböző iparági igényeknek. Emellett egyedülálló megközelítést kínál a konszenzushoz, amely megkönnyíti a skálázható teljesítményt, miközben megőrzi az adatvédelmet. Számos más projekt és laboratórium is kapcsolódik a Fabrichoz, és támogatni tudja Önt a megoldások telepítésében. *Jó lehet pl konténerek nyomonkövetésére* [más megoldások](https://www.servermania.com/kb/articles/hyperledger-corda-quorom)

![](https://www.mdpi.com/applsci/applsci-12-07898/article_deploy/html/images/applsci-12-07898-g001-550.jpg)

## [Elosztott főkönyvi technológia](https://penzmuzeumpedia.hu/elosztott-fokonyvi-technologia/)
> - felhasználók
> - mi van a főkönyvben
> - a főkönyv egy példánya

tudom-e a főkönyvet olvasni:
- nyílt: bárki olvashatja
- zárt: csak egyesek láthatják, de ott se mindenki

[DLT](https://www.investopedia.com/terms/d/distributed-ledger-technology-dlt.asp)

The [European Blockchain Services Infrastructure (EBSI)](https://ec.europa.eu/digital-building-blocks/sites/display/EBSI/Home) was born in 2018 when 29 countries (all EU members states, Norway and Liechtenstein) and the EU Commission joined forces to create the European Blockchain Partnership (EBP). The EBP’s vision is to leverage blockchain to create cross-border services for public administrations, businesses, citizens and their ecosystems to verify information and make services trustworthy.

## [Smart contract](https://www.ibm.com/topics/smart-contracts) avagy *Főkönyvön értelmezett tárolt eljárás*

![](https://imiblockchain.com/wp-content/uploads/2023/10/distributed-ledger-technology-history-timeline.jpeg)

Főkönyvi data modell:
- kulcs érték párok

Pl:
```
Sub-ledger: ChoclateID -> lecturerID
Req: sender, choclateID, receiver

IF
(request.signature1 = sender
 request.signature2 = reciever
 choclateID.owner = sender
 choclateID.bestBefore > now +1w)

THEN
choclateID.owner = reciever
```

Okos szerződés minták elérhetőek ingyen: https://www.openzeppelin.com/

![](https://ars.els-cdn.com/content/image/1-s2.0-S2352467721001247-gr9.jpg)

# Publikus blokkláncok
> **Bizánci generális probléma:** Ha minden tábornok összehangoltan támad, a csatát megnyertük (balra). Ha két tábornok hamisan kijelenti, hogy támadni szándékozik, de ehelyett visszavonul, a csata elveszett (jobbra).
>
> ![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Byzantine_Generals.png/435px-Byzantine_Generals.png)

## [Proof of Work (PoW)](https://academy.binance.com/hu/articles/proof-of-work-explained)
*Találgatok és azért fogadjuk el az én eredményemet mert elsőként megtaláltam*

## [Proof of stake](https://academy.binance.com/hu/articles/proof-of-stake-explained)
> A proof-of-stake blokklánc hálózaton résztvevő entitásokat mintereknek (szabatos fordításban pénzverőknek) vagy más néven validátorokonak nevezzük. A legtöbb protokollban a validátorok jutalmat kapnak a tevékenységért.

*Letétet rakok le, és a letétek arányában részesülök, a kis letétesek nagyobb arányban kapnak, hogy ne vesszenek el.*

> Előnyök:
> - jutalékok olcsóbbak
> - trust intermediation

# Ötletek blokkláncon
https://www.kaleido.io/

Költségek és tranzakciós idő vizualizálva:https://txcity.io/

Polygon hálózat (ETH alapú): https://polygonscan.com/
- mintha nap végén küldöm be az összes infómat, tehát késik az infó, de cserébe olcsóbb
- [layer2](https://kriptotarca.hu/a-layer-2-fogalma-mi-az-a-layer-2-halozat-es-hogyan-mukodik-a-layer-1-network-hoz-kepest/) megoldások
- legnépszerűbb megoldás: [OpenSea](https://opensea.io/)
  - Klint csókjának NFTje: https://thekiss.art/

Solidity példa játék ([eth virtual machine](https://ethereum.org/en/developers/docs/evm/)on): https://cryptozombies.io/

![](https://www.slideteam.net/media/catalog/product/cache/1280x720/c/o/comparison_of_consensus_mechanism_algorithms_in_blockchain_training_ppt_slide01.jpg)

| ![](https://appinventiv.com/wp-content/uploads/2023/12/Exploring-the-Business-Benefits-of-Permissioned-Blockchains-Efficiency-Security-and-Collaboration-07.webp) | Functional: identificable participants <br> <br> Extra functional: scalability, privacy, predictable costs, availability |
| ----- | ---- |

> A lakossági központi banki digitális valutarendszer (CBDC) kifejlesztése jelentős vállalkozás, és a központi bankoknak számos területet kell megvizsgálniuk, többek között: Hogyan javítható a köz- és magánszféra együttműködése? Hogyan lehet maximalizálni az átjárhatóságot, ösztönözni a versenyt és lehetővé tenni az elfogadást? Hogyan felelhet meg a kiskereskedelmi CBDC a jelenlegi és jövőbeli fogyasztói igényeknek a gyorsan változó fizetési környezetben?
>
> https://www.bis.org/about/bisih/topics/cbdc/rosalind.htm

**Tipikus szoftveres megoldások:**
- hyperledger technologies
- R3 Corda
- Digital Asset
- ethereum variants: Quorum, HL Besu
- bitcoin
- [BcaaS](https://www.scirp.org/journal/paperinformation?paperid=117570)

## példa
aktorok:
- vevők
- gyártók
- stakeholderek

-> üzleti folyamat

> ### Elosztott főkönyv
>
> **[Digital Asset language](https://www.digitalasset.com/developers)**
>
> *A Daml egy intelligens szerződési nyelv, amelyet úgy terveztek, hogy összeállítható alkalmazásokat építsen egy absztrakt Daml Ledger Model koncepcióra.*
> 
> - https://github.com/digital-asset/daml
> - https://www.digitalasset.com/developers/examples
> - https://cambridge-intelligence.com/kronograph/


> #### Elosztott főkönyv kereskedelemben
>
> *"A nemzetközi kereskedelem digitalizálása a legtöbbet vizsgált témák közé tartozik, különösen a Covid-19 pandémia után. A mesterséges intelligencia chatGPT és az Apple vegyes valóság szemüvegének, a világ első viselhető számítógépének, a "Vision Pro"-nak a megjelenésével nehéz elhinni, hogy a nemzetközi kereskedelem több mint 25 billió dollárnyi része még mindig papíron zajlik. Kétségtelen, hogy az elosztott főkönyvi technológia (DLT) vagy blokklánc a legfontosabb technológiai áttörés, amely lehetővé teszi a nemzetközi kereskedelem digitalizálását."*
>
> https://www.linkedin.com/pulse/when-digitalization-dlt-norm-international-trade-meral-%C5%9Feng%C3%B6z/
>
> ![](https://media.licdn.com/dms/image/v2/D4D12AQEkC_s1FTH-MA/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1687438754531?e=1739404800&v=beta&t=9HSu-gMVAGBqrXIGKXhzIyjhsE6lLwnuymGWzKUYB_Y)




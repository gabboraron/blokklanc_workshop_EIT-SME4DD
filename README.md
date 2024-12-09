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

![](https://ars.els-cdn.com/content/image/1-s2.0-S2352467721001247-gr9.jpg)

# Publikus blokkláncok
> **Bizánci generális probléma:** Ha minden tábornok összehangoltan támad, a csatát megnyertük (balra). Ha két tábornok hamisan kijelenti, hogy támadni szándékozik, de ehelyett visszavonul, a csata elveszett (jobbra).
>
> ![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Byzantine_Generals.png/435px-Byzantine_Generals.png)

## [Proof of Work (PoW)](https://academy.binance.com/hu/articles/proof-of-work-explained)
*Találgatok és azért fogadjuk el az én eredményemet mert elsőként megtaláltam*

## [Proof of stake](https://academy.binance.com/hu/articles/proof-of-stake-explained)
A proof-of-stake blokklánc hálózaton résztvevő entitásokat mintereknek (szabatos fordításban pénzverőknek) vagy más néven validátorokonak nevezzük. A legtöbb protokollban a validátorok jutalmat kapnak a tevékenységért.

*Letétet rakok le, és a letétek arányában részesülök, a kis letétesek nagyobb arányban kapnak, hogy ne vesszenek el.*





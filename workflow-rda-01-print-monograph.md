---
section: Arbetsflöden
title: Tryckt monografi RDA
order: 30
tags:
- editor
- rda
- workflow
- print-monograph
---

# Tryckt monografi RDA

_Arbetsflödet är under arbete._

[Extern länk till MARC21-anpassad information](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/)

För generella riktlinjer om hur man återger element som de förekommer i källan, se ”Transcription” – RDA 1.7.


## Innehåll

* [Element tillhörande instans/manifestation](#paragraph1)
    * [Föredragen källa (RDA 2.2)](#subparagraph1)
    * [Utgivningssätt (RDA 2.13)](#subparagraph2)
    * [Titelinformation](#subparagraph3)
* [Huvudtitel (RDA 2.3.2)](#paragraph2)
    * [Alternativtitel som är en del av huvudtiteln](#subparagraph4)
    * [Felaktigheter](#subparagraph5)
---

---
## Element tillhörande instans/manifestation <a name="paragraph1"></a>

### Föredragen källa (RDA 2.2) <a name="subparagraph1"></a>

Börja med den information som finns på titelsidan (RDA 2.1.2.2 och RDA 2.2.2.2).

Uppgifter som saknas på titelsidan hämtas i första hand från valfri källa inom resursen. Det finns ingen prioriteringsordning bland övriga källor inom resursen.

Uppgifter från copyright: Det är endast uppgift om copyrightår som kan hämtas från copyrightuppgiften. När andra uppgifter som ska anges i beskrivningen endast finns i copyrightuppgiften (till exempel uppgift om upphov, utgivare eller utgivningsort) kan uppgiften tas därifrån om den bedöms rimlig och avser manifestationen. Uppgiften måste då anges inom klammer.

För samlingsverk som saknar gemensam titelsida behandlas de ingående verkens titelsidor som en gemensam titelsida för instansen/manifestationen (RDA 2.1.2.2).

Om det finns flera titelsidor eller olika källor med olika datum, använd i första hand den information som finns i källan med det senaste datumet (RDA 2.2.3.2).

Om resursen saknar titelsida eller annan källa med information som är nödvändig för att identifiera resursen, använd information som finns på (i denna ordning): medföljande material som inte är en del av resursen själv, annan publicerad beskrivning av resursen, en förpackning, annan tillgänglig källa. Klamra information som hämtats utanför resursen (RDA 2.2.4).

### Utgivningssätt (RDA 2.13) <a name="subparagraph2"></a>

Ange utgivningssätt för den beskrivna resursen. För en tryckt monografi anges ”resurs bestående av en enhet”.

### Titelinformation <a name="subparagraph3"></a>

_Arbetsflödet är under arbete._

Alla titlar som är en del av den beskrivna resursens samlas i en gruppen kallad hasTitle (Har titel).

Under huvudelementet Title (Titel) kan flera titeltyper anges:
* Huvudtitel
* Deltitel
* Delbeteckning
* Övrig titelinformation

Huvudtitel och Övrig titelinformation är förvalda i mallen _Tryckt monografi – RDA_.

## Huvudtitel (RDA 2.3.2)  <a name="paragraph2"></a>

Huvudtitel är ett kärnelement. 

Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan (se RDA 1.7). 
Librispraxis: Generellt förkortas aldrig en huvudtitel (se valfritt alternativ under RDA 2.3.1.4).

### Alternativtitel som är en del av huvudtiteln <a name="subparagraph4"></a>

Inkludera en alternativtitel som är en del av huvudtiteln.

**Titel**
`Huvudtitel: Bilbo eller En Hobs äventyr`

### Felaktigheter <a name="subparagraph5"></a>

Rätta inte felaktigheter. Om en korrekt form av huvudtiteln är viktig för identifikation och åtkomst anges den i titeltypen Varianttitel (RDA 1.7.9).

**Titel**
`Huvudtitel: Heirarchy in organizations`

**Varianttitel**
`Benämning?: Titel felstavad, korrekt titel: Hierarchy in organizations`

Den rättstavade titeln anges vanligen som Föredragen titel för verket under Instans av verk.

## Namn på personer, familjer/släkter och institutioner i titeln

Om en huvudtitel innehåller namn som normalt skulle behandlas som en del av upphovsuppgiften eller utgivaruppgiften etc. och namnet utgör en integrerad del av huvudtiteln, ange hela huvudtiteln i titeltypen Huvudtitel och allt utom i namnet i titeltypen Del av huvudtiteln (RDA 2.3.1.5).

**Titel** 
`Huvudtitel: Disney’s 102 dalmatiner` 

**Del av huvudtitel** 
`Benämning?: 102 dalmatiner`

Genitivformen "Disney's" inleder huvudtiteln. Upphovsuppgift ska inte anges såvida den inte förekommer som en separat uppgift i resursen. 

## Inledande ord etc.

Återge inte inledande ord som inte är en del av huvudtiteln (RDA 2.3.1.6). 

Librispraxis: Tillämpa det valfria alternativet och ange hela huvudtiteln i titeltypen Även med titel.

**Titel**
`Huvudtitel: Törnrosa`

**Även med titel**
`Benämning?: Disney presenterar Törnrosa`

## Varianttitlar

Ange varianttitlar om det bedöms viktigt för identifikation eller åtkomst, se RDA 2.3.6.3. 

**Titel**
`Huvudtitel: Sanvikens IF 75 år`

**Omslagstitel**
`Benämning?: Sandvikens IF 1918-1993`

Varianttitel hämtad från källa som inte kan anges med hjälp av andraindikatorn. 

**Varianttitel**
`Benämning?: Titel på spikblad: Between humans and things : #b an interactionistic analysis of collecting`

## Flera titlar i olika former

Om det i den föredragna källan förekommer flera titlar i olika former (men på samma språk och i samma skriftart), välj huvudtitel utifrån den ordning som markeras av ordningsföljd, layout eller typografi. Om ordningsföljd etc. är oklara eller otillräckliga för att bestämma den inbördes ordningen, välj den huvudtitel som är mest fullständig (RDA 2.3.2.5).

## Resurs som saknar titel

Om resursen saknar titel men titeln kan hämtas från en källa utanför resursen, ange titeln inom klammer. Gör en anmärkning om varifrån titeln hämtats (RDA 2.3.2.10 och RDA 2.17.2.3).

## Konstruerad titel
Om det inte går att fastställa en huvudtitel, konstruera en huvudtitel på svenska enligt anvisningarna i RDA 2.3.2.10. En konstruerad huvudtitel anges inom klammer. Ange i en anmärkning att huvudtiteln är konstruerad (RDA 2.17.2.3).

**Anmärkning**
`Benämning: Titel konstruerad av katalogisatör`

## Titlar på delar, sektioner eller supplement

Om titeln på delen, sektionen eller supplementet förekommer i källan utan den titel som är gemensam för alla delar återges titeln på delen etc. som huvudtitel. Ange den titel som är gemensam för alla delar som serieuppgift och som titeln på ett relaterat verk.

Om titeln på delen, sektionen eller supplementet förekommer i källan tillsammans med den titel som är gemensam för alla delar och denna titel inte räcker till för att identifiera resursen, återges den gemensamma titeln som huvudtitel. Titeln på delen anges i titeltypen Deltitel och/eller Delbeteckning (RDA 2.3.1.7.1)

**Titel**
`Huvudtitel: Favorit matematik
Deltitel: Tankenötter
Delbeteckning: 1A`

Om titeln på delen, sektionen eller supplementet förekommer i källan tillsammans med den titel som är gemensam för alla delar och denna titel är tillräcklig för att identifiera resursen, återge titeln på delen etc. som huvudtitel (RDA 2.3.1.7.2).

**Titel**
`Huvudtitel: Fadershuset`

**Serieuppgift**
`Nordisk kvinnolitteraturhistoria ; band 2`

## Övrig titelinformation (RDA 2.3.4)

Övrig titelinformation är inte ett kärnelement men obligatorisk enligt Librispraxis. 

Hämta övrig titelinformation från samma källa som huvudtiteln, RDA 2.3.4.2.

Librispraxis: Övrig titelinformation som återfinns i annan källa än huvudtiteln anges endast om den tillför ytterligare information och inte är reklam, slogans etc. Ord och fraser som sammanfaller med genre/formterm redovisas ej som Övrig titelinformation, men andra ord och fraser ska redovisas, t.ex. "spänningsroman", "dokumentärroman". Ange alltid källan som den hämtas från.

**Titel**
`Huvudtitel: Bergens väktare
Övrig titelinformation: Djingis Khan – historiens förste erövrare`

Om övrig titelinformation förekommer på mer än ett språk eller i mer än en skriftart anges den övriga titelinformation som är på huvudtitelns språk eller i dess skriftart, RDA 2.3.4.4.

Om det finns flera undertitlar anges de i den ordning som markeras av ordningsföljd, layout och typografi i källan, RDA 2.3.4.3. Eftersom titeltypen Övrig titelinformation inte är repeterbar anges alla undertitlar i samma fält åtskilda med kolon. 

**Titel**
`Huvudtitel: En arbetsdag i skriftsamhället
Övrig titelinformation: ett etnografiskt perspektiv på skriftanvändning i vanliga yrken : småskrift utarbetad av Språkrådet`

## Parallell huvudtitel (RDA 2.3.3)

Parallell huvudtitel är huvudtiteln på ett annat språk eller i en annan skriftart. Parallell huvudtitel är inte ett kärnelement men enligt Librispraxis är den första parallella huvudtiteln i den föredragna källan obligatorisk. Därutöver redovisas en påföljande parallell huvudtitel på svenska. Övriga parallella huvudtitlar är valfria. 

NB-praxis: Ange alla parallella huvudtitlar som är framhävda i resursen.

En parallell huvudtitel får hämtas från hela resursen, RDA 2.3.3.2. Om huvudtiteln hämtas utanför resursen, ska parallelltiteln hämtas från samma källa.

Parallell huvudtitel anges i titeltyp _Parallelltitel_.

**Parallelltitel**
`Huvudtitel: Finishing of dairy steers`

Titeltypen _Parallelltitel_ är repeterbar.

## Upphovsuppgift (RDA 2.4)

Upphovsuppgift som hänför sig till huvudtiteln är ett kärnelement. Om det finns mer än en, är endast den första ett kärnelement.

Hämta upphovsuppgift som hänför sig till huvudtiteln från följande källor (i denna ordning):
1. Samma källa som huvudtiteln
2. En annan källa inom resursen
3. En annan av de källor som specificeras i RDA 2.2.4.

Endast upphovsuppgifter som hämtas från en källa utanför resursen ska klamras.

Återge upphovsuppgiften som den förekommer i källan, RDA 2.4.1.4. Åtskilj varje enskild upphovsuppgift med ISBD-interpunktion.
`Conn Iggulden ; översättning av Lennart Johansson`

I RDA 2.4.1.4 finns en valfri uteslutning som gör det möjligt att förkorta omfångsrika upphovsuppgifter men bara om det kan göras utan att värdefull information förloras. Librispraxis är att generellt inte förkorta upphovsuppgifter.
`Kiki Lundberg och Carina Trägårdh Tornhill ; faktagranskare: Eva Skoog, leg. dietist, Lisa Lundmark, leg. dietist och Elisabeth Nilsson, leg. sjuksköterska ; fotografi: Helén Sahlstrand, Härlig hälsa, Istock, Shutterstock`

### Upphovsuppgift med fler än en namngiven agent

Återge varje enskild upphovsuppgift som ett element oavsett om två eller flera personer etc. agenter som omnämns har samma eller olika funktioner, RDA 2.4.1.5.
`Helena Rosén Andersson, Eva-Maj Mühlenbock, Henrik Willquist, Natalie Svensson`

Valfri uteslutning: Om en enskild upphovsuppgift namnger fler än tre agenter, uteslut alla utom den första. Uteslutningen markeras med en klamrad summering av vad som uteslutits.
`Helena Rosén Andersson [och tre andra]`

Librispraxis: Katalogisatören avgör om den valfria uteslutningen ska tillämpas. 

NB-praxis: Generellt, tillämpa inte den valfria uteslutningen.

När kunskap finns, ska summeringen vara på resursens språk.
`Knut Sydsæter [and three others]`

## Mer än en upphovsuppgift

Om det finns mer än en upphovsuppgift kan även övriga upphovsuppgifter återges om de är viktiga för identifikation. Librispraxis uppmanar katalogisatören att ta med alla upphovsuppgifter som är av betydelse.

NB-praxis: Ta alltid med uppgifter om skapare (se RDA 19.2) och de upphovsuppgifter som återfinns i samma källa som huvudtiteln (vanligtvis titelsidan). Ta med upphovsuppgifter för översättare även från andra källor i resursen. För skönlitteratur, ta även med upphovsuppgifter för illustratörer från andra källor i resursen. Var i övrigt restriktiv med att hämta upphovsuppgifter från andra källor i resursen. 

Uppgifterna återges i den ordning som markeras av ordningsföljd, layout eller typografi i källan. Om detta är oklart, återge dem i den ordning som framstår som rimligast, RDA 2.4.1.6. 

Ibland finns uppgift om upphov endast angivet i copyrightuppgiften. En copyrightuppgift är inte en upphovsuppgift men om man kan belägga att copyrightinnehavaren också har upphovsansvar kan uppgiften från copyrightuppgiften läggas till inom klammer. Uppgiften behöver inte återges exakt som den förekommer i källan. Om man lägger till flera upphovsuppgifter från copyrightuppgiften ska varje upphovsuppgift klamras för sig.
`[text & koncept: Smriti Prasadam-Halls] ; [illustrationer: Emily Bolam] ; översättning: Marie Helleday Ekwurtzel`

På bakre omslag:
`text & koncept ©Smriti Prasadam-Halls
illustrationer ©Emily Bolam 2010
översättning Marie Helleday Ekwurtzel`

Om inte alla upphovsuppgifter tas med ska förtur ges åt dem som identifierar skaparna av det intellektuella eller konstnärliga innehållet, RDA 2.4.2.3.

Antalet agenter man tar med i upphovsuppgiften behöver inte motsvara antalet relaterade agenter som man anger. Katalogisatören måste här använda sitt omdöme. 

## Klargörande av roll

Om sambandet mellan titeln och den(de) agenter som nämns i upphovsuppgiften är oklart, lägg till ett ord eller en kort fras inom klammer, RDA 2.4.1.7.
`[sammanställda av] Said Mahmoudi`

## Substantivfraser som förekommer tillsammans med en upphovsuppgift

Om ordning, layout eller typografi i källan indikerar att ett substantiv eller en substantivfras är en del av upphovsuppgiften och substantivfrasen talar om vilken roll agenten i upphovsuppgiften har, behandla den som en del av upphovsuppgiften, RDA 2.4.1.8.
`maps by Rand McNally ; photographs by Davis Muench`

## Ingen namngiven agent i upphovsuppgiften

Återge en upphovsuppgift även om ingen person etc. är namngiven i uppgiften, RDA 2.4.1.9
`av en mellanstadieklass i Sigtuna`

### Upphovsuppgift som hänför sig till huvudtiteln på mer än ett språk eller i mer än en skriftart

Om en upphovsuppgift som hänför sig till huvudtiteln förekommer på mer än ett språk eller i mer än en skriftart återges den upphovsuppgift som är på huvudtitelns språk eller i dess skriftart (RDA 2.4.2.4).

NB-praxis: Obligatoriskt att ange parallell upphovsuppgift som hänför sig till huvudtiteln (RDA 2.4.3).

## Identifikator för instansen/manifestationen (RDA 2.15)

Identifikator för instansen/manifestationen är ett kärnelement. Uppgift om identifikator hämtas från valfri källa. 

### ISBN

Ange varje ISBN som finns i resursen. Ange ISBN som är giltiga och hör till manifestationen som katalogiseras i fältet för giltigt ISBN. Ange ISBN som är ogiltiga, felaktiga eller inte hör till den manifestation som katalogiseras i fältet för ogiltiga ISBN. Ange bestämningar till ISBN i Anmärkning. 

ISBN anges utan bindestreck. Om numret slutar med ett litet ”x” anges det med ett stort ”X”. Om både trettonsiffrigt och tiosiffrigt ISBN finns i resursen anges enbart det trettonsiffriga. Numret kan sökas på båda sätten i Libris, oavsett hur det är registrerat i den bibliografiska posten och behöver inte dubbleras.

**ISBN**
`Värde: 9789113069753 
Anmärkning: inbunden`

Om ISBN hämtas från en källa utanför resursen, komplettera gärna med en anmärkning:

**Anmärkning**
`Benämning: ISBN ej angivet i publikationen`

Vanligen anges endast ett giltigt ISBN, men i de fall när separata poster inte skulle göras (när en manifestation ges ut av flera utgivare tillsammans och ett ISBN för varje utgivare finns i manifestationen) anges båda utgivarnas ISBN som giltiga (RDA 2.15.1.6). Lägg till respektive utgivare som bestämning i Anmärkning. 

**ISBN** (giltigt, utgivare 1)
`Värde: 9172092556
Anmärkning: Riksantikvarieämbetet`
**ISBN** (giltigt, utgivare 2)
`Värde: 9152007073
Anmärkning: Svenska Institutet`

## Bestämningar

Om mer än ett ISBN finns i resursen (till exempel ISBN för andra instanser/manifestationer) anges en kort bestämning för varje ISBN i Anmärkning. 

**ISBN** (giltigt, tillhörande instansen/manifestationen som katalogiseras)
`Värde: 9789188185174 
Anmärkning: häftad`
**ISBN** (ogiltigt, tillhörande annan instans/manifestation av samma verk)
`Värde: 9789188185181 
Anmärkning: e-bok`

## Bandtyper

Om resursen endast har en identifikator, ange bandtyp om det bedöms viktigt för identifikation. Bandtyp kan anges med en överordnad eller en mer detaljerad term. Överordnade termer, med definition:

* inbunden: skrift med hårda pärmar, oavsett om den är limmad eller trådhäftad. Pärmarna ska vara styva och alltså inte gå att böja.
* häftad: skrift med mjuka pärmar, med till exempel limmad eller klammerhäftad rygg (till exempel broschyrer). Normalt anges inte bandtypen för dessa. När andra ISBN förekommer i posten bör häftad läggas till som en bestämning.
* spiralbunden: skrift med spiralrygg och hårda pärmar. En skrift med spiralrygg och hårda pärmar betraktas som spiralbunden även om spiralen är synlig.
* spiralhäftad: skrift med spiralrygg och mjuka pärmar

NB-praxis: Från och med juni 2016 anger NB bandtyper med mer detaljerade termer, anpassade utifrån den standard som används av den svenska förlagsbranschen. Det innebär att fler bandtyper än ovan nämnda anges i posterna. Andra bibliotek som vill använda termerna kan göra det. Nedan följer de bandtyper som används:

* inbunden
  
  * board book
  
  * halvfranskt band
  
  * halvklotband
  
  * kartonnage
  
  * klotband

* häftad
  
  * danskt band
  
  * flipback-bok
  
  * flexband
  
  * pocket
  
  * storpocket

* spiralhäftad
  
  * spiralbunden

Kommentar: Vid osäkerhet om bandtyp välj det överordnade begreppet, t.ex. vid osäkerhet om ett band är ett halvfranskt band välj då istället inbunden.

Om katalogisatören bedömer det viktigt att ange bandtyp, och resursen inte har ett ISBN, ska uppgiften om bandtyp anges i en Anmärkning. 

**Anmärkning**
`Benämning: I ringpärm`

Ange bestämningar som hämtas från resursen i den form de har där och bestämningar som hämtas utanför resursen i utskriven form. Ange till exempel kart. om det står så i resursen, och annars den utskrivna formen kartonnage.

## Ogiltiga ISBN och ISBN som hör till en annan version

Ange ISBN i fältet för ogiltigt ISBN om det är ogiltigt eller om det representerar en annan manifestation än den resurs som katalogiseras och den manifestationen skulle kräva en egen post. Texten "ogiltigt nummer/annan version" genereras då automatiskt i Libris. Exempel är ISBN som hör till en version i storstil, en e-bok eller en utgåva på ett annat språk:

**ISBN** (giltigt, tillhörande instansen/manifestationen som katalogiseras)
`Värde: 9789171008466
Anmärkning: inbunden`

**ISBN** (ogiltigt, tillhörande annan version)
`Värde: 9789171008473 
Anmärkning: utgåva på engelska`

Om både ett giltigt och ett ogiltigt ISBN finns i resursen och båda avser samma manifestation/format anges båda ISBN men endast det giltiga ska ha en bestämning. 

**ISBN** (giltigt)
`Värde: 9113245227
Anmärkning: inbunden`

**ISBN** (ogiltigt)
`Värde: 91123457`

Om endast ett ogiltigt nummer finns i resursen och ett giltigt ISBN kan hämtas utanför resursen, lägg till bestämningen korrigerat följt av bandtyp om det behövs. 

**ISBN** (giltigt)
`Värde: 9789186589646
Anmärkning: korrigerat
Anmärkning: inbunden`

**ISBN** (ogiltigt)
`Värde: 9789186592646`

Om endast ett ogiltigt nummer finns i resursen och ett giltigt ISBN inte kan hämtas utanför resursen anges endast det ogiltiga ISBN, med en bestämning om så önskas.

**ISBN** (ogiltigt)
`Värde: 9789173538459
Anmärkning: inbunden`
 
Om en ny tryckning av en manifestation med ett tiosiffrigt ISBN har ett ogiltigt trettonsiffrigt ISBN, ange det korrigerade trettonsiffriga numret i ett nytt fält med bestämningen korrigerat. I fältet för ogiltigt ISBN läggs det ogiltiga numret, med angivande av vilken/vilka tryckningar det avser som bestämning.

**ISBN** (giltigt, tiosiffrigt)
`Värde: 9163840383`

**ISBN** (giltigt, trettonsiffrigt, korrigerat)
`Värde: 9789163840388
Anmärkning: korrigerat`

**ISBN** (ogiltigt)
`Värde: 9789163840368
Anmärkning: 3.-4. Tryckningen`

Om resursen består av två eller flera delar och det finns en identifikator för resursen som helhet liksom för resursens individuella delar, är Librispraxis att ange identifikatorn för hela resursen och för de enskilda delarna (det vill säga att tillämpa det valfria tillägget, RDA 2.15.1.5). Ange den identifikator som hör till instansen/manifestationen som katalogiseras som giltig, och den andra som ogiltig (det vill säga felaktig/ogiltig/icke hörande till instansen/manifestationen). 

**ISBN** (giltigt, tillhörande instansen/manifestationen som katalogiseras)
`Värde: 9789197841214
Anmärkning: inbunden`
**ISBN** (ogiltigt, tillhörande hela resursen) 
`Värde: 9789197841207
Anmärkning: del 1-2`

För resurser med enbart gemensamt ISBN läggs det gemensamma numret i alla delarna i fältet för ogiltigt ISBN. Lägg till en bestämning i Anmärkning.

**ISBN** (ogiltigt, tillhörande hela resursen)
`Värde: 9140635422
Anmärkning: tillsammans med 3 andra böcker`

## ISBN på inklistrad etikett
Det finns två olika fall av ISBN på inklistrad etikett:  

1. När ISBN endast finns på en inklistrad etikett (och inte tryckt i resursen) anges ISBN som korrekt. Komplettera med en Anmärkning.

**ISBN**
`Värde: 9789163915871
Anmärkning: kartonnage`

**Anmärkning**
`Benämning: ISBN på inklistrad etikett`

2. När ett ISBN på en inklistrad etikett är avsett att ersätta manifestationens ursprungliga ISBN, till exempel när en restupplaga har köpts upp av annat förlag och det förlaget har klistrat på en etikett med ett nytt ISBN, ange detta ISBN i ett nytt fält för ogiltigt ISBN i posten för den ursprungliga manifestationen. Lägg till eventuella utgivningsuppgifter från etiketten som bestämning. Gör också en Anmärkning, till exempel:

**ISBN**
`Värde: 9789170053900
Anmärkning: häftad`

**ISBN** (ogiltigt)
`Värde: 978918251005
Anmärkning: ID föslag`

**Anmärkning**
`Benämning: Senare tilldelat ISBN från annat förlag, på inklistrad etikett: ISBN 9789198251005`

## Förpackningar och ISBN

### Olika ISBN i publikation och på förpackning

Publikationer med eventuella tillbehör som ligger i en förpackning (t.ex. låda eller skyddskassett) där publikationen har ett ISBN och förpackningen ett annat ISBN, får två ISBN-fält, med bestämningar. Lägg ISBN för den manifestation som katalogiseras i fältet för giltigt ISBN och ISBN för förpackningen i fältet för ogiltigt ISBN. Formulera bestämningen för förpackningen med innehåll enligt konstruktionen: ”tillsammans med x i låda/skyddskassett”. Förpackningen beskrivs i första hand med någon av termerna:

* låda (= förpackning med lock) eller 
* skyddskassett (= specialgjort skyddsfodral eller skyddsbox för böcker med åtminstone en öppen sida (boken/böckerna skjuts in i kassetten)).

Om ingen av dessa termer är tillämplig kan annan term användas. 

Använd samma term i bestämningen och i övriga berörda fält i posten, t.ex. i fältet för mått. 

**ISBN** (giltigt, tillhörande instansen/manifestationen som katalogiseras)
`Värde: 9789129687705
Anmärkning: inbunden`

**ISBN** (ogiltigt, tillhörande förpackningen)
`Värde: 9789129686685
Anmärkning: tillsammans med tygkatt i låda`

**Mått**
`Benämning: 24 cm i låda 25 x 20 x 7 cm`

Om lådan/skyddskasetten har en egen titel, redovisa denna titel som en Varianttitel.

## Tidigare utgiven publikation i ny förpackning

Ibland händer det att en redan katalogiserad manifestation ges ut på nytt sätt vid ett senare tillfälle. Ofta handlar det om att publikationen förpackas med tillbehör i en låda eller tillsammans med andra publikationer i en skyddskassett. Lägg i sådana fall till den nya förpackningens ISBN med bestämning i ett nytt ISBN-fält (ogiltigt), i den befintliga bibliografiska posten för manifestationen och lägg till en bestämning. Formulera bestämningen för förpackningen med innehåll enligt konstruktionen: ”tillsammans med x i låda/skyddskassett”.  Komplettera med en förklarande 500-anmärkning.

Anmärkningen i fält 500 kan se olika ut i olika fall, beroende på vad som behöver förklaras:

**ISBN** (giltigt, tillhörande instansen/manifestationen som katalogiseras)
`Värde: 9789174056976
Anmärkning: inbunden`

**ISBN** (ogiltigt, tillhörande förpackningen)
`Värde: 9789129689884
Anmärkning: tillsammans med 3 plastfigurer i låda`

## Utgivning

**Plats**
`Benämning: Stockholm`

**Agent**
`Benämning: Rabén & Sjögren`

**Datum**
`2009`

**Anmärkning**
`Benämning: 5. tr., 2013 utgiven med 3 plastfigurer i låda`

**ISBN** (giltigt, tillhörande instansen/manifestationen som katalogiseras)
`Värde: 9789174056976
Anmärkning: inbunden`

**ISBN** (ogiltigt, tillhörande förpackningen)
`Värde: 9789174058567
Anmärkning: tillsammans med 2 andra böcker i skyddskasett`

**Utgivning**

**Plats**
`Benämning: Malmö`

**Agent**
`Benämning: Egmont Kärnan`

**Datum**
`2012`

**Anmärkning**
`Benämning: Skyddskasett, med titel: Sunes bästisar! :presentbox med tre Suneböcker, utgiven 2013 av Egmont Kids media.`

## Andra identifikatorer för manifestationen än ISBN

Om det inte finns ett ISBN, ange någon annan identifikator från valfri källa. Föredra identifikatorer från internationellt erkända system. Sådana identifikatorer kan även anges utöver ISBN om det bedöms viktigt för identifikation eller åtkomst. Följ instruktionerna i RDA 2.15. 

## Upplageuppgift, RDA 2.5

Upplagebeteckning och påföljande upplagebeteckning är kärnelement. Övriga underelement är valfria. Samtliga underelement anges i fältet för upplageuppgift med lämplig ISBD-interpunktion.

Återge upplageuppgiften så som den förekommer i resursen, dock inte nödvändigtvis när det gäller stora och små bokstäver eller interpunktion, se dokumentet ”Transcription” - RDA 1.7. Förkortningar används endast om de förekommer i källan som uppgiften hämtas från.

Återge inte en uppgift som är relaterad till tryckning eller antal exemplar av en viss upplaga som upplageuppgift. Då det är tveksamt om en uppgift är att betrakta som upplageuppgift, ska ord som utgåva, upplaga, nummer, version (eller deras motsvarigheter på andra språk) uppfattas som tecken på att uppgiften är en upplageuppgift, och då behandlas som en sådan. Ta inte med uppgift om oförändrad tryckning som står tillsammans med upplageuppgiften såvida inte uppgiften om tryckning är en oskiljaktig del av upplageuppgiften, d.v.s. är grammatikaliskt sammanbunden.

Om en resurs saknar upplageuppgift men det är känt att betydliga ändringar från tidigare upplagor gjorts, tillämpa det valfria tillägget och lägg till en upplageuppgift, om det är viktigt för identifikation och åtkomst, RDA 2.5.1.2. Ange uppgiften inom klammer på huvudtitelns språk. För resurser med huvudtitel på svenska, följ Svenska skrivreglers rekommendation och använd termen “upplaga” för förändrat innehåll.
`[Utökad upplaga]`

## Upplagebeteckning

Upplagebeteckning är ett kärnelement. Hämta uppgiften från följande källor (i denna ordning): 
1. samma källa som huvudtiteln
2. en annan källa inom resursen
3. en annan av de källor som specificeras i RDA 2.2.4

`Ny udgave`

`*** ed.`

`1st ed.`

`Svensk utgåva [när uppgiften utgör upplageuppgift]`

`Första upplagans första tryckning`

`Uppl. 1`

Men:

I källan: Upplaga 1:1 
`Upplaga 1`

I källan: First edition, first printing
`First edition`

Om upplageuppgiften består av en bokstav eller bokstäver och/eller en siffra eller siffror utan påföljande ord, tilläggs tillämpligt ord, RDA 2.5.2.3.
`3 [upplagan]`

Återge tal angivna med siffror eller med bokstäver som de återfinns i resursen. Eftersom upplageuppgift inte är med i listan i RDA 1.8.1 gäller inte specialreglerna i RDA 1.8.2-1.8.5. Även romerska siffror återges alltså som de återfinns i resursen.
`Version IV`

### Upplagebeteckning på mer än ett språk eller i mer än en skriftart

Om upplagebeteckningen förekommer i källan på mer än ett språk eller i mer än en skriftart, återge den uppgift som är på huvudtitelns språk eller i dess skriftart. Om detta kriterium inte går att tillämpa, återge den upplagebeteckning som kommer först i källan, RDA 2.5.2.4.

### Upplagebeteckning som är en del av huvudtitel, etc.

Upplagebeteckning som är en integrerad del av huvudtitel, övrig titelinformation eller upphovsuppgift, eller grammatiskt sammanhängande med något av dessa element ska anges tillsammans med det element som det är en del av. Ange det inte igen som en upplagebeteckning, RDA 2.5.2.6.
`Tenth anniversary edition of Economic justice for all`
`The compact edition of the Oxford English Dictionary`

Upplagebeteckning som är en integrerad del av huvudtitel, övrig titelinformation eller upphovsuppgift, eller grammatiskt sammanhängande med något av dessa element ska anges tillsammans med det element som det är en del av.

## Upplagespecifik upphovsuppgift
_Ej kärnelement._

NB-praxis: Obligatoriskt att ange upplagespecifik upphovsuppgift (RDA 2.5.4).

Upplagespecifika upphovsuppgifter består av en upplagebeteckning och en upphovsuppgift som båda finns i samma källa och relaterar till just den upplagan. Det är endast bidragsgivare (aldrig skapare) som kan vara upplagespecifika. Hämta alltid upplagespecifika upphovsuppgifter från samma källa som upplagebeteckningen.

I källan, på insidan av bakre omslag: ”Tredje upplagan, reviderad och korrigerad av Maja Lindblad”
`Tredje upplagan / reviderad och korrigerad av Maja Lindblad`

## Påföljande upplagebeteckning
_Påföljande upplagebeteckning är ett kärnelement._

Om en resurs betecknas som en återutgivning som innehåller förändringar i förhållande till en viss upplaga, anges denna uppgift efter upplagebeteckningen, RDA 2.5.6.3. Hämta påföljande upplagebeteckning från följande källor (i denna ordning): samma källa som upplagebeteckningen, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4.
`250 #a 6. upplagan, rättad och reviderad`

### Påföljande upplagebeteckning på mer än ett språk eller i mer än en skriftart

Om påföljande upplagebeteckning förekommer i källan på mer än ett språk eller i mer än en skriftart, återge den uppgift som är på huvudtitelns språk eller i dess skriftart. Om detta kriterium inte går att tillämpa, återge den påföljande upplagebeteckning som kommer först i källan, RDA 2.5.6.4.

### Upphovsuppgifter som hänför sig till påföljande upplagebeteckning
_Ej kärnelement._

NB-praxis: Obligatoriskt att ange upphovsuppgifter som hänför sig till påföljande upplagebeteckning (RDA 2.5.8).

## Utgivning (RDA 2.8)
_Utgivningsort, utgivare och är kärnelement._ 

RDA har separata element för utgivnings-, distributions- och tillverkningsuppgifter och dessa anges i separata fält. Om uppgifterna hämtas utanför resursen ska varje element klamras för sig, RDA Appendix D. 1.

**Plats**
`Benämning: [Storstad]`

**Agent**
`Benämning:[Förlaget]`
**Datum**
`[1989]`

## Utgivningsort

Hämta uppgift om utgivningsort från följande källor (i denna ordning): samma källa som utgivarens namn, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4.

Ange utgivningsort som den förekommer i källan, följ de generella riktlinjerna i dokumentet ”Transcription" - RDA 1.7.

Librispraxis är att följa det andra valfria tillägget i RDA 2.8.2.3, d.v.s. att lägga till namn på land, delstat, provins etc. om det behövs för identifiering eller åtkomst. Om uppgiften hämtas utanför resursen ska den klamras. Använd svensk namnform om sådan finns, annars den officiella inhemska formen. Använd förkortningarna av namn på delstater, provinser och territorier etc. i Australien, Förenta staterna och Kanada enligt RDA Appendix B.11. Förkorta inte namn på länder (se dokumentet Appendix i RDA).

**Plats**
Ortnamn och land förekommer i resursen
`Benämning: Tolworth, England`

**Plats**
Ortnamn och delstat förekommer i resursen
`Benämning: Cambridge, Mass.`

**Plats**
Enbart ortnamnet förekommer i resursen
`Benämning: Santiago [Chile]`

**Plats**
Enbart ortnamnet förekommer i resursen
`Benämning: Kiruna`

Om fler än en utgivningsort förekommer i källan är endast den första kärnelement enligt RDA. Librispraxis är att om en utgivare har avdelningar på flera orter, och dessa redovisas i resursen, ska den först nämnda anges. Utöver det anges därpå följande ort som särskilt framhålls genom källans layout eller typografi. Om den först nämnda orten och den särskilt framhävda orten inte är svensk, anges även den första av alla därpå följande svenska orter. Om en resurs har flera utgivare återges den först nämnda utgivarens ort. Dessutom anges påföljande utgivares orter (om de avviker från den redan nämnda orten):

* När en påföljande institution klart framhävs som huvudagent (huvudutgivare) genom layout eller typografi, anges även orten för den särskild framhävda utgivaren.
* När påföljande utgivare är svensk men inte den först nämnda.
* I de fall då utgivaren har ett svenskt ISBN (978-91-) men endast en utländsk ort står i publikationen anges även den svenska utgivningsorten inom klammer (söks fram via Svenska ISBN-registret).

**Plats**
`Benämning: Stockholm`

**Plats**
`Benämning: Malmö
Orten Malmö är framhävd genom källans layout`

**Agent**
`Benämning: Förlaget`

**Datum**
`[2008]`

**Plats**
`Benämning: Oslo`

**Agent**
`Benämning: Samlaget`

**Plats**
`Benämning: Stockholm`

**Agent**
`Benämning: Läsrörelsen`

**Datum**
`[2008]`

**Utgivningsland**
Påföljande utgivare är svensk men inte den först nämnda.
`Norge Sverige`	

### Utgivningsort på mer än ett språk eller i mer än en skriftart

Om namnet på utgivningsorten förekommer i källan på mer än ett språk eller i mer än en skriftart, ange den uppgift som är på huvudtitelns språk. Om detta kriterium inte kan tillämpas, återge den uppgift som kommer först i källan, RDA 2.8.2.5.

### Uppgift om utgivningsort saknas i resursen

Om ingen utgivningsplats är angiven i resursen, RDA 2.8.2.6, lägg till utgivningsplatsen eller den troliga utgivningsplatsen inom klammer enligt följande prioritetsordning:

1. Känd ort [Stockholm]
2. Trolig ort [Stockholm?]
3. Känt land, känd stat, provins etc. [Sverige]
4. Troligt land, stat, provins etc. [Sverige?]
5. Okänd ort [Utgivningsort okänd]

## Utgivarnamn

Hämta uppgift om utgivarens namn från följande källor (i denna ordning): samma källa som huvudtiteln, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4.

Om fler än en utgivare förekommer i källan är endast den första kärnelement i RDA. Librispraxis är att dessutom ange påföljande utgivare när en påföljande institution klart framhävs som huvudutgivare genom layout eller typografi eller när påföljande utgivare är svensk men inte den först nämnda.

NB-praxis: Följ ovanstående Libris-praxis men ange även påföljande utgivare när denna (men inte den första utgivaren) utgörs av ett förlag som står i klartext i resursen. Påföljande utgivare kan vid behov anges även i andra fall. Katalogisatören avgör.  

Återge utgivarens namn som det förekommer i källan, följ de generella riktlinjerna i dokumentet ”Transcription" - RDA 1.7. Om första och påföljande utgivare är förenade till en enda uppgift, ange dem så.

**Agent**
`Benämning: Bonnier fakta i samarbete med Sjuan och TV4-gruppen`

Tillämpa generellt inte det valfria tillägget att lägga till en term som anger en utgivares funktion om det inte behövs en mer specifik funktionsuppgift än den som redan angetts i fält 264, andra indikatorn.

Tillämpa generellt inte den valfria uteslutningen i RDA 2.8.4.3, att utesluta hierarkiska nivåer i utgivarens organisation.

**Agent**
`Benämning: Avdelningen för forskning och utbildning i modern svenska, Institutionen för nordiska språk, Uppsala universitet`

### Utgivarens) namn på mer än ett språk eller i mer än en skriftart

Om namnet på utgivaren förekommer i källan på mer än ett språk eller i mer än en skriftart, ange det namn som är på huvudtitelns språk. Om detta kriterium inte kan tillämpas, återge den uppgift som kommer först i källan, RDA 2.8.4.6.

### Utgivarens namn felstavat på titelsidan
Titelsidan är föredragen källa för utgivarnamn. Om det finns en titelsida och utgivarens namn är felstavat där, återge utgivarnamnet som det förekommer på titelsidan och gör en anmärkning om det korrekta namnet, se Anmärkning om utgivningsuppgift.

### Uppgift om utgivare saknas i resursen

Om uppgift om utgivare saknas i resursen och inte kan hämtas från någon annan källa ange [utgivare okänd], RDA 2.8.4.7.

## Utgivningstid
Utgivningstid är ett kärnelement. Librispraxis är att tillämpa det valfria tillägget i RDA 2.8.6.3 om uppgiften inte är angiven enligt gregoriansk eller juliansk kalender.

Hämta uppgift om utgivningstid från följande källor (i denna ordning): samma källa som huvudtiteln, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4.

Följ riktlinjerna i dokumenten Tal (siffror och bokstäver - RDA 1.8 och Tidsangivelser - RDA 1.9.

Om utgivningstid inte kan identifieras, men distributionstid, tillverkningstid eller copyrightår finns angivet i resursen, är Librispraxis att hämta uppgiften om utgivningstid från någon av dessa och ange den inom klammer i elementet för utgivningstid. Välj i första hand distributionstiden, i andra hand tillverkningstiden och i tredje hand copyrightåret. När utgivningstiden hämtas från någon av dessa uppgifter ska distributionstid/tillverkningstid/copyrightår även anges i respektive element - distributionstid/tillverkningstid/copyrightår. 

Om varken distributionstid/tillverkningstid/copyrightår kan identifieras, ange en ungefärlig utgivningstid enligt instruktionerna i RDA 1.9.2. Ange i sista hand [utgivningstid okänd].

### Utgivning

**Plats**
`Benämning: Stockholm`
**Agent**
`Benämning: Brå`
**Datum**
`2015`

### Tillverkning

Endast tillverkningstid finns i resursen. Den anges dels inom klammer i fältet för datum under utgivning och dels i fältet för datum under tillverkning.

`Datum`
**2015**

_Producerad år ..._ i tryckta monografier betraktas som tillverkningstid.

## Fiktiv eller felaktig utgivningstid

Om det är känt att utgivningstiden som är angiven i resursen är fiktiv eller felaktig, ange den utgivningstid som står i resursen fältet för datum och gör en anmärkning om den korrekta eller troliga utgivningstiden, RDA 2.8.6.3. Om korrekt uppgift om distributionstid/tillverkningstid/copyrightår finns i resursen anges denna i fältet för datum med tillämplig andraindikator. I fält 008 anges den korrekta utgivningstiden hämtad från anmärkning eller distributionstid/tillverkningstid/copyrightår. 

### Utgivning

**Datum**
`2007`

**Anmärkning**
Känt att utgivningsåret är felaktigt
`Benämning: Felaktigt utgivningsår i publikationen, skall vara 2017`

### Utgivning

**Datum**
`2006`

### Tillverkning

**Datum**
Korrekt tillverkningstid finns i resursen
`2006`

## Distribution (RDA 2.9)

### Distributionsort

_Distributionsort är inte ett kärnelement._ 

Librispraxis är att endast ange distributionsort om den framgår av resursen. Trolig eller [distributionsort okänd] anges inte.
För källor, se RDA 2.9.2.2.

För instruktioner om hur man anger distributionort, se RDA 2.9.2.3.

Tillämpa det andra valfria tillägget men inte det första.

### Distributörsnamn

_Distributörsnamn är inte ett kärnelement._ 

Librispraxis är att endast ange distributörens namn om det framgår av resursen. Trolig eller [distributör okänd] anges ej.
För val av källa, se RDA 2.9.2.2.

För instruktioner om hur man anger distributörsnamn, se RDA 2.9.4.3. Tillämpa generellt inte den valfria uteslutningen.
Tillämpa inte det valfria tillägget i RDA 2.9.4.4 om det inte behövs en mer specifik funktionsuppgift.

### Distribution
**Plats**
`Benämning: Stockholm`
**Agent**
`Benämning: Avanco`

### Distributionstid

_Distributionstid är inte ett kärnelement._ 

Librispraxis är att hämta uppgift om utgivningstid från distributionstiden när denna finns angiven i resursen och utgivningstiden inte kan identifieras. Distributionstiden anges i dessa fall dels inom klammer i fältet för datum under utgivning, dels utan klammer i fältet för datum under distribution.

För val av källa, se RDA 2.9.6.2.

För instruktioner om hur man anger distributionstid, se RDA 2.9.6.3. Följ även riktlinjerna i dokumentet: Tal (siffror och bokstäver) - RDA 1.8. Tillämpa det valfria tillägget.

Om distributionstiden angivits i källan i form av ett kronogram, RDA 2.9.6.4, tillämpa alternativet och ange uppgiften med arabiska siffror enligt den gregorianska eller julianska kalendern. Klamra. Ange kronogrammet i en anmärkning om det är viktigt för identifiering.

## Tillverkning (RDA 2.10)

### Tillverkningsort

_Tillverkningsort är inte ett kärnelement och inte obligatoriskt enligt Librispraxis._

NB-praxis: Obligatoriskt att ange tillverkningsort om svensk tillverkningsort och/eller svensk tillverkare finns i resursen. Följ vid behov anvisningarna i RDA 2.10.2.6 för att ange tillverkningsort.

För val av källa, se RDA 2.10.2.2.

För instruktioner om hur man anger tillverkningsort, se RDA 2.10.2.3. Tillämpa det andra valfria tillägget men inte det första.

### Tillverkarnamn

_Tillverkarnamn är inte ett kärnelement och inte obligatoriskt enligt Librispraxis._

NB-praxis: Obligatoriskt att ange tillverkarnamn om svensk tillverkare och/eller svensk tillverkningsplats finns i resursen. Följ anvisningarna i RDA 2.10.4.7 och ange [tillverkare okänd] när enbart svensk tillverkningsplats finns i resursen.

För val av källa, se RDA 2.10.4.2.

För instruktioner om hur man anger tillverkarnamn, se RDA 2.10.4.3. Tillämpa generellt inte den valfria uteslutningen. Tillämpa inte det valfria tillägget i RDA 2.10.4.4 om det inte behövs en mer specifik funktionsuppgift.

Att omslaget är tryckt av annat tryckeri än inlagan redovisas inte. Det är tryckeriet av inlagan som är leveransskyldigt.

### Tillverkningstid

_Tillverkningstid är inte ett kärnelement._ 

Librispraxis är att hämta uppgift om utgivningstid från tillverkningstiden när denna finns angiven i resursen och utgivningstid eller distributionstid inte kan identifieras. Tillverkningstiden anges i dessa fall dels inom klammer i fältet för datum under utgivning, dels utan klammer i fältet för datum under tillverkning.

För val av källa, se RDA 2.10.6.2.

För instruktioner om hur man anger tillverkningstid, se RDA 2.10.6.3. Följ även riktlinjerna i dokumentet: ”Tal (siffror och bokstäver) - RDA 1.8”. Tillämpa det valfria tillägget.

Om tillverkningstiden angivits i källan i form av ett kronogram, RDA 2.10.6.4, tillämpa alternativet och ange uppgiften med arabiska siffror enligt den gregorianska eller julianska kalendern. Klamra. Ange kronogrammet i en anmärkning om det är viktigt för identifiering.

Om både utgivningstid och tillverkningstid finns i resursen och åren skiljer sig från varandra anges båda, i fältet för datum under utgivning respektive i fältet för datum under tillverkning. 

### Copyrightår (RDA 2.11)
_Copyrightår är inte ett kärnelement._

Librispraxis är att ange copyrightår i fältet för datum under copyright när uppgift om utgivningstid, distributionstid och tillverkningstid saknas i resursen (eller när utgivningstiden i resursen är fiktiv/felaktig). Det gäller endast copyrightår som hör till den manifestation som katalogiseras. Om copyrightåret kan antas vara samma år som utgivningsåret anges copyrightåret inom klammer i fältet för datum under utgivning. I annat fall suppleras utgivningstid enligt anvisningarna i dokumentet Tidsangivelser - RDA 1.9.

Copyrightår ska föregås av symbolen © eller fonogramsymbolen ?. Om symbolen inte kan återges ska tiden föregås av copyright eller phonogram copyright.

### Utgivning
**Datum**
`[2015]`

### Copyright
Endast copyrightår finns i resursen
**Datum**
`©2015`

### Utgivning
**Datum**
`[2015]`
### Copyright
Utgivningstiden är känd och suppleras enligt anvisningar i dokumentet Tidsangivelser – RDA 1.9. Copyrightår är det enda som finns i resursen.
**Datum**
`©2001`

## Serieuppgift (RDA 2.12)

En serieuppgift är en uppgift som identifierar serien till vilken resursen hör och numreringen av resursen i serien. 
Elementet serieuppgift har ett antal underlement. Huvudtitel till serie, Numrering inom serie, Huvudtitel till underserie och Numrering inom underserie är kärnelement. Series ISSN och Underseries ISSN är obligatoriska element enligt Librispraxis. 

Om resursen ingår i en serie, återge serieuppgiften som den förekommer i källan (RDA 1.7). 

**Serieuppgift**
Huvudtitel till serie, Series ISSN ; Numrering inom serie
`Basic readings in culture and aestetics, 2002-6463 ; 1`
**Serieuppgift**
Huvudtitel till serie ; Numrering inom serie. Huvudtitel till underserie ; Numrering inom underserie 
`Department of State publication ; 7846. Department and Foreign Service series ; 128`

Om resursen ingår i flera serier, återge serieuppgifterna i separata fält.

Vid osäkerhet om en uppgift är en serieuppgift eller ej kan uppgiften citeras i en anmärkning:

**Anmärkning**
Om varje titel i en serie verk inleds med samma fras (till exempel Lätta fakta om ..., Allt du behöver veta om ...) betraktas inte frasen som en serieuppgift såvida inte frasen även förekommer separat, som en serieuppgift, i en annan källa i resursen.
`Benämning: ”An Evangelical Theological Society publication”`

## Huvudtitel till serie

_Huvudtitel till serie är ett kärnelement._

En alternativtitel behandlas som del av huvudtiteln.

Hämta huvudtitel till serie från följande källor (i prioriteringsordning):

* titelsidan för serien
* annan källa i resursen (se RDA 2.2.2)
* en av de andra källorna som specificeras i RDA 2.2.4

Det innebär att uppgift om huvudtitel till serie som hämtas från löst skyddsomslag inte behöver klamras (se RDA 2.2.2).

NB-praxis: Hämta huvudtitel till serie från följande källor (i prioritetsordning):

* titelsidan för serien
* monografins titelsida
* Annan källa i resursen (i prioriteringsordning):
   * omslag, eller löst skyddsomslag utgivet med resursen
   * övrig källa inom resursen. Föredrag källor där informationen är formellt presenterad
* en av de övriga källorna som specificeras i RDA 2.2.4

Ange huvudtitel till serie genom att följa instruktionerna för att ange titlar i RDA 2.3.1, se även Huvudtitel ovan. Ta med inledande artiklar.

**Serieuppgift**
`En kalasbok från Alfabeta`

Återge numrering eller tidsangivelser som är grammatisk sammanbundna med huvudtiteln till serien som en del av huvudtiteln (RDA 2.12.2.3).

Återge en huvudtitel till serie som hämtats från en källa utanför resursen inom klammer (RDA 2.2.4).

Om serietiteln i resursen anges på mer än ett språk eller i mer än en skriftart, välj som huvudtitel titeln på språket eller i skriftarten för huvuddelen av resursens innehåll.

## Parallell huvudtitel till serie

Parallell huvudtitel till serie är huvudtiteln till serien på ett annat språk eller i en annan skriftart. Uppgift om parallell huvudtitel till serie hämtas från valfri källa i resursen (RDA 2.12.3.2).

Parallell huvudtitel till serie är inte ett kärnelement. Om uppgiften anges, ska den föregås av ISBD-interpunktion (likhetstecken).
Om parallella huvudtitlar anges och numreringen också förekommer på mer än ett språk eller i mer än en skriftart, anges numreringen efter respektive huvudtitel.

**Serieuppgift**
Huvudtitel till serie ; Numrering inom serie = Parallell huvudtitel till serie ; Numrering inom serie 
`Schriften zum 100-jähringen Jubiläum der Eisenbahnfährlinie Sassnitz-Trelleborg ; 3 = Skrifter till 100-årsjubileum på tågfärjeleden Trelleborg-Sassnitz ; 3`

Om numreringen endast förekommer en gång, ange den efter den huvudtitel den hör till, eller efter den sista huvudtiteln om den hör till alla, mer än en eller till ingen av huvudtitlarna.

**Serieuppgift**
Huvudtitel till serie, ISSN till serie = Parallell huvudtitel till serie = Parallell huvudtitel till serie ; numrering inom serie
`Helsingin kaupungin tietokeskuksen tutkimuksia, 0788-1533 = Helsinfors stads faktacentrals undersökningar = Studies published by the City of Helsinki Information Management Centre ; 1993:9`

### Övrig titelinformation för serie

Övrig titelinformation för serie är information som förekommer tillsammans med, och är underordnad, seriens huvudtitel.

Övrig titelinformation för serie hämtas från samma källa som huvudtiteln till serien och anges endast om den är viktig för seriens identifikation.

Uppgiften ska föregås av ISBD-interpunktion (mellanslag kolon mellanslag).

**Serieuppgift**
`Statens offentliga utredningar : SOU, 0375-250X ; 2017:42`

### Upphovsuppgift till serie

Upphovsuppgift till serie hämtas från samma källa som huvudtiteln till serien och anges endast om den är viktig för seriens identifikation. 

NB-praxis: Ange upphovsuppgifter som förekommer tillsammans med serietiteln, om de bedöms vara viktiga för seriens identifikation.
Upphovsuppgift till serie ska föregås av ISBD-interpunktion (snedstreck).

**Serieuppgift**
`Meddelande / Lövskogens vänner`

## Series ISSN

_Enligt Librispraxis är uppgiften obligatorisk._

Uppgiften ska föregås av ISBD-interpunktion (kommatecken). Ta med bindestrecket som skiljer de fyra första siffrorna från de fyra senare, men uteslut ordet "ISSN".

Hämta i första hand seriens ISSN från titelsidan, i andra hand från annan källa i resursen (se RDA 2.2.2) och i sista hand från en av de andra källorna som specificeras i RDA 2.2.4.

Om ISSN hämtas från en källa utanför resursen ska uppgiften klamras. 

**Serieuppgift**
`Umeå University medical dissertations, [0346-6612]`

Ange underseries ISSN, om det förekommer i resursen. Librispraxis är att inte tillämpa den valfria uteslutningen i RDA 2.12.8.3, utan att även ange huvudseriens ISSN om båda finns i resursen. 

Om en monografi innehållet ett ISSN som hör till en annan serie kan det citeras i en anmärkning.

**Anmärkning**
`Benämning: Titelbladets baksida: ”ISSN 2042-8057 (online)”`

## Numrering inom serie

Numrering inom serie är ett kärnelement (RDA 2.12.9). Uppgiften ska föregås av ISBD-interpunktion (mellanslag semikolon mellanslag).

**Serieuppgift**
`Tekniska nomenklaturcentralens publikationer, 0081-573X ; 67`

Hämta i första hand uppgifter om numrering från seriens titelsida, i andra hand från annan källa i resursen (se RDA 2.2.2) och i sista hand från en av de andra källorna som specificeras i RDA 2.2.4.

Ange siffor, bokstäver, andra tecken eller kombinationer av dessa med eller utan delord och/eller kronologisk beteckning som de förekommer i källan. Ange tal angivna med siffror eller bokstäver enligt de generella riktlinjerna i dokumentet Tal (siffror och bokstäver) - RDA 1.8. Återge andra bokstäver, tecken eller bokstavsgrupperingar och/eller teckengrupperingar som de förekommer i källan enligt de generella riktlinjerna i dokumentet "Transcription" - RDA 1.7. 

Librispraxis är att ersätta romerska siffror med arabiska. Alternativ 1 och 2 i RDA 1.8.2 (att återge siffror i den form de förekommer i källan) tillämpas ej.

**Serieuppgift**
I källan: del III
`... ; del 3`

Librispraxis: Ersätt tal angivna med bokstäver med siffror (RDA 1.8.3).

**Serieuppgift**
I källan: del fyra
`... ; del 4`

Ordningstal skrivs med siffror, enligt respektive språks regler (se exempel i RDA 1.8.5). Enligt Svenska skrivregler skrivs svenska ordningstal med siffror följda av kolon och ordningstalets sista bokstav, till exempel 1:a, 2:a, 3:e, 20:e numret. zvapp

**Serieuppgift**
I källan: tredje delen 
`... ; 3:e delen`

RDA skiljer sig från KRS genom att termer som är en del av seriens numrering alltid ska anges.

**Serieuppgift**
 `... ; no. 1`

För termer som är en del av seriens numrering, tillämpa riktlinjerna för stora och små bokstäver för det språk som termen är på, se RDA Appendix A och Appendix i RDA med anvisningar om tillämpning i Libris. Läs även om hur termer som är en del av seriens numrering ska anges i auktoriserade sökingångar i Del i serie.

Återge andra ord och alfabetiska beteckningar som är en del av numreringen så som de ser ut i resursen. Finns förkortningar i källan, återge dem.

**Serieuppgift**
`... ; set 1`

**Serieuppgift**
`... ; reel A-4`

**Serieuppgift**
`... ; Bd. 8`

Om beteckningen består av ett år och en sifferbeteckning som utgör en del av ett år, ange året före siffran (RDA 2.12.9.3 och RDA 2.6.2.3).

**Serieuppgift**
`... ; 2000, no. 3`

Om numreringen utgörs av både en numerisk och/eller alfabetisk beteckning och en kronologisk beteckning, ange båda, med den kronologiska beteckningen inom parentes efter den numeriska (RDA 2.12.9.4 och RDA 2.6.3.3).

**Serieuppgift**
`Årsbok för kristen humanism och samhällssyn, 1650-0113 ; 63(2001)`

**Serieuppgift**
`... ; vol. 1, nr 1(juli/augusti 2005)`

Om numreringen utgörs av mer än ett självständigt beteckningssystem, anges beteckningarna i den ordningsföljd de förekommer i primärkällan (RDA 2.12.9.7), åtskilda av mellanslag likhetstecken mellanslag.

**Serieuppgift**
`Årsbok i svensk undervisniningshistoria, 0346-8461 ; 82(2002) = 198`

Om det är känt att numreringen som förekommer i källan är felaktig, återge den som den förekommer. Gör en anmärkning med den korrekta numreringen (RDA 2.17.11.4).

**Serieuppgift**
`Moderna museets utställningskatalog ; 281`

**Anmärkning**
`Benämning: Numreringen skall vara: 202`

Om resursen saknar numrering, men innehåller en förteckning över övriga resurser i serien och dessa är numrerade, anta i allmänhet att resursen utgör nästa nummer och klamra in uppgiften. Vid tvekan ange ingen numrering. 

Inkludera ord som åtskiljer en nummersvit i serien från en annan.

**Serieuppgift**
`... ; ny serie, nr 1`

Om det är känt att flera nummersviter i serien har samma numrering och resurser med numrering inom den nya nummersviten inte åtföljs av ord, till exempel ny serie, lägg till "ny serie" eller dylikt inom klammer.  

**Serieuppgift**
`... ; [ny serie], nr 1`

## Underserie (RDA 2.12.10-2.12.17)

_Huvudtitel till underserie och numrering inom underserie är kärnelement._

Hämta i första hand uppgifterna om underserie från seriens titelsida.

Underseries ISSN är obligatorisk uppgift enligt Librispraxis. 

Tillämpa inte den valfria uteslutningen i RDA 2.12.16.3, dvs ange även huvudseriens ISSN om båda finns i resursen.
Övriga uppgifter som hör till underserie är inte obligatoriska enligt Librispraxis.

**Serieuppgift**
`Acta Wexionensia, 1404-4307 ; 31. Pedagogik`

**Serieuppgift**
`Progress in monecular and subcellular biology, 0079-6484 ; 46. Marine molecular biotechnology, 1611-6119`

## Medietyp (RDA 3.2)

Obligatoriskt enligt Librispraxis.

Källor för beskrivningen av medietyp är resursen, medföljande material eller förpackning/behållare. Uppgifter kan även hämtas utanför resursen.
Om ingen av termerna i listan är lämplig, välj “annan” (x). Om medietypen/medietyperna inte lätt kan bestämmas, välj “ospecificerad” (z).

Om resursen består av mer än en medietyp är Librispraxis att ange den medietyp som är tillämplig på den huvudsakliga delen av resursen. Ange inte medietyp för medföljande material av uppenbart underordnad karaktär.

Om resursen består av flera likvärdiga delar (kombinerat material) ange medietyp för alla delarna.

## Bärartyp (RDA 3.3)

_Bärartyp är ett kärnelement._

Källor för beskrivningen av bärare är resursen, medföljande material eller förpackning/behållare. Uppgifter kan även hämtas utanför resursen.

Om ingen av termerna i listan är lämplig, välj “annan” (nz). Om bärartypen/bärartyperna inte lätt kan bestämmas, välj “ospecificerad” (zu).

Om resursen består av mer än en bärartyp är Librispraxis att ange den bärartyp som är tillämplig på den huvudsakliga delen av resursen. Ange inte bärartyp för medföljande material av uppenbart underordnad karaktär.

Valfritt tillägg: Om bärarna ligger i en behållare/förpackning, namnge behållaren och dess mått.

Librispraxis: Katalogisatören avgör om det valfria tillägget ska tillämpas.

NB-praxis: Tillämpa det valfria tillägget.

## Omfång (RDA 3.4)

Omfång är ett kärnelement om resursen är komplett eller om det totala antalet fysiska enheter är känt.

Omfång är antalet och typen av enheter (t.ex. volym) och underenheter (t.ex. sidor) en resurs består av.

Använd hela resursen (eller medföljande material eller behållare) som källa. Om det behövs kan kompletterande information hämtas utanför resursen.

Ange resursens omfång genom att ange antalet och typen av enheter den består av. För typen kan en passande term från listan för bärartyper i RDA 3.3.1.3 (bärartyperna på svenska) användas. Alternativ: Använd en vanligt förekommande term (inklusive varumärken, om det är tillämpligt):

1. om bäraren inte finns i listan 
eller
2. som ett alternativ till en term i listan

Librispraxis: Tillämpa alternativ a) och använd en vanligt förekommande term om bäraren inte finns i listan. För fysiska digitala resurser ska alternativ 2.) tillämpas. Använd t.ex. CD, CD-ROM, DVD, DVD-ROM och diskett i stället för term från listan.
RDA har särskilda instruktioner för bland annat textresurser, se RDA 3.4.5 och nästa stycke.

## Omfång för text (RDA 3.4.5)

Riktlinjerna är uppdelade på resurser som består av en enhet och resurser som består av flera enheter. 
Texten nedan gäller för resurser som består av en enhet.

## Enstaka volym med numrerade sidor, blad eller spalter 

För en resurs som består av en volym, ange omfång i antal sidor, blad eller spalter i enlighet med de numeriska eller alfabetiska sviterna i volymen (RDA 3.4.5.2). 

Tillämpa följande generella riktlinjer:
* Om volymen är numrerad i termer av sidor, ange antal sidor.
* Om volymen är numrerad i termer av blad, ange antal blad.
* Om volymen består av sidor med mer än en spalt per sida och spalterna är numrerade, ange antal spalter.
* Om volymen består av sviter av blad och sidor eller sidor och numrerade spalter, eller blad och numrerade spalter, ange varje svit för sig.

Om volymen är numrerad som blad men har text på båda sidor, se RDA 3.4.5.5 eller förklara i en anmärkning, se RDA 3.21.2.11.

**Omfång**
`Benämning: 48 blad, det vill säga 96 sidor`

eller

**Omfång**
`Benämning: 48 blad`

**Anmärkning**
`Benämning: Numrerade blad med tryck på båda sidor`

Vissa undantag från regeln finns. För lösbladspublikationer som uppdateras, _ange 1 volym_, följt av lösblad inom parentes:

**Omfång**
`Benämning: 1 volym (lösblad)`

###Enstaka volym med onumrerade sidor, blad eller spalter 

RDA 3.4.5.3 ger tre alternativ:
* Räkna alla sidor, blad, spalter och ange t.ex. ”8 onumrerade sidor”. Använd ”blad” om de har tryck endast  på ena sidan.
* Ange ett uppskattat antal: ”cirka 400 sidor”. Använd ”blad” om de har tryck endast  på ena sidan.
* Ange t.ex. ”1 volym (opaginerad)”. 

Librispraxis: Om antalet sidor, blad eller spalter lätt kan fastställas, tillämpa alternativ a). Om antalet inte lätt kan fastställas, tillämpa alternativ b) eller c). Katalogisatören avgör.

NB-praxis: Vid primärkatalogisering, tillämpa alternativ a) för resurser under 100 sidor. För resurser över 99 sidor tillämpa c).

### Enstaka volym med numrerade och onumrerade sviter 

Om resursen består av både numrerade och onumrerade sviter av sidor, blad eller spalter, bortse från de onumrerade utom när:

* den onumrerade sviten utgör en väsentlig del av resursen (Librispraxis: med väsentlig del av resursen avses mer än 25%), se även RDA 3.4.5.8,
eller
* den onumrerade sviten inkluderar sidor etc. som det refereras till i en anmärkning.
(RDA 3.4.5.3.1)
När onumrerade sviter anges, uppge antingen:
* det exakta antalet följt av ”onumrerade sidor/blad” etc.
* ett uppskattat antal, föregånget av ”cirka”
* ”onumrerad svit av sidor/blad” etc.

Librispraxis: Om en resurs sidor eller blad är onumrerade men sidantalet lätt kan fastställas tillämpa alternativ a). Om sidantalet inte lätt kan fastställas, tillämpa alternativ b).

**Omfång**
`Benämning: 33 blad, 31 onumrerade blad`

**Omfång**
`Benämning: 8, vii, cirka 300, 73 sidor`

**Omfång**
`Benämning: 27 sidor, onumrerad svit av blad`

**Omfång**
`Benämning: 8 onumrerade sidor, 155 sidor`

### Ändring av numrering inom en svit 

Om numreringen ändras inom en svit (t.ex. från romerska till arabiska siffror), bortse från numreringen i svitens första del (RDA 3.4.5.4).

**Omfång
Sidorna numrerade: i-xii, 13-176
`Benämning: 176 sidor`

**Sidor etc. numrerade som del i en större svit**
Om sidorna etc. numrerats som del i en större svit , ange sidornas etc. första och sista nummer, föregångna av lämplig term (RDA 3.4.5.7).

**Omfång**
`Benämning: Sidorna 713-797`

### Komplicerad och oregelbunden paginering

RDA 3.4.5.8 ger tre alternativ:

1. Ange det totala antalet sidor etc., följt av ”med varierande paginering/bladnumrering”
2. Ange den komplicerade pagineringen etc. exakt som den är
3. Ange 1 volym (varierande paginering)

Librispraxis: Om en resurs paginering är komplicerad eller oregelbunden men sidantalet lätt kan fastställas tillämpa alternativ 1. Om sidantalet inte lätt kan fastställas, tillämpa alternativ 3.

Onumrerade planschblad eller planschsidor (RDA 3.4.5.9)

Ange omfånget för en onumrerad svit av planschblad eller planschsidor om:

1. den onumrerade sviten utgör en väsentlig del av resursen (Librispraxis: med väsentlig del av resursen avses mer än 25%), se även RDA 3.4.5.8,
eller
2. den onumrerade sviten inkluderar sidor etc. som det refereras till i en anmärkning.
3. Informationen är viktig för identifikation och urval.

När onumrerade sviter anges, uppge antingen:

1. det exakta antalet (om uppgiften är lätt åtkomlig) följt av ”onumrerade planschsidor/blad” etc.
2. ett uppskattat antal, föregånget av ”cirka” och följt av ”planschblad” etc.

Librispraxis: Om en resurs har onumrerade planschsidor/blad men antalet lätt kan fastställas tillämpa alternativ 1. Om sidantalet inte lätt kan fastställas, tillämpa alternativ 2.

### Planschblad eller planschsidor 

Om planschbladen eller planschsidorna i en resurs inte ingår i numreringen av en eller flera sviter av blad eller sidor med text etc., ange antalet planschblad eller planschsidor sist i sviten av pagineringar. Ange antalet planschblad eller planschsidor efter de paginerade sviterna oavsett om planscherna återfinns samlade eller utspridda i resursen (RDA 3.4.5.9).

Numrerade planschblad eller planschsidor:

**Omfång**
`Benämning: 246 sidor, 32 planschsidor`

**Omfång**
`Benämning: xiv, 145 sidor, 10 planschblad, xii planschsidor`

Onumrerade planschblad eller planschsidor:

**Omfång**
`Benämning: 10 onumrerade sidor, 16 onumrerade planschsidor`

**Omfång**
`Benämning: xiv, 249 sidor, 12 onumrerade planschblad`

Läs mer i RDA 3.4.5.9.

### Portfölj, fodral eller mapp 

För en resurs som består av ett eller flera ark i en portfölj, fodral eller mapp, ange omfånget som 1 mapp, 1 fodral eller 1 mapp (RDA 3.4.5.15).

**Omfång**
`Benämning: 1 mapp`

Librispraxis: Katalogisatören avgör om det valfria tillägget att ange typ och antal underenheter ska tillämpas.

**Omfång**
`Benämning: 1 mapp (2 ark)`

## Mått (RDA 3.5)

Enligt Librispraxis är det inte obligatoriskt att ange mått. Mått som är standard för bäraren anges inte.

Om mått anges, och om instruktionerna inte säger något annat, ange mått i centimeter, avrundat uppåt till närmaste hela centimetertal. Ange måttet i cm (om en volym mäter 17,2 cm, anges måttet som 18 cm).

**Mått**
`Benämning: 25 cm`

**Mått**
`Benämning: 50 mm`

**Mått**
`Benämning: 21 x 37 cm`

**Mått**
`Benämning: 27 cm i skyddskassett 28 x 25 x 5 cm`

## Anmärkningar om instansen/manifestationen (RDA 2.17)

_Anmärkningar om manifestationen är inte ett kärnelement._

Gör anmärkning när det bedöms viktigt för identifikation, urval eller åtkomst.

### Citat (RDA 1.10.3)

Ange källhänvisning för citat ur resursen, såvida det inte är hämtat från den föredragna källan. Citatet ska anges inom citationstecken. Librispraxis är att ange källan före citatet.

**Anmärkning**
`Benämning: Omslag: ”Tryck, lyssna och sjung med”`

### Anmärkning om titel (RDA 2.17.2)

Gör en anmärkning om källan för huvudtiteln om den inte tagits från någon av dessa källor (för resurs som består av flera sidor, blad, ark eller kort (eller en bild av dessa)): titelsidan, titelblad eller titelkort (eller en bild av dessa).

Om resursen bara har en titel och titeln förekommer i resursen, behöver inte anmärkning om titelns källa anges (Librispraxis är att tillämpa den valfria uteslutningen).

**Anmärkning**
`Benämning: Titel från rygg`

**Anmärkning**
`Benämning: Titel från omslag`

**Anmärkning**
`Benämning: Titel från kolofon`

**Anmärkning**
`Benämning: Titel konstruerad av katalogisatör`

Om det bedöms viktigt för identifikation eller åtkomst, gör en anmärkning om källan för varianttitel (se RDA 2.3.6.3). 

**Titel**
`Huvudtitel: Sanvikens IF 75 år`

**Omslagstitel**
`Benämning?: Sandvikens IF 1918-1993`

### Anmärkning om upphovsuppgift (RDA 2.17.3)

Gör vid behov anmärkningar om upphovsuppgiften. En anmärkning kan innehålla information om att en person, familj/släkt eller institution som inte nämns i upphovsuppgiften tillskrivs ansvaret för det intellektuella eller konstnärliga innehållet i resursen, om olika namnformer som förekommer i resursen eller andra detaljer som rör upphovsansvaret. Zvapp!

### Teckengrad (RDA 3.13)

För resurser med typsnitt anpassat för personer med synnedsättning, ange storleken på typsnittet med termen stor stil.

Katalogisatören avgör om det valfria tillägget att ange storleken på typsnittet i antal punkter inom parentes ska tillämpas.

---
section: Arbetsflöden
title: Tryckt seriell resurs RDA
order: 36
tags:
- editor
- rda
- workflow
- seriell
---

# Tryckt seriell resurs RDA

_Arbetsflödet är under arbete._

[Extern länk till MARC21-anpassad information](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-seriella-resurser/)

För generella riktlinjer om hur man återger element som de förekommer i källan, se ”Transcription” – RDA 1.7.

## Innehåll

**Element tillhörande instans/manifestation**
* [Källa för resursen som helhet](#paragraph1)
* [Föredragen källa](#paragraph2)
* [Huvudtitel](#paragraph3)
* [Parallell huvudtitel](#paragraph4)
* [Övrig titelinformation](#paragraph5)
* [Parallell övrig titelinformation ](#paragraph6)
* [Nyckeltitel](#paragraph7)
* [Upphovsuppgift](#paragraph8)
* [Upplageuppgift](#paragraph9)
* [Numrering av seriella resurser](#paragraph10)
* [Utgivningsuppgifter](#paragraph11)
* [Distributionsuppgifter](#paragraph12)
* [Tillverkningsuppgifter](#paragraph13)
* [Frekvens](#paragraph14)
* [Identifikator för manifestationen](#paragraph15)
* [Anmärkningar om manifestationen](#paragraph16)
* [Medietyp](#paragraph17)
* [Bärartyp](#paragraph18)
* [Omfång](#paragraph19)
* [Mått](#paragraph20)
* [Teckenstorlek](#paragraph21)

# Element tillhörande manifestationen  

## Källa för resursen som helhet (RDA 2.1) <a name="paragraph1"></a>

Beskrivningen av en seriell resurs baseras på första numret eller första delen. Om första numret saknas, använd det första tillgängliga numret eller den första tillgängliga delen (RDA 2.1.2.3).

Om numret/delen som används för beskrivningen inte är det/den första, gör en anmärkning om vilket nummer eller vilken del som använts (RDA 2.17.13.3).

**Exempel**
`text`

Om fler än ett nummer/fler än en del har använts för att beskriva resursen (d.v.s. ett senare nummer/senare del), ange det i en anmärkning, (RDA 2.17.13.3.1). 

**Exempel**
`text`

## Föredragen källa (RDA 2.2) <a name="paragraph2"></a>

Börja med den information som finns på titelsidan (RDA 2.2.2.2). 

Uppgifter som saknas på titelsidan hämtas i första hand från valfri källa inom resursen. Det finns ingen prioriteringsordning bland övriga källor inom resursen.

Om det finns flera titelsidor eller olika källor med olika datum, använd i första hand den information som finns i källan med det senaste datumet (RDA 2.2.3.2).

Om resursen saknar titelsida eller annan källa som identifierar den, använd information som finns på (i denna ordning): medföljande material som inte är en del av resursen själv, annan publicerad beskrivning av resursen, en förpackning, annan tillgänglig källa. 
Klamra information hämtad utanför resursen (RDA 2.2.4). 

## Huvudtitel (RDA 2.3.2) <a name="paragraph3"></a>

_Huvudtitel är ett kärnelement._

Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan (RDA 1.7). 

NB-praxis: För monografiska serier som saknar titelsida, hämtas huvudtiteln i första hand från monografins titelsida, om det finns en sådan. Därefter följs prioriteringsordningen i RDA 2.2.2.2.

NB-praxis: Förkorta aldrig en huvudtitel.

Librispraxis: Generellt förkortas aldrig en huvudtitel (se valfritt alternativ under RDA 2.3.1.4).

## Undantag som gäller seriella resurser

### Felaktigheter 

Rätta uppenbara felaktigheter i huvudtiteln för en seriell resurs. Ange den felaktiga titeln som en varianttitel (RDA 2.3.1.4).

**Exempel**
Tidsuppgift, namn, numrering etc. som varierar från nummer till nummer eller del till del  
`text`

### Tidsuppgift, namn, numrering etc. som varierar från nummer till nummer eller från del till del ska uteslutas. 

Uppgifterna ersätts med uteslutningstecken (RDA 2.13.1.4).
 
**Exempel**
`text`
 
### Akronymer och fullständig form

Om huvudtiteln i den föredragna källan förekommer både i fullständig form och i form av en akronym eller i förkortad form, välj den fullständiga formen som huvudtitel (RDA 2.3.2.5). 

Om akronymen anses viktig för identifikation eller åtkomst anges den antingen som a) övrig titelinformation (RDA 2.3.4), eller som en varianttitel (RDA 2.3.6). ISSN Sverige följer ISSN Manual och anger akronymen som en varianttitel. 

**Exempel**
`text`

### Separat utgivna sektioner och supplement  

Om en seriell resurs utgör en separat  utgiven sektion av, eller ett supplement till, en annan seriell resurs och både den för samtliga sektioner/supplement gemensamma titeln och sektionens/supplementets titel anges i samma källa, ange båda titlarna. Den gemensamma titeln anges först och därefter sektionens eller supplementets titel (RDA 2.3.1.7.2).
 
**Exempel**
`text`
  
### Förändring i huvudtiteln 

Om det sker en större förändring i huvudtiteln ska en ny beskrivning göras för den nya titeln. De två beskrivningarna är beskrivningar av relaterade verk (RDA 2.3.2.12). För anvisningar om hur man anger relationer mellan verk, se Relaterade verk, uttryck m.m. nedan.

Om det sker en mindre förändring i huvudtiteln hos en seriell resurs anges den efterföljande titeln (RDA 2.3.8) om den är viktigt för identifikation eller åtkomst (RDA 2.3.8.3). För riktlinjer om vad som är en större och en mindre förändring i huvudtiteln hos en seriell resurs, se RDA 2.3.2.13.

**Exempel**
`text`

Librispraxis: Obligatoriskt att ange efterföljande titel för tidskrifter och årsböcker. Om förändringarna är många, kan dock alternativet i (RDA 2.3.8.3) följas och en generell anmärkning göras. 

**Exempel**
`text`

För monografiserier med huvudpost anges inte mindre förändringar i huvudtiteln. 

## Parallell huvudtitel (RDA 2.3.3) <a name="paragraph4"></a>

Parallell huvudtitel är huvudtiteln på ett annat språk eller i en annan skriftart. Enligt Librispraxis är den första parallella huvudtiteln i den föredragna källan obligatorisk. Därefter redovisas en påföljande parallell huvudtitel på svenska. Övriga parallella huvudtitlar är valfria. 

NB-praxis: Ange alla parallella huvudtitlar som är framhävda.

En parallell huvudtitel får hämtas från hela resursen (RDA 2.3.3.2). Om huvudtiteln hämtas utanför resursen ska parallelltiteln hämtas från samma källa. 

**Exempel**
`text`

### Förändring i parallell huvudtitel 

Om en parallell huvudtitel läggs till eller ändras i ett påföljande nummer eller i en påföljande del (och det är av betydelse för identifikation eller åtkomst), ange den nya parallella huvudtiteln som en varianttitel i fält 246 (RDA 2.3.5.4.2). Ange tidsbegränsning i delfält #f.

**Exempel**
`text`

Om en parallell huvudtitel tas bort i ett påföljande nummer eller i en påföljande del, ange detta i en anmärkning om det är av betydelse för identifikation eller åtkomst (RDA 2.3.5.4.2).

**Exempel**
`text`

## Övrig titelinformation (RDA 2.3.4) <a name="paragraph5"></a>

Övrig titelinformation är inte ett kärnelement men obligatoriskt enligt Librispraxis. Övrig titelinformation anges i delfält 245 #b och hämtas från samma källa som huvudtiteln (RDA 2.3.4.2). 

Librispraxis: Övrig titelinformation som återfinns i annan källa än huvudtiteln återges som en varianttitel om den är viktig för identifikation. Det gäller dock endast övrig titelinformation som tillför ytterligare information och som inte är reklam, slogans etc.   

**Exempel**
`text`

Om övrig titelinformation förekommer på mer än ett språk eller i mer än en skriftart anges den övriga titelinformation som är på huvudtitelns språk eller i dess skriftart (RDA 2.3.4.4).

Om det finns flera undertitlar anges de i den ordning som markeras av ordningsföljd, layout och typografi i källan (RDA 2.3.4.3). Eftersom delfält #b inte är repeterbart anges alla undertitlar i samma delfält åtskilda med kolon.

### Förändring i övrig titelinformation 

Om övrig titelinformation läggs till eller ändras i ett påföljande nummer eller i en påföljande del (och det är av betydelse för identifikation eller åtkomst), ange denna som en varianttitel (RDA 2.3.4.7.2). Lägg hela titeln (huvudtitel samt övrig titelinformation) i fält 246. 

Redovisa endast viktiga varierande undertitlar. Det kan vara förändringar gällande t.ex. målgrupp, ämne, inriktning och utgivare/institution. Här behöver man inte ange tidsbegränsning i delfält #f.

**Exempel**
`text`

Om övrig titelinformation saknas i ett påföljande nummer eller i en påföljande del, ange detta i en anmärkning om det är av betydelse för identifikation eller åtkomst (RDA 2.17.2.4).

## Parallell övrig titelinformation (RDA 2.3.5 ) <a name="paragraph6"></a>

Parallell övrig titelinformation är inte ett kärnelement men obligatoriskt enligt NB-praxis. Parallell övrig titelinformation är övrig titelinformation som är på ett annat språk eller i en annan skriftart än den som angivits i elementet för övrig titelinformation. 

Parallell övrig titelinformation hämtas från samma källa som motsvarande parallella huvudtitel. Om det inte finns någon motsvarande parallell huvudtitel, hämta parallell övrig titelinformation från samma källa som huvudtiteln.

Om parallell övrig titelinformation förekommer på mer än ett språk eller i mer än en skriftart anges parallell övrig titelinformation i samma ordning som motsvarande parallella huvudtitlar. Om det inte är tillämpbart, ange dem i samma ordning som är i resursen (RDA 2.3.5.3).

**Exempel**
`text`

## Nyckeltitel (RDA 2.3.9) <a name="paragraph7"></a>

Nyckeltitel är en unik titel för en seriell resurs med ISSN. Nyckeltitel är inte ett kärnelement men obligatoriskt enligt Librispraxis för resurser med ISSN. 
Läs mer om hur man anger ISSN under Identifikator för manifestationen.
Det är respektive lands ISSN-central som tilldelar resurser nyckeltitlar och i Sverige görs det av ISSN Sverige på Kungliga biblioteket. Övriga Libriskatalogisatörer ska inte ange nyckeltitel för svenska resurser men det är bra att känna till hur de konstrueras. Större förändringar i nyckeltiteln kräver ny post och nytt ISSN. 
För att ta reda på vilken nyckeltitel som har tilldelats en seriell resurs med utländskt ISSN kan man söka i utgivningslandets nationella katalog. Det går också bra att vända sig till ISSN Sverige som kan stå till tjänst med sökningar i den internationella ISSN-portalen. 
Nyckeltitel anges i fält 222 och konstrueras med hjälp av huvudtiteln. Eftersom en nyckeltitel måste vara unik kräver likalydande huvudtitlar särskiljande tillägg. Särskiljande tillägg anges inom parentes i delfält #b och väljs så att nyckeltiteln blir unik med så få termer som möjligt. 
222	_	0	#a Rapport #b (Institutionen för konstruktion och mekanik, Chalmers tekniska högskola)

222	_	0	#a Cinema #b (Stockholm)

222	_	0	#a Resemagasinet #b (Stockholm. 1992)
 
Upp

Upphovsuppgift (RDA 2.4) 
Upphovsuppgift som hänför sig till huvudtiteln är ett kärnelement och anges i delfält 245 #c. Om det finns mer än en, är endast den första kärnelement. 
Hämta upphovsuppgifter som hänför sig till huvudtiteln från följande källor (i denna ordning): samma källa som huvudtiteln, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4. Denna prioritetsordning ska följas även om en påföljande källa har en mer fullständig upphovsuppgift för samma person, familj/släkt eller institution med samma funktion. Endast upphovsuppgifter som hämtas från en källa utanför resursen ska klamras. 
Upphovsuppgiften återges som den förekommer i källan (RDA 2.4.1.4). Inkludera ord och fraser som talar om sambandet mellan titeln och den eller de personer etc.  som nämns i upphovsuppgiften. Tillämpa generellt inte den valfria uteslutningen som gör det möjligt att förkorta en upphovsuppgift.
245	1	0	#a Årsstatistik för Stockholms län och landsting / #c sammanställd av Statistiska centralbyrån, på uppdrag av Stockholms läns landsting, Regionplane- och trafikkontoret

Återge en upphovsuppgift även om den inte namnger specifika personer eller institutioner (RDA 2.4.1.9).
 
245	1	0	#a ... / #c av elever på Bergs folkhögskola
 
Undantag som gäller seriella resurser
Återge en upphovsuppgift som identifierar en redaktör endast om personen är viktig för att kunna identifiera resursen, t.ex. om personen varit resursens redaktör under större delen av utgivningen (RDA 2.4.1.4).
245	1	0	#a Patrick Moore's yearbook of astronomy / #c edited by Patrick Moore and John Mason

Anvisningar för Importerade poster.
Upp
Upphovsuppgift med fler än en namngiven person, familj/släkt eller institution 
Återge varje enskild upphovsuppgift som ett element oavsett om två eller flera personer etc. som omnämns har samma eller olika funktioner (RDA 2.4.1.5).
Valfri uteslutning: Om en enskild upphovsuppgift namnger fler än tre personer, familjer/släkter eller institutioner, uteslut alla utom den första personen etc. Uteslutningen markeras med en klamrad summering av vad som uteslutits.
245	1	0	#a ... / #c utgiven av Institutionen för omvårdnad, Institutionen för vård och omsorg, Institutionen för psykisk hälsa och Institutionen för socialt arbete

eller
245	1	0	#a ... / #c utgiven av Institutionen för omvårdnad [och tre andra]
 
Librispraxis är att det är katalogisatören som avgör om den valfria uteslutningen ska tillämpas. När kunskap finns, ska summeringen vara på resursen språk.
245	1	0	#a ... / #c by Department of Health [and three others]
Mer än en upphovsuppgift 
Om det finns mer än en upphovsuppgift kan även övriga upphovsuppgifter återges om de är viktiga för identifikation. Librispraxis uppmanar katalogisatören att ta med alla upphovsuppgifter som är av betydelse. Uppgifterna återges i den ordning som markeras av ordningsföljd, layout eller typografi i källan. Om detta är oklart, återge dem i den ordning som framstår som rimligast, RDA 2.4.1.6.
Om inte alla upphovsuppgifter tas med ska förtur ges åt dem som identifierar skaparna av det intellektuella eller konstnärliga innehållet (RDA 2.4.2.3). Om det är tveksamt, ange den första upphovsuppgiften.
Antalet personer etc. man tar med i upphovsuppgiften behöver inte motsvara antalet personer etc. man anger i sökingångar. Katalogisatören måste här använda sitt omdöme.
Förändringar i upphovsuppgiften 
Om en upphovsuppgift som bedöms vara viktig för identifikation eller åtkomst tillkommer eller ändras i ett påföljande nummer eller i en påföljande del av en seriell resurs (och det inte innebär att en ny post måste göras) ska sökingång/sökingångar för det nya namnet/de nya namnen läggas till. 
245	1	0	#a Allt om jobbet / #c utgiven av Sveriges kommunaltjänstemannaförbund (SKTF)
264	_	1	#a Stockholm : #b Sveriges kommunaltjänstemannaförbund (SKTF), #c 2008-
264	3	1	#a Stockholm : #b Vision
710	2	_	#a SKTF #4 isb
710	2	_	#a Vision #4 isb
Upphovsuppgift som hänför sig till huvudtiteln på mer än ett språk eller i mer än en skriftart 
Om en upphovsuppgift som hänför sig till huvudtiteln förekommer på mer än ett språk eller i mer än en skriftart återges den upphovsuppgift som är på huvudtitelns språk eller dess skriftart (RDA 2.4.2.4).
NB-praxis: Obligatoriskt att ange parallell upphovsuppgift som hänför sig till huvudtiteln (RDA 2.4.3).
Upp

Upplageuppgift (RDA 2.5)
Upplagebeteckning och påföljande upplagebeteckning är kärnelement. Övriga element är valfria. För seriella resurser är det vanligtvis endast upplagebeteckning som är aktuellt.
Upplageuppgiften återges som den förekommer i resursen, dock inte nödvändigtvis när det gäller stora och små bokstäver eller interpunktion, se dokumentet "Transcription" - RDA 1.7.
Förkortningar används endast om de förekommer i källan som uppgiften hämtas från.
Återge inte en uppgift som är relaterad till tryckning eller antal exemplar av en viss upplaga som upplageuppgift eller en uppgift som endast hör till ett särskilt nummer eller en särskild del av resursen. Då det är tveksamt om en uppgift är att betrakta som upplageuppgift, ska ord som utgåva, upplaga, nummer, version (eller deras motsvarigheter på andra språk) uppfattas som tecken på att uppgiften är en upplageuppgift, och då behandlas som en sådan.
Om en resurs saknar upplagebeteckning men det är känt att den skiljer sig från andra upplagor, tillämpa det valfria tillägget och lägg till en upplageuppgift om det är av betydelse för identifikation eller åtkomst (RDA 2.5.1.4). Ange uppgiften inom klammer på huvudtitelns språk. För resurser med huvudtitel på svenska, följ Svenska skrivreglers rekommendation och använd termen "upplaga" för förändrat/annat innehåll.
250	_	_	#a [Upplaga B] 
Upplagebeteckning
Upplagebeteckning är ett kärnelement och anges i delfält 250 #a. Hämta uppgiften från följande källor (i denna ordning): samma källa som huvudtiteln, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4. 
Om upplageuppgiften består av en bokstav eller bokstäver och/eller en siffra eller siffror utan påföljande ord, tilläggs tillämpligt ord (RDA 2.5.2.3).
250	_	_	#a [Version] 1.1

Återge tal angivna med siffror eller med bokstäver som de återfinns i resursen. Eftersom upplageuppgift inte är med i listan i RDA 1.8.1 gäller inte specialreglerna i RDA 1.8.2-1.8.5. Även romerska siffror återges alltså som de återfinns i resursen.
250	_	_	#a Version IV
Upplagebeteckning på mer än ett språk eller i mer än en skriftart
Om upplagebeteckningen förekommer i källan på mer än ett språk eller i mer än en skriftart, återge den uppgift som är på huvudtitelns språk eller i dess skriftart. Om detta kriterium inte går att tillämpa, återge den upplagebeteckning som kommer först i källan (RDA 2.5.2.4).
Upplagebeteckning som är en del av huvudtitel, etc.
Upplagebeteckning som är en integrerad del av huvudtitel, övrig titelinformation eller upphovsuppgift, eller grammatiskt sammanhängande med något av dessa element ska anges tillsammans med det element som det är en del av. Ange det inte igen som en upplagebeteckning (RDA 2.5.2.6).
245	1	0	#a DSI special edition

Upp

Numrering av seriella resurser (RDA 2.6)
Elementet innehåller flera underelement. Kärnelement är numerisk och/eller alfabetisk beteckning för första numret/delen i första eller enda sviten, kronologisk beteckning för första numret/delen i första eller enda sviten, numerisk och/eller alfabetisk beteckning för sista numret/delen i sista eller enda sviten, kronologisk beteckning för sista numret/delen i sista eller enda sviten.
Källor 
Uppgift om numrering av en seriell resurs hämtas från följande källor (i denna ordning): samma källa som huvudtiteln, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4. 
Om varken första numret eller information om första numret är tillgänglig vid katalogiseringstillfället, ska elementet uteslutas och en anmärkning ska göras om vilket nummer som använts som grund för beskrivningen. 
500	_	_	#a Beskrivningen grundad på 1988, nr 3

Om beskrivningen av resursen inte grundar sig på första numret men numreringen kan hämtas från en källa utanför resursen (t.ex. från webben) är Librispraxis att klamra in uppgiften. 
362	0	_	#a [1988, nr 1]-

Samma sak gäller om resursen upphör och sista numret inte finns tillgängligt. Kan numreringen hämtas från en källa utanför resursen anges uppgiften inom klammer.
362	0	_	#a 1988, nr 1-[1991, nr 2]
Första numret är tillgängligt men inte sista. Information om numreringen i sista numret har hämtats från en källa utanför resursen. 
  
362	0	_	#a [1988, nr 1]-[1991, nr 2]
Varken första eller sista numret är tillgängligt men information om numreringen i första och sista numret har hämtats från en källa utanför resursen.
Om det första numret eller delen saknar numrering men påföljande nummer/delar har det, kan numrering baserad på numreringen i påföljande nummer/delar läggas till inom klammer.
 
362	0	_	#a [Del 1]-
Påföljande delar har numreringen: Del 2, Del 3, etc.

Det är inte tillåtet att ange en trolig numrering följd av frågetecken, t. ex. [1987, nummer 1?]-. Ungefärlig utgivningstid anges i elementet för utgivningstid, se nedan under Uppgift om utgivningstid saknas.
 
Upp
Ange numrering av seriella resurser 
RDA säger inget om hur de olika underelementen i numreringen ska sättas samman, varken när de står tillsammans eller på olika ställen i resursen, utan ger instruktioner för varje underelement för sig.

I MARC21 anges samtliga underelement i ett enda fält, 362 #a. ISBD (International Standard Bibliographic Description), paragraf 3.3, ger följande instruktioner för hur de olika underelementen ska anges tillsammans:

Numerisk och/eller alfabetisk beteckning och/eller kronologisk beteckning för första numret av en seriell resurs ska följas av ett bindestreck.
362	0	_	#a 1998-

När den seriella resursen upphör anges numerisk och/eller alfabetisk beteckning och/eller kronologisk beteckning för sista numret efter bindestrecket.
362	0	_	#a 1998-1999

Om endast numerisk och/eller alfabetisk och/eller kronologisk beteckning för sista numret av en seriell resurs anges ska denna föregås av ett bindestreck.
362	0	_	#a -1999, nr 1

Om ett nummer av en seriell resurs identifieras med både numerisk och/eller alfabetisk och kronologisk beteckning anges den kronologiska beteckningen inom parentes efter den numeriska och/eller alfabetiska beteckningen.
362	0	_	#a No. 1(Jan. 1971)-
 
Om numret bara avser en del av den kronologiska perioden utan att denna specificeras, och varje årgång börjar med nummer ett eller motsvarande, anges den numerisk och/eller alfabetiska beteckningen efter den kronologiska beteckningen.
362	0	_	#a 1999, nr 1-
 
362	0	_	#a Årg. 1(1988), nr 1-

362	0	_	#a Årgång 1(april 1999), nummer 1-
Om den numerisk och/eller alfabetiska beteckningen består av flera nivåer ska dessa anges i hierarkisk ordning.
362	0	_	#a Vol. 1, nr 1-

Om en seriell resurs påbörjar en ny nummersvit utan att förändra huvudtiteln anges beteckningen på det första och sista numret av varje svit. I fält 362 ska en ny nummersvit föregås av mellanslag, semikolon, mellanslag:
362	0	_	#a Volume 1, number 1-volume 10, number 12 ; No. 1-no. 3
 
NB-praxis: Numrering anges endast för första och sista numret av en seriell resurs:
362	0	_	#a Volume 1, number 1-no. 3

Tal angivna med siffror eller bokstäver ska anges enligt de generella riktlinjerna i RDA 1.8. Librispraxis är att ersätta romerska siffror med arabiska. Övriga ord, bokstäver eller grupper av ord och/eller tecken återges som de förekommer i källan enligt RDA 1.7. Återge interpunktion som den förekommer i källan om det inte blir otydligt, se alternativet samt undantagen i RDA 1.7.3. Observera dock undantaget i RDA 2.6.1.4 som innebär att bindestreck alltid ska ersättas med snedstreck för ökad tydlighet.
362	0	_	#a 1999/2000
I källan: 1999-2000 

Om en kronologisk beteckning omfattar tidsuppgifter som inte angivits enligt den gregorianska eller julianska kalendern (RDA 2.6.3.3 och RDA 2.6.5.3), följs det valfria tillägget och motsvarande uppgifter tilläggs enligt den gregorianska eller julianska kalendern:
362	0	_	#a 5722 [2012]-

Upp
Utgivningsuppgifter (RDA 2.8)
Utgivningsort, utgivarnamn och utgivningstid är kärnelement. RDA har separata element för utgivnings-, distributions- och tillverkningsuppgifter och dessa anges i separata 264-fält. Med andraindikatorn anger man vilken typ av uppgift fältet innehåller. För utgivningsuppgifter anges 1. Om uppgifterna hämtas utanför resursen ska varje underelement klamras för sig enligt ISBD (International Standard Bibliographic Description), paragraf A.3.2.8.
 
264	_	1	#a [Storstad] : #b [Förlaget], #c [1989]-

I många befintliga poster kommer utgivningsuppgifterna att ligga i fält 260. Dessa ska inte flyttas till fält 264 men om utgivarnamnet ändras i ett påföljande nummer ska den nya informationen anges i ett 264-fält, se Förändringar i utgivningsuppgifter.
Anvisningar för Importerade poster.
Utgivningsort  
Hämta uppgift om utgivningsort från följande källor (i denna ordning): samma källa som utgivarens namn, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4. 
Ange utgivningsort som den förekommer i källan, följ de generella riktlinjerna i dokumentet "Transcription" - RDA 1.7. Librispraxis är att följa det andra valfria tillägget i RDA 2.8.2.3, d.v.s. att lägga till namn på land, delstat, provins etc.om det behövs för identifikation eller åtkomst. Om uppgiften hämtas utanför resursen ska den klamras. 
Använd svensk namnform om en sådan finns, annars den officiella inhemska formen. Använd förkortningarna av namn på delstater, provinser och territorier etc. i Australien, Förenta staterna och Kanada enligt RDA Appendix B.11. Förkorta inte namn på länder (se Librispraxis, KBSP, vid Appendix B.11).
264	_	1	#a Dublin, Ohio
 
264	_	1	#a London [Ontario]

Om fler än en utgivningsort förekommer i källan är endast den första kärnelement enligt RDA. Librispraxis är att om en utgivare har avdelningar på flera orter, och dessa redovisas i resursen, ska den först nämnda anges. Utöver det anges därpå följande ort som särskilt framhålls genom källans layout eller typografi. 
264	_	1	#a Stockholm ; #a Malmö : #b Förlaget, #c [2009]-

Om den först nämnda orten och den särskilt framhävda orten inte är svensk, anges även den första av alla därpå följande svenska orter.
Om en resurs har flera utgivare återges den först nämnda utgivarens ort. Dessutom anges påföljande utgivares orter (om de avviker från den redan nämnda orten):
•	när en påföljande institution klart framhävs som huvudutgivare genom layout eller typografi, anges även orten för den särskild framhävda utgivaren 
•	när påföljande utgivare är svensk men inte den först nämnda 
Utgivningsort på mer än ett språk eller i mer än en skriftart 
Om namnet på utgivningsorten förekommer i källan på mer än ett språk eller i mer än en skriftart, ange den uppgift som är på huvudtitelns språk. Om detta kriterium inte kan tillämpas, återge den uppgift som kommer först i källan (RDA 2.8.2.5).
Uppgift om utgivningsort saknas i resursen 
Om ingen utgivningsort är angiven i resursen (RDA 2.8.2.6), lägg till utgivningsorten eller den troliga utgivningsorten inom klammer enligt följande prioriteringsordning:
a) Känd ort [Stockholm]
b) Trolig ort [Stockholm?]
c) Känt land, känd stat, provins etc. [Sverige]
d) Troligt land, stat, provins etc. [Sverige?]
e) Okänd ort [Utgivningsort okänd]
Upp
Utgivarnamn
Hämta uppgift om utgivarens namn från följande källor (i denna ordning): samma källa som huvudtiteln, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4.
Om fler än en utgivare förekommer i källan är endast den första kärnelement i RDA. Librispraxis är att dessutom ange påföljande utgivare när en påföljande institution klart framhävs som huvudutgivare genom layout eller typografi eller när påföljande utgivare är svensk men inte den först nämnda. 
NB-praxis: Följ ovanstående Libris-praxis men ange även påföljande utgivare när denna (men inte den första utgivaren) utgörs av ett förlag som står i klartext i resursen. Påföljande utgivare kan vid behov anges även i andra fall. Katalogisatören avgör.  
Återge utgivarens namn som det förekommer i källan, följ de generella riktlinjerna i dokumentet ”Transcription" - RDA 1.7. Om första och påföljande utgivare är förenade till en enda uppgift, ange dem så. 
264	_	1	#a Stockholm : #b Almqvist & Wicksell i samarbete med fortbildningsavdelningarna vid universiteten i Linköping och Lund

Tillämpa generellt inte det valfria tillägget att lägga till en term som anger en utgivares funktion om det inte behövs en mer specifik funktionsuppgift än den som redan angetts i fält 264, andra indikatorn.

Tillämpa generellt inte den valfria uteslutningen i RDA 2.8.4.3, att utesluta hierarkiska nivåer i utgivarens organisation.
264	_	1	#a Uppsala : #b Avdelningen för forskning och utbildning i modern svenska, Institutionen för nordiska språk, Uppsala universitet
Utgivarens namn på mer än ett språk eller i mer än en skriftart
Om namnet på utgivaren förekommer i källan på mer än ett språk eller i mer än en skriftart, ange det namn som är på huvudtitelns språk. Om detta kriterium inte kan tillämpas, återge den uppgift som kommer först i källan, RDA 2.8.4.6.
Utgivarens namn felstavat på titelsidan
Titelsidan är föredragen källa för utgivarnamn. Om det finns en titelsida och utgivarens namn är felstavat där, återge utgivarnamnet som det förekommer på titelsidan och gör en anmärkning om det korrekta namnet, se Anmärkning om utgivningsuppgift i arbetsflödet Tryckta monografier.
Uppgift om utgivare saknas i resursen
Om uppgift om utgivare saknas i resursen och inte kan hämtas från någon annan källa ange [utgivare okänd], RDA 2.8.4.7.
Upp
Utgivningstid
Utgivningstid är ett kärnelement. Librispraxis är att tillämpa det valfria tillägget i RDA 2.8.6.3 om uppgiften inte är angiven enligt gregoriansk eller juliansk kalender.
Hämta uppgift om utgivningstid från första och/eller sista numret eller delen av en seriell resurs i följande källor (i denna ordning): samma källa som huvudtiteln, en annan källa inom resursen, en annan av de källor som specificeras i RDA 2.2.4. Följ riktlinjerna i dokumenten Tal (siffror och bokstäver) - RDA 1.8 och Tidsangivelser - RDA 1.9. För seriella resurser följs även RDA 2.8.6.5. 
Vid pågående utgivning ska den seriella resursens startår följas av ett bindestreck:
264	_	1	#a Uppsala : #b Förlaget, #c 1988-

När utgivningen upphör anges slutår efter bindestrecket:
264	_	1	#a Uppsala : #b Förlaget, #c 1988-2007

Om den seriella resursen upphör men startår är okänt, ange slutår föregånget av bindestreck:
264	_	1	#a Uppsala : #b Förlaget, #c -2007

Om en seriell resurs upphör inom ett år, ange endast ett årtal:
264	_	1	#a Uppsala : #b Förlaget, #c 2007
Uppgift om utgivningstid saknas 
Om uppgift om utgivningstid saknas, lägg till utgivningstid enligt instruktionerna i RDA 1.9.2.
•	Om första numret/delen och/eller sista numret/delen inte är tillgängligt vid katalogiseringstillfället men uppgift om utgivningstid kan hämtas från en källa utanför resursen, lägg till utgivningstiden. Uppgiften ska klamras. 
•	Om första numret/delen och/eller sista numret/delen saknar uppgift om utgivningstid men distributionstid, tillverkningstid, copyrightår eller kronologisk beteckning finns i resursen, lägg till en utgivningstid baserad på någon/några av dessa uppgifter. Uppgiften ska klamras.
•	Om första numret/delen och/eller sista numret/delen saknar uppgift om utgivningstid, distributionstid, tillverkningstid, copyrightår eller kronologisk beteckning men uppgift om utgivningstid kan hämtas från en källa utanför resursen, lägg till en utgivningstid. Uppgiften ska klamras.
Startåret är känt:
264	_	1	#a Uppsala : #b Förlaget, #c [1988]-

Det är känt att resursen upphörde 2007:
264	_	1	#a Uppsala : #b Förlaget, #c 1988-[2007]

Utgivningstiden är känd:
264	_	1	#a Uppsala : #b Förlaget, #c [1988]-[2007]
 
Det är känt att startåret är ett av två på varandra följande år:
264	_	1	#a Uppsala : #b Förlaget, #c [1988 eller 1989]-

Det är troligt att startåret faller inom ett visst tidsintervall:
264	_	1	#a Uppsala : #b Förlaget, #c [mellan 1999 och 2001?]-

Troligt startår:
264	_	1	#a Uppsala : #b Förlaget, #c [1999?]-

Tidigast möjliga startår är känt:
264	_	1	#a Uppsala : #b Förlaget, #c [ej före 1997]-
 
Senast möjliga startår är känt:
264	_	1	#a Uppsala : #b Förlaget, #c [ej efter 1997]-
Utgivningstid okänd
Om utgivningstiden för en seriell resurs är okänd och ingen ungefärlig utgivningstid kan anges, ska ingen utgivningstid alls anges. Ange inte [utgivningstid okänd].
Fiktiv eller felaktig utgivningstid
Om det är känt att utgivningstiden som är angiven i resursen är fiktiv eller felaktig, ange den utgivningstid som står i resursen i elementet för utgivningstid och gör en anmärkning om den korrekta eller troliga utgivningstiden, RDA 2.8.6.3. I fält 008 anges den korrekta utgivningstiden hämtad från anmärkningen.
Läs mer om hur man anger utgivningstid i fält 008 under Typ av utgivningsdatum och Årtal/tid. 
008/07_10	_	_	1988
264	_	1	#a Uppsala : #b Förlaget, #c 1888-
500	_	_	#a Felaktigt utgivningsår i första numret, ska vara 1988
Känt att utgivningsåret är felaktigt.
Upp
Förändringar i utgivningsuppgifter
Librispraxis är att inte redovisa växlande utgivningsort (RDA 2.8.1.5.2).  Däremot ska förändringar i utgivaruppgifter som inte enbart består i hur utgivarnamnet presenteras redovisas. Librispraxis är att ange första och nuvarande utgivare men inte mellanliggande utgivare. 
I MARC21 anges förändringarna genom att fält 264 upprepas och att olika värden i förstaindikatorn anges.
Förstaindikator 3 anger nuvarande/senaste utgivare.
264	_	1	#a Stockholm : #b Scandecor trading, #c [1998]-
264	3	1	#a Stockholm : #b Rosenudde

Om posten från början innehåller utgivaruppgifter angivna i fält 260, behålls dessa men ny utgivarinformation anges i ett 264-fält.
260	_	_	#a Stockholm : #b Scandecor trading, #c [1998]-
264	3	1	#a Stockholm : #b Rosenudde

Librispraxis är att ange relationen mellan manifestationen och en institution som är utgivare, se Personer, familjer/släkter och institutioner knutna till en manifestation. Om en institution som är utgivare ändras eller tillkommer i ett påföljande nummer eller en påföljande del av en seriell resurs så ska en auktoriserad sökingång för den nya institutionen läggas till.
Upp
Distributörsuppgift (RDA 2.9)
Distributörsuppgifter anges i fält 264 med andraindikator 2.
Distributionsort
Distributionsort är inte ett kärnelement. Librispraxis är att endast ange distributionsort om den framgår av resursen. För källor, se RDA 2.9.2.2. För instruktioner om hur man anger distributionsort, se RDA 2.9.2.3. Tillämpa det andra valfria tillägget men inte det första.
Distributörsnamn
Distributörsnamn är inte ett kärnelement. Librispraxis är att endast ange distributörens namn om det framgår av resursen. För val av källa, se RDA 2.9.4.2. För instruktioner om hur man anger distributörsnamn, se RDA 2.9.4.3. Tillämpa generellt inte den valfria uteslutningen. Tillämpa inte det valfria tillägget i RDA 2.9.4.4 om det inte behövs en mer specifik funktionsuppgift än den som angivits i fält 264, andra indikatorn.
264	_	1	#a Uppsala : #b Förlaget, #c [1998]-
264	_	2	#a Uppsala : #b Akademiska bokhandeln, #c 1998-
Distributionstid
Distributionstid är inte ett kärnelement. För val av källa, se RDA 2.9.6.2.
För instruktioner om hur man anger distributionstid, se RDA 2.9.6.3. Följ även riktlinjerna i dokumentet: Tal (siffror och bokstäver) - RDA 1.8. Tillämpa det valfria tillägget.

Om distributionstiden angivits i källan i form av ett kronogram, RDA 2.9.6.4, tillämpa alternativet och ange uppgiften med arabiska siffror enligt den gregorianska eller julianska kalendern. Klamra. Ange kronogrammet i en anmärkning om det är viktigt för identifiering.
Distributionstid okänd
Om distributionstiden för en seriell resurs är okänd och ingen ungefärlig distributionstid kan anges, ska ingen distributionstid alls anges. Ange inte [distributionstid okänd].
Förändringar i distributionsuppgifter
Librispraxis är att inte redovisa växlande distributionsort (RDA 2.9.1.5.2).  Däremot ska förändringar som inte enbart består i hur distributörsnamnet presenteras redovisas. Librispraxis är att ange första och nuvarande distributör men inte mellanliggande distributör. 
I MARC21 anges förändringarna genom att fält 264 upprepas och att olika värden i förstaindikatorn anges.
Förstaindikator 3 anger nuvarande/senaste distributör.
264	_	2	#a Uppsala : #b Akademiska bokhandeln [distributör], #c [1998]-
264	3	2	#a Uppsala : #b Swedish Science Press

Om posten från början innehåller distributörsuppgifter angivna i fält 260, behålls dessa men ny distributörsinformation anges i ett 264-fält.
260	_	_	#a Uppsala : #b Akademiska bokhandeln [distributör], #c [1998]-
264	3	2	#a Uppsala : #b Swedish Science Press
 
Upp
Tillverkningsuppgifter (RDA 2.10)
Tillverkningsuppgifter anges i fält 264 med andraindikator 3. 
Tillverkningsort
Tillverkningort är inte ett kärnelement. För val av källa, se RDA 2.10.2.2.
För instruktioner om hur man anger tillverkningsort, se RDA 2.10.2.3. Tillämpa det andra valfria tillägget men inte det första.  
Tillverkarnamn
Tillverkarnamn är inte ett kärnelement. För val av källa, se RDA 2.10.4.2.
För instruktioner om hur man anger tillverkarnamn, se RDA 2.10.4.3. Tillämpa generellt inte den valfria uteslutningen.
Tillämpa inte det valfria tillägget i RDA 2.10.4.4 om det inte behövs en mer specifik funktionsuppgift än den som angivits i fält 264, andra indikatorn. 
Tillverkningstid
Tillverkningstid är inte ett kärnelement. För val av källa, se RDA 2.10.6.2.
För instruktioner om hur man anger tillverkningstid, se RDA 2.10.6.3. Följ även riktlinjerna i dokumentet: ”Tal (siffror och bokstäver) - RDA 1.8”. Tillämpa det valfria tillägget.
Om tillverkningstiden angivits i källan i form av ett kronogram, RDA 2.10.6.4, tillämpa alternativet och ange uppgiften med arabiska siffror enligt den gregorianska eller julianska kalendern. Klamra. Ange kronogrammet i en anmärkning om det är viktigt för identifiering. 
Tillverkningstid okänd
Om tillverkningstiden för en seriell resurs är okänd och ingen ungefärlig tillverkningstid kan anges, ska ingen tillverkningstid alls anges. Ange inte [tillverkningstid okänd].
Förändringar i tillverkningsuppgifter
Librispraxis är att inte redovisa växlande tillverkningsuppgifter (RDA 2.10.1.5.2).
Upp

Frekvens (RDA 2.14)
Frekvens är inte ett kärnelement. Uppgiften kan hämtas från valfri källa. Frekvens kan kodas i 008 och anges i fält 310. Om frekvens anges i fält 310 är Librispraxis att ange enligt följande:
 
1 nr/kvartal 

1 nr/vecka 

1 nr/månad 
Ca 1 nr/månad (när t.ex. 13 nr/år = 1 nr/månad i 008) 
1 nr/år 
Årlig (endast för årsböcker) 
Varannan månad 
2 nr/vecka 
Daglig 
Varannan vecka (föredras framför 2 nr/månad) 
2 nr/månad (används endast när det uttryckligen står så i tidskriften) 
2 nr/år 
Vartannat år 
Vart tredje år 
3 nr/vecka 
3 nr/månad 
Oregelbunden 
3 nr/år 
Ca 5 nr/år  
NB-praxis: Frekvens anges generellt enbart i fält 008 och inte i fält 310. I de fall man kodar z (= Annan frekvens) i fält 008 anges dock den korrekta frekvensen i fält 310.
Upp
 
Identifikator för manifestationen (RDA 2.15)
Identifikator för manifestationen är ett kärnelement. En identifikator är en teckensträng som är knuten till manifestationen, till exempel ISSN. Uppgift om identifikator kan hämtas från valfri källa. 
Anvisningar för Importerade poster.
ISSN (Internationellt standardserienummer)
ISSN är ett internationellt standardnummer för seriella och integrerande resurser. Resurser utgivna av svenska utgivare tilldelas ISSN av ISSN Sverige på Kungliga biblioteket.
Ett ISSN-nummer är alltid knutet till en nyckeltitel som är unik, se nedan under Nyckeltitel. 
ISSN anges i fält 022. Ange bindestreck enligt modellen 1122-3344.
Vid katalogisering av svenska resurser anges första indikator 0 (Internationellt intresse; fullständig post registrerad med ISSN) och följande delfält används aktivt:
022 0/_ #a Korrekt ISSN
022 0/_ #2 f (= kod för ISSN Sverige, dvs. svenskt nummer)
Vid behov används även följande delfält:
022 0/_ #y Felaktigt ISSN
022 0/_ #z Annullerat ISSN
Om ISSN för e-resursen står i den tryckta manifestationen (eller tvärtom) lägger man detta nummer i delfält 022 #y i posten för den tryckta manifestationen.
Observera att alla delfält placeras i samma 022-fält.
022	0	_	#a 1653-736X #y 1122-3344 #2 f

Följande delfält kan förekomma men används inte aktivt (låt vara kvar om de är korrekta):
022 0/_ #l ISSN-L
022 0/_ #m Annullerat ISSN-L
Delfält 022 #l används för att ange ISSN-L (ISSN-Link). ISSN-L är ett standardnummer tilldelat av ISSN-nätverket för att samla olika manifestationer av samma fortlöpande resurs. Det är alltså en identifikator för uttrycket men den nämns inte i RDA. Det ISSN som först tilldelas en fortlöpande resurs blir ISSN-L. 
ISSN Sverige lägger inte ISSN-L i svenska poster men bibliotek som så önskar kan använda delfältet om ISSN-L står angivet i resursen. Det är dock viktigt att numret är korrekt. Ett annullerat ISSN-L hamnar i delfält 022 #m. För att kontrollera om ett angivet ISSN-L är riktigt kan man söka i en tabell (ISSN-L table) på ISSN International Centres webbplats.
022	0	_	#a 1654-1529 #l 1654-1529 #y 1651-0798 #z 1653-6770 #2 f

Upp
 
Anmärkningar om manifestationen (RDA 2.17)
Anmärkningar om manifestationen är inte kärnelement.
Gör anmärkning när det bedöms viktigt för identifikation, urval eller åtkomst.
Anvisningar för Importerade poster.
Citat
Ange källhänvisning för citat ur resursen såvida det inte är hämtat från den föredragna källan. Citatet ska anges inom citationstecken (RDA 1.10.3). Librispraxis är att ange källan före citatet. 
500	_	_	#a I redaktionsruta: "det folkliga boulevardbladet"
Anmärkning om källa för resursen som helhet
Om numret/delen som används för beskrivningen inte är det/den första, gör en anmärkning om vilket nummer eller vilken del som använts (RDA 2.17.13.3). För exempel, se Källa för resursen som helhet.
Anmärkning om titel 
Resurs som saknar titel
Om resursen saknar titel men titeln kan hämtas från en källa utanför resursen anges titeln inom klammer. Gör en anmärkning om varifrån titeln hämtats (RDA 2.3.2.10 och RDA 2.17.2.3)
Konstruerad titel
Om det inte går att fastställa en huvudtitel konstrueras en huvudtitel på svenska enligt anvisningarna i RDA 2.3.2.10. En konstruerad titel anges inom klammer. Gör en anmärkning om att titeln är konstruerad (RDA 2.17.2.3).
Felaktigheter
Felaktigheter i titeln för en seriell resurs rättas om det inte är ett medvetet fel som används i varje nummer eller del (RDA 2.3.1.4). Gör en anmärkning om den felaktiga titel (RDA 2.17.2.4). För exempel, se Felaktigheter under elementet Huvudtitel.
Källa för varianttitlar
Gör en anmärkning om källan för en varianttitel om det är viktigt för identifikation eller åtkomst (RDA 2.17.2.3). För exempel, se Övrig titelinformation. 
Förändring i huvudtitel
Om det sker en mindre förändring i huvudtiteln anges den efterföljande titeln som en varianttitel i fält 246 (RDA 2.3.2.12). Enligt Librispraxis är det obligatoriskt att ange efterföljande titel för tidskrifter och årsböcker. Om förändringarna är många kan dock alternativet tillämpas som är att göra generell anmärkning (RDA 2.17.2.4). För exempel, se Förändringar i huvudtiteln.
Förändring i parallell huvudtitel
Om en parallell huvudtitel tas bort i ett påföljande nummer eller i en påföljande del, ange detta i en anmärkning om det är av betydelse för identifikation eller åtkomst (RDA 2.17.2.4). För exempel, se Förändring i parallell huvudtitel.
Förändring i övrig titelinformation
Om övrig titelinformation tas bort i ett påföljande nummer eller i en påföljande del, ange detta i en anmärkning om det är av betydelse för identifikation och åtkomst (RDA 2.17.2.4). För exempel, se Förändring i övrig titelinformation.
Upp
Medietyp (RDA 3.2)
Medietyp är obligatoriskt enligt Librispraxis och anges i fält 337.
Medietyp anger vilken typ av enhet som behövs för att se, spela eller visa innehållet i resursen. 
Källor för beskrivningen av medietyp är resursen, medföljande material eller förpackning/behållare. Uppgifter kan även hämtas utanför resursen
I RDA 3.2.1.3 finns en lista med termer för medietyp. Listan, ”Term and Code List for RDA Media Types” finns översatt till svenska. Vid katalogisering i Libris, ange medietyp i kodad form i delfält #b. Ange även att koden/koderna hämtats från godkänd lista genom att ange "rdamedia" i delfält #2.
För textresurser används koden n (omedierad). 
337	_	 _	#b n #2 rdamedia

Om ingen av termerna i listan är lämplig, välj "annan" (x).
Om medietypen/medietyperna inte lätt kan bestämmas, välj "ospecificerad" (z).
Om resursen består av mer än en medietyp är Librispraxis att ange den medietyp som är tillämplig på den huvudsakliga delen av resursen. Ange inte medietyp för medföljande material av uppenbart underordnad karaktär.
245	1	0	#a CD-ROM & multimedia : #b den första kompletta CD-ROM-tidskriften för Mac & PC
337	_	 _	#b n #2 rdamedia
500	_	_	#a Varje nummer med CD-ROM som bilaga

Om resursen består av flera likvärdiga delar (kombinerat material) ange medietyp för alla delarna. 
Anvisningar för Importerade poster. 
Upp
Bärartyp, RDA 3.3
Bärartyp är ett kärnelement och anges i fält 338.
Bärartyp anger fysiskt medium för lagring samt den enhet som behövs för att se, spela eller visa innehållet i resursen. Bärartyperna korrelerar till medietyperna och kan ses som underindelningar till dessa. 
Källor för beskrivningen av bärare är resursen, medföljande material eller förpackning/behållare. Uppgifter kan även hämtas utanför resursen.

I RDA 3.3.1.3 finns en lista med termer för bärartyp. Listan, ”Term and Code List for RDA Carrier Types”, finns översatt till svenska. Vid katalogisering i Libris, ange bärartyp i kodad form i delfält #b. Ange även att koden/koderna hämtats från godkänd lista genom att ange "rdacarrier" i delfält #2. 
För tryckta seriella resurser är den vanligaste koden nc (volym). 
338	_	 _	#b nc #2 rdacarrier

Om ingen av termerna i listan är lämplig, välj "annan" (nz).
Om bärartypen/bärartyperna inte lätt kan bestämmas, välj "ospecificerad" (zu).
Om resursen består av mer än en bärartyp är Librispraxis att ange den bärartyp som är tillämplig på den huvudsakliga delen av resursen. Ange inte bärartyp för medföljande material av uppenbart underordnad karaktär.
245	1	0	#a CD-ROM & multimedia : #b den första kompletta CD-ROM-tidskriften för Mac & PC
338	_	 _	#b nc #2 rdacarrier
500	_	_	#a Varje nummer med CD-ROM som bilaga

Om resursen består av flera likvärdiga delar (kombinerat material) ange medietyp för alla delarna. 
Anvisningar för Importerade poster.
Omfång (RDA 3.4)
Omfång är ett kärnelement om resursen är komplett eller om det totala antalet fysiska enheter är känt. Librispraxis är dock att inte ange omfång för seriella resurser.
Mått (RDA 3.5)
Mått är inte ett kärnelement. Librispraxis är att inte ange mått som är standard för bäraren. 
NB-praxis: Mått anges inte för tidskrifter.
För anvisningar om hur man anger mått, se arbetsflödet Tryckta monografier.
Teckenstorlek (RDA 3.13)
För anvisningar om hur man anger teckenstorlek, se arbetsflödet Tryckta monografier.
Upp

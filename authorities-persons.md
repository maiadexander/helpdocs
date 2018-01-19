---
section: Auktoritetsarbete
title: Personer
order: 51
tags:
- editor
- rda
---

# Personer

Val av föredraget namn, konstruktion av sökingångar och utformning av auktoritetsposter.

[Extern länk till MARC21-anpassad information](http://www.kb.se/rdakatalogisering/personer/) 

## Innehåll

* [Definition av person](#paragraph1)
* [Anvisningar för personer - var i RDA?](#paragraph2)
* [Auktoritetspost - när behövs det?](#paragraph3)
* [Val av föredraget namn](#paragraph4)
* [Val mellan olika former av samma namn (fullständighet, språk, icke latinsk skriftart och stavning)](#paragraph5)
* [Klassiska grekiska, romerska och bysantinska personer](#paragraph6)
* [Namn skrivna med kyrillisk skrift - som translittererats](#paragraph7)
* [Namnbyte](#paragraph8)
* [Pseudonymer](#paragraph9)
* [Ordningselement (hur namnet sorteras)](#paragraph10)

### Definition av person  <a name="paragraph1"></a>

Med person avses i RDA en individ eller en identitet etablerad av en individ (antingen ensam eller i samarbete med en eller flera andra individer). Termen inkluderar även personer i heliga skrifter, fiktiva gestalter och ickemänskliga entiteter, till exempel djurskådespelare (RDA 8.1.2, RDA 9.0).

Sammanslutningar av personer, till exempel juridiska personer och musikgrupper, behandlas som organisationer.

För att avgöra om namnet ska auktoriseras som person, institution eller ämnesord konsulteras Library of Congress Alphabetical list of ambiguous headings. Här listas olika typer av ingångar med anvisningar om till vilken kategori var och en ska föras.

### Auktoritetsposter för personer – var i RDA?  <a name="paragraph2"></a>

**Att registrera attribut:**
* Allmänna riktlinjer: RDA kapitel 8
* Att identifiera personer: RDA kapitel 9

**Att ange relationer:**
* Allmänna riktlinjer: RDA kapitel 29
* Relaterade personer: RDA kapitel 30

**Appendix:**
* Stora och små bokstäver: RDA appendix A (Svenska skrivregler gäller dock i första hand)
* Förkortningar: RDA appendix B
* Interpunktion i sökingångar: RDA appendix E
* Tilläggsinstruktioner för personnamn (till exempel språk): RDA appendix F
* Adelstitlar etc.: RDA appendix G
* Tid i den kristna kalendern: RDA appendix H (Appendix H i svensk översättning)

(Relationsbeteckningar: RDA appendix K, används inte tills vidare.)

### Auktoritetspost - när behövs det?  <a name="paragraph3"></a>

Auktoritetspost upprättas när man har behov av att hänvisa från alternativa sökingångar eller när man har biografiska uppgifter om en person som är viktiga att dokumentera.

När en auktoritetspost upprättas anges den auktoriserade sökingången i fält 100.

Gör alltid auktoritetspost, för både svenska och utländska personer, när:

* en person har varierande namnformer som förs samman till ett föredraget namn. Gör se-hänvisningar från varianterna.
* en person har ett sammansatt släktnamn eller släktnamn med prefix. Gör se-hänvisningar från alla led.
* flera auktoritetsposter har upprättats för en individ (till exempel för verkligt namn och pseudonym). Gör se även-hänvisning mellan namnformerna.
* man har tillgång till biografiska uppgifter om en person.
* två eller flera personer har samma namnform och därför behöver särskiljas.

I Libris tillämpas praxisen att om inget passande tillägg finns, används samma sökingång för flera personer med samma namn. Upprätta inte någon auktoritetspost i sådana fall.

### Val av föredraget namn <a name="paragraph4"></a>

Föredraget namn är det namn eller den namnform som väljs som grund för den auktoriserade sökingången. (I den auktoriserade sökingången kompletterar man sedan det föredragna namnet med andra element, till exempel födelsetid, kunglig titel eller yrke.)

Det namn under vilket personen är mest känd väljs som föredraget namn (RDA 9.2.2.3).

För att bestämma under vilket namn en person är mest känd används följande källor (i prioriteringsordning):
1. de föredragna källorna, se RDA 2.2.2, i resurser knutna till personen
2. andra formella uppgifter som förekommer i resurser knutna till personen
3. övriga källor (till exempel referenskällor)

Men observera att:
* vissa namn har en vedertagen svensk form. Det gäller till exempel helgon, kungligheter, påvar, biskopar etc., klassiska grekiska, romerska och bysantinska personer samt personer verksamma före år 1400.
* för utländska personer verksamma efter år 1400 hämtas namnformen oftast från respektive lands nationalbibliografi (många finns i VIAF) eller konstrueras med hjälp av Names of persons. Läs mer under Källor.
* för personer som byter namn gäller i princip att det senaste namnet väljs som föredraget namn, se Namnbyte.
* en person kan ha mer än en identitet och då upprättas flera auktoritetsposter. Läs mer under Se även-hänvisningar.

Följ de generella riktlinjerna för att ange namn (till exempel för namn som innehåller initialer eller förkortningar) i RDA 8.5. 

### Val mellan olika former av samma namn <a name="paragraph1"></a>

Om en person är känd under mer än en form av samma namn, välj föredraget namn genom att följa anvisningarna i RDA 9.2.2.5 angående:

* fullständighet
* språk. Läs bland annat om Grekiska och latinska former kontra former på personens eget språk och om Klassiska grekiska, romerska och bysantinska personer
* namn skrivna i icke latinsk skriftart. Läs bland annat om Namn skrivna med kyrillisk skrift - som translittererats i den deskriptiva katalogiseringen
* stavning

### Fullständighet

Om formerna för en persons namn varierar i fullständighet, välj som föredraget namn den vanligaste formen (RDA 9.2.2.5.1).
Om ingen form dominerar, välj den senaste formen som föredraget namn. Vid tvekan, välj den mer fullständiga formen.

**Exempel** 
`Text`

### Språk

Om en persons namn förekommer på olika språk i resurser som är knutna till personen, välj som föredraget namn den namnform som förekommer i flest resurser (RDA 9.2.2.5.2).

Om namnet inte förekommer i resurser som är knutna till personen, eller vid tveksamhet, välj den form som är vanligast förekommande i referenskällor från den personens hemland eller det land personen är verksam i. Denna paragraf har två undantag: Grekiska och latinska former kontra former på personens eget språk och Vedertagen svensk namnform.

För Libris har utarbetats praktiska anvisningar för klassiska grekiska, romerska och bysantinska personer. Grekiska och latinska former kontra former på personens eget språk

Olika namnformer återfinns ibland i referenskällor och i resurser knutna till en person. Om namnet på personen återfinns både i en grekisk eller latinsk form och i en form på personens eget språk, välj som föredragen form den form som är mest förekommande i referenskällor i det land personen verkade. 

Vid tveksamhet, välj den grekiska eller latinska formen för personer verksamma före år 1400 och en form på personens eget språk för personer verksamma efter 1400.

För utländska personer verksamma efter år 1400 betyder det i allmänhet att man använder den nationella namnformen, som hämtas från VIAF eller respektive lands nationalbibliotek.

Se även nedan om Vedertagen svensk namnform.

Gör en auktoritetspost och hänvisa till variantformer av namnet under vilken personen också är känd. Hänvisa till den namnform LC eller respektive nationalbibliotek använder (sök i VIAF).

Latinska namnformer ska anges i nominativ. Om man är osäker får man ofta hjälp av Deutsche Nationalbibliothek (sök i VIAF) eller CERL Thesaurus:

För en utländsk person verksam efter år 1400 använder man normalt den form som personens lands nationalbibliotek använder.
Nederländernas nationalbibliotek har valt den latinska formen:

**Exempel** 
`Text`

Det är vanligt att svenska namnformer förekommer i latinsk form in på 1700-talet. Välj den svenska namnformen som föredraget namn. Den latinska namnformen ska finnas med som hänvisning i auktoritetsposten:

**Exempel** 
`Text`
 
### Vedertagen svensk namnform

Om det första elementet i en persons föredragna namn består av ett förnamn och/eller ett ord eller en fras knutet/knuten till personen, se RDA 9.2.2.18, bestäm namnform med hjälp av referenskällor. Om det finns en väletablerad namnform på svenska, välj den som föredraget namn. Vid tveksamhet, välj en form på personens språk eller den latinska formen.

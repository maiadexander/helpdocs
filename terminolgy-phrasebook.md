---
section: Terminologi
title: Parlör
order: 40
tags:
- bibframe
- rda
---

# Terminologi
## Kort parlör

[Extern länk till Libris undersidor](http://www.kb.se/libris/Om-LIBRIS/Introduktion-till-nya-Libris-och-XL/BIBFRAME-svensk-terminologi/)

|**XL**|**Voyager**|**Klartext**|**RDA**|**RDF**|**Kommentar**|
|:------------- |:------------- |:----- |:----- |:----- |:----- |
|Agent |1XX/7XX, 260/264 #b, 600/610/611 |Huvuduppslag/biuppslag personnamn/institutionsnamn/konferensnamn, Ämnesord personnamn/institutionsnamn/konferensnamn |Agent | | |
|Benämning | | |rdfs:label |En instans av en egenskap som kan användas för en läsbar version av en resurs namn.
Exempel: ämnesordet: Matlagning eller omfångsuppgiften: 77 sidor |
|Bestånd |Hldngs |Bestånd | | | |
|Exakt match? |Auth: 4XX |Se-hänvisning |Variantnamn och alternativa sökingångar (se-hänvisningar) | | |
|Funktion |1XX/7XX #4 |Funktionskod |Relationsbeteckning | | |
|Instans | | |Maniestation | | |
|Jurisdiktion |110/710 i1:1 |Institutionsnamn, Namn på administrativ enhet |Officiellt organ | | |
|Kod | | | | |Teckensträng som används för koder som representerar information. Exempel: Dewey-koden: 839.738, språkkoden: fre|
|Koncept |006-008, 082-084, 648, 650, 651, 653, 655 |Kompletterande mediespecifika koder/Koder för fysiska bäraregenskaper/Mediespecifika koder/Klassifikation/Kronologiska/Allmänna/Geografiska ämnesord/Indexterm - kontrollerad/Genre/form |- |- | |skos:concept | |
|Medverkan |7XX |Biuppslag personnamn/institutionsnamn/konferensnamn |Bidragsgivare: person/institution/konferens, skapare: person/institution/konferens (om fler än en) | |
|Möte |110/610/710, 111/611/711 |Konferensnamn |Konferens | | |
|Organisation |110/710 i1:2 |Institutionsnamn, Namn i rak följd |Institution | | |
|Persona? | | |Variantnamn | | |
|Plats |260 #a #e, 264 #a, 370 #c #e #f |Utgivningsort, Ort/Plats, Associerad plats/ort |Ort - kommer att ändras till Plats | | |
|Primär medverkan |1XX |Huvuduppslag personnamn/institutionsnamn/konferensnamn |Skapare: person/institution/konferens | | |
|Släkt |600 i1:3 |Beteckning för hel släkt |Familj/släkt - kommer att ändras till Släkt | | |
|Utgivningssätt |000/07 |Bibliografisk nivå |Utgivningssätt | | |
|Verk | | |Verk, Uttryck | | |
|Värde | | | |rdf:value |En instans av en egenskap som kan användas för att beskriva strukturerade värden. Exempel: ISBN: 9789185352951, ISSN: 0065-0897, systemnummer: 13457927 |

# Förslag 

|**XL**|**Voyager**|**Klartext**|**Exporterad MARC21**|
|:------------- |:------------- |:----- |:----- |:----- |:----- |
|Agent |1XX/7XX, 260/264 #b, 600/610/611 |Huvuduppslag/biuppslag personnamn/institutionsnamn/konferensnamn, Ämnesord personnamn/institutionsnamn/konferensnamn |Agent |
|Benämning | | |rdfs:label |En instans av en egenskap som kan användas för en läsbar version av en resurs namn.
Exempel: ämnesordet: Matlagning eller omfångsuppgiften: 77 sidor |
|Bestånd |Hldngs |Bestånd | |
|Exakt match? |Auth: 4XX |Se-hänvisning |Variantnamn och alternativa sökingångar (se-hänvisningar) | 
|Funktion |1XX/7XX #4 |Funktionskod |Relationsbeteckning | 
|Instans | | |Maniestation | 
|Jurisdiktion |110/710 i1:1 |Institutionsnamn, Namn på administrativ enhet |Officiellt organ | 
|Kod | | | | |Teckensträng som används för koder som representerar information. Exempel: Dewey-koden: 839.738, språkkoden: fre|
|Koncept |006-008, 082-084, 648, 650, 651, 653, 655 |Kompletterande mediespecifika koder/Koder för fysiska bäraregenskaper/Mediespecifika koder/Klassifikation/Kronologiska/Allmänna/Geografiska ämnesord/Indexterm - kontrollerad/Genre/form | | | 
|Medverkan |7XX |Biuppslag personnamn/institutionsnamn/konferensnamn |Bidragsgivare: person/institution/konferens, skapare: person/institution/konferens (om fler än en) | |
|Möte |110/610/710, 111/611/711 |Konferensnamn |Konferens | 
|Organisation |110/710 i1:2 |Institutionsnamn, Namn i rak följd |Institution | 
|Persona? | | |Variantnamn | 
|Plats |260 #a #e, 264 #a, 370 #c #e #f |Utgivningsort, Ort/Plats, Associerad plats/ort |Ort - kommer att ändras till Plats |
|Primär medverkan |1XX |Huvuduppslag personnamn/institutionsnamn/konferensnamn |Skapare: person/institution/konferens | 
|Släkt |600 i1:3 |Beteckning för hel släkt |Familj/släkt - kommer att ändras till Släkt | 
|Utgivningssätt |000/07 |Bibliografisk nivå |Utgivningssätt |
|Verk | | |Verk, Uttryck |
|Värde | | | 
# Old:

|**XL**|**Voyager**|**MARC21 (RDA)**|
|:------------- |:------------- |:----- |
|Verk |Verk, som i Verktitel |Verk, Uttryck |
|Instans |- |Manifestation |
|Medverkan |1XX/7XX | Skapare, Bidragsgivare? |
|Primär medverkan |1XX |Skapare? |
|Agent |1XX/7XX |Agent |
|Funktion |1XX/7XX |Relationsbetckning |
|Släkt |600 i1:3 |Familj/släkt - kommer att ändras till Släkt |
|Organisation |110/710 i1:2 |Institution (vidare term än Organisation) |
|Jurisdiktion |110/710 i1:1 |Officiellt organ? |
|Möte |111/611/711 |(kommer att ingå i Kollektiv agent enl. LRM) |
|Händelse | |Exempel på RES enl. LRM |
|Koncept |6XX |Inte kvar i Bibframetexten - ersattes med "saker" - kanske ändra tillbaka till Koncept! |
|Benämning |Innehållet i ett fält, t ex ett ämnesord, ett namn, en titel |- |
|Exemplar | |Exemplar |
|Bestånd |852 | | 


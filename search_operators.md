---
section: Sök
title: Utforma sökfrågor
order: 1
tags:
- search
---

# Sök

## Operatorer för frågespråk

   `+` används för OCH 
   `"` används för frassökning i exakt ordning
   `|` används för ELLER 
   `-` utesluter term
   ´(´ och ´)´ grupperar termer och operatorer
   `*` trunkerar term

### Standardsökning

En standardsökning ger träff på sammanslagen sökterm. En sökning på `Astrid Lindgren` kommer matcha poster innehållandes `Astrid` och `Lindgren`, `Astrid Lindgren`. Sökningen ger även träff på `Lindgren Astrid`. Båda sökorden kommer att finnas med i posten. 

### Exakt sökning

Om du vill söka på en exakt fras, använd `"`. En sökning på `"Emil i Lönneberga"` ger träff på fras i angiven ordning. 

### Eller

Om du vill söka på eller, använd `"|"`. Exempelvis ger `"Tove Jansson" | "Astrid Lindgren"` träff på `Tove Jansson` eller `Astrid Lindgren`.

### Exkludera termer

Om du vill exkludera en term, använder `-`. Exempelvis ger `Astrid -Lindgren` träff på alla träffar som innehåller `Astrid` men inte `Lindgren`.

### Gruppering av termer 

Om du vill gruppera termer och operatorer, använd `(` och `)`. Exempelvis ger en sökning på `(Tove | Lars) Jansson`träff på Tove eller Lars Jansson. Utan parenteserna söker du efter `Tove` eller `Lars Jansson`, men med parenteserna söker du på `Tove Jansson` eller `Lars Jansson`

### Trunkering

Om du vill trunkera, använd `*`. Trunkering ger träff på alla ändelser efter prefixet. Exempelvis ger `sol*` träff på bland andra `solros` , `sola` och `solig`.

---
section: Sök
title: Utforma sökfrågor
order: 1
tags:
- search
---

# Sök

## Operatorer för frågespråk

`+` betyder AND
`"` används för frassökning i exakt ordning
`|` betyder OR
`-` innebär uteslutning av term
´(´ och ´)´ grupperar termer och operatorer
`*` trunkering av en term

### Standardsökning

En standardsökning ger träff på sammanslagen sökterm, `AND`. En sökning på `Astrid Lindgren` kommer matcha poster innehållandes `Astrid` och `Lindgren`, `Astrid Lindgren`. Sökningen ger även träff på ´Lindgren Astrid.´ Båda sökorden måste finnas i posten. 

### Exakt sökning

Om du vill söka på en exakt fras, använd ´"´. En sökning på "Emil i Lönneberga" ger träff på samma fras i angiven ordning. 

### Eller

Om du vill söka på ´Tove Jansson´ eller ´Astrid Lindgren´, använd ´"|"´ ´Exempel: "Tove Jansson" | "Astrid Lindgren"´.

### Exkludera termer

Om du vill exkludera en term använder du ´-´. Exempelvis ger ´Astrid -Lindgren´ träff på alla träffar som innehåller ´Astrid´ men inte ´Lindgren´.

### Gruppering av termer 

´(´ och ´)´ grupperar termer och operatorer. Exempelvis ger en sökning på 

Om du vill ha en sökning på Tove eller Lars Jannson, använd ´(Tove | Lars) Jansson´. Utan parenteserna söker du efter ´Tove´ eller ´Lars Jansson´, men med parenteserna söker du på ´Tove Jansson´ eller ´Lars Jansson´

### Trunkering

Trunkering sker med ´*´ och ger träff på alla ändelser efter prefixet. Exempelvis ger ´sol*´ ger träff på bland annat 'solros' , ´sola´ och ´solig´.

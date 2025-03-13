# 3D_Platformer

## Översikt
Detta är ett enkelt 3D-plattformsspel utvecklat i Godot med GDScript. Spelet går ut på att spelaren navigerar en 3D-miljö, samlar mynt och undviker fiender som patrullerar området. Målet är att samla så många mynt som möjligt innan tiden tar slut eller spelaren träffas av en fiende.

## Spelmekanik
- **Spelarkontroll:** Spelaren styrs med WASD-tangenterna och hoppar med mellanslag.
- **Fiender:** Fiender patrullerar en specifik sträcka och rör sig automatiskt.
- **Samlarobjekt:** Mynt placeras ut i banan. När spelaren nuddar ett mynt, försvinner det och spelarens poäng ökar.
- **Vinst-/Förlustvillkor:** Om spelaren faller under en viss nivå eller träffas av en fiende, visas en Game Over-skärm. Vid insamling av alla mynt kan ett vinstmeddelande visas.

## Designskiss
- **Utseende:**  
  Spelet har en minimalistisk 3D-stil med enkla geometriska former. Spelaren representeras av en kapsel eller kub, miljön av plana ytor och väggar, medan fiender och mynt är enkla former med olika färger.
  
- **Spelupplägg:**  
  Spelaren börjar i huvudmenyn och startar spelet med en knapptryckning. I spelets värld navigerar spelaren genom plattformar, samlar mynt och undviker fiender. Om spelaren lyckas samla alla mynt inom tiden vinner hen, annars förlorar hen om hen träffas av en fiende eller faller ut ur banan.



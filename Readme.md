# Tic Tac Toe
Ett litet exempel på luffarschack

## beskrivning av lösningen
- Spelplanen representeras av en array av chars (NxN)
- Spelaren anger rad och kolumn när drag görs
- Om spelaren skriver in en position som redan är tagen får spelaren göra om draget
- Spelet tar slut när det inte finns tomma rutor eler när någon spelare fått M i rad
- Algoritmen för att hitta en vinnare bygger på att gå igenom hela spelplanen och för varje position kontrollera om det finns M likadana till höger, neråt, diagonalt neråt åt höger eller diagonalt neråt åt vänster

`[_ _ _ X > > _ _ _]`

`[_ _ x v x _  _ _ _]`

`[_ x _ v _ x  _ _ _]`

`[_ _ _ _  _  _ _ _ _]`

`[_ _ _ _  _  _ _ _ _]`

`[_ _ _ _  _  _ _ _ _]`

`[_ _ _ _  _  _ _ _ _]`

`[_ _ _ _  _  _ _ _ _]`

`[_ _ _ _  _  _ _ _ _]`

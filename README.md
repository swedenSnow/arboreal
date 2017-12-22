Arboreal || Häni Abu Zeid FEND17

Utgångspunkten när jag startade denna uppgift var att lära mig mer om flexbox. 
Jag valde en single-page lösning, och gjorde 2 sidor som jag skrotade.
Designen återspeglar också tidsnöden jag hamnade i och mycket lämnas att önska.






Validerade HTML och CSS och fick inga fel.
---------------------------------------------------------------------------------------------
"Document checking completed. No errors or warnings to show."
---------------------------------------------------------------------------------------------
"W3C CSS-valideringsresultat för style.css (CSS nivå 3)

Gratulerar! Inga fel har hittats"
---------------------------------------------------------------------------------------------
FEEDBACK (Mikael Larsson):

Jag skulle gjort intenderingen annorlunda i HTML filen.
Som den är nu känns den lite svårläst för att följa flödet.

Input type skulle kunna vara email på E-mail input.
Vet inte om du behöver listor när du bara har 1 list item.

Det finns en bortkommenterad rad som finns under.

CSS:en Känns bra, det är bara lite mellanslag och lite radbrytningar här och där som kunde snyggat upp den.
Och tagit bort kod som inte används och är bortkommenterad.

Namngiviningen är tydlig tror inte jag såg något jag inte förstod.
Dock så skulle premium exclusive och standard namnges ännu tydligare för att verkligen följa resten.

Överflödig CSS
Det känns som det finns klasser som är väldigt lika förutom på ett par punkter.
Vet inte om det är bättre eller sämre men de skulle kunna delas upp och göra klasser för de som de har gemensamt.


Ändringar i Design

Skuggningen på texten uppe till vänster gör att den känns "trasig".

Jag förstår valet av samma bakgrund på pricing och themes, har du testat olika bakgrundsfärger för att tydliggöra vart gränsen går.
Top-marginalen till themes känns större än pricing.

Vet inte om du behöver target sidan på kontaktformuläret kanske bara skulle lämna den tom.

Facebook och Twitter adressen står längst ner, men länkar inte till sidorna. Ikonerna för Facebook och Twitter länkar bara till själva huvudsidan.
-----------------------------------------------------------------------------------------

Jag tog till mig av all feedback och ändrade sidan därefter. Jag tog även bort ikonerna för facebook och twitter för det såg snyggare ut utan.

Jag valde min första breakpoint för telefon på 375px(som är iphone 6,7,8 och X använder),där sloganen försvinner och endast navbaren och loggan är kvar i headern. Vidare transformerar jag alla boxar till 100% flex-basis för att fördela dom snyggare när sidan blir mindre, och responsivt som 'mostly fluid'. 
Även samma orsak för tablett, på 768px. Även min form-text lägger sig i mitten av fältet istället för till vänster, och loggan längst ner försvinner. Detta tar även hand om mobiler större än 375px med att flexa boxarna så dom är lika stora. 

Jag la även in vendor prefixes för border och flex. 

Jag började med graceful degradation, men tidsnöden gjorde att jag inte hann längre. 






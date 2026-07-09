# Handoff

Sist oppdatert: 2026-07-09

## Prosjektstatus

Prosjektet er en statisk nettside for den fiktive virksomheten "Theodor Sandaker". Hovedfilen er `Bedriften-theodor-sandaker.html`. Nettsiden kan åpnes direkte i nettleser uten byggesteg.

Ansattkortene ligger i JavaScript-arrayen `employees` i HTML-filen. Kortene er sortert alfabetisk. De fleste ansatte har bilde koblet via `image:"ansattbilder/<filnavn>.png"`. Roller uten ferdig bilde ligger foreløpig bare i prosjektbeskrivelsen/todo-listen, ikke nødvendigvis i HTML-arrayen.

## Viktige filer og mapper

- `Bedriften-theodor-sandaker.html` - selve nettsiden.
- `ansattbilder/` - aktive ansattbilder som nettsiden bruker.
- `ansattbilder/Tidligere versjoner/` - arkiv for eldre versjoner av regenererte bilder.
- `Referansebilder/` - bilder av Theodor som brukes som identitetsreferanser ved bildebruk.
- `Presentasjon av bedriften «Theodor Sandaker» prosjektbeskrivelse og ansatte.md` - lang arbeidsbeskrivelse med ansatte, beskrivelser, visuelle særtrekk og historikk.
- `todo.md` - kort statusliste over ferdige og gjenstående ansattbilder.
- `prosjektbeskrivelse.md` - kompakt prosjektbeskrivelse for videre arbeid.

## Arbeidsflyt for ansattbilder

1. Les brukerens rollebeskrivelse og eventuelle vedlagte referansebilder.
2. Bruk referansebildene i `Referansebilder/` for ansikt/identitet.
3. Generer et kvadratisk fotorealistisk ansattportrett.
4. Hvis rollen allerede har aktivt bilde i `ansattbilder/`, flytt dette først til `ansattbilder/Tidligere versjoner/<rolle>-YYYY-MM-DD-HHMMSS.png`.
5. Lagre valgt bilde i `ansattbilder/` med stabilt filnavn.
6. Koble bildet i `Bedriften-theodor-sandaker.html`.
7. Oppdater `todo.md` og eventuelt den lange prosjektbeskrivelsen.

## Nåværende gjenstående bildearbeid

- Renholder
- HMS-ansvarlig
- Kantinemedarbeider
- Revisor
- Rekvisittansvarlig
- Løvetemmer
- IT-ansvarlig
- Overgangsleder (transition manager)
- Game show host
- Eventyrforteller

## Nylige endringer som er verdt å vite

- `trener.png` ble regenerert for å ligne mer på Theodor. Forrige versjon ble arkivert i `ansattbilder/Tidligere versjoner/`.
- `kursholder-giraffspraket.png` ble generert og koblet til `Kursholder i giraffspråket`.
- `speiderleder.png` ble generert og koblet til `Speiderleder`.
- `filosof.png` ble tidligere regenerert med Aristoteles-inspirert hår og skjegg.
- `kurator.png` ble ferdigstilt manuelt av bruker i ChatGPT og skal ikke overskrives uten ny beskjed.

## Stil og innhold

Nettsiden har varm, lett absurd og karakterdrevet tone. Ansattbeskrivelsene skal være korte, humoristiske og presise. Bildene skal være fotorealistiske, kvadratiske og tydelig karikerte gjennom rolle, rekvisitter og miljø, men med Theodors ansikt/identitet.

Unnga lesbar tekst i bilder. Unnga logoer, varemerker og kopiering av identiteten til referansepersoner; bruk referanser kun for klær, positur, rekvisitter og uttrykk når det er relevant.


# Prosjektbeskrivelse

## Kort fortalt

"Bedriften Theodor Sandaker" er en statisk, humoristisk presentasjonsside for en fiktiv virksomhet der alle ansatte er ulike roller, sider og fagfunksjoner hos samme person. Prosjektet kombinerer korte rollebeskrivelser med fotorealistiske ansattportretter.

## Teknisk oppsett

Prosjektet er enkelt og flyttbart:

- Ingen byggesteg.
- Ingen pakkeavhengigheter.
- Hovedsiden er `index.html`.
- Bilder ligger relativt til HTML-filen i `ansattbilder/`.
- Referansebilder for ansiktsidentitet ligger i `Referansebilder/`.

Åpne `index.html` direkte i nettleseren for å se nettsiden.

## Innholdsstruktur

Ansatte defineres i `employees`-arrayen nederst i HTML-filen. Hvert objekt har normalt:

- `title` - rollen/stillingstittelen.
- `emoji` - fallback-symbol hvis bilde mangler.
- `bg` - bakgrunnsfarge for fallback.
- `image` - relativ sti til ansattbildet.
- `desc` - kort tekst på nettsiden.

Eksempel:

```js
{ title:"Trener", emoji:"🏋️", bg:"#e8e0b8", image:"ansattbilder/trener.png",
  desc:"Har teknisk blikk, høy intensitet og et litt personlig forhold til progresjon." },
```

## Visuell retning

Ansattbildene skal være kvadratiske, fotorealistiske portretter med tydelig rolleidentitet. De skal vise Theodor i ulike kostymer, miljøer og rekvisitter. Referansebilder av Theodor brukes for ansikt, alder, hud, øyne, ansiktsform og grunnidentitet. Andre referansebilder brukes bare til klær, positur, rekvisitter, stil eller hår/skjegg når brukeren ber om det.

Når nye versjoner av eksisterende bilder lages, skal forrige aktive bilde alltid flyttes til `ansattbilder/Tidligere versjoner/` før ny versjon legges inn.

## Nåværende status

De fleste rollene på nettsiden har ferdige bilder og er koblet i HTML-filen. Gjenstående bildearbeid er samlet i `todo.md`.

Den lange arbeidsbeskrivelsen ligger i `Presentasjon av bedriften «Theodor Sandaker» prosjektbeskrivelse og ansatte.md` og inneholder mer detaljerte rollebeskrivelser, visuelle særtrekk og todo-historikk.

## Tone

Tekstene skal ha en varm og tørr humor. Rollen skal virke som en ekte stilling i en usedvanlig tverrfaglig virksomhet, men med et tydelig absurd eller selvobserverende preg. Beskrivelsene bør være korte nok til å fungere på kort, men konkrete nok til at hvert bilde får særpreg.


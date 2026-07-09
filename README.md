# Bedriften «Theodor Sandaker»

En statisk, humoristisk presentasjonsside for en fiktiv virksomhet der alle «ansatte» er ulike roller, sider og fagfunksjoner hos én og samme person. Prosjektet kombinerer korte, tørrvittige rollebeskrivelser med fotorealistiske ansattportretter.

## Kom i gang

Prosjektet krever ingen byggesteg og ingen avhengigheter. Åpne hovedfilen direkte i nettleseren:

```
Bedriften-theodor-sandaker.html
```

## Struktur

| Fil / mappe | Innhold |
| --- | --- |
| `Bedriften-theodor-sandaker.html` | Selve nettsiden. Ansatte defineres i `employees`-arrayen nederst i filen. |
| `ansattbilder/` | Aktive ansattbilder som nettsiden bruker. |
| `prosjektbeskrivelse.md` | Kompakt prosjektbeskrivelse. |
| `handoff.md` | Statusoverlevering og arbeidsflyt. |
| `todo.md` | Statusliste over ferdige og gjenstående ansattbilder. |
| `Presentasjon av bedriften …md` | Lang arbeidsbeskrivelse med detaljerte rollebeskrivelser. |

## Legge til en ansatt

Hvert ansattkort er et objekt i `employees`-arrayen i HTML-filen:

```js
{ title:"Trener", emoji:"🏋️", bg:"#e8e0b8", image:"ansattbilder/trener.png",
  desc:"Har teknisk blikk, høy intensitet og et litt personlig forhold til progresjon." },
```

- `title` – rollen/stillingstittelen
- `emoji` – fallback-symbol hvis bilde mangler
- `bg` – bakgrunnsfarge for fallback
- `image` – relativ sti til ansattbildet
- `desc` – kort tekst på kortet

## Tone

Varm og tørr humor. Hver rolle skal virke som en ekte stilling i en usedvanlig tverrfaglig virksomhet, men med et tydelig absurd og selvobserverende preg.

## Merknad

Personlige referansefoto (`Referansebilder/`) og arkivet over tidligere bildeversjoner (`ansattbilder/Tidligere versjoner/`) er holdt utenfor dette repoet og er ikke nødvendige for å kjøre nettsiden.

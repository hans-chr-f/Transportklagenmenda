# Juss og språkmodeller anno 2024

Denne nettsiden dokumenter teknologibruk og framgangsmåte i forskningen som ligger til grunn for artikkelen *Juss og språkmodeller anno 2024* som er publisert i XXXX.

I prosjektet utforsker vi språkteknologi og anvender store språkmodeller og vektordatabaser med dokumentembeddinger for å løse rettsspørsmål. Vi har valgt å gå inn på et avgrenset område, transportrett og å avgrense oss til å løse transportrettslige spørsmål med vekt på vedtak fra Transportklagenemnda.

Transportklagenemnda egner seg godt til en slik undersøkelse. For det første er en omfattende praksis (over 12000 vedtak) tilgjengelig. For det andre er hvert enkelt vedtak relativt kort. 


## Framgangsmåte

1. [Etablering av korpus med vedtak fra Transportklagenemnda.](https://github.com/hans-chr-f/Transportklagenmenda/blob/main/Etablering_av_vedtakskorpus.ipynb)  
Først laster vi ned alle vedtak fra transportklagenemnda som pdf-filer. Disse konverterer vi så til rene tekst filer. Vi prosesserer også alle vedtakene og fjerner navn på alle nemndsmedlemmer.
2. Parsing av vedtak
3. Embedding av dokumenter og opplasting til vektordatabase.
4. RAG
5. Løsing av rettspørsmål


## Kontakt

- Hans Christian Farsethås
- Anders Løvlie
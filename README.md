# Juss og språkmodeller anno 2025

Denne nettsiden dokumenter teknologibruk og framgangsmåte i forskningen som ligger til grunn for artikkelen *Juss og språkmodeller anno 2025* som er publisert i XXXX.

I prosjektet utforsker vi språkteknologi og anvender store språkmodeller og vektordatabaser med dokumentembeddinger for å løse rettsspørsmål. Vi har valgt å gå inn på et avgrenset område, transportrett og å avgrense oss til å løse transportrettslige spørsmål med vekt på vedtak fra Transportklagenemnda.

Transportklagenemnda egner seg godt til en slik undersøkelse. For det første er en omfattende praksis (over 14000 vedtak) tilgjengelig. For det andre er hvert enkelt vedtak relativt kort. 


## Framgangsmåte

1. [Etablering av korpus med vedtak fra Transportklagenemnda.](https://github.com/hans-chr-f/Transportklagenmenda/blob/main/Etablering_av_vedtakskorpus.ipynb)  
Først laster vi ned alle vedtak fra transportklagenemnda som pdf-filer. Disse konverterer vi så til ren tekst. Vi fjerner opplysninger (navn) om nemndsmedlemmer.
2. [Parsing av vedtak.](https://github.com/hans-chr-f/Transportklagenmenda/blob/main/Parsing_av_vedtak.ipynb) Vi leser ut informasjon om hvilken delnemnd som har skrevet vedtaket (fly, sjø, kollektivreiser, pakkereiser). Vi leser også ut en unik id fra filnavnet. Så lager vi denne informasjonen på et felles format sammen med vedtakene (jsonl).
3. Embedding av dokumenter og opplasting til vektordatabase.
4. RAG
5. Løsing av rettspørsmål


## Kontakt

- Hans Christian Farsethås
- Anders Løvlie
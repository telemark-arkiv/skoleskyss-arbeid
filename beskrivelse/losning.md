# Løsningsbeskrivelse

## Arbeidsflyt

Søkeren går til nettadressen [selvbetjening.t-fk.no](https://selvbetjening.t-fk.no) og logger seg inn via ID-porten.

Ved vellykket innlogging kommer man til selve søknadskjemaet. Fødselsnummeret vil være ferdig utfylt.

Skjemaet sendes inn og mellomlagres i en database.

Søknaden hentes ut fra databasen, sendes gjennom en saksbehandlingsmodul, lagres som en .json-fil og slettes fra databasen ved vellykket saksbehandling.

Filen plukkes opp av en ekspederingsmodul som genererer kvittering og svarbrev.

Kvittering og svarbrev sendes til søkeren via SvarUt.

All kommunikasjon lagres i sak/arkiv-systemet public360.

## Teknisk oppsett

- [Teknisk oppsett](oppsett.md)

- [Moduloversikt](moduler.md)

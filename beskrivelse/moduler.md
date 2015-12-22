# Moduler

Det er utviklet en rekke moduler i forbindelse med skoleskyss. Alle er gjort under åpne lisenser og ligger fritt tilgjengelig på GitHub.

Modulene er selvstendige og kan byttes ut med andre så sant de kommuniserer via samme API.

Beskrivelse og eventuelle tilleggskrav ligger på hver enkelt modul.

## Søknadskjema
Alle moduler som brukes til søknadsskjemaet

- [tfk-form-skoleskyss](https://github.com/telemark/tfk-form-skoleskyss) - frontend/skjema
- [api.t-fk.no](https://github.com/telemark/api.t-fk.no) - backend
- [tfk-api-session](https://github.com/telemark/tfk-api-session) - backend/oppslag
- [tfk-api-postnummer](https://github.com/zrrrzzt/tfk-api-postnummer) - backend/oppslag
- [tfk-api-forms](https://github.com/zrrrzzt/tfk-api-forms) - backend/lagring

## Saksbehandling
Alle moduler som brukes til saksbehandling

- [tfk-saksbehandling](https://github.com/telemark/tfk-saksbehandling) - rammeverk
- [tfk-saksbehandling-skoleskyss](https://github.com/telemark/tfk-saksbehandling-skoleskyss) - plugin
- [tfk-dsf](https://github.com/telemark/dsf) - oppslag DSF
- [tfk-utils-fix-address-for-seeiendom](https://github.com/telemark/tfk-utils-fix-address-for-seeiendom) - formattere adresser for seeiendom
- [seeiendom](https://github.com/zrrrzzt/seeiendom) - oppslag Seeiendom
- [tfk-saksbehandling-skoleskyss-nsb](https://github.com/telemark/tfk-saksbehandling-skoleskyss-nsb) - filter
- [tfk-saksbehandling-skoleskyss-tbr](https://github.com/telemark/tfk-saksbehandling-skoleskyss-tbr) - filter
- [tfk-saksbehandling-skoleskyss-fara](https://github.com/telemark/tfk-saksbehandling-skoleskyss-fara) - filter
- [tfk-api-distance](https://github.com/zrrrzzt/tfk-api-distance) - Beregning av avstand

## Ekspedering
Alle moduler som brukes til ekspedering

- [tfk-run-skoleskyss](https://github.com/telemark/tfk-run-skoleskyss) - starter behandling/ekspedering
- [tfk-flow](https://github.com/telemark/tfk-flow) - setter opp dokumenter og SvarUt
- [tfk-templater](https://github.com/telemark/tfk-templater) - genererer dokumenter
- [tfk-svarut](https://github.com/telemark/tfk-svarut) - sender til SvarUt 
- [360Import](https://github.com/telemark/360import) - importerer til 360

## Ubrukte moduler
Moduler som ble utviklet undervegs, men som ikke ble benyttet til slutt

- [utils-geocode-adresses](https://github.com/telemark/utils-geocode-address) - geokode adresser
- [is-valid-fodselsnummer](https://github.com/zrrrzzt/is-valid-fodselsnummer) - validere fødselsnummer
- [tfk-api-stages](https://github.com/zrrrzzt/tfk-api-stages) - holdeplasser i Telemark
- [tfk-api-geocode](https://github.com/zrrrzzt/tfk-api-geocode) - geocode API
- [tfk-api-schools](https://github.com/zrrrzzt/tfk-api-schools) - Skoler i Telemark, geokodet

## PoC moduler
Proof of concept moduler er laget for å teste muligheter

- [poc-skoleskyss-avstand](https://github.com/zrrrzzt/poc-skoleskyss-avstand) - beregne avstand
- [poc-map-render](https://github.com/zrrrzzt/poc-map-render) - skjermbilde av kart
- [tfk-api-unoconv] (https://github.com/zrrrzzt/tfk-api-unoconv) - unoconv som webservice
- [docker-unoconv-webservice](https://github.com/zrrrzzt/docker-unoconv-webservice) - dockerimage for tfk-api-unoconv

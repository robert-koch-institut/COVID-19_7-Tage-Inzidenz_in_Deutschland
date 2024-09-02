### Variable specification for data file `frictionless_data_schema_COVID-19-Faelle_7-Tage-Inzidenz_Bundeslaender`

| Variable        | Typ     | Ausprägungen                                                     | Beschreibung                                                                                                                            |
|:----------------|:--------|:-----------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|
| Meldedatum      | date    | Format: `%Y-%m-%d`                                               | Datum, an dem das lokale Gesundheitsamt Kenntnis über den Fall erlangt und ihn elektronisch erfasst hat                                 |
| Bundesland_id   | string  |                                                                  | ID des Bundeslands, aus dem die COVID-19-Fälle übermittelt wurden, auf Basis des amtlichen Gemeindeschlüssels                           |
| Altersgruppe    | string  | Werte: `00-04`, `05-14`, `15-34`, `35-59`, `60-79`, `80+`, `00+` | Altersgruppe der gemeldeten Fälle                                                                                                       |
| Bevoelkerung    | integer | Minimum: 0                                                       | Anzahl der Einwohner:innen in der Bezugsgruppe, Daten der Bevölkerungsstatistik des Statistischen Bundesamtes mit Datenstand 31.12.2021 |
| Faelle_gesamt   | integer | Minimum: 0                                                       | COVID-19-Fälle seit Beginn der Datenerhebung                                                                                            |
| Faelle_neu      | integer | Minimum: 0                                                       | Anzahl Fälle, die erstmals in der Berichterstattung des RKI veröffentlicht werden                                                       |
| Faelle_7-Tage   | integer | Minimum: 0                                                       | Anzahl COVID-19-Fälle mit Meldedatum innerhalb der letzten sieben Tage                                                                  |
| Inzidenz_7-Tage | number  | Minimum: 0                                                       | COVID-19-Fälle mit Meldedatum innerhalb der letzten sieben Tage je 100.000 Einwohner:innen                                              |


### Variable specification for data file `frictionless_data_schema_COVID-19-Faelle_7-Tage-Inzidenz_Deutschland`

| Variable        | Typ     | Ausprägungen                                                     | Beschreibung                                                                                                                            |
|:----------------|:--------|:-----------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|
| Meldedatum      | date    | Format: `%Y-%m-%d`                                               | Datum, an dem das lokale Gesundheitsamt Kenntnis über den Fall erlangt und ihn elektronisch erfasst hat                                 |
| Altersgruppe    | string  | Werte: `00-04`, `05-14`, `15-34`, `35-59`, `60-79`, `80+`, `00+` | Altersgruppe der übermittelten COVID-19-Fälle                                                                                           |
| Bevoelkerung    | integer | Minimum: 0                                                       | Anzahl der Einwohner:innen in der Bezugsgruppe, Daten der Bevölkerungsstatistik des Statistischen Bundesamtes mit Datenstand 31.12.2021 |
| Faelle_gesamt   | integer | Minimum: 0                                                       | COVID-19-Fälle seit Beginn der Datenerhebung                                                                                            |
| Faelle_neu      | integer | Minimum: 0                                                       | Anzahl Fälle, die erstmals in der Berichterstattung des RKI veröffentlicht werden                                                       |
| Faelle_7-Tage   | integer | Minimum: 0                                                       | Anzahl COVID-19-Fälle mit Meldedatum innerhalb der letzten sieben Tage                                                                  |
| Inzidenz_7-Tage | number  | Minimum: 0                                                       | COVID-19-Fälle mit Meldedatum innerhalb der letzten sieben Tage je 100.000 Einwohner:innen                                              |


### Variable specification for data file `frictionless_data_schema_COVID-19-Faelle_7-Tage-Inzidenz_Landkreise`

| Variable        | Typ     | Ausprägungen                           | Beschreibung                                                                                                                            |
|:----------------|:--------|:---------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|
| Meldedatum      | date    | Format: `%Y-%m-%d`                     | Datum, an dem das lokale Gesundheitsamt Kenntnis über den Fall erlangt und ihn elektronisch erfasst hat                                 |
| Landkreis_id    | string  | Format: `^(1[0-6]?\|0[0-9]?)[0-9]{3}$` | ID des Landkreises, aus dem die COVID-19-Fälle übermittelt wurden, auf Basis des amtlichen Gemeindeschlüssels                           |
| Bevoelkerung    | integer | Minimum: 0                             | Anzahl der Einwohner:innen in der Bezugsgruppe, Daten der Bevölkerungsstatistik des Statistischen Bundesamtes mit Datenstand 31.12.2021 |
| Faelle_gesamt   | integer | Minimum: 0                             | COVID-19-Fälle seit Beginn der Datenerhebung                                                                                            |
| Faelle_neu      | integer | Minimum: 0                             | Anzahl Fälle, die erstmals in der Berichterstattung des RKI veröffentlicht werden                                                       |
| Faelle_7-Tage   | integer | Minimum: 0                             | Anzahl COVID-19-Fälle mit Meldedatum innerhalb der letzten sieben Tage                                                                  |
| Inzidenz_7-Tage | number  | Minimum: 0                             | COVID-19-Fälle mit Meldedatum innerhalb der letzten sieben Tage je 100.000 Einwohner:innen                                              |



# July 2016 - University of Tennesee
## About
* Metadata Format - **MODS**
* OAI Endpoint - **http://dpla.lib.utk.edu/repox/OAIHandler**

## Schema Overview


| key                                                                   | types                                 | occurrences | percents               |
| --------------------------------------------------------------------- | ------------------------------------- | ----------- | ---------------------- |
| _id                                                                   | ObjectId                              |        8511 | 100.000000000000000000 |
| metadata                                                              | Object                                |        8511 | 100.000000000000000000 |
| metadata.mods                                                         | Object                                |        8511 | 100.000000000000000000 |
| metadata.mods.@version                                                | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.@xmlns                                                  | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.@xmlns:xlink                                            | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.@xmlns:xsi                                              | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.@xsi:schemaLocation                                     | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.accessCondition                                         | Object (6978),String (1533)           |        8511 | 100.000000000000000000 |
| metadata.mods.identifier                                              | Array (4946),Object (3565)            |        8511 | 100.000000000000000000 |
| metadata.mods.location                                                | Object                                |        8511 | 100.000000000000000000 |
| metadata.mods.location.url                                            | Array                                 |        8511 | 100.000000000000000000 |
| metadata.mods.location.url.XX.#text                                   | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.location.url.XX.@access                                 | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.location.url.XX.@usage                                  | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.originInfo                                              | Object (7033),Array (1478)            |        8511 | 100.000000000000000000 |
| metadata.mods.physicalDescription                                     | Object                                |        8511 | 100.000000000000000000 |
| metadata.mods.titleInfo                                               | Object (8428),Array (83)              |        8511 | 100.000000000000000000 |
| metadata.mods.typeOfResource                                          | String (8496),Array (15)              |        8511 | 100.000000000000000000 |
| oai_provider                                                          | String                                |        8511 | 100.000000000000000000 |
| record_id                                                             | String                                |        8511 | 100.000000000000000000 |
| metadata.mods.subject                                                 | Array (8081),Object (411)             |        8492 |  99.776759487721776054 |
| metadata.mods.relatedItem                                             | Array (7734),Object (722)             |        8456 |  99.353777464457763813 |
| metadata.mods.titleInfo.title                                         | String                                |        8428 |  99.024791446363522596 |
| metadata.mods.name                                                    | Array (1005),Object (7227)            |        8232 |  96.721889319703919341 |
| metadata.mods.relatedItem.XX.@type                                    | String                                |        7734 |  90.870637997885083337 |
| metadata.mods.relatedItem.XX.titleInfo                                | Object                                |        7734 |  90.870637997885083337 |
| metadata.mods.relatedItem.XX.titleInfo.title                          | String                                |        7734 |  90.870637997885083337 |
| metadata.mods.language                                                | Object                                |        7608 |  89.390200916461054703 |
| metadata.mods.language.languageTerm                                   | Object                                |        7608 |  89.390200916461054703 |
| metadata.mods.language.languageTerm.#text                             | String                                |        7608 |  89.390200916461054703 |
| metadata.mods.language.languageTerm.@type                             | String                                |        7608 |  89.390200916461054703 |
| metadata.mods.subject.XX.topic                                        | String (7386),null (2)                |        7386 |  86.781811772999645882 |
| metadata.mods.name.namePart                                           | String                                |        7227 |  84.913641170250258483 |
| metadata.mods.name.role                                               | Object (7219),Array (8)               |        7227 |  84.913641170250258483 |
| metadata.mods.name.role.roleTerm                                      | Object                                |        7219 |  84.819645165080487459 |
| metadata.mods.name.role.roleTerm.#text                                | String                                |        7219 |  84.819645165080487459 |
| metadata.mods.name.role.roleTerm.@type                                | String                                |        7219 |  84.819645165080487459 |
| metadata.mods.@xmlns:xs                                               | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.accessCondition.#text                                   | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.accessCondition.@type                                   | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.language.languageTerm.@authority                        | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.location.physicalLocation                               | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.originInfo.dateCreated                                  | Array                                 |        6978 |  81.988015509340854692 |
| metadata.mods.originInfo.dateCreated.XX.@encoding                     | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.originInfo.dateCreated.XX.@keyDate                      | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.physicalDescription.digitalOrigin                       | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.physicalDescription.form                                | Object (6652),Array (14),String (312) |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo                                              | Object                                |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.languageOfCataloging                         | Object                                |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm            | Object                                |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.#text      | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@authority | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@type      | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.recordContentSource                          | String (6797),null (181)              |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.recordIdentifier                             | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.recordInfo.recordOrigin                                 | String                                |        6978 |  81.988015509340854692 |
| metadata.mods.originInfo.dateCreated.XX.#text                         | String                                |        6976 |  81.964516508048404830 |
| metadata.mods.physicalDescription.internetMediaType                   | String                                |        6902 |  81.095053460227944697 |
| metadata.mods.physicalDescription.form.#text                          | String                                |        6652 |  78.157678298672308870 |
| metadata.mods.physicalDescription.form.@authority                     | String                                |        6652 |  78.157678298672308870 |
| metadata.mods.name.role.roleTerm.@authority                           | String                                |        6405 |  75.255551639055340729 |
| metadata.mods.physicalDescription.form.@valueURI                      | String                                |        6337 |  74.456585595112201759 |
| metadata.mods.relatedItem.XX.@displayLabel                            | String                                |        6256 |  73.504876042768188427 |
| metadata.mods.name.role.roleTerm.@valueURI                            | String                                |        6093 |  71.589707437433915516 |
| metadata.mods.physicalDescription.extent                              | String (5133),null (1)                |        5134 |  60.321936317706494890 |
| metadata.mods.identifier.XX.#text                                     | String                                |        4946 |  58.113030196216662659 |
| metadata.mods.identifier.XX.@type                                     | String                                |        4946 |  58.113030196216662659 |
| metadata.mods.originInfo.place                                        | Object (4682),Array (84)              |        4766 |  55.998120079896601453 |
| metadata.mods.subject.XX.geographic                                   | Object (3052),String (2051),null (1)  |        4761 |  55.939372576665491010 |
| metadata.mods.subject.XX.@authority                                   | String                                |        4753 |  55.845376571495712881 |
| metadata.mods.originInfo.place.@supplied                              | String                                |        4682 |  55.011162025613913329 |
| metadata.mods.originInfo.place.placeTerm                              | Object                                |        4682 |  55.011162025613913329 |
| metadata.mods.originInfo.place.placeTerm.@type                        | String                                |        4682 |  55.011162025613913329 |
| metadata.mods.relatedItem.XX.identifier                               | Object                                |        4090 |  48.055457643050168315 |
| metadata.mods.relatedItem.XX.identifier.#text                         | String                                |        4090 |  48.055457643050168315 |
| metadata.mods.relatedItem.XX.identifier.@type                         | String                                |        4090 |  48.055457643050168315 |
| metadata.mods.genre                                                   | String (440),Object (3329)            |        3769 |  44.283867935612732936 |
| metadata.mods.subject.XX.@valueURI                                    | String                                |        3599 |  42.286452825754906826 |
| metadata.mods.identifier.#text                                        | String                                |        3565 |  41.886969803783337341 |
| metadata.mods.identifier.@type                                        | String                                |        3565 |  41.886969803783337341 |
| metadata.mods.abstract                                                | String (3480),Array (18)              |        3498 |  41.099753260486430406 |
| metadata.mods.relatedItem.XX.location                                 | Object                                |        3405 |  40.007049700387732116 |
| metadata.mods.relatedItem.XX.location.url                             | String                                |        3405 |  40.007049700387732116 |
| metadata.mods.genre.@authority                                        | String                                |        3326 |  39.078839149336154435 |
| metadata.mods.genre.#text                                             | String                                |        3325 |  39.067089648689929504 |
| metadata.mods.originInfo.place.placeTerm.#text                        | String                                |        3307 |  38.855598637057923384 |
| metadata.mods.subject.XX.cartographics                                | Object                                |        3180 |  37.363412054987662714 |
| metadata.mods.subject.XX.cartographics.coordinates                    | String (3179),null (2)                |        3180 |  37.363412054987662714 |
| metadata.mods.subject.XX.geographic.#text                             | String                                |        3052 |  35.859475972271177113 |
| metadata.mods.subject.XX.geographic.@authority                        | String                                |        3052 |  35.859475972271177113 |
| metadata.mods.subject.XX.geographic.@valueURI                         | String                                |        3045 |  35.777229467747623914 |
| metadata.mods.note                                                    | String (2342),Array (649),null (1)    |        2992 |  35.154505933497823378 |
| metadata.mods.subject.XX.name                                         | Object                                |        2637 |  30.983433204088825619 |
| metadata.mods.subject.XX.name.namePart                                | String                                |        2637 |  30.983433204088825619 |
| metadata.mods.originInfo.place.placeTerm.@valueURI                    | String                                |        2545 |  29.902479144636352260 |
| metadata.mods.name.@type                                              | String                                |        2535 |  29.784984138174127821 |
| metadata.mods.recordInfo.recordChangeDate                             | Array (2154),Object (315)             |        2469 |  29.009517095523438712 |
| metadata.mods.location.holdingSimple                                  | Object                                |        2442 |  28.692280578075433084 |
| metadata.mods.location.holdingSimple.copyInformation                  | Object                                |        2442 |  28.692280578075433084 |
| metadata.mods.location.holdingSimple.copyInformation.shelfLocator     | String                                |        2442 |  28.692280578075433084 |
| metadata.mods.originInfo.dateCreated.XX.@qualifier                    | String                                |        2441 |  28.680531077429208153 |
| metadata.mods.subject.XX.temporal                                     | String (2432),null (2)                |        2434 |  28.598284572905651402 |
| metadata.mods.recordInfo.recordChangeDate.XX.#text                    | String                                |        2154 |  25.308424391963342259 |
| metadata.mods.recordInfo.recordChangeDate.XX.@encoding                | String                                |        2154 |  25.308424391963342259 |
| metadata.mods.subject.XX.@displayLabel                                | String                                |        2154 |  25.308424391963342259 |
| metadata.mods.originInfo.dateCreated.XX.@point                        | String                                |        2144 |  25.190929385501117821 |
| metadata.mods.@xmlns:iso20775                                         | String                                |        2090 |  24.556456350605099459 |
| metadata.mods.location.holdingExternal                                | Object                                |        2090 |  24.556456350605099459 |
| metadata.mods.location.holdingExternal.holding                        | Object                                |        2090 |  24.556456350605099459 |
| metadata.mods.location.holdingExternal.holding.@xsi:schemaLocation    | String                                |        2090 |  24.556456350605099459 |
| metadata.mods.location.holdingExternal.holding.physicalAddress        | Object                                |        2090 |  24.556456350605099459 |
| metadata.mods.location.holdingExternal.holding.physicalAddress.text   | Array                                 |        2090 |  24.556456350605099459 |
| metadata.mods.recordInfo.recordCreationDate                           | Object                                |        2090 |  24.556456350605099459 |
| metadata.mods.recordInfo.recordCreationDate.#text                     | String                                |        2090 |  24.556456350605099459 |
| metadata.mods.recordInfo.recordCreationDate.@encoding                 | String                                |        2090 |  24.556456350605099459 |
| metadata.mods.genre.@valueURI                                         | String                                |        1795 |  21.090353659969451883 |
| metadata.mods.originInfo.XX.dateOther                                 | String                                |        1478 |  17.365761955116909121 |
| metadata.mods.originInfo.XX.publisher                                 | String                                |        1478 |  17.365761955116909121 |
| metadata.mods.subject.XX.name.@authority                              | String                                |        1436 |  16.872282927975561506 |
| metadata.mods.subject.XX.name.@valueURI                               | String                                |        1430 |  16.801785924098226133 |
| metadata.mods.physicalDescription.note                                | String (1014),Array (232)             |        1246 |  14.639877805193279414 |
| metadata.mods.name.@authority                                         | String                                |        1135 |  13.335683233462578556 |
| metadata.mods.name.@valueURI                                          | String                                |        1135 |  13.335683233462578556 |
| metadata.mods.originInfo.publisher                                    | String (1097),null (1)                |        1098 |  12.900951709552343161 |
| metadata.mods.name.XX.namePart                                        | String                                |        1005 |  11.808248149453648423 |
| metadata.mods.name.XX.role                                            | Object                                |        1005 |  11.808248149453648423 |
| metadata.mods.name.XX.role.roleTerm                                   | Object                                |        1005 |  11.808248149453648423 |
| metadata.mods.name.XX.role.roleTerm.#text                             | String                                |        1005 |  11.808248149453648423 |
| metadata.mods.name.XX.role.roleTerm.@type                             | String                                |        1005 |  11.808248149453648423 |
| metadata.mods.relatedItem.XX.identifer                                | Object                                |         875 |  10.280813065444718291 |
| metadata.mods.relatedItem.XX.identifer.#text                          | String                                |         875 |  10.280813065444718291 |
| metadata.mods.relatedItem.XX.identifer.@type                          | String                                |         875 |  10.280813065444718291 |
| metadata.mods.relatedItem.@displayLabel                               | String                                |         722 |   8.483139466572669818 |
| metadata.mods.relatedItem.@type                                       | String                                |         722 |   8.483139466572669818 |
| metadata.mods.relatedItem.titleInfo                                   | Object                                |         722 |   8.483139466572669818 |
| metadata.mods.relatedItem.titleInfo.title                             | String                                |         722 |   8.483139466572669818 |
| metadata.mods.relatedItem.location                                    | Object                                |         630 |   7.402185407120197347 |
| metadata.mods.relatedItem.location.url                                | String                                |         630 |   7.402185407120197347 |
| metadata.mods.titleInfo.nonSort                                       | String                                |         589 |   6.920455880625073775 |
| metadata.mods.relatedItem.XX.part                                     | Object                                |         413 |   4.852543766889906962 |
| metadata.mods.relatedItem.XX.part.detail                              | Object (1),Array (412)                |         413 |   4.852543766889906962 |
| metadata.mods.relatedItem.XX.part.detail.XX.@type                     | String                                |         412 |   4.840794266243684696 |
| metadata.mods.relatedItem.XX.part.detail.XX.number                    | String                                |         412 |   4.840794266243684696 |
| metadata.mods.relatedItem.XX.titleInfo.nonSort                        | String                                |         386 |   4.535307249441898669 |
| metadata.mods.relatedItem.XX.abstract                                 | String                                |         359 |   4.218070731993890377 |
| metadata.mods.recordInfo.recordChangeDate.#text                       | String                                |         315 |   3.701092703560098673 |
| metadata.mods.recordInfo.recordChangeDate.@encoding                   | String                                |         315 |   3.701092703560098673 |
| metadata.mods.name.@usage                                             | String                                |         311 |   3.654094700975208720 |
| metadata.mods.name.XX.role.roleTerm.@authority                        | String                                |         286 |   3.360357184819644960 |
| metadata.mods.name.XX.role.roleTerm.@valueURI                         | String                                |         286 |   3.360357184819644960 |
| metadata.mods.relatedItem.abstract                                    | String                                |         256 |   3.007872165432968981 |
| metadata.mods.titleInfo.partName                                      | String                                |         256 |   3.007872165432968981 |
| metadata.mods.originInfo.dateIssued                                   | Object                                |         249 |   2.925625660909411341 |
| metadata.mods.originInfo.dateIssued.#text                             | String                                |         249 |   2.925625660909411341 |
| metadata.mods.originInfo.dateIssued.@encoding                         | String                                |         249 |   2.925625660909411341 |
| metadata.mods.originInfo.dateIssued.@keyDate                          | String                                |         249 |   2.925625660909411341 |
| metadata.mods.part                                                    | Object                                |         245 |   2.878627658324521388 |
| metadata.mods.part.detail                                             | Object                                |         245 |   2.878627658324521388 |
| metadata.mods.part.detail.title                                       | String                                |         245 |   2.878627658324521388 |
| metadata.mods.name.XX.@type                                           | String                                |         213 |   2.502643637645399988 |
| metadata.mods.originInfo.dateIssued.@qualifier                        | String                                |         177 |   2.079661614381388635 |
| metadata.mods.subject.geographic                                      | String (118),Object (47)              |         165 |   1.938667606626718332 |
| metadata.mods.subject.name                                            | Object                                |         134 |   1.574433086593819864 |
| metadata.mods.subject.name.namePart                                   | String                                |         134 |   1.574433086593819864 |
| metadata.mods.name.XX.@authority                                      | String                                |         133 |   1.562683585947597154 |
| metadata.mods.name.XX.@valueURI                                       | String                                |         133 |   1.562683585947597154 |
| metadata.mods.subject.name.@authority                                 | String                                |         129 |   1.515685583362706979 |
| metadata.mods.subject.name.@valueURI                                  | String                                |         129 |   1.515685583362706979 |
| metadata.mods.subject.topic                                           | String                                |         112 |   1.315944072376924012 |
| metadata.mods.subject.cartographics                                   | Object                                |          99 |   1.163200563976030999 |
| metadata.mods.subject.cartographics.coordinates                       | String                                |          99 |   1.163200563976030999 |
| metadata.mods.originInfo.place.XX.@supplied                           | String                                |          84 |   0.986958054282693009 |
| metadata.mods.originInfo.place.XX.placeTerm                           | Object                                |          84 |   0.986958054282693009 |
| metadata.mods.originInfo.place.XX.placeTerm.@type                     | String                                |          84 |   0.986958054282693009 |
| metadata.mods.originInfo.place.XX.placeTerm.#text                     | String                                |          83 |   0.975208553636470410 |
| metadata.mods.originInfo.place.XX.placeTerm.@valueURI                 | String                                |          83 |   0.975208553636470410 |
| metadata.mods.titleInfo.XX.@type                                      | String                                |          83 |   0.975208553636470410 |
| metadata.mods.titleInfo.XX.title                                      | String                                |          83 |   0.975208553636470410 |
| metadata.mods.originInfo.dateOther                                    | String                                |          55 |   0.646222535542239407 |
| metadata.mods.subject.geographic.#text                                | String                                |          47 |   0.552226530372459168 |
| metadata.mods.subject.geographic.@authority                           | String                                |          47 |   0.552226530372459168 |
| metadata.mods.subject.geographic.@valueURI                            | String                                |          47 |   0.552226530372459168 |
| metadata.mods.subject.@authority                                      | String                                |          29 |   0.340735518740453547 |
| metadata.mods.subject.@valueURI                                       | String                                |          21 |   0.246739513570673252 |
| metadata.mods.physicalDescription.form.XX.#text                       | String                                |          14 |   0.164493009047115502 |
| metadata.mods.physicalDescription.form.XX.@authority                  | String                                |          14 |   0.164493009047115502 |
| metadata.mods.physicalDescription.form.XX.@valueURI                   | String                                |          14 |   0.164493009047115502 |
| metadata.mods.classification                                          | Object                                |          13 |   0.152743508400892958 |
| metadata.mods.classification.#text                                    | String                                |          13 |   0.152743508400892958 |
| metadata.mods.classification.@authority                               | String                                |          13 |   0.152743508400892958 |
| metadata.mods.name.role.XX.roleTerm                                   | Object                                |           8 |   0.093996005169780281 |
| metadata.mods.name.role.XX.roleTerm.#text                             | String                                |           8 |   0.093996005169780281 |
| metadata.mods.name.role.XX.roleTerm.@authority                        | String                                |           8 |   0.093996005169780281 |
| metadata.mods.name.role.XX.roleTerm.@type                             | String                                |           8 |   0.093996005169780281 |
| metadata.mods.name.role.XX.roleTerm.@valueURI                         | String                                |           8 |   0.093996005169780281 |
| metadata.mods.name.XX.@usage                                          | String                                |           3 |   0.035248501938667604 |
| metadata.mods.titleInfo.XX.partName                                   | String                                |           3 |   0.035248501938667604 |
| metadata.mods.@xmlns:mods                                             | String                                |           1 |   0.011749500646222535 |
| metadata.mods.originInfo.place.XX.placeTerm.@authority                | String                                |           1 |   0.011749500646222535 |
| metadata.mods.relatedItem.XX.part.detail.@type                        | String                                |           1 |   0.011749500646222535 |
| metadata.mods.relatedItem.XX.part.detail.number                       | String                                |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic                       | Object                                |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic.city                  | null                                  |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic.citySection           | null                                  |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic.continent             | null                                  |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic.country               | null                                  |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic.county                | null                                  |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic.province              | null                                  |           1 |   0.011749500646222535 |
| metadata.mods.subject.XX.hierarchicalGeographic.region                | null                                  |           1 |   0.011749500646222535 |
| metadata.mods.titleInfo.subTitle                                      | null                                  |           1 |   0.011749500646222535 |

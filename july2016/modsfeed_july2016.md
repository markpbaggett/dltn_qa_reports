# July 2016 - MODS Feed
## About
* Metadata Format - **MODS**
* OAI Endpoint - **http://dpla.lib.utk.edu/repox/OAIHandler**

## Schema Overview


| key                                                                   | types                                      | occurrences | percents                |
| --------------------------------------------------------------------- | ------------------------------------------ | ----------- | ----------------------- |
| _id                                                                   | ObjectId                                   |      160126 | 100.0000000000000000000 |
| metadata                                                              | Object                                     |      160126 | 100.0000000000000000000 |
| metadata.mods                                                         | Object                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.@version                                                | String                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.@xmlns                                                  | String                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.@xmlns:oai                                              | String                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.@xmlns:xlink                                            | String                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.@xmlns:xsi                                              | String                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.@xsi:schemaLocation                                     | String                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.accessCondition                                         | Object (5050),String (154529),Array (547)  |      160126 | 100.0000000000000000000 |
| metadata.mods.location                                                | Object                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.titleInfo                                               | Object (154999),Array (5127)               |      160126 | 100.0000000000000000000 |
| oai_provider                                                          | String                                     |      160126 | 100.0000000000000000000 |
| record_id                                                             | String                                     |      160126 | 100.0000000000000000000 |
| metadata.mods.location.url                                            | Array                                      |      160117 |  99.9943794262018599284 |
| metadata.mods.location.url.XX.#text                                   | String                                     |      160117 |  99.9943794262018599284 |
| metadata.mods.location.url.XX.@access                                 | String                                     |      160117 |  99.9943794262018599284 |
| metadata.mods.location.url.XX.@usage                                  | String                                     |      160117 |  99.9943794262018599284 |
| metadata.mods.recordInfo                                              | Object                                     |      158731 |  99.1288110612892410245 |
| metadata.mods.recordInfo.languageOfCataloging                         | Object                                     |      158731 |  99.1288110612892410245 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm            | Object                                     |      158731 |  99.1288110612892410245 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.#text      | String                                     |      158731 |  99.1288110612892410245 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@authority | String                                     |      158731 |  99.1288110612892410245 |
| metadata.mods.recordInfo.languageOfCataloging.languageTerm.@type      | String                                     |      158731 |  99.1288110612892410245 |
| metadata.mods.recordInfo.recordContentSource                          | String (158550),null (181)                 |      158731 |  99.1288110612892410245 |
| metadata.mods.recordInfo.recordOrigin                                 | String                                     |      158731 |  99.1288110612892410245 |
| metadata.mods.subject                                                 | Array (153409),Object (4250)               |      157659 |  98.4593382711115054917 |
| metadata.mods.relatedItem                                             | Object (127908),Array (29518)              |      157426 |  98.3138278605598117110 |
| metadata.mods.typeOfResource                                          | String (155724),Array (1378)               |      157102 |  98.1114872038269822951 |
| metadata.mods.physicalDescription                                     | Object (156328),null (151)                 |      156479 |  97.7224185953561601536 |
| metadata.mods.identifier                                              | Array (8553),Object (3427),String (143191) |      155171 |  96.9055618700273555532 |
| metadata.mods.titleInfo.title                                         | String                                     |      154999 |  96.7981464596630161168 |
| metadata.mods.recordInfo.recordChangeDate                             | Array (500),Object (315),String (153681)   |      154496 |  96.4840188351673049283 |
| metadata.mods.originInfo                                              | Object (150996),Array (1340),null (2101)   |      154437 |  96.4471728513795341087 |
| metadata.mods.@xmlns:dc                                               | String                                     |      153681 |  95.9750446523362796825 |
| metadata.mods.@xmlns:oai_dc                                           | String                                     |      153681 |  95.9750446523362796825 |
| metadata.mods.abstract                                                | String (153069),Array (79)                 |      153148 |  95.6421817818468014138 |
| metadata.mods.subject.XX.topic                                        | String (152685),null (4)                   |      152685 |  95.3530344853427891394 |
| metadata.mods.originInfo.dateCreated                                  | Object (146747),Array (1875),String (1624) |      150246 |  93.8298589860484923975 |
| metadata.mods.physicalDescription.form                                | Object (4736),Array (9404),String (133881) |      148021 |  92.4403282415098175306 |
| metadata.mods.location.physicalLocation                               | String (142928),Array (4303)               |      147231 |  91.9469667636736005534 |
| metadata.mods.originInfo.dateCreated.#text                            | String                                     |      146743 |  91.6422067621747942212 |
| metadata.mods.originInfo.dateCreated.@encoding                        | String                                     |      145891 |  91.1101257759514311374 |
| metadata.mods.originInfo.dateCreated.@keyDate                         | String                                     |      145891 |  91.1101257759514311374 |
| metadata.mods.physicalDescription.internetMediaType                   | String (141536),Array (2737)               |      144273 |  90.0996715086869102151 |
| metadata.mods.genre                                                   | Object (133334),Array (10706)              |      144040 |  89.9541610981352164345 |
| metadata.mods.genre.@authority                                        | String                                     |      133334 |  83.2681763111549599898 |
| metadata.mods.genre.#text                                             | String                                     |      133333 |  83.2675518029551682275 |
| metadata.mods.genre.@valueURI                                         | String                                     |      131938 |  82.3963628642444092520 |
| metadata.mods.language                                                | Object (131670),null (102),Array (32)      |      131804 |  82.3126787654721852050 |
| metadata.mods.language.languageTerm                                   | Object                                     |      131670 |  82.2289946666999753688 |
| metadata.mods.language.languageTerm.#text                             | String                                     |      131670 |  82.2289946666999753688 |
| metadata.mods.language.languageTerm.@type                             | String                                     |      131670 |  82.2289946666999753688 |
| metadata.mods.language.languageTerm.@authority                        | String                                     |      131040 |  81.8355545008305966803 |
| metadata.mods.subject.XX.geographic                                   | Object (119346),String (11238),null (1)    |      129751 |  81.0305634312978497746 |
| metadata.mods.relatedItem.@displayLabel                               | String                                     |      127908 |  79.8795948190799691702 |
| metadata.mods.relatedItem.@type                                       | String                                     |      127908 |  79.8795948190799691702 |
| metadata.mods.relatedItem.titleInfo                                   | Object                                     |      127908 |  79.8795948190799691702 |
| metadata.mods.relatedItem.titleInfo.title                             | String                                     |      127908 |  79.8795948190799691702 |
| metadata.mods.relatedItem.location                                    | Object                                     |      127816 |  79.8221400646990559835 |
| metadata.mods.relatedItem.location.url                                | String                                     |      127816 |  79.8221400646990559835 |
| metadata.mods.subject.XX.temporal                                     | String (1166),null (2),Object (126577)     |      127619 |  79.6991119493398940676 |
| metadata.mods.subject.XX.temporal.#text                               | String                                     |      126577 |  79.0483744051559398258 |
| metadata.mods.subject.XX.temporal.@encoding                           | String                                     |      126577 |  79.0483744051559398258 |
| metadata.mods.subject.XX.cartographics                                | Object                                     |      121874 |  76.1113123415310468545 |
| metadata.mods.subject.XX.cartographics.coordinates                    | String (121873),null (2)                   |      121874 |  76.1113123415310468545 |
| metadata.mods.originInfo.publisher                                    | Array (1455),String (119559)               |      121014 |  75.5742352897093496722 |
| metadata.mods.subject.XX.geographic.#text                             | String                                     |      119346 |  74.5325556124551980020 |
| metadata.mods.subject.XX.geographic.@authority                        | String                                     |      119346 |  74.5325556124551980020 |
| metadata.mods.subject.XX.geographic.@valueURI                         | String                                     |      119339 |  74.5281840550566414549 |
| metadata.mods.extension                                               | Object (116044),Array (1)                  |      116045 |  72.4710540449396063423 |
| metadata.mods.extension.@xmlns:dcterms                                | String                                     |      116044 |  72.4704295367398145800 |
| metadata.mods.extension.dcterms:available                             | Object                                     |      116044 |  72.4704295367398145800 |
| metadata.mods.extension.dcterms:available.#text                       | String                                     |      116044 |  72.4704295367398145800 |
| metadata.mods.extension.dcterms:available.@encoding                   | String                                     |      116044 |  72.4704295367398145800 |
| metadata.mods.subject.XX.titleInfo                                    | Object                                     |      114968 |  71.7984587137629119979 |
| metadata.mods.subject.XX.titleInfo.title                              | String                                     |      114968 |  71.7984587137629119979 |
| metadata.mods.name                                                    | Object (21310),Array (8384)                |       29694 |  18.5441464846433419211 |
| metadata.mods.relatedItem.XX.@type                                    | String                                     |       29518 |  18.4342330414798354354 |
| metadata.mods.relatedItem.XX.titleInfo                                | Object                                     |       29518 |  18.4342330414798354354 |
| metadata.mods.relatedItem.XX.titleInfo.title                          | String                                     |       29518 |  18.4342330414798354354 |
| metadata.mods.relatedItem.XX.@displayLabel                            | String                                     |       28178 |  17.5973920537576660195 |
| metadata.mods.relatedItem.XX.location                                 | Object                                     |       25601 |  15.9880344228919728522 |
| metadata.mods.relatedItem.XX.location.url                             | String                                     |       25601 |  15.9880344228919728522 |
| metadata.mods.physicalDescription.extent                              | String (23468),null (1),Array (414)        |       23883 |  14.9151293356481762231 |
| metadata.mods.name.namePart                                           | String                                     |       21310 |  13.3082697375816536578 |
| metadata.mods.name.role                                               | Object (19359),Array (1947)                |       21306 |  13.3057717047824830559 |
| metadata.mods.subject.XX.@authority                                   | String                                     |       20723 |  12.9416834243033616048 |
| metadata.mods.subject.XX.@valueURI                                    | String                                     |       19818 |  12.3765035034910013678 |
| metadata.mods.name.role.roleTerm                                      | Object                                     |       19359 |  12.0898542397861685771 |
| metadata.mods.name.role.roleTerm.#text                                | String                                     |       19359 |  12.0898542397861685771 |
| metadata.mods.name.role.roleTerm.@type                                | String                                     |       19359 |  12.0898542397861685771 |
| metadata.mods.relatedItem.XX.abstract                                 | String                                     |       18377 |  11.4765871875897733645 |
| metadata.mods.name.role.roleTerm.@valueURI                            | String                                     |       18107 |  11.3079699736457541803 |
| metadata.mods.note                                                    | String (10085),Array (641),null (1)        |       10727 |   6.6990994591758985521 |
| metadata.mods.genre.XX.#text                                          | String                                     |       10706 |   6.6859847869802528919 |
| metadata.mods.genre.XX.@authority                                     | String                                     |       10706 |   6.6859847869802528919 |
| metadata.mods.genre.XX.@valueURI                                      | String                                     |       10706 |   6.6859847869802528919 |
| metadata.mods.relatedItem.abstract                                    | String                                     |        9634 |   6.0165119968025182473 |
| metadata.mods.name.XX.namePart                                        | String                                     |        8384 |   5.2358767470616891515 |
| metadata.mods.name.XX.role                                            | Object (8299),Array (2587)                 |        8384 |   5.2358767470616891515 |
| metadata.mods.name.XX.role.roleTerm                                   | Object                                     |        8299 |   5.1827935500793129719 |
| metadata.mods.name.XX.role.roleTerm.#text                             | String                                     |        8299 |   5.1827935500793129719 |
| metadata.mods.name.XX.role.roleTerm.@type                             | String                                     |        8299 |   5.1827935500793129719 |
| metadata.mods.name.XX.role.roleTerm.@valueURI                         | String                                     |        7982 |   4.9848244507450383267 |
| metadata.mods.@xmlns:xs                                               | String                                     |        6445 |   4.0249553476637149885 |
| metadata.mods.physicalDescription.digitalOrigin                       | String                                     |        5990 |   3.7408041167580532438 |
| metadata.mods.titleInfo.XX.title                                      | String (5127),Object (5044)                |        5127 |   3.2018535403369847714 |
| metadata.mods.relatedItem.XX.identifier                               | Object (3816),Array (384),String (875)     |        5075 |   3.1693791139477660579 |
| metadata.mods.accessCondition.#text                                   | String                                     |        5050 |   3.1537664089529493516 |
| metadata.mods.accessCondition.@type                                   | String                                     |        5050 |   3.1537664089529493516 |
| metadata.mods.recordInfo.recordIdentifier                             | String                                     |        5050 |   3.1537664089529493516 |
| metadata.mods.titleInfo.XX.title.#text                                | String                                     |        5044 |   3.1500193597541934487 |
| metadata.mods.titleInfo.XX.title.@type                                | String                                     |        5044 |   3.1500193597541934487 |
| metadata.mods.physicalDescription.form.#text                          | String                                     |        4736 |   2.9576708342180531019 |
| metadata.mods.physicalDescription.form.@authority                     | String                                     |        4736 |   2.9576708342180531019 |
| metadata.mods.physicalDescription.note                                | String (2896),Array (1567)                 |        4463 |   2.7871800956746564104 |
| metadata.mods.physicalDescription.form.@valueURI                      | String                                     |        4421 |   2.7609507512833642018 |
| metadata.mods.name.role.roleTerm.@authority                           | String                                     |        4255 |   2.6572823901177824446 |
| metadata.mods.subject.XX.name                                         | Object (3592),String (664)                 |        4255 |   2.6572823901177824446 |
| metadata.mods.subject.XX.temporal.@keyDate                            | String                                     |        3887 |   2.4274633725940821805 |
| metadata.mods.relatedItem.XX.identifier.#text                         | String                                     |        3816 |   2.3831232904088031077 |
| metadata.mods.relatedItem.XX.identifier.@type                         | String                                     |        3816 |   2.3831232904088031077 |
| metadata.mods.subject.XX.name.namePart                                | String                                     |        3588 |   2.2407354208560756881 |
| metadata.mods.location.shelfLocator                                   | String (3564),Array (17)                   |        3581 |   2.2363638634575271347 |
| metadata.mods.identifier.#text                                        | String                                     |        3427 |   2.1401896006894571833 |
| metadata.mods.identifier.@type                                        | String                                     |        3427 |   2.1401896006894571833 |
| metadata.mods.originInfo.place                                        | String                                     |        3307 |   2.0652486167143373486 |
| metadata.mods.identifier.XX.#text                                     | String                                     |        3018 |   1.8847657469742578051 |
| metadata.mods.identifier.XX.@type                                     | String                                     |        3018 |   1.8847657469742578051 |
| metadata.mods.name.XX.role.XX.roleTerm                                | Object                                     |        2587 |   1.6156027128636198942 |
| metadata.mods.name.XX.role.XX.roleTerm.#text                          | String                                     |        2587 |   1.6156027128636198942 |
| metadata.mods.name.XX.role.XX.roleTerm.@type                          | String                                     |        2587 |   1.6156027128636198942 |
| metadata.mods.name.XX.role.XX.roleTerm.@valueURI                      | String                                     |        2587 |   1.6156027128636198942 |
| metadata.mods.subject.XX.name.@authority                              | String                                     |        2586 |   1.6149782046638272437 |
| metadata.mods.subject.XX.name.@valueURI                               | String                                     |        2580 |   1.6112311554650713408 |
| metadata.mods.subject.geographic                                      | String (2259),Object (312)                 |        2571 |   1.6056105816669372643 |
| metadata.mods.name.role.XX.roleTerm                                   | Object                                     |        1947 |   1.2159174649963153669 |
| metadata.mods.name.role.XX.roleTerm.#text                             | String                                     |        1947 |   1.2159174649963153669 |
| metadata.mods.name.role.XX.roleTerm.@type                             | String                                     |        1947 |   1.2159174649963153669 |
| metadata.mods.name.role.XX.roleTerm.@valueURI                         | String                                     |        1947 |   1.2159174649963153669 |
| metadata.mods.originInfo.dateCreated.XX.#text                         | String                                     |        1875 |   1.1709528746112436437 |
| metadata.mods.originInfo.dateCreated.XX.@encoding                     | String                                     |        1875 |   1.1709528746112436437 |
| metadata.mods.originInfo.dateCreated.XX.@keyDate                      | String                                     |        1875 |   1.1709528746112436437 |
| metadata.mods.location.holdingSimple                                  | Object                                     |        1722 |   1.0754031200429661208 |
| metadata.mods.location.holdingSimple.copyInformation                  | Object                                     |        1722 |   1.0754031200429661208 |
| metadata.mods.location.holdingSimple.copyInformation.shelfLocator     | String                                     |        1722 |   1.0754031200429661208 |
| metadata.mods.subject.topic                                           | String                                     |        1465 |   0.9149045126962517260 |
| metadata.mods.originInfo.dateCreated.XX.@point                        | String                                     |        1412 |   0.8818055781072405841 |
| metadata.mods.originInfo.dateCreated.XX.@qualifier                    | String                                     |        1349 |   0.8424615615203027152 |
| metadata.mods.originInfo.dateCreated.@qualifier                       | String                                     |        1212 |   0.7569039381487079332 |
| metadata.mods.subject.@authority                                      | String                                     |         888 |   0.5545632814158849566 |
| metadata.mods.subject.@valueURI                                       | String                                     |         880 |   0.5495672158175436417 |
| metadata.mods.relatedItem.XX.identifer                                | Object                                     |         875 |   0.5464446748185803893 |
| metadata.mods.relatedItem.XX.identifer.#text                          | String                                     |         875 |   0.5464446748185803893 |
| metadata.mods.relatedItem.XX.identifer.@type                          | String                                     |         875 |   0.5464446748185803893 |
| metadata.mods.#text                                                   | String                                     |         804 |   0.5021045926333013165 |
| metadata.mods.titleInfo.nonSort                                       | String                                     |         504 |   0.3147521326955022847 |
| metadata.mods.recordInfo.recordChangeDate.XX.#text                    | String                                     |         500 |   0.3122540998963316272 |
| metadata.mods.recordInfo.recordChangeDate.XX.@encoding                | String                                     |         500 |   0.3122540998963316272 |
| metadata.mods.subject.XX.@displayLabel                                | String                                     |         500 |   0.3122540998963316272 |
| metadata.mods.location.holdingExternal                                | Object                                     |         487 |   0.3041354932990270044 |
| metadata.mods.location.holdingExternal.holding                        | Object                                     |         487 |   0.3041354932990270044 |
| metadata.mods.location.holdingExternal.holding.@xsi:schemaLocation    | String                                     |         487 |   0.3041354932990270044 |
| metadata.mods.location.holdingExternal.holding.physicalAddress        | Object                                     |         487 |   0.3041354932990270044 |
| metadata.mods.location.holdingExternal.holding.physicalAddress.text   | Array                                      |         487 |   0.3041354932990270044 |
| metadata.mods.recordInfo.recordCreationDate                           | Object                                     |         487 |   0.3041354932990270044 |
| metadata.mods.recordInfo.recordCreationDate.#text                     | String                                     |         487 |   0.3041354932990270044 |
| metadata.mods.recordInfo.recordCreationDate.@encoding                 | String                                     |         487 |   0.3041354932990270044 |
| metadata.mods.part                                                    | Object                                     |         464 |   0.2897718047037957656 |
| metadata.mods.part.detail                                             | Object                                     |         464 |   0.2897718047037957656 |
| metadata.mods.relatedItem.XX.part                                     | Object                                     |         412 |   0.2572973783145772741 |
| metadata.mods.relatedItem.XX.part.detail                              | Array                                      |         412 |   0.2572973783145772741 |
| metadata.mods.relatedItem.XX.part.detail.XX.@type                     | String                                     |         412 |   0.2572973783145772741 |
| metadata.mods.relatedItem.XX.part.detail.XX.number                    | String                                     |         412 |   0.2572973783145772741 |
| metadata.mods.relatedItem.XX.titleInfo.nonSort                        | String                                     |         386 |   0.2410601651199680284 |
| metadata.mods.subject.cartographics                                   | Object                                     |         336 |   0.2098347551303348657 |
| metadata.mods.subject.cartographics.coordinates                       | String                                     |         336 |   0.2098347551303348657 |
| metadata.mods.recordInfo.recordChangeDate.#text                       | String                                     |         315 |   0.1967200829346889279 |
| metadata.mods.recordInfo.recordChangeDate.@encoding                   | String                                     |         315 |   0.1967200829346889279 |
| metadata.mods.subject.geographic.#text                                | String                                     |         312 |   0.1948465583353109487 |
| metadata.mods.subject.geographic.@authority                           | String                                     |         312 |   0.1948465583353109487 |
| metadata.mods.subject.geographic.@valueURI                            | String                                     |         312 |   0.1948465583353109487 |
| metadata.mods.location.#text                                          | String                                     |         302 |   0.1886014763373843051 |
| metadata.mods.titleInfo.partName                                      | String                                     |         256 |   0.1598740991469217998 |
| metadata.mods.part.detail.title                                       | String                                     |         245 |   0.1530045089492025057 |
| metadata.mods.part.detail.number                                      | String                                     |         219 |   0.1367672957545932599 |
| metadata.mods.subject.name                                            | Object                                     |         136 |   0.0849331151718022009 |
| metadata.mods.subject.name.namePart                                   | String                                     |         136 |   0.0849331151718022009 |
| metadata.mods.subject.name.@authority                                 | String                                     |         131 |   0.0818105741728388930 |
| metadata.mods.subject.name.@valueURI                                  | String                                     |         131 |   0.0818105741728388930 |
| metadata.mods.titleInfo.XX.@type                                      | String                                     |          83 |   0.0518341805827910521 |
| metadata.mods.subject.temporal                                        | String (1),Object (77)                     |          78 |   0.0487116395838277372 |
| metadata.mods.subject.temporal.#text                                  | String                                     |          77 |   0.0480871313840350728 |
| metadata.mods.subject.temporal.@encoding                              | String                                     |          77 |   0.0480871313840350728 |
| metadata.mods.subject.XX.name.#text                                   | String                                     |          48 |   0.0299763935900478375 |
| metadata.mods.name.XX.role.roleTerm.@authority                        | String                                     |          39 |   0.0243558197919138686 |
| metadata.mods.language.XX.languageTerm                                | Object                                     |          31 |   0.0193597541935725606 |
| metadata.mods.language.XX.languageTerm.#text                          | String                                     |          31 |   0.0193597541935725606 |
| metadata.mods.language.XX.languageTerm.@authority                     | String                                     |          31 |   0.0193597541935725606 |
| metadata.mods.language.XX.languageTerm.@type                          | String                                     |          31 |   0.0193597541935725606 |
| metadata.mods.subject.XX.topical                                      | String                                     |          29 |   0.0181107377939872354 |
| metadata.mods.name.role.XX.roleTerm.@authority                        | String                                     |           3 |   0.0018735245993779898 |
| metadata.mods.titleInfo.XX.partName                                   | String                                     |           3 |   0.0018735245993779898 |
| metadata.mods.physicalDescription.form.XX.#text                       | String                                     |           2 |   0.0012490163995853266 |
| metadata.mods.physicalDescription.form.XX.@authority                  | String                                     |           2 |   0.0012490163995853266 |
| metadata.mods.physicalDescription.form.XX.@valueURI                   | String                                     |           2 |   0.0012490163995853266 |
| metadata.mods.extension.XX.@xmlns:dcterms                             | String                                     |           1 |   0.0006245081997926633 |
| metadata.mods.extension.XX.dcterms:available                          | Object                                     |           1 |   0.0006245081997926633 |
| metadata.mods.extension.XX.dcterms:available.#text                    | String                                     |           1 |   0.0006245081997926633 |
| metadata.mods.extension.XX.dcterms:available.@encoding                | String                                     |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic                       | Object                                     |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic.city                  | null                                       |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic.citySection           | null                                       |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic.continent             | null                                       |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic.country               | null                                       |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic.county                | null                                       |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic.province              | null                                       |           1 |   0.0006245081997926633 |
| metadata.mods.subject.XX.hierarchicalGeographic.region                | null                                       |           1 |   0.0006245081997926633 |
| metadata.mods.subject.temporal.@keyDate                               | String                                     |           1 |   0.0006245081997926633 |
| metadata.mods.titleInfo.subTitle                                      | null                                       |           1 |   0.0006245081997926633 |
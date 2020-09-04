# SBI codes 2008 (upd.2019) linked data

This repository contains the dataset representing Dutch Standard Business Classification codes - SBI 2008 upd.2019. It includes both Dutch and English classification.

The sources [CSV data](https://www.cbs.nl/nl-nl/onze-diensten/methoden/classificaties/activiteiten/sbi-2008-standaard-bedrijfsindeling-2008) were retrived from the web site of the CBS (Centraal Bureau voor de Statistiek).

The Dutch Standaard Bedrijfsindeling (SBI 2008) is based on the activity classification of the European Union (Nomenclature statistique des activités économiques dans la Communauté Européenne, NACE) and on the classification of the United Nations (International Standard Industrial Classification of All Economic Activities, ISIC). For convenience we also include the NACE momenclature code in the SBI data.

NACE linked data can be found in the following repository: [nace-linked-data](https://github.com/KnowSyms/nace-linked-data)


## files
* [SBI_2008_upd.2019.ttl](https://github.com/KnowSyms/sbi-linked-data/blob/master/SBI_2008_upd.2019.ttl) - Turle format SBI codes
* [SBI_2008_upd.2019.nt](https://github.com/KnowSyms/sbi-linked-data/blob/master/SBI_2008_upd.2019.nt) - N-Triples format SBI codes
* [SBI_2008_upd.2019.jsonld](https://github.com/KnowSyms/sbi-linked-data/blob/master/SBI_2008_upd.2019.jsonld) - JSON-LD format SBI codes


## coverage
To include the NACE nomenclature we have used the `schema:nace` property that has been defined in the [`mfg.schema.org` extension](http://mfg.sdo-mfg.appspot.com/nace).


## desclaimer

Data is used under the following [desclaimer](https://www.cbs.nl/-/media/statline/documenten/disclaimer-open-data-v-2.pdf)

![image](https://github.com/bionomia/bionomia/blob/master/public/images/banner.jpg)

Bionomia is a web application that lives at https://bionomia.net whose MIT-licensed code is at https://github.com/bionomia/bionomia. Data about natural history specimens are periodically refreshed from the Global Biodiversity Information Facility from an avro-based download, processed using Apache Spark and sidekiq, then presented for ORCID-based OAuth2-authenticated people to claim or attribute to others with an ORCID or a wikidata Q number. Data and links are additionally archived to Zenodo.

- [Developer resources & APIs](https://bionomia.net/developers)
- [Downloads](https://bionomia.net/downloads)
- [Workshops and videos](https://bionomia.net/workshops)
- [User help](https://bionomia.net/help)

Person name parsing is done through the [dwc_agent](https://github.com/bionomia/dwc_agent) ruby gem to build an Elasticsearch index. Parsing outputs can be explored at https://bionomia.net/parse.

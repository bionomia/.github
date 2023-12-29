# Bionomia

![image](https://github.com/bionomia/bionomia/blob/master/public/images/banner.jpg)

<img align="left" width="100" height="100" src="https://github.com/bionomia/bionomia/blob/master/public/images/logo.png">
Bionomia is a web application that lives at https://bionomia.net. Developer resources and APIs are found at https://bionomia.net/developers, user help at https://bionomia.net/help, and workshops at https://bionomia.net/workshops. Data about natural history specimens are periodically refreshed from the Global Biodiversity Information Facility from an avro-based download, processed using Apache Spark and sidekiq, then presented for ORCID-based OAuth2 authenticated people to claim or attribute to others either with an ORCID or a wikidata Q number.


Person name parsing is used to supplemement search. The [dwc_agent](https://github.com/bionomia/dwc_agent) ruby gem can be explored at https://bionomia.net/parse.

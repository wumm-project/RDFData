# RDFData

The RDFData collected within the Open Discovery Project.

## Naming Conventions

### Namespaces

* od: <http://opendiscovery.org/rdf/Model#> is the RDF model.
* odp: <http://opendiscovery.org/rdf/Person/> - namespace for people
* odq: <http://opendiscovery.org/rdf/Principle/> - namespace for the principles
* odr: <http://opendiscovery.org/rdf/Parameter/> - namespace for the parameters within the matrix

### External Ontologies Used

* bibo: <http://purl.org/ontology/bibo/> - Bibliography (see Books.ttl)
* cc: <http://creativecommons.org/ns#> - Creative Commons
* dc: <http://purl.org/dc/elements/1.1/> - Dublin Core basic (see Books.ttl)
* dcterms: <http://purl.org/dc/terms/> - Dublin Core new (see Books.ttl)
* foaf: <http://xmlns.com/foaf/0.1/> - Friend of a Friend (see People.ttl)
* ical: <http://www.w3.org/2002/12/cal/ical#> - Event Dates (see Conferences)
* owl: <http://www.w3.org/2002/07/owl#> - Ontology Web Language
* rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> - RDF Basics
* rdfs: <http://www.w3.org/2000/01/rdf-schema#> - RDF Basicss
* skos: <http://www.w3.org/2004/02/skos/core#> - Knowledge description 
* swc: <http://data.semanticweb.org/ns/swc/ontology#> - Semantic Web Conference Ontology (see Conferences) 
* xsd: <http://www.w3.org/2001/XMLSchema#> - XSchema Data Types

### File Name Conventions

* The Turtle file xxx.ttl contains data of the
  <http://opendiscovery.org/rdf/xxx/> RDF graph. Usually xxx is in plural
  form or prepended with "The" (as "TheMatrix").

* The instances within such an RDF graph are named by naming conventions that
  are specified elsewhere (to be added). All instances of a certain type have
  a namespace prefix <http://opendiscovery.org/rdf/xxx/> in common where xxx
  is usually in singular form.

* We try to supply all graphs with information in english, german and russian.
  It is a raw translation by Google Translate that requires additional QA. 

## RDF Graphs

* Books.ttl - A list of TRIZ-related books.
  * Uses terminology as recommended in <http://eprints.rclis.org/22454/1/LODE-BD-2.pdf>
  * Contains bibliography supplied by V.M.Petrov
  * Contains bibliography supplied by D.Zobel
  * Contains selected books freom the TRIZ Body of Knowledge reference list
* ConferenceSeries.ttl - information about TRIZ Conference Series
* Conferences - information about several TRIZ Conferences 
* Glossary.ttl - A glossary extracted from the German VDI norm
* MATRIZ-Certificates.ttl - Data of MATRIZ certificates
  * 2020-04-06 graebe: Level 4 certificates
  * 2020-04-18 graebe: Level 5 certificates
* Ontology.ttl - A first RDF version of the ontology proposed at <https://r1.nubex.ru/s828-c8b/ca459bfe73_fit-in~160x160__f3107_7e> 
* PastConferences.ttl - Information about Past TRIZ Conferences, in particular links to the proceedings, if published.
* People.ttl - People within the TRIZ Social Network
  * 2020-04-01 graebe: Update with the authors listed in the TBK-2012
  * 2020-04-06 graebe: Update with the MATRIZ Level 4 certificates
  * 2020-04-17 graebe: Update with the authors listed in the TBK-2007
  * 2020-04-18 graebe: Update with the MATRIZ Level 5 certificates
* SeparationPrinciples.ttl - The 4 Separation Principles
* StandardSolutions.ttl - The 76 Standard Solutions 
* TBK1-Concepts.ttl - Concepts in the TRIZ Body of Knowledge (2012 English
  version) as RDF Data
* TBK2-Concepts.ttl - Concepts in the TRIZ Body of Knowledge (2007 Russian
  version) as RDF Data
* TBK-References.ttl - Literature referenced in TBK1 and TBK2
* TheMatrix.ttl - Altshullers 39x39 matrix 
* TheParameters.ttl - The 39 parameters as in the matrix of Altshuller 1985 
* ThePrinciples.ttl - The 40 principles according to Altshuller 1985 


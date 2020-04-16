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
* owl: <http://www.w3.org/2002/07/owl#> - Ontology Web Language
* rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> - RDF Basics
* rdfs: <http://www.w3.org/2000/01/rdf-schema#> - RDF Basicss
* skos: <http://www.w3.org/2004/02/skos/core#> - Knowledge description 
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
* Conferences/TRIZ-Summit-2019.ttl - information about the TRIZ Summit 2019 in
  Minsk
* Glossary.ttl - A glossary extracted from the German VDI norm
* MATRIZ-Certificates.ttl - Data of MATRIZ certificates (Level 4 only at the moment)
* People.ttl - People within the TRIZ Social Network
  * HGG, 2020-04-01: Update with the authors listed in the TBK
  * HGG, 2020-04-06: Update with the MATRIZ Level 4 certificates
* StandardSolutions.ttl - The 76 Standard Solutions in TRIZ form
* TBK.ttl - TRIZ Body of Knowledge as RDF Data
* TheParameters.ttl - The 39 parameters as in the matrix of Altshuller 1985 
* ThePrinciples.ttl - The 40 principles according to Altshuller 1985 
* TheMatrix.ttl - Altshullers 39x39 matrix 


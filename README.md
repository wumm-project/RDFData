# RDFData

The RDFData collected within the Open Discovery Project.

## Naming Conventions

* od: <http://opendiscovery.org/rdf/Model#> is the RDF model.

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
  * This uses terminology as recommended in
    <http://eprints.rclis.org/22454/1/LODE-BD-2.pdf>
  * Contains at the moment mainly bibliography supplied by V.M.Petrov
* Conferences/TRIZ-Summit-2019.ttl - information about the TRIZ Summit 2019 in
  Minsk
* Glossary.ttl  -  A glossary extracted from the German VDI norm
* People.ttl - People within the TRIZ Social Network
* StandardSolutions.ttl - The 76 Standard Solutions in TRIZ form
* ThePrinciples.ttl - The 40 principles according to Altshuller 1985 
* TheMatrix.ttl - Altshullers 39x39 matrix 


# Achievement Standards Network (ASN) Files for T3 DESM

## Schema Files

ASN namespace files defining terms (properties and classes)--four (RDF and JSONLD) schema files and a JSONLD @context file:

1. **Schema File 1 (asnTerms.jsonld):** A JSONLD version of the namespace file defining ASN terms ONLY; 

1. **Schema file 2 (asnProfile.jsonld):** A JSONLD version of the profile schema file including all of the ASN terms and all terms borrowed from other namespaces (e.g., Dublin Core 1.1 and Terms).

1. **Schema File 3 (asnTerms.rdf):** An RDF version of the namespace file defining ASN terms ONLY; 

1. **Schema file 4 (asnProfile.rdf):** An RDF version of the profile schema file including all of the ASN terms and all terms borrowed from other namespaces (e.g., Dublin Core 1.1 and Terms).

1. **Context File (asnContext.json):** A context file for referencing from ASN data instances using JSON-LD that includes ALL terms from both the ASN namespace and profile schemas.

*Note 1: In the ASN namespace, the competency framework class is called StandardsDocument and a competency is called a Statement.

*Note 2: Ignore any other files in the repo.

## Concept Scheme Files

Currrently, there are thirteen concept schemes modeled using W3C's Simple Knowledge Organization System ([SKOS](http://www.w3.org/2004/02/skos/core#)) with most encoded in RDF/XML or JSON-LD. 

The most frequently found vocabulary terms come from the: (1) Subject/Topic vocabulary, (2) Education Level vocabularies, (3) Publication Status vocabulary, and (4) Indexing Status vocabulary.

1. U.S. Subject/Topic Vocabulary (SKOS Encoding)—**ASNTopic.rdf**
This vocabulary of learning area subjects is intended to provide a uniform categorization of U.S. achievement standards.

1. U.S. Education Level Vocabulary (SKOS Encoding) U.S. Department of Education's education level vocabulary—**ASNEducationLevel.rdf** (augmented)

1. Publication Status Vocabulary (SKOS Encoding)—**ASNPublicationStatus.json** | **ASNPublicationStatus.rdf**
This vocabulary describes the various publication statuses of ASN Standard Documents and Statements.

1. Authority Status (Original or derived)—**ASNAuthorityStatus.rdf**

1. Indexing Status Vocabulary (SKOS Encoding)—**ASNIndexingStatus.rdf**
This vocabulary defines whether a statement should or should not be used in correlation work.

1. ASN Export Version Vocabulary (SKOS Encoding)—**ASNExport.rdf**
We distribute and make available through web services only the most current export version of the ASN. The current ASN export version is 3.1.0.

1. Jurisdiction (SKOS Encoding)—**ASNjurisdiction.rdf**
The jurisdiction of applicability of the standard.

1. Bloom's Taxonomy—**ASNBloomsTaxonomy.rdf**

Some of the schemes are encoded in **both** rdf/XML and JSON-LD. 

## Upload

In all cases, use the Schema File 2 (asnProfile.jsonld) and as many of the thirteen concept schemes as necessary. Also condider whether the asnContext.json file is needed to suport JSON-LD serializations.


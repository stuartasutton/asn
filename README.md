# Achievement Standards Network (ASN) Files for T3 DESM

## Schema Files
There are two ASN schema files defining terms (properties and classes) and a @context file:
1. **Schema File 1 (asnTerms.json):** A namespace file defining ASN terms ONLY; 

1. **Schema file 2 (ASN_Profile.jsonld):** A profile schema file including all of the ASN terms in Schema File 1 plus all terms borrowed from other namespaces (e.g., Dublin Core 1.1 and Terms).

1. **Context File (asnContext.json):** A context file for use in JSON-LD that includes ALL terms from both Schema File 1 and Schema File 2.

For DESM purposes, Schema file 2 should be used since it provides all terms that will be found in ASN competency framework instances. Note that in the ASN namespace, the competency framework class is called StandardsDocument and a competency is called a Statement.

## Concept Scheme Files

Currrently, there are eleven concept schemes modeled using W3C's Simple Knowledge Organization System ([SKOS](http://www.w3.org/2004/02/skos/core#)) with most encoded in RDF/XML or JSON-LD. Some of the schemes are encoded in **both** rdf/XML and JSON-LD.  None of the concept schemes have been added to the context file since range URIs are stated in full in ASN data. 

1. ASN U.S. Subject/Topic Vocabulary (SKOS Encoding)—**ASNTopic.rdf**
This vocabulary of learning area subjects is intended to provide a uniform categorization of U.S. achievement standards.

1. U.S. Education Level Vocabulary (SKOS Encoding) U.S. Department of Education's education level vocabulary—**ASNEducationLevel.rdf** 

1. Canada, British Columbia's education level vocabulary— **ASNEducationLevel_CAN-BC.rdf**

1. Canada, Ontario's education level vicabulary—**ASNEducationLevel_CAN-ON.rdf** 

1. ASN Publication Status Vocabulary (SKOS Encoding)—**ASNPublicationStatus.json** | **ASNPublicationStatus.rdf**
This vocabulary describes the various publication statuses of ASN Standard Documents and Statements.

1. Authority Status (Original or derived)—**ASNAuthorityStatus.rdf**

1. ASN Indexing Status Vocabulary (SKOS Encoding)—**ASNIndexingStatus.rdf**
This vocabulary defines whether a statement should or should not be used in correlation work.

1. ASN Export Version Vocabulary (SKOS Encoding)—**ASNExport.rdf**
We distribute and make available through web services only the most current export version of the ASN. The current ASN export version is 3.1.0.

1. ASN NGSS Topic Vocabulary (SKOS Encoding)—**NGSSTopic.rdf**
This vocabulary consists of the topics found in the Next Generation Science Standards.

1. New York State (NYS) Social Studoes Framework Themes (SKOS Encoding)—**NYS-SS-Theme.rdf**

1. Scottish Curriculum for Excellence Learning Experiences Vocabulary—**CfEExperience.rdf**

***The most frequently found vocabulary terms come from the: (1) Subject/Topic vocabulary, (2) Education Level vocabularies, (3) Publication Status vocabulary, and (4) Indexing Status vocabulary.*** 

## Upload

In all cases, upload the Schema File 2 (ASN_Profile.jsonld) and as many of the thirteen concept schemes as the mapping project demands. Also condider whether the asnContext.json file is needed.

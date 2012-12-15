# British National Bibliography Queries

The British National Bibliography (BNB) is a bibliographic database that contains information on a wide range of books and serial publications that have been published in the UK and Ireland since the 1950s. The database is available under a public domain license and can be accessed via an online API.

This project contains a number of sample SPARQL queries for working with the [British National Bibliography Linked Data](http://www.bl.uk/bibliographic/datafree.html#lod).

The public SPARQL endpoint for the dataset can be found at:

	http://bnb.data.bl.uk/sparql

Each query in this project has been tested against the live dataset and is known to return useful results.

## Prefixes

The `_prefixes.rq` file provides a useful set of starting prefixes for working with the data. These include the following:

	PREFIX bio: <http://purl.org/vocab/bio/0.1/> 
	PREFIX bibo: <http://purl.org/ontology/bibo/> 
	PREFIX blterms: <http://www.bl.uk/schemas/bibliographic/blterms#> 
	PREFIX dct: <http://purl.org/dc/terms/> 
	PREFIX event: <http://purl.org/NET/c4dm/event.owl#> 
	PREFIX foaf: <http://xmlns.com/foaf/0.1/> 
	PREFIX geo: <http://www.w3.org/2003/01/geo/wgs84_pos#> 
	PREFIX isbd: <http://iflastandards.info/ns/isbd/elements/> 
	PREFIX org: <http://www.w3.org/ns/org#> 
	PREFIX owl: <http://www.w3.org/2002/07/owl#> 
	PREFIX rda: <http://RDVocab.info/ElementsGr2/> 
	PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> 
	PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#> 
	PREFIX skos: <http://www.w3.org/2004/02/skos/core#> 
	PREFIX xsd: <http://www.w3.org/2001/XMLSchema#> 

## Rights

The contents of this project including all text, queries or other sample code is placed into the public domain under the terms of 
the [CC0 Waiver](<http://creativecommons.org/publicdomain/zero/1.0/>)


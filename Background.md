# Background

## What is the British National Bibliography?

The British National Bibliography has been in development for over 60 years with the first record added in 1950. It contains data about virtually every book and journal title published or distributed in the UK and Ireland since that date. In its role as the [library of legal deposit](http://www.bl.uk/aboutus/stratpolprog/legaldep/) in the United Kingdom the British Library is responsible for preserving a wide variety of works, and the majority of these are catalogued in the BNB. The [exclusions](http://www.bl.uk/bibliographic/exclude.html) largely relate to some official government publications that are catalogued elsewhere, or other locally published or ephemeral material. With an increasing number of works being published electronically, in 2003 the BNB was extended to also include data about type of publication.

## The BNB Data Model

There are high level overview diagrams that show the main types of resources and relationships in the BNB dataset. One diagram summarises [the data model for books](http://www.bl.uk/bibliographic/pdfs/bldatamodelbook.pdf) while another summarises [the model for serials](http://www.bl.uk/bibliographic/pdfs/bldatamodelserial.pdf) (e.g periodicals and newspapers).

## RDF and OWL Schemas

The BNB dataset makes use of a number of standard schemas. These are summarised in the following table along with their base URI and links to their individual documentation.

<table border="1">
	<tr>
		<th>Name</th><th>URI</th><th>Role</th>
	</tr>
	<tr>
		<td><a href="http://bibliontology.com/">Bibliographic Ontology</a></td><td><code>http://purl.org/ontology/bibo/</code></td><td>A rich vocabulary for describing many types of publication and their related metadata</td>
	</tr>
	<tr>
		<td><a href="http://vocab.org/bio/0.1/.html">Bio</a></td><td><code>http://purl.org/vocab/bio/0.1/</code></td><td>Contains terms for publishing biographical information</td>
	</tr>
	<tr>
		<td><a href="http://www.bl.uk/schemas/">British Library Terms</a></td><td><code>http://www.bl.uk/schemas/bibliographic/blterms</code></td><td>A new schema published by the British Library which contains some terms not covered in the other vocabularies</td>
	</tr>

	<tr>
		<td><a href="http://purl.org/dc/terms/">Dublin Core</a></td><td><code>http://purl.org/dc/terms/</code></td><td>Basic bibliographic metadata terms like title and creator</td>
	</tr>
	<tr>
		<td><a href="http://motools.sourceforge.net/event/event.html">Event Ontology</a></td><td><code>http://purl.org/NET/c4dm/event.owl#</code></td><td>Properties for describing events and their participants</td>
	</tr>
	<tr>
		<td><a href="http://xmlns.com/foaf/spec/">FOAF</a></td><td><code>http://xmlns.com/foaf/0.1/</code></td><td>Contains terms for describing people, their names and relationships</td>
	</tr>
	<tr>
		<td><a href="http://metadataregistry.org/schema/show/id/25.html">ISBD</a></td><td><code>http://iflastandards.info/ns/isbd/elements/</code></td><td>Terms from the International Standard Bibliographic Description standard</td>
	</tr>
	<tr>
		<td><a href="http://www.epimorphics.com/public/vocabulary/org.html">Org</a></td><td><code>http://www.w3.org/ns/org#</code></td><td>Contains terms for describing organisations</td>
	</tr>
	<tr>
		<td><a href="http://www.w3.org/TR/owl-features/">Web Ontology Language</a></td><td><code>http://www.w3.org/2002/07/owl#</code></td><td>A standard ontology for describing terms and equivalencies between resources</td>
	</tr>
	<tr>
		<td><a href="http://www.w3.org/TR/rdf-schema/">RDF Schema</a></td><td><code>http://www.w3.org/2000/01/rdf-schema#</code></td><td>The core RDF schema language which is used to publish new terms</td>
	</tr>

	<tr>
		<td><a href="http://metadataregistry.org/schema/show/id/15.html">Resource Description and Access</a></td><td><code>http://rdvocab.info/ElementsGr2#</code></td><td>Defines some standard library cataloguing terms</td>
	</tr>
	<tr>
		<td><a href="http://www.w3.org/2004/02/skos/">SKOS</a></td><td><code>http://www.w3.org/2004/02/skos/core#</code></td><td>Supports publication of subject classifications and taxonomies</td>
	</tr>
	<tr>
		<td><a href="http://www.w3.org/2003/01/geo/">WGS84 Geo Positioning</a></td><td><code>http://www.w3.org/2003/01/geo/wgs84_pos#</code></td><td>Geographic points, latitude and longitude</td>
	</tr>
</table>

## Further Reading

* The [BNB Linked Data](http://www.bl.uk/bibliographic/datafree.html#lod)
* The [BNB Bibliographic Number](http://www.bl.uk/bibliographic/bnbstruct.html)
* The [BNB Linked Data on the Data Hub](http://datahub.io/dataset/bluk-bnb)

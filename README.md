## Resource Repository for the Open Risk Academy Course PYT 26060

This repo collects resources (data and python scripts) used in the [course PYT26060](https://www.openriskacademy.com/course/view.php?id=60)

## Scripts

### Step 2
* hello_world_rdflib.py (load and parse a file containing rdf triples)
* explore_rdf_file.py (print out statistics about an rdf graph)
* filter_rdf_file.py (filter triples matching specific criteria)
* json_to_rdf.py (convert a json file to rdf)

### Step 3
* hello_world_owlready.py (loading, parsing and printing ontology properties)
* json_to_owl.py (convert a json file to owl class instances)

### Step 4
* hello_world_jsonld.py (convert an ontology form rdf/xml format to json-ld format)
* json_to_jsonld.py (convert a json file into a json-ld serialized set of owl class instances)

### Step 5
* hello_world_pyshacl.py (validate an OWL graph using a SHACL shape file)


## Data sets (only the input files - various files are created during the course)
* cro.owl an ontology file serialized in rdf/xml format
* ecai_list.json a json file with credit rating agency data (from ESMA)
* shacl_graph.ttl (a SHACL validation shape)


## DISCLAIMER

* The credit rating agency data sets included in this repo are actual published data obtained from [ESMA](https://www.esma.europa.eu/supervision/credit-rating-agencies/risk). They are only used here for educational purposes.

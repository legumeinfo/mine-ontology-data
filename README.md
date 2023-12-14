# mine-ontology-data

Scripts to update the ontology data that are loaded into the mines

The data are not stored in this repo, and reside in the following ignored directories, which are created by the update scripts if not already present.

```
ChEBI/
InterPro/
PANTHER/
Pfam/
SO-Ontologies/
crop-ontology/
gene-ontology/
phytozome/
plant-ontology/
plant-reactome/
plant-trait-ontology/
semanticscience/
soybean-ontology/
```

Note that update-crop-ontology uses `jar/robot.jar` to convert the downloaded OWL/RDF file into an OBO file.

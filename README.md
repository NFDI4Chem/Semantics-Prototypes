# Jupyter notebooks Prototypes for integrating semantics into NFID4Chem

Using [Terminology Service](https://terminology.nfdi4chem.de/ts/index) and SPARQL endpoints


**Create and start virtual environment**
`python -m venv venv`

`source venv/bin/activate`

**Install dependencies:**
`pip install -r requirements.txt`

**start jupyter notebook**
`jupyter-notebook`

## Notebooks - Prototypes
Run Notebooks in the Browser via [BINDER](https://mybinder.org/v2/gh/NFDI4Chem/Semantics-Prototypes/main)

* [SPARQL Queries to ChEBI in triple store](Chebi_SPARQL.ipynb) 
* [Chemistry Ontologies Explorer](ontologies_explorer.ipynb) Displays the Network of borrowed terms for Chemistry ontologies 
* [RXNO *Reaction Types* Tree via Ontology Look Service (OLS) API](RXNO-Reactions-OLSAPI.ipynb) 
* [SPARQL queries to Wikidata to enrich Chemotion data](chemotion-query-wikidata.ipynb)

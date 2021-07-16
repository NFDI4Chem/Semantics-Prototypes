# Prototype for including Semantic in [Chemotion](https://www.chemotion-repository.net)
Using Python3 and Jupyter notebooks


**Create and start virtual environment**
`python -m venv venv`

`source venv/bin/activate`

**Install dependencies:**
`pip install -r requirements.txt`

**start jupyter notebook**

## Notebooks - Prototypes 
* [Chemistry Ontologies Explorer](ontologies_explorer.ipynb) Displays the Network of borrowed terms for Chemistry ontologies 
* [RXNO *Reaction Types* Tree via Ontology Look Service (OLS) API](RXNO-Reactions-OLSAPI.ipynb) - run notebook in [Binder](https://mybinder.org/v2/gh/NFDI4Chem/Sematics-in-Chemotion-Prototypes/HEAD?filepath=RXNO-Reactions-OLSAPI.ipynb)
* [SPARQL queries to Wikidata to enrich Chemotion data](chemotion-query-wikidata.ipynb) - run notebook in [Binder](https://mybinder.org/v2/gh/NFDI4Chem/Sematics-in-Chemotion-Prototypes/HEAD?filepath=chemotion-query-wikidata.ipynb)


## Further ideas:
* store structured Chemotion reactions data into a triples format using [Apache Jena Fuseki](https://github.com/NFDI4Chem/Fuseki-Box)
  * perform SPARQL queries on data - in order to showcase the possibilities of querying a Chemotion Knowledge Graphs (triples) - whereby questions such as: *What are the reactions that have C7H5ClO as starting material & a density > 1.0ml.* can be answered.
  * and associate results with other Knowledge Graphs  such as Wikidata or PubChem

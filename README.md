# Translatorpy
Python package for interacting the NCATS Biomedical Data Translator.

Learn more about the NCATS Biomedical Data Translator:

* https://ncats.nih.gov/translator
* https://smart-api.info/registry?tags=translator
* https://arax.ncats.io/

Our method directly queries translator and pipes the results into the [Knowledge Graph Exchange](https://github.com/biolink/kgx) format to enable easier downstream analysis. KGX formatted files can be piped to RDF, Neo4j or analyzed on their own.

## Installation

```
pip install . 
```

## Examples

The single_query_example.py script shows a single example of a query. That script prints out a URL that one can follow to see the results of the query within the Translator ARAX user interface.

See the notebooks/Gene-to-compound.ipynb jupyter notebook for a single worked example of how to use the package.
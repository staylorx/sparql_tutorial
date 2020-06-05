# sparql_tutorial

This is the very fine Jena SPARQL tutorial using Python notebooks, and using the results as Panda's DataFrames.

A fairly comprehensive tutorial on using SPARQL in Python, including,

- Converting the SPARQL request into a Pandas DataFrame. It's turning out to be a lot easier to manipulate the dataframe outside of the SPARQL query that inside it.
- Loading a graph via data and strings instead of files.
- A very good list of FILTER, UNION, GRAPH, etc... which I can take no credit for. This is a copy of the Apache Jena tutorial found here: https://jena.apache.org/tutorials/sparql.html

This does need some work in the conjunctive graph space.

At a minimum this needs the packages in requirements:

`pip install -r requirements`

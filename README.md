# ABCDoExperiments
Experiments to support paper "Artificial Benchmark for Community Detection with Outliers" in a Python Jupyter Notebook.

## Datasets

* The ABCD+o datasets were built using: https://github.com/bkamins/ABCDGraphGenerator.jl
* The email_EU dataset is taken from: https://snap.stanford.edu/data/email-Eu-core.html
* The Football dataset reference: "Community structure in social and biological networks", M. Girvan and M. E. J. Newman PNAS June 11, 2002 99 (12) 7821-7826; https://doi.org/10.1073/pnas.122653799

## Required packages

The notebook uses mainly common Python packages, with the addition of:
* pip install **igraph** (see: https://pypi.org/project/igraph/ and https://igraph.readthedocs.io/en/0.10.2/)
* pip install **partition-igraph** (see: https://pypi.org/project/partition-igraph/)

## Optional tools

Files with stored experiment results are supplied for a few (longer) tests, but those can also be re-created. The following tools then need to be installed to run those: 
* The **node2vec** graph embedding code from: https://github.com/snap-stanford/snap/tree/master/examples/node2vec
* The graph embedding divergence (**GED**) code from: https://github.com/ftheberge/Comparing_Graph_Embeddings

and the full paths to the executables needs to be supplied, as explained in the notebook.

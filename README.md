# dbase_search

Perform a substructure search against a compound database using RDkit in a Jupyter notebook.  Notebooks for follow-up analysis as well as plotting the hits are provided as well.

The workflow described in this repository starts with a compound database prepared using the workflow in the `dbase_prep` repository.

# Requirements

* Compound database in pickle format
* RDkit
* Jupyter notebook
* Pandas

# Usage

As the workflow in this repository is contained in Jupyter notebooks, there are no usage instructions.  Feel free to work your way through the notebooks in the following order, using `58_molobj.pkl` as an example compound database pickle:

1. `substructure_search.ipynb`
2. `plot_mols.ipynb`

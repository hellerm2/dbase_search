# dbase_search

Perform a substructure or similarity search against a compound database using RDkit in a Jupyter notebook.  A notebook for plotting the hits is provided as well.

The workflow described in this repository starts with a compound database prepared using the workflow in the `dbase_prep` repository.

# Requirements

* Compound database in pickle format
* RDkit
* Jupyter notebook
* Pandas

# Usage

As the workflow in this repository is contained in Jupyter notebooks, there are no usage instructions.  Feel free to work your way through the notebooks in the following order, using `58_molobj.pkl` as an example compound database pickle:

1. Open `substructure_search.ipynb` or `similarity_search.ipynb` in Jupyter
2. Open `plot_mols.ipynb` in Jupyter

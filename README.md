
# Macauqe regulatory network explorer

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/shelby2919/Macaque_GRN.git/main)

Interactive visualization of transcriptional regulatory networks (TRNs) and gene expression heatmaps.

This repository uses Jupyter notebooks to interactively visualize TRNs and gene expression heatmaps 
with [jp_gene_viz](https://github.com/simonsfoundation/jp_gene_viz)

In order to run the notebook, perform the following actions:
1) Click on launch binder button at top of README section
2) Navigate to Notebooks file in home folder
3) Click on Endo Basic or Epi Basic to launch the respective notebook
4) Run the first two cells of code
5) The third cell can be run if you only want to visualize the GRN
6) The fourth cell can be run if you want to generate GRN and heatmap visualization of the data
7) Enjoy!

This repository is designed to either run in the cloud using 
[Binder](https://mybinder.org/v2/gh/shelby2919/Macaque_GRN.git/main)
or locally in a encapsulated container using
[`repo2docker`](https://repo2docker.readthedocs.io/en/latest/)
to build and run a `docker` container which includes
the code for running the analysis and all needed dependencies.
The `repo2docker` tool requires the `docker` infrastructure
and Python 3 to run.  See the 
[installation instructions](https://repo2docker.readthedocs.io/en/latest/install.html).

To build and run the docker image from the command line

```bash
jupyter-repo2docker https://github.com/shelby2919/Macaque_GRN
```

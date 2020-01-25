# data-oriented-programming-paradigms-ws19


To Install R Cells in jupyter notebooks:

The following works for windows 10 and miniconda

conda install -c r r-irkernel
conda install -c rpy2
conda install -c conda-forge tzlocal
conda install -c anaconda simplegeneric


In Jupyter one has to activate the rpy2 extension in a Python cell first:
%load_ext rpy2.ipython

Then one can use the R Magic %%R to execute R code! 
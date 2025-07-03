Install Conda using miniconda on Mac

Next execute the below command 

`conda create -n faiss -c conda-forge -c pytorch python=3.11 faiss-cpu=1.11.0`

`conda activate faiss`

The above command uses conda package manager to create faiss namespace and then use the pytorch channel and the conda-forge channel/repos to install the faiss-cpu package and the dependency around libcxx>20

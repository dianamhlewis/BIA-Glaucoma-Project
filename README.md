The miniconda environment file can be found here as a txt file

Open a new miniconda prompt
conda install --file tensorflow_environment.txt





conda create --name tf python=3.9

conda activate tf

ipython kernel install --user --name=my-conda-env-kernel

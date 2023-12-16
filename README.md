# basicDataStructures_vectors
Basic Data Structures: VECTORS

Before runing the code:
1. Install **rpy2**. Open _Terminal_ from Anaconda (use the _environment_ for this workshop) and run: **pip install rpy2[all]** ([see options](https://pypi.org/project/rpy2/)).
2. While in the _Terminal_, verify the Python version of your environment (python -V) and find the **R** PATH using: **R RHOME**
3. Start Jupyter. If you have problems runing **%load_ext rpy2.ipython** locally (not in Colab), set the path like this:
import os
os.environ['R_HOME'] = '_write the path you got in step 2_'

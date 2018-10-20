
To run this tutorial on a Mac, you can install Miniconda + necessary packages with:

Download miniconda from the website https://conda.io/miniconda.html

```
bash Miniconda2-latest-MacOSX-x86_64.sh


conda create -n env_for_tp_n7 python=2.7
source activate env_for_tp_n7
pip install jupyter
conda install numpy
conda install scipy
conda install pytorch torchvision -c pytorch
pip install matplotlib
conda install -c pytorch faiss-cpu
pip install ipdb
```
(Adapt to your OS and favorite python version (this is 2.7)

# metal
Snorkel MeTaL: The best of Snorkel plus multi-task learning (MTL) &amp; hierarchical weak supervision

## Setup
[1] [install anaconda3]

[2] Create conda environment:
```
conda create -n metal python=3.6
source activate metal
```

[3] Download dependencies:
```
conda install -q matplotlib numpy pandas pytorch scipy torchvision -c pytorch
```

[4] Test functionality:
```
python -m unittest discover tests
```

[5] View analysis tools:
[launch jupyter notebook] (see Tips below to get proper environment)

launch ```notebooks/Tools.ipynb```

restart and run all


### Tips
To run a jupyter notebook with a conda environment named `metal`, use one of the
following:

1) Temporary solution:

```python -m ipykernel install --user --name metal --display-name "Python 3 (MeTaL)"```

2) Permanent solution:

```conda install --channel=conda-forge nb_conda_kernels```

Then select the kernel named `metal` in the upper right corner of the notebook.

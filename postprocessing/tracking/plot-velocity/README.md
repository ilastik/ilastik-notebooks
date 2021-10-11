## How to plot velocity vs angle in a "rose-plot"

Related forum discussion [on image.sc](https://forum.image.sc/t/rose-plot-from-ilastik-tracking/58384)

### How to run the notebook

The easiest way to run this notebook is installing a [conda](https://docs.conda.io/en/latest/miniconda.html) environment with the following command:

```bash
conda create -n ilastik-tracking-analysis -c conda-forge jupyter notebook seaborn matplotlib pandas h5py pytables
```

Then activate the environment and run the notebook server

```bash
conda activate ilastik-tracking-analysis
jupyter notebook --notebook-dir .
```

Then the browser should open and let you navigate/choose the notebook.


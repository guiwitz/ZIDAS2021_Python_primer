[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guiwitz/ZIDAS2021_Python_primer/master?urlpath=lab)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guiwitz/ZIDAS2021_Python_primer/blob/master)

# ZIDAS 2021 Python primer

This repository contains an example notebook with the simple analysis workflow demonstrated during the presentation. You can run this material interactively by clicking on the *launch binder* button above.

## Installing on your own computer

If you use conda to install Python software on your computer, you can create an environment that contains the appropriate software to run the notebook using the [environment.yml](environment.yml) file that you can download with the entire repository with [this link](https://github.com/guiwitz/ZIDAS2021_Python_primer/archive/refs/heads/master.zip).

Then, if you use the Anaconda Navigator, go to the ```Environments``` tab, select ```import``` and select the downloaded ```environment.yml``` file. Select that environment before starting Jupyter to use this environment.

If you use mini-forge or miniconda, open a terminal, move to the downloaded folder and type:

```
conda env create -f environment.yml
```

Then when you want to use this environment, open a terminal, activate it, and start Jupyter:

```
conda activate ZIDAS
jupyter lab
```

## Next step

You can learn more about bioimage processing with Python in another course also available on GitHub: https://github.com/guiwitz/PyImageCourse_beginner#readme. That course is for beginners and starts with basics of Python, and ends with an analysis pipeline reproducing that from the excellent [Fiji Macro Programming course](https://github.com/ahklemm/ImageJMacro_Introduction) by Anna Klemm.

## Data

The example image comes from the [Cell Atlas](https://www.proteinatlas.org/humanproteome/cell). For more information see the publication of Thul PJ et al., A subcellular map of the human proteome. **Science**. (2017) DOI: [10.1126/science.aal3321](https://doi.org/10.1126/science.aal3321). The image is covered by a [Creative Commons Attribution-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-sa/3.0/).
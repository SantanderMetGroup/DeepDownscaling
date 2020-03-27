[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3731351.svg)](https://doi.org/10.5281/zenodo.3731351)

# DeepDownscaling
### Deep learning approaches for statistical downscaling in climate

Transparency and reproducibility are key ingredients to develop top-quality science. For this reason, this repository is aimed at hosting and maintaining updated versions of the code and notebooks needed to (partly or fully) reproduce the results of the papers developed in the Santander MetGroup dealing with the application of deep learning techniques for statistical dowscaling in climate.

These works build on [climate4R](https://github.com/SantanderMetGroup/climate4R), a bundle of `R` packages developed for transparent climate data access, post processing (including bias correction and downscaling), visualization and model validation. A battery of Jupyter notebooks with worked examples explaining how to use the main functionalities of the core climate4R packages (including [downscaleR](https://github.com/SantanderMetGroup/downscaleR) for standard statistical downscaling methods) can be found at the [notebooks' repositoty](https://github.com/SantanderMetGroup/notebooks).
For deep learning impplementations we use [`keras`](https://cran.r-project.org/web/packages/keras/index.html), an `R` library which provides an interface to [Keras](https://keras.io), a high-level neural networks API which supports arbitrary network architectures and is seamlessly integrated with [TensorFlow](https://www.tensorflow.org), and a wrapper of this package for the downscaleR package, [downscaleR.keras](https://github.com/SantanderMetGroup/downscaleR.keras).

The table below lists the documents (Jupyter notebooks, scripts, etc.) contained in this respository along with the information of the corresponding published (or submitted) papers.
 
| Notebook files  | Article Title | Journal | Paper files 	
|---|---|---|---
| 2020_Bano_GMD.ipynb 2020_Bano_GMD_FULL.ipynb | Configuration and Intercomparison of Deep Learning Neural Models for Statistical Downscaling | Geoscientific Model Development | 	https://doi.org/10.5194/gmd-2019-278
| - | The Importance of Inductive Bias in Convolutional Models for Statistical Downscaling | Proceedings of the 9th International Workshop on Climate Informatics (CI2019) | 2019_Bano_CI.pdf
| - | Deep Convolutional Networks for Feature Selection in Statistical Downscaling | Proceedings of the 8th International Workshop on Climate Informatics (CI2018) | 2018_Bano_CI.pdf
|  |  |  |

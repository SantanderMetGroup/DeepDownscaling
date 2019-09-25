# DeepDownscaling
### Deep learning approaches for statistical downscaling of climate

Transparency and reproducibility are key ingredients to develop top-quality science. For this reason, this repository is aimed at hosting and maintaining updated versions of the code needed to (partly or fully) reproduce the results presented in the [Santander Met Group](http://www.meteo.unican.es/en/view/publications) papers dealing with the application of deep learning techniques for statistical dowscaling of climate.

On the one hand, we lean for many tasks on [climate4R](https://github.com/SantanderMetGroup/climate4R), a bundle of `R` packages developed by the Santander Met Group for transparent climate data access, post processing (including bias correction and downscaling) and visualization. A battery of notebooks with worked examples explaining how to use the main functionalities of the core climate4R packges ([loadeR](https://github.com/SantanderMetGroup/loadeR), [transformeR](https://github.com/SantanderMetGroup/transformeR), [downscaleR](https://github.com/SantanderMetGroup/downscaleR), [visualizeR](https://github.com/SantanderMetGroup/visualizeR) and [climate4R.value](https://github.com/SantanderMetGroup/climate4R.value)) can be found [here](https://github.com/SantanderMetGroup/notebooks).
On the other hand, we rely on [`keras`](https://cran.r-project.org/web/packages/keras/index.html) for the design of the different deep learning models tested. `keras` is an `R` library which provides an interface to [Keras](https://keras.io), a high-level neural networks API which supports arbitrary network architectures and is seamlessly integrated with [TensorFlow](https://www.tensorflow.org/) (note that Keras and TensorFlow are the state of the art in deep learning tools).

The table below lists the documents (notebooks, scripts, etc.) contained in this respository along with the information of the corresponding published (or submitted) papers.
 
| notebook  | Article Title | Journal | DOI  	
|---|---|---|---
| 2019_deepDownscaling_GMD_CNN10 (.ipynb)                    2019_deepDownscaling_GMD_FULL (.pdf, .Rmd)| Configuration and Intercomparison of Deep Learning Neural Models for Statistical Downscaling | Geoscientific Model Development |
|  |  |  |

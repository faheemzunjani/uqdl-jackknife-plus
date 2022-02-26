# Uncertainty Quantification using Jackknife+

**Paper:** Predictive Inference with the Jackknife+  
**Authors:** Rina Foygel Barber and Emmanuel J. Candes and Aaditya Ramdas and Ryan J. Tibshirani

In this project, I have extended the code written by the original authors to experiment with automated ML driven deep models for regression tasks on a new dataset (Life Expectancy WHO). 

My new experiments with real data: 
* jackknife\_realdata_Faheem.ipynb (Jupyter notebook).
* The code uses the AWS AutoGluon AutoML library.

Simulations from original paper: 
* jackknife\_simulation.ipynb (Jupyter notebook), jackknife\_simulation.html (html version).
* The code has an option to include or exclude the full conformal prediction method. By default this is set to False as the full CP method takes an extremely long time to run. If set to True, the code then depends on the nonconformist library (https://github.com/donlnz/nonconformist).


Real data experiments from original paper: 
* jackknife\_realdata.ipynb (Jupyter notebook), jackknife\_realdata.html (html version).
* See code for instructions for how to download the data sets.
* Code needed for data preprocessing: get\_meps\_data.ipynb


See also the MAPIE package created by Vianney Taquet and Grégoire Martinon at Quantmetry. (https://mapie.readthedocs.io/en/latest/)

# Modeling the relationship between privacy and accuracy

The file `privacy-accuracy.ipynb` is a Jupyter notebook containing an analysis of how differential privacy affects accuracy in a hypothetical statistical study. Our analysis is based on an economic model from the paper [Differential Privacy: An Economic Method for Choosing Epsilon](https://doi.org/10.1109/CSF.2014.35) (2014) by Hsu et al. First we analyze how changes in the value of epsilon affect accuracy. Then we model a non-private version of the study. In both cases we assume that people want to be paid for participating in the study, and their participation fee varies in function of the privacy guarantees we offer: if we offer better privacy guarantees, we can pay them less. Assuming we have a fixed budget, with better privacy guarantees we can get more participants, and possibly higher accuracy.

If you have problems running the notebook, you can use the provided YAML file to recreate the same virtual environment we used:
```
conda env create -f environment.yml
```

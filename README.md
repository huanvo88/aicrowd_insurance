The jupyter notebook [grid_search.ipynb](grid_search.ipynb) is used in the aicrowd competition [insurance market simulation](https://www.aicrowd.com/challenges/insurance-pricing-game), where the goal is to build a loss cost model for an insurance company. 

There are several useful features in the notebook:

* Bayesian grid search the optimal parameters (using hyperopt) together with visualization of the distribution spaces

* Ensemble top performing models

* Combine frequency and severity (or log scaled severity) models

* Stack models with out-of-fold predictions based on time. 
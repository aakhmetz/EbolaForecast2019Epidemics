# EbolaForecast2019Epidemics

Supporting materials for Akhmetzhanov AR, Lee H, Jung SM, Kayano T, Yuan B, Nishiura H 2019 "Analyzing and forecasting the Ebola incidence in North Kivu, the Democratic Republic of the Congo from 2018-19 in real time" *Epidemics* [doi:10.1016/j.epidem.2019.05.002](https://doi.org/10.1016/j.epidem.2019.05.002)

-----

Code scripts are present by two notebooks:
* "[*A. Main analysis [python, MLE in pymc3, bash, latex].ipynb*](https://nbviewer.jupyter.org/github/aakhmetz/EbolaForecast2019Epidemics/blob/master/scripts/A.%20Main%20analysis%20%5Bpython%2C%20MLE%20in%20pymc3%2C%20bash%2C%20latex%5D.ipynb)" shows the main part of the analysis
* "[*B. Generating additional figures [python, bash, latex].ipynb*](https://nbviewer.jupyter.org/github/aakhmetz/EbolaForecast2019Epidemics/blob/master/scripts/B.%20Generating%20additional%20figures%20%5Bpython%2C%20bash%2C%20latex%5D.ipynb)" finalizes the analysis.

The folder **figures** shows all figures used in the paper, **results** is the list of all output files from executing the notebooks. **Data**-folder contains all aggregated datasets, where the file "data-WHO.xlsx" was mainly used for the analysis. The subfolder **data/Epicurves** shows the snapshots epicurves routingly extracted from different publicly available sources.

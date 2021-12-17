# Capstone-Climate-Mitigation
An analysis of farmer survey and farm census data from "Data on farmers’ adoption of climate change mitigation measures, individual characteristics, risk attitudes and social influences in a region of Switzerland" (https://doi.org/10.1016/j.dib.2020.105410).

This work was completed by Brooke Hawkins as part of the Master's in Data Science program at University of Michigan.

# What's the goal?
This analysis looks for covariates and predictors of farmers implementing climate mitigations on their farms.
* I fit an ordinary least squares (OLS) regressor to test six hypotheses
* I fit an explainable boosting machine (EBM) regressor to surface useful predictors
* I compared my findings to an external analysis by the dataset creators "The role of non-cognitive skills in farmers' adoption of climate change mitigation measures" (https://doi.org/10.1016/j.ecolecon.2021.107169)

# What did I find?
* I determined three significant covariates for farmers implementing mitigations.
  * Thinking measures effective
  * Being capable of implementing measures
  * Perceiving extreme weather changes
* I surfaced additional possible predictors of farmers implementing mitigations.
  * Social comparison as a motivator warrants future study in agriculture
  * Innovativeness warrants future study in agriculture
  *	Being capable of implementing measures warrants future study in psychology
*	I supported one key finding of an external analysis.
    *	Locus of control was an important covariate in my OLS model
    *	Locus of control and innovativeness were important features in my EBM model

# What's in this repo?
### Reports
* Visualizations of the raw data are in `01-dataset-visualizations.ipynb`.
* The OLS data preparation, assumption testing, and model fitting is in `02-OLS-regression.ipynb`.
* The EBM data preparation and model fitting is in `03-EBM-regression.ipynb`.
### References
* My detailed findings are in `Hawkins_Report.pdf`.
* The codebook, surveys, and lottery explanation were published with the original dataset.
### Data
* The cited dataset is in `data/raw`.
* Data I used to train an ordinarly least squares regressor and explainable boosting machine regressor are in `data/processed`.
### Figures
* Figures from the `Hawkins_Report.pdf` are saved here.

# How can I run this code?
The code is all in jupyter notebooks, which have already been run. Feel free to download them, restart the kernel, and experiment with the subsections on your own!

# What do I need to run this code?
Check out the `requirements.txt` file for code dependencies, and check out the watermarks at the end of each jupyter notebook to check for version information.

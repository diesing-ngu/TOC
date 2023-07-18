# MAREANO_TOC
R scripts for the spatial prediction of total organic carbon (TOC) in surface sediments based on MOSAIC (van der Voort et al., 2021) data.

### Main characteristics

Harmonised total organic carbon data from the MOSAIC database (https://biogeoscience.ethz.ch/research/data_collections/mosaic.html).

Variable pre-selection with Boruta algorithm (Kursa & Rudnicki, 2010) and de-correlation analysis.

Spatial predictions with Quantile Regression Forests (Meinshausen, 2006) including spatial 10-fold cross validation and model tuning (mtry and final variable selection with forward feature selection).

Estimation of the area of applicability of the model (Meyer & Pebesma, 2021).

### References

Kursa, M. B., & Rudnicki, W. R. (2010). Feature Selection with the Boruta Package. Journal of Statistical Software, 36(11), 1–13. https://doi.org/10.18637/jss.v036.i11

Meinshausen, N. (2006). Quantile Regression Forests. Journal of Machine Learning Research, 7(35), 983-999. http://jmlr.org/papers/v7/meinshausen06a.html

Meyer, H., & Pebesma, E. (2021). Predicting into unknown space? Estimating the area of applicability of spatial prediction models. Methods in Ecology and Evolution, 12(9), 1620–1633. https://doi.org/https://doi.org/10.1111/2041-210X.13650

van der Voort, T. S., Blattmann, T. M., Usman, M., Montluçon, D., Loeffler, T., Tavagna, M. L., Gruber, N., and Eglinton, T. I. (2021) MOSAIC (Modern Ocean Sediment Archive and Inventory of Carbon): a (radio)carbon-centric database for seafloor surficial sediments, Earth Syst. Sci. Data, 13, 2135–2146. https://doi.org/10.5194/essd-13-2135-2021

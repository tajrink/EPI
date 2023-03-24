# EPI

To create a pipeline for EDA firstly,we pulled EPI data from  postgres databases using `sqlalchemy`, and save it into a dataframe.Then,loaded 'corruption. csv' file into  pipeline as a dataframe via `pandas`.

## Visuals
Analyzed the relationship visually between one column in geographic `epi` dataframe (such as 'forestry','fisheries','agriculture','climate') and one column in the new dataframe.
Univariate analysis visuals by using histogram - distribution of the variables
Bivariate analysis visuals by using scatterplot- the relationships between corruption score & epi metrics


# JE_larvae

welcome to the repository for this project!
2 datasets are required for reproduction of the main analyses.
these are contained in JE_larvae/datasets

'stdset.csv' are the combined larval fish and copepod abundance data, standardised to density (individuals/m^3).
'set.csv' are the combined larval fish and copepod abundance data, untransformed. Larval fish abundance is recorded in individuals, copepod abundance is recorded in individuals/m^3. 

'stdset.csv' MUST be used for copula ordination and graphical modelling. 

'set.csv' is used for post-hoc modelling. Integer response data are appropriate for the models specified, although standardised data are not invalid for this approach. 

3 code files correspond to the 3 main analysis workflows.
these are contained in JE_larvae/code.
An additional code file is included to reproduce the map figure (Figure 2).


'copula_ordinations.Rmd' contains the code necessary to reproduce copula latent variable ordinations for both larval fish and copepod communities.
'g_c_g_m_.Rmd' contains the code necessary to reproduce two gaussian copula graphical models with combined data.
'envmodels.Rmd' contains the code necessary to reproduce the generalised linear models used to assess significance of copepod species density variables. 
'envmodels.Rmd' also contains the code necessary to perform type III ANOVA required to assess the contribution of each variable to the explanation of variance in the response.
'envmodels.Rmd' also contains the code necessary to produce partial effects plots.
'fishmap.Rmd' contains the code necessary to reproduce the map figure.
 

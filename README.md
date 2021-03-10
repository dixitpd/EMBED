# EMBED
Scripts used to infer a lower-dimensional description of microbiome abundance dynamics

The repository comprises scripts required to infer ecological normal modes from microbiome abundance time series data. As input, the method requires an OTU table (N days, O bacteria) and K (the number of components used to model the time series). We first infer latents Z and loadings Theta from the OTU table and then perform a rotation Z -> Y and Theta -> Phi that obtains the ecological normal modes Y(t). 

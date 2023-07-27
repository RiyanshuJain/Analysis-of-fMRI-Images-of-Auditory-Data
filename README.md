# **Analysis-of-Auditory-fMRI-Images**
Pre-processing fMRI time-series data to analyze structural and functional brain networks to finally perform Graph Theoritical Analysis.
> Dataset Link -- [Raw functional and structural data](https://www.fil.ion.ucl.ac.uk/spm/data/auditory/)

### Steps considered in Pre-processing using MATLAB :
1. Motion Correction & Realignment
2. Coregistration
3. Deformation
4. Spatial Normalization
5. Smoothening

Then we used AAL, MarsBaR to identify top 5 ROIs among 116 ROIs from left and right hemisphere of brain. At the end to perform Graph theoritic analysis, 
we find the Functional Connectivity network using Pearson’s Correlation Coefficient, 
clustering coefficient of each node, 
transitivity of the binary network 
and characteristic path length of the binary network.

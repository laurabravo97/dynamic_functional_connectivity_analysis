# Dynamic Functional Connectivity Analysis of resting-state fMRI data

Jupyter Notebook (Python) script to obtain dynamic functional connectivity metrics, after using a sliding window approach and plots using plotly (code available, but interactive plots don't displayed on github). 


Indices obtained: 

a) average of the Pearson's z-transformed correlation coefficient between two seeds (anterior and posterior rTPJ) across the set of sliding windows.
b) variability of these connectivity values (SD) across windows. 


Five connectivity states were obatined: high negative, moderate negative, low-uncorrelated, moderate positive, high positive.
Indices to classify these different states of brain connectivity (i.e. connectivity patterns) were obtained:  

a) proportion of windows in each state
b) Mean Dwell Time (MDT) in each state
c) Probability of Transition (PT) from other states to each specific one. 



Data obtained from Autism Brain Imaging Data Exchange repository (ABIDE; http://fcon_1000.projects.nitrc.org/indi/abide/) [Di Martino et al., 2017; Di Martino et al., 2014]; ABIDE II  Barrow Neurological Institute repository (http://fcon_1000.projects.nitrc.org/indi/abide/abide_II.html)

Di Martino, A., Yan, C.G., Li, Q., Denio, E., Castellanos, F.X., Alaerts, K., et al. (2014). The autism brain imaging data exchange: Towards a large-scale evaluation of the intrinsic brain architecture in autism. Molecular Psychiatry, 19, 659– 667. https://doi.org/10.1038/mp.2013.78

Di Martino, O’Connor, D., Chen, B. et al. (2017). Enhancing studies of the connectome in autism using the autism brain imaging data exchange II. Scientific Data, 4, 170010. https://doi.org/10.1038/sdata.2017.10 

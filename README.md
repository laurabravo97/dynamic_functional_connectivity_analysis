# Dynamic Functional Connectivity Analysis of resting-state fMRI data

If using this script please cite: 

Bravo Balsa, L., Abu-Akel, A., & Mevorach, C. (2024). Dynamic functional connectivity in the right temporoparietal junction captures variations in male autistic trait expression. Autism research: official journal of the International Society for Autism Research, 17(4), 702–715. https://doi.org/10.1002/aur.3117



Jupyter Notebook (Python) script to obtain dynamic functional connectivity metrics after conducting a sliding window approach, and interactive plots using plotly. 

Five connectivity states were obatined: high negative, moderate negative, low-uncorrelated, moderate positive, high positive.
Three connectivity state indices were obtained:  

a) proportion of windows in each state
b) Mean Dwell Time (MDT) in each state
c) Probability of Transition (PT) from other states to each specific one. 

Data obtained from Autism Brain Imaging Data Exchange repository (ABIDE; http://fcon_1000.projects.nitrc.org/indi/abide/) [Di Martino et al., 2017; Di Martino et al., 2014]; ABIDE II  Barrow Neurological Institute repository (http://fcon_1000.projects.nitrc.org/indi/abide/abide_II.html)

Di Martino, A., Yan, C.G., Li, Q., Denio, E., Castellanos, F.X., Alaerts, K., et al. (2014). The autism brain imaging data exchange: Towards a large-scale evaluation of the intrinsic brain architecture in autism. Molecular Psychiatry, 19, 659– 667. https://doi.org/10.1038/mp.2013.78

Di Martino, O’Connor, D., Chen, B. et al. (2017). Enhancing studies of the connectome in autism using the autism brain imaging data exchange II. Scientific Data, 4, 170010. https://doi.org/10.1038/sdata.2017.10 

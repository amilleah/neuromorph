## NeuroMorph: A High-Temporal Resolution MEG Dataset for Morpheme-Based Linguistic Analysis

**Authors:** Amilleah Rodriguez, Dan Zhao, Kyra Wilson, Ritika Saboo, Sergey V Samsonau, Alec Marantz

**TL;DR:** We present NeuroMorph: neural data of 24 high-resolution MEG recordings capturing real-time processing of multi-morphemic words with over 17 hours of data from a lexical decision task, which can help improve cognitive modeling and NLP.

**Keywords:** natural language processing, morphemes, cognitive science, linguistics, magnetoencephalography, MEG

You can find the dataset on [OpenNeuro](https://openneuro.org/datasets/ds005241)

---

### Download the dataset

You can download the dataset from OpenNeuro using datalad: 

`pip install datalad`
`datalad install https://github.com/OpenNeuroDatasets/ds005241.git`
`datalad get .`

### What's included in the github

The repository includes a few Jupyter notebooks to help you preprocess and analyze the data for both the lexical decision task and the functional localizer. It also includes ML modelling code for two classification tasks. 

### Dataset details (n = 24)

KIT/Yokogawa MEG system with 208 magnetometer channels
24 recordings amounting to over 17 hours of data
stored in MEG-BIDS format (version 1.7.0)
the dataset is published on OpenNeuro

### And some resources for getting started

https://mne.tools/stable/documentation/cookbook.html
https://mne.tools/stable/documentation/glossary.html

### References

Appelhoff, S., Sanderson, M., Brooks, T., Vliet, M., Quentin, R., Holdgraf, C., Chaumon, M., Mikulan, E., Tavabi, K., Höchenberger, R., Welke, D., Brunner, C., Rockhill, A., Larson, E., Gramfort, A. and Jas, M. (2019). MNE-BIDS: Organizing electrophysiological data into the BIDS format and facilitating their analysis. Journal of Open Source Software 4: (1896).https://doi.org/10.21105/joss.01896

Niso, G., Gorgolewski, K. J., Bock, E., Brooks, T. L., Flandin, G., Gramfort, A., Henson, R. N., Jas, M., Litvak, V., Moreau, J., Oostenveld, R., Schoffelen, J., Tadel, F., Wexler, J., Baillet, S. (2018). MEG-BIDS, the brain imaging data structure extended to magnetoencephalography. Scientific Data, 5, 180110.https://doi.org/10.1038/sdata.2018.110

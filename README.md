## NeuroMorph: A High-Temporal Resolution MEG Dataset for Morpheme-Based Linguistic Analysis

**Authors:** Amilleah Rodriguez, Dan Zhao, Kyra Wilson, Ritika Saboo, Sergey V Samsonau, Alec Marantz

**TL;DR:** We present NeuroMorph: neural data of 24 high-resolution MEG recordings capturing real-time processing of multi-morphemic words with over 17 hours of data from a lexical decision task, which can help improve cognitive modeling and NLP.

**Keywords:** natural language processing, morphemes, cognitive science, linguistics, magnetoencephalography, MEG

you can find the paper [here](https://openreview.net/attachment?id=i6gd9PUq9I&name=pdf))
you can find the dataset [here](https://openneuro.org/datasets/ds005241)

---

### what's included in the github

The repository includes a few Jupyter notebooks to help you preprocess and analyze the data for both the lexical decision task and the functional localizer:

```
neuromorph/
  -Tark Analysis Clean.ipynb
  -neuromorph_preprocessing.ipynb
  -neuromorph_plotting.ipynb
  -requirements.txt
  -README.md
```

### dataset details (n = 24)

We use MEG-BIDS format (version 1.7.0) to structure and publish the dataset on OpenNeuro:

```
|neuromorph/
|--- README
|--- dataset_description.json
|--- participants.json
|--- participants.tsv
|--- sub-A0394/
|------ ses-01/
|--------- sub-A0394_ses-01_scans.tsv
|--------- meg/
|------------ sub-A0394_ses-01_coordsystem.json
|------------ sub-A0394_ses-01_task-lexicaldecision_channels.tsv
|------------ sub-A0394_ses-01_task-lexicaldecision_events.json
|------------ sub-A0394_ses-01_task-lexicaldecision_events.tsv
|------------ sub-A0394_ses-01_task-lexicaldecision_meg.json
|------------ sub-A0394_ses-01_task-lexicaldecision_split-01_meg.fif
|------------ sub-A0394_ses-01_task-lexicaldecision_split-02_meg.fif
|------ ses-02/
|--------- sub-A0394_ses-02_scans.tsv
|--------- meg/
|------------ sub-A0394_ses-02_coordsystem.json
|------------ sub-A0394_ses-02_task-lexicaldecision_channels.tsv
|------------ sub-A0394_ses-02_task-lexicaldecision_events.json
|------------ sub-A0394_ses-02_task-lexicaldecision_events.tsv
|------------ sub-A0394_ses-02_task-lexicaldecision_meg.json
|------------ sub-A0394_ses-02_task-lexicaldecision_split-01_meg.fif
|------------ sub-A0394_ses-02_task-lexicaldecision_split-02_meg.fif
|------ ses-tark/
|--------- sub-A0394_ses-tark_scans.tsv
|--------- meg/
|------------ sub-A0394_ses-tark_coordsystem.json
|------------ sub-A0394_ses-tark_task-localizer_channels.tsv
|------------ sub-A0394_ses-tark_task-localizer_events.json
|------------ sub-A0394_ses-tark_task-localizer_events.tsv
|------------ sub-A0394_ses-tark_task-localizer_meg.fif
|------------ sub-A0394_ses-tark_task-localizer_meg.json
```

### and some resources for getting started

https://mne.tools/stable/documentation/cookbook.html
https://mne.tools/stable/documentation/glossary.html

### References

Appelhoff, S., Sanderson, M., Brooks, T., Vliet, M., Quentin, R., Holdgraf, C., Chaumon, M., Mikulan, E., Tavabi, K., Höchenberger, R., Welke, D., Brunner, C., Rockhill, A., Larson, E., Gramfort, A. and Jas, M. (2019). MNE-BIDS: Organizing electrophysiological data into the BIDS format and facilitating their analysis. Journal of Open Source Software 4: (1896).https://doi.org/10.21105/joss.01896

Niso, G., Gorgolewski, K. J., Bock, E., Brooks, T. L., Flandin, G., Gramfort, A., Henson, R. N., Jas, M., Litvak, V., Moreau, J., Oostenveld, R., Schoffelen, J., Tadel, F., Wexler, J., Baillet, S. (2018). MEG-BIDS, the brain imaging data structure extended to magnetoencephalography. Scientific Data, 5, 180110.https://doi.org/10.1038/sdata.2018.110

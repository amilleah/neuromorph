## NeuroMorph: A High-Temporal Resolution MEG Dataset for Morpheme-Based Linguistic Analysis

**TL;DR:** We present NeuroMorph: neural data of 24 high-resolution MEG recordings capturing real-time processing of multi-morphemic words with over 17 hours of data from a lexical decision task, which can help improve cognitive modeling and NLP.

**Keywords:** natural language processing, morphemes, cognitive science, linguistics, magnetoencephalography, MEG

you can find the paper [here](https://openreview.net/attachment?id=i6gd9PUq9I&name=pdf))

---

### dataset links

you can find the dataset [here](https://openneuro.org/datasets/ds005241)

### what's included in the dataset (n = 24)
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

### what's included in the github repo
```
neuromorph/
  -Tark Analysis Clean.ipynb
  -neuromorph_preprocessing.ipynb
  -neuromorph_plotting.ipynb
  -requirements.txt
  -README.md
```
### some resources for getting started

https://mne.tools/stable/documentation/cookbook.html
https://mne.tools/stable/documentation/glossary.html





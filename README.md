## NeuroMorph: A High-Temporal Resolution MEG Dataset for Morpheme-Based Linguistic Analysis

**TL;DR:** We present NeuroMorph: neural data of 24 high-resolution MEG recordings capturing real-time processing of multi-morphemic words with over 17 hours of data from a lexical decision task, which can help improve cognitive modeling and NLP.

**Keywords:** natural language processing, morphemes, cognitive science, linguistics, magnetoencephalography, MEG

[paper here](link here soon)

---

### dataset links

you can find the dataset [here](link here soon)

### what's included in the dataset (n = 24)
```
neuromorph/
  logs/
    - subj_block1_lexical-decision.csv
    - subj_block2_lexical-decision.csv
  anat/
    subj/
    - block1_lexical-decision_before.mkr
    - block1_lexical-decision_after.mkr
    - block2_lexical-decision_before.mkr
    - block2_lexical-decision_after.mkr
    - localizer_before.mkr
    - localizer_after.mkr
    - headshape.txt
    - points.txt
  meg/
    subj/
      - block1_lexical-decision.con
      - block2_lexical-decision.con
      - localizer.con
      - lexical-decision_noise-reduced.fif
```

### what's included in the github repo
```
neuromorph/
  -Tark Analysis Clean.ipynb
  -neuromorph_analysis.ipynb
  -neuromorph_preprocessing.ipynb
  -neuromorph_stc_plotting.ipynb
  -mne.yml
  -eelbrain.yml
  -README.md
```
### some resources for getting started

https://mne.tools/stable/documentation/cookbook.html
https://mne.tools/stable/documentation/glossary.html





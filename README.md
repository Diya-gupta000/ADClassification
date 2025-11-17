# ADClassification
Uses ADReSS IS2020 dataset to conduct a binary classification based off a combination of linguistic and acoustic features.
1. Prepare metadata and segment structure.
2. Extract acoustic features (openSMILE + MRCG).
3. (Optionally) add linguistic features from CLAN.
4. Merge everything at subject level.
5. Train simple baseline models (classification & MMSE regression).

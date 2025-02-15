# TSFSM
The architecture works on three dataset,
MHEALTH, UCIHAR and KUHAR having their respective folders

MHEATLH:-
mhealth-resampled-preprocess : image generation using GAF
mhealth_classified_dataset: split images into train-test
mhealth-img112-irnv2: feature extraction using Inception ResNet
mhealth-img112-env2b1: feature extraction using EfficientNet
mhealth-img112-ex: feature extraction using Xception
mhealth-merged: merge features and selection using chi-square
h-b-feat-select-mhealth: feature selection using BHBA 
feature-importance-mhealth: finding feature importance

KUHAR:-
ku-har-preprocessing:image generation using GAF
Kuhar_classified_dataset: split images into train-test
kuhar-img84-irnv2: feature extraction using Inception ResNet
kuhar-img84-env2b1: feature extraction using EfficientNet
kuhar-img84-ex: feature extraction using Xception
kuhar-merge-ex-feat: merge features 
feat-ex-kuhar-1500: selection features using chi-square
h-b-feat-select-kuhar: feature selection using BHBA 
feature-importance-kuhar: finding feature importance

UCIHAR:-
inertial-signal_img90_traingenerate :training image generation using GAF
inertial-signal_img90_testgenerate :testing image generation using GAF
classified-ucihar-dataset-create: split images into train-test
transferlearn-irnv2-img90: feature extraction using Inception ResNet
transferlearn-env2b1-img90: feature extraction using EfficientNet
transferlearn-ex-img90: feature extraction using Xception
img90-merging-features: merge features 
uchi-chi-featselect: selection features using chi-square
h-b-feat-select-ucihar: feature selection using BHBA 
feature-importance-ucihar: finding feature importance

# Semi-Supervised Learning for Affect Modelling
This repository contatins the code for my Final Year Project at the University of Malta. Along with this code, another folder needs to be downloaded from this link: https://drive.google.com/file/d/1mAxzgdWGEPWBaS3eeRtYH_5TA2SCXAxY/view?usp=sharing (this is uploaded elsewhere due to the github limitation with files over 100mb). This folder should be extracted and placed in the same root folder as all the other files and folders.

## Results naming convention
Each piece of data is labelled to refer to the test it was taken from. The naming convention for these will be described below for both RECOLA and AGAIN, as they slightly differ. 

RECOLA: For supervised models, the data uses a "Feature_Label" format, and for semi-supervised model the data uses a "Feature\_Label\_BaseEst\_NumOfLabelled" format. So "AudioArousal" is a model that uses audio as a feature and arousal as a label, and "AudioArousalBLR4" is a model that uses audio as a feature, arousal as a label, binary logistic regression as a base estimator and four labelled groups.

AGAIN: For supervised models, the data uses "GameName", and for semi-supervised model, the data uses a "GameName_BaseEst_NumOfLabelled" format. So "TopDown" is a model trained using the TopDown dataset, and "TopDownBLR4" is a model trained using the TopDown dataset, uses binary logistic regression as a base estimator and four labelled groups.

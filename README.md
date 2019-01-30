# TUM_Thesis
## Abstract
Abstract
Real-time detection and classification of dynamic hand gestures in video data is a challenging
task since (i) there is no indication when a gesture starts and ends in the video,
(ii) performed gestures should only be recognized once, and (iii) the entire architecture
should be designed considering the memory and power budget. In this work, we
address these challenges by proposing a hierarchical structure enabling online-working
convolutional neural network (CNN) architectures to operate efficiently in real-time by
using sliding window approach. The proposed architecture consists of two models: (1)
Detector which is a lightweight CNN architecture for detecting gestures and (2) Classi
fier which is a deep CNN for classifying the detected gestures. In order to evaluate
the single-time activations of the detected gestures, we propose to use the Levenshtein
metric. We evaluate our architecture on two publicly available datasets - EgoGesture
and NVIDIA Dynamic Hand Gesture Datasets (nvGesture) - which require temporal
detection and classification of the performed hand gestures. ResNeXt-101 model which
is used as classifier achieves the state-of-the-art online classification accuracy of 94.04%
on EgoGesture dataset and 83.82% on the nvGesture dataset. In online detection and
classification, we achive 91.04% and 77.39% accuracy on the Levenshtein metric in the
EgoGesture and nvGesture, respectively. Additionally, the proposed architecture can
detect gestures even before it actually ends since each gestures discriminative information
is contained in its middle.

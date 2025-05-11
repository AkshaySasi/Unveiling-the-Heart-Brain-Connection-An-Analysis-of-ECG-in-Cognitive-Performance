# Unveiling-the-Heart-Brain-Connection-An-Analysis-of-ECG-in-Cognitive-Performance
MTech Thesis Project

**Abstract**

Dynamic heart-brain-neural system interaction, or heart-brain connection, has a significant
contribution to cognitive function but little-known application for non-invasive cognitive load
monitoring. This thesis, ”Unveiling the Heart Brain Connection: An Analysis of ECG in Cog-
nitive Performance”, examines the application of ECG-derived Heart Rate Variability (HRV)
and time-series features, with Electroencephalogram (EEG) signals, in working memory task
cognitive load prediction. Using the OpenNeuro dataset (ds003838) with multimodal physi-
ological recordings of 86 subjects completing an auditory Digit Span Task, the work makes
use of a robust machine learning pipeline for classifying cognitive load levels (Just Listen,
Five-digit, Nine-digit, Thirteen-digit). ECG signals were subjected to extracting HRV measures
(e.g., SDNN, RMSSD) and Catch22 time-series features, while EEG signals were preprocessing
to record neural activity in theta, alpha, and beta bands. Classic machine learning algorithms
(Random Forest, SVM, XGBoost) and deep learning models (1D-CNN, BiLSTM, Transformer)
were trained on both modalities with outstanding performance in the Memory Classifier task,
with Catch22 features providing 98.68% accuracy in ECG and 99.82% in EEG using XGBoost.
A new transfer learning-based fusion classifier, combining ECG and EEG features, showed
bidirectional heart-brain functional coupling, with ECG-trained/EEG-tested models reaching
99.62% accuracy. These results confirm Catch22’s high discriminative ability compared to con-
ventional HRV features and confirm ECG as a sensible substitute for EEG in the estimation of
cognitive load. Through the delivery of a scalable model for real-time cognitive monitoring,
this work advances the discipline of neuroergonomics and introduces the possibility of adap-
tive systems within educational, clinical, and operational settings, with potential integration
into wearable technology for personalizable assessment of mental state.
Keywords: Electrocardiogram (ECG), Electroencephalogram (EEG), Heart Rate Variability (HRV),
Catch22, Feature Extraction, Cognitive Performance, Working Memory, Machine Learning, Deep
Learning, Transfer Learning, Classification, Cognitive load prediction.


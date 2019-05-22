## (Toy examples) Deep Learning and Big Data for Healthcare: A Double Review for Critical Beginners 
Paper in press.

### Description
Some toy examples have been developed to help the beginners to start with some introductory
available  code  and  by  considering  one  of  the  world’s  most  popular  biomedical  database, the Multiparameter Intelligent Monitoring in Intensive Care (MIMIC) database, which is freely available. Some results were obtained by selecting 1546 files for training, 1328 for validation and 525 for test, from the MIMIC dataset. Each file with a length of 250 samples. Examples are implemented in PyTorch. A DL architecture, which is based in the U-Net network has been designed:  (1) To predict the arterial blood pressure signal by using the plethysmogram signal (PLETH to ABP example) as input; And (2) to predict the plethysmogram signal (ABP to PLETH example) by using the arterial blood pressure signal as input, that is, the reverse problem. The architecture is a 1-dimension CNN, called fully convolutional network, with a deeply-supervised encoder-decoder which are connected through a series of skip pathways, and in which the input and the output have the same size. In particular, the network learns how to transform a 1-dimension time signal with a size of 250 samples into another signal with the same size (arterial blood pressure signal to plethysmogram signal or vice versa). For that, it uses convolution kernels of size 3 with stride and padding of size 1, batch normalization, and regularization through dropout.

### Dataset
https://www.kaggle.com/lbote87/mimic-pleth-to-abp

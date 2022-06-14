# DL_Basics-CIFAR10
### Term project on Deep Learning Basics course, Department of AI, Kyungpook National University

Image Classification is still one of the important supervised learning based
task in Computer Vision (CV) domain. CIFAR 10 has been benchmark dataset for
research community to compare their proposed methods with other current
techniques for image classifi cation task. Since the main aim of this term project is to
apply different modern CV recipes to get higher validation accuracy on CIFAR 10
dataset, we compare various baseline models by utilizing modern data augmentation
methods, miscellaneous learning rat e schedulers and carefully designed CNN layers
after the baseline model. We used ResNet50 as an baseline m odel, which achieved
state of the art (SOTA) accuracy on several datasets. This network architecture can
be a baseline model for newer architectures and is used as a backbone feature
extractor for other downstream tasks such as image segmentation and object
detection. By initializing model weights trained on ImageNet dataset and
implementing modern training recipes we have achieved **98.99 %** accuracy on the
validation set.

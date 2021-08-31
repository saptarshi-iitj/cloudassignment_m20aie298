# VGG16 based Image classifier

We have trained a VGG 16 pre-trained model on Pascal VOC 2012 dataset. The initial VGG16 model is set to classify 1000 labels, however the Pascal VOC dataset has only 20 classes namely
`person, bottle, aeroplane, bird, boat, dog, pottedplant, cat, sofa, bicycle, chair, car, train, cow, horse, tvmonitor, diningtable, bus, sheep, motorbike`

We have inported the VGG 16 model, removed the last prediction layer and replavced it by another prediction layer for predicting 20 classes. Additionally we have trained the model for the new last layer only, ant it resulted in about 71% accuracy on validation dataset.

Once the model has trained, we downloaded the weights file and 



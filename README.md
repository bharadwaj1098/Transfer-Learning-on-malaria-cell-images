# Transfer-Learning-on-malaria-cell-images
Arrabelly, Sai Bharadwaj Reddy &amp; Juliet, Sujitha. (2019). Transfer Learning with ResNet-50 for Malaria Cell-Image Classification. 0945-0949. 10.1109/ICCSP.2019.8697909. 

The dataset contains of 27,558 images of infected and uninfected cells. This data first appeared along with the publication of Rajaraman et al., (Rajaraman S, Antani SK, Poostchi M, Silamut K, Hossain MA, Maude RJ, Jaeger S, Thoma GR.2018. Pre-trained Convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood amear images).

The Dataset is available on the official website of National Library of Medicine (NLM).

 Pre-Trained Weights for the ResNet50 model is be imported. The input data will be trained with the pre-trained weights and the only layer which is learning with back propagation is the dense layer

https://keras.io/api/applications/
 is the link to download the  pre-trained weights
 
 Change the path of the data and pre-trained weights in the code while implementing 

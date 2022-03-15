# Melanoma-Diagnosis-Using-Lesion-Segmentation
Melanoma Diagnosis Using Lesion Segmentation on ISIC 2017 challenge dataset. The lesions were segmented using a Unet model.
Instead of producing the output as a sever upsampling out of the last feature map, it designs a decoder that doubles the feature map size until it reaches the image size.
Also it introduces the skip connection technique to combine the encoder and decoder learned features to produce finer segmentation masks.


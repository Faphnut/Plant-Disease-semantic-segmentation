# Low-Level Feature Representation in the RCSU-Net Model Using Channel-Spatial Attention Blocks for Semantic Segmentation of Plant Leaves

Abstract— 	Smart agriculture leverages advanced technologies such as the Internet of Things (IoT), deep learning, and computer vision to address challenges in pest and disease detection.Semantic image segmentation has emerged as a vital tool for monitoring plant health, enabling the detection of subtle anomalies and patterns through visual data analysis. Deep encoder-decoder architectures, such as U-Net, have shown significant potential in this domain. However, challenges in the encoding phase, including the loss of low-level features, incomplete texture analysis, and weak edge detection, often limit segmentation accuracy.To overcome these limitations, this study introduces an enhanced U-Net model that integrates ResNet-50 as the encoder and incorporates a channel-spatial attention block in the decoding phase.This attention block first compresses channel features and subsequently amplifies spatial features across different regions, improving the preservation and recovery of low-level features.This enhancement enables more precise and distinguishable segmentation of diseased regions in plant leaves. Experimental results highlight the effectiveness of the proposed approach, achieving an Intersection over Union (IoU) of 93.35% and a Dice coefficient of 0.9645% in plant disease segmentation tasks.These advancements demonstrate significant potential for real-world applications, facilitating accurate disease detection and efficient crop management in smart agriculture
Initially appeared on


## Getting Started

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. See deployment
for notes on deploying the project on a live system.



### Installing



this Library have many segmentation model with different Encoder that is Necessary for the Project

    !pip install -q -U segmentation-models-pytorch albumentations > /dev/null

for Loading the Built dataset fist:
    !pip install gdown
and then use this code to load the built dataset
    !gdown --id 1qoadjw0j-_ZMDOJ-OvC7gL9jFDooGDCA
    
there are many other librarys Needex on this code but this two are necessary 

## Running the tests

here is the out put of the byilt model compare to ther implemented models:
![image](https://github.com/user-attachments/assets/f3dc97e8-fb04-4703-900c-3a12f90a26b5)

Additionally, as illustrated in Fig. 3, the performance of various models, including the proposed approach, was evaluated on three samples of disease-affected plant leaves. In the figure, the segmented regions are highlighted with boxes. The results demonstrate that the proposed method, leveraging edge detection, effectively enhances the separation between affected and healthy areas. This improvement is particularly evident in complex images, indicating that the model performs well in identifying and segmenting disease-affected regions.




## Deployment

this project has built in google collab Environment



## License

This project is licensed under the [Apache 2.0](LICENSE.md)



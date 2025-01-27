# Enhanced Aerial Image Segmentation via Hybrid Swin-UNet with Dilated Convolutions and Multi-Scale Fusion
## 
## Dataset - https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery

### Abstract - Rapid urbanization and climate change have significantly altered urban landscapes and the environment, necessitating methods to quantify their impact. Aerial imaging, combined with computer vision techniques, can provide insights into environmental changes, guiding urban planning and disaster management. Recent advancements in deep learning have demonstrated the superiority of segmentation models over traditional methods, particularly for complex scenes such as aerial images. This work proposes a hybrid UNet model that replaces the standard convolutional backbone with Swin Transformer blocks. This enhancement captures global contextual details through self-attention mechanisms, while maintaining the strong localization capabilities of UNet for precise segmentation. Dilated convolutions in the decoder capture fine-grained spatial details, and a multi-scale fusion mechanism effectively integrates features at multiple resolutions. The proposed model is evaluated on satellite images from the Mohammed Bin Rashid Space Center in Dubai, achieving an overall accuracy of 86.21% and 85.52%, and a mean Intersection over Union of 70.39% and 69.28% for the validation and test sets, respectively. These results demonstrate the superiority of the proposed architecture over classical models such as UNet, DeepLab-v3+, and SegNet.

## Architecture -
![image](https://github.com/user-attachments/assets/d3877958-3b4f-4dfd-a7f4-893e28d3db1a)

![image](https://github.com/user-attachments/assets/e6ce173f-0bfa-4b4d-90b4-05846ad5dd76)

## Results - 

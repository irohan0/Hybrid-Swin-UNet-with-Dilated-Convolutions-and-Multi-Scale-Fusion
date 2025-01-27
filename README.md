# Enhanced Aerial Image Segmentation via Hybrid Swin-UNet with Dilated Convolutions and Multi-Scale Fusion
## Additional codes and results (for unet, deeplabv3 and segnet) - https://drive.google.com/drive/folders/1oXdh8Nfwb-MlcWuvEvHXHIFszRiIw0KR?usp=sharing
## Dataset - https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery

### Abstract - Rapid urbanization and climate change have significantly altered urban landscapes and the environment, necessitating methods to quantify their impact. Aerial imaging, combined with computer vision techniques, can provide insights into environmental changes, guiding urban planning and disaster management. Recent advancements in deep learning have demonstrated the superiority of segmentation models over traditional methods, particularly for complex scenes such as aerial images. This work proposes a hybrid UNet model that replaces the standard convolutional backbone with Swin Transformer blocks. This enhancement captures global contextual details through self-attention mechanisms, while maintaining the strong localization capabilities of UNet for precise segmentation. Dilated convolutions in the decoder capture fine-grained spatial details, and a multi-scale fusion mechanism effectively integrates features at multiple resolutions. The proposed model is evaluated on satellite images from the Mohammed Bin Rashid Space Center in Dubai, achieving an overall accuracy of 86.21% and 85.52%, and a mean Intersection over Union of 70.39% and 69.28% for the validation and test sets, respectively. These results demonstrate the superiority of the proposed architecture over classical models such as UNet, DeepLab-v3+, and SegNet.

## Architecture -
![image](https://github.com/user-attachments/assets/1f96b024-f738-4154-82ac-f74959cc5c7a)

![image](https://github.com/user-attachments/assets/4a72323c-b505-498b-8b84-6e50f442e80d)

![image](https://github.com/user-attachments/assets/ae559ca4-ee01-4432-9a08-6e32709c7c56)

## Results - 
![image](https://github.com/user-attachments/assets/8c716311-c7d0-46bf-a4b8-c9d0ca707fb5)


![image](https://github.com/user-attachments/assets/a80afab9-70d7-4c81-85ad-ce81385adb43)

![image](https://github.com/user-attachments/assets/f41f6ed5-d856-40de-8f4f-e9a5c5404c59)

![image](https://github.com/user-attachments/assets/35b01d3e-4488-40ea-bde4-15cd58a5c401)

## Predictions - 

![image](https://github.com/user-attachments/assets/9fb9ee63-c39b-4173-ae69-ccce8148847a)


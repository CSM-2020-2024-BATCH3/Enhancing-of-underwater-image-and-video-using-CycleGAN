# Enhancing of Underwater Image and Video using CycleGAN

## Introduction
The task focuses on improving the quality of recorded images and videos taken underwater through the application of deep learning, specifically CycleGAN. Underwater environments pose challenges such as light reduction, color distortion, and loss of visibility, which degrade the quality of media captured underwater. CycleGAN, known for its effectiveness in image-to-image translations, is expected to enhance underwater media by learning the mapping between original underwater images/videos and their enhanced versions.

## Methodology
1. **Data Collection**: Gather a large dataset of paired underwater images and their corresponding enhanced versions. Enhanced versions can be obtained through existing enhancement algorithms or manual enhancement.
2. **Model Architecture**: Employ CycleGAN, consisting of generator and discriminator networks. The generator transforms input underwater media into enhanced versions, while the discriminator distinguishes between generated and real enhanced media.
3. **Training**: Optimize both networks in parallel to improve the quality of generated enhancements.
4. **Application**: Apply the trained CycleGAN model to new underwater images and videos to generate their enhanced versions.
5. **Post-processing**: Further enhance the generated media using post-processing techniques to achieve desired quality.

## Expected Outcomes
The proposed work aims to significantly enhance underwater images and videos, benefiting applications such as underwater exploration, surveillance, marine biology, and filmmaking. By leveraging CycleGAN, the project seeks to produce visually improved media for various underwater-related tasks.

## Implementation Details
- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow or PyTorch
- **Dataset**: Obtain underwater image and video datasets, ensuring proper pairing of originals and enhanced versions.
- **Model Training**: Train the CycleGAN model on the collected dataset, optimizing both the generator and discriminator networks.
- **Evaluation**: Evaluate the quality of generated enhancements through quantitative metrics and visual inspection.
- **Deployment**: Deploy the trained model for real-world applications, providing enhanced underwater media for diverse use cases.
## Dataset Details
- **Download link for Dataset** :  https://drive.google.com/drive/folders/1ZEql33CajGfHHzPe1vFxUFCMcP0YbZb3

## Conclusion
Enhancing underwater images and videos using CycleGAN offers a promising approach to overcome challenges associated with underwater visibility. The proposed methodology, coupled with deep learning techniques, aims to produce high-quality enhancements suitable for various underwater applications.


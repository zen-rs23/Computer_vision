# Transfer Learning for Food101 Image Classification

## Overview

This project explores the application of transfer learning using pre-trained deep learning models on the Food101 dataset. We evaluated the performance of GoogLeNet and MobileNetV3_small architectures, focusing on their adaptability and effectiveness in classifying diverse food images. The project emphasizes the utility of transfer learning in enhancing model performance with limited data.

## Data Understanding and Preparation

The Food101 dataset contains 101,000 images across 101 food categories. Key data preparation steps included:
- Resizing images to 224x224 pixels to fit model requirements.
- Applying data augmentation techniques like random cropping, horizontal flipping, and rotation to enhance model generalization.

## Methodology

We utilized pre-trained models GoogLeNet and MobileNetV3_small:
- **GoogLeNet:** Known for its inception modules, this model was fine-tuned to classify food categories, achieving a baseline test accuracy.
- **MobileNetV3_small:** A lightweight model optimized for mobile applications, fine-tuned to improve accuracy and reduce overfitting.

Both models were fine-tuned using the Adam optimizer, with careful adjustments to hyperparameters for optimal learning.

## Results

- **GoogLeNet:** Achieved a test accuracy of 26.34% after initial training.
- **MobileNetV3_small:** Improved significantly through fine-tuning, reaching a final test accuracy of 60.16% and a test loss of 1.4927.

## Key Learnings and Contributions

The project demonstrated the power of transfer learning in leveraging pre-trained features for new tasks, especially with models like MobileNetV3_small that are efficient and adaptable. Our approach highlighted the importance of fine-tuning pre-trained models and the impact of data augmentation on model performance.

## Future Work

Future enhancements could involve exploring more efficient neural network architectures and expanding access to high-performance GPUs to accelerate training processes. Further research into optimizing model architectures and training techniques will continue to be a focus.

## Conclusion

This project underscores the effectiveness of transfer learning in specialized tasks like food image classification. The fine-tuning process notably improved MobileNetV3_small's performance, making it a strong candidate for real-world applications requiring efficient and accurate image recognition.

## Contact

For inquiries, please contact [Rohit Sharma](https://www.linkedin.com/in/rohit-sharma-2459096002/).

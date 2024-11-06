# Bone Fracture Detection using CNN Architectures

## Project Overview
This project explores the use of deep learning models for bone fracture detection in X-ray images. We compare the performance of advanced architectures—InceptionV3, ResNet50, VGG16—and a custom CNN, assessing their ability to capture intricate patterns in medical images.

## Models Used
1. **InceptionV3**  
   - **Accuracy:** 92%
   - **Inference:** Best performer with multi-scale feature capture, making it highly effective for complex image classification.

2. **ResNet50**  
   - **Accuracy:** 89%
   - **Inference:** Residual connections helped maintain high accuracy in deeper layers, ideal for intricate patterns in X-rays.

3. **VGG16**  
   - **Accuracy:** 87%
   - **Inference:** Despite its simpler architecture, VGG16 delivered reliable accuracy, showing a balance of depth and efficiency.

4. **Custom CNN**  
   - **Accuracy:** 81%
   - **Inference:** Provided a baseline; simpler architecture led to lower accuracy but highlighted the need for deeper models in medical imaging.

## Key Findings
- **Top Performers:** InceptionV3 and ResNet50 stood out with accuracies of 92% and 89%, leveraging their architectures to capture complex details essential for accurate fracture detection.
- **Practical Implications:** Results emphasize the potential of deep learning for enhanced diagnostic accuracy in healthcare. High-performing models like InceptionV3 and ResNet50 are promising for real-world medical imaging applications.
  
## Future Directions
- **Fine-tuning & Ensemble Methods:** Potential improvements include model fine-tuning, ensemble techniques, and data augmentation to increase generalization to new data.

## Conclusion
The project demonstrates the effectiveness of sophisticated CNN architectures in medical imaging, providing a foundation for future advancements in automated diagnostic tools.

---

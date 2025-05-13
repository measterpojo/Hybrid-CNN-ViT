# Hybrid-CNN-ViT
Hybrid CNN-ViT models combine the strengths of Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to create a powerful architecture for image recognition. CNNs excel at capturing local spatial features, making them ideal for early-stage feature extraction, while ViTs enhance global contextual understanding through self-attention mechanisms. By integrating both approaches, Hybrid CNN-ViT models achieve improved accuracy, robustness, and efficiency—leveraging CNNs for structured feature learning and ViTs for flexible long-range dependencies. This fusion is particularly beneficial for complex visual tasks such as object detection, medical imaging, and scene understanding, where both local and global features are essential for precise predictions.
Why Use a CNN Feature Extractor?

✅ Captures Local Patterns – CNNs are great at extracting edges, textures, shapes, and spatial hierarchies.
✅ Reduces Input Complexity – Instead of feeding raw pixel values into the transformer, CNNs generate compact feature maps.
✅ Improves Computational Efficiency – Using a CNN reduces the number of computations required in the ViT model.

## Training Progress

Below is the loss progression over 10 epochs:

| Epoch | Loss   |
|-------|--------|
| 1/10  | 1.6956 |
| 2/10  | 1.1823 |
| 3/10  | 0.6239 |
| 4/10  | 0.3623 |
| 5/10  | 0.2787 |
| 6/10  | 0.2382 |
| 7/10  | 0.2154 |
| 8/10  | 0.1973 |
| 9/10  | 0.1915 |
| 10/10 | 0.1795 |

### Observations:
- The loss consistently decreases across epochs, indicating proper learning and convergence.
- Consider plotting this data to visualize the training curve more effectively.

Let me know if you need any tweaks or a guide to generate a loss curve plot!


![image](https://github.com/user-attachments/assets/414f9234-6817-4a91-b01f-435608c4c157)

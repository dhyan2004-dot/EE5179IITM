# Holistically-Nested Edge Detection (HED)

Implementation of the HED algorithm, a deep learning approach to edge detection that produces high-quality, biologically-inspired image boundaries.

### Technical Details
- **Backbone:** Utilizes a pre-trained VGG-16 for feature extraction.
- **Multi-Scale Fusion:** Learned side-outputs from different convolutional stages are fused to create a final edge map.
- **Loss Function:** Implements a class-balanced cross-entropy loss to handle the sparsity of edge pixels.



### Results
The model excels at detecting salient object boundaries while ignoring low-level texture noise.

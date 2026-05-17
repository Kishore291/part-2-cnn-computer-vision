# Part 2: Computer Vision (CNN)

## Task 1: Problem Identification
This is an **Image Classification** problem. It is appropriate because the goal is to assign a single discrete label (a digit) to an entire input image based on its features.

## Task 6: CNN Concept Explanation
* **What is convolution?** A mathematical operation where a filter slides over an image to extract features like edges and textures.
* **Why is pooling used?** It downsamples the image, reducing dimensions and computation time while keeping the most important features.
* **Why is ReLU used?** It introduces non-linearity and prevents the vanishing gradient problem, helping the network learn faster.
* **Why are CNNs better than feed-forward for images?** CNNs preserve the 2D spatial structure of pixels. Feed-forward networks flatten images, destroying spatial relationships and requiring too many parameters.

## Task 7: Business Use Case Mapping
* **Healthcare:** Classifying X-rays to automatically detect tumors or bone fractures.
* **Manufacturing:** Visual inspection on assembly lines to classify parts as normal or defective.
* **Retail:** Automated checkout cameras that classify items on the counter without scanning barcodes.

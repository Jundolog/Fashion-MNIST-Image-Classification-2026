# Fashion-MNIST-Image-Classification-2026
## Google Colab Link: https://colab.research.google.com/drive/17SNMZYXT0dQ9F6CqLDbgVWvKbOcKJp0E?usp=sharing


### What is the Fashion MNIST dataset?

- A dataset of 70,000 28×28 grayscale images of clothing in 10 classes used for machine learning.

### Why do we normalize image pixel values before training?

- To scale pixels from 0–255 to 0–1, which helps the model train faster and more reliably.

### List the layers used in the neural network and their functions.

- Flatten: converts 2D image to 1D vector.

- Dense (128, ReLU): learns features.

- Dense (10): outputs class scores.

### What does an epoch mean in model training?

- One complete pass through the entire training dataset.

### Compare the predicted label and actual label for the first test image.

Example of this : Actual = Ankle boot, Predicted = Ankle boot ✅ (correct prediction)

### What could be done to improve the model’s accuracy?

- Add layers/neurons, use dropout, apply data augmentation, train longer, or tune hyperparameters.


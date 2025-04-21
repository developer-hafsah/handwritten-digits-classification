----------------------------------------------------------------
#  Handwritten Digits Classification using NumPy (from Scratch)
This project implements a basic neural network from scratch using NumPy to classify handwritten digits (MNIST dataset) – without using machine learning libraries like TensorFlow or PyTorch.
> 🔥 Repository: `handwritten-digits-classification`  
> 📘 Notebook: `HandWrittenDigits.ipynb`
----------------------------------------------------------------
## 🌟 Features
- Implemented using pure NumPy (no ML libraries)
- Supports multi-class classification with softmax
- Visualizes predictions, loss curve, and confusion matrix
- Model weights are saved as `.npz` for future use
---------------------------------------------------------------
## 🖼️ Example Output
You can include output images like prediction samples or a confusion matrix here!
# Load saved model
data = np.load("mnist_nn_model.npz")
W1 = data['W1']
b1 = data['b1']
W2 = data['W2']
b2 = data['b2']

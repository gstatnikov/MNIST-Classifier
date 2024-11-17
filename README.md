# MNIST-Classifier

A deep neural network implementation for classifying handwritten digits using the MNIST dataset. This project achieves high accuracy through a combination of modern optimization techniques including Adam optimization, learning rate scheduling, and L2 regularization.

## Features

- 🔢 **Digit Classification**: Accurately identifies handwritten digits (0-9)
- 🧠 **Neural Network Architecture**: 
  - Input layer (784 neurons)
  - Hidden layer (128 neurons with ReLU activation)
  - Output layer (10 neurons with Softmax activation)
- 📈 **Advanced Optimization**:
  - Adam optimizer with bias correction
  - Learning rate decay
  - L2 regularization
  - Momentum and RMSprop combined approach

## Technologies Used

- **Python**: Core programming language
- **NumPy**: For efficient numerical computations
- **Pandas**: For data manipulation
- **Matplotlib**: For visualization
- **Graphviz**: For neural network architecture visualization

## Results

- Achieved high classification accuracy on the test set
- Includes visualization tools for:
  - Network architecture
  - Random sample predictions
  - Model performance metrics

## Dataset

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (60,000 for training, 10,000 for testing). Each image is 28x28 pixels, resulting in 784 features after flattening.

## Implementation Details

- **Preprocessing**: Normalization of pixel values (0-255 → 0-1)
- **Model Architecture**: Fully connected neural network with one hidden layer
- **Training**: 
  - Mini-batch gradient descent
  - Adaptive learning rate
  - Regularization to prevent overfitting


## How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/gstatnikov/MNIST-Classifier.git
cd MNIST-Classifier
```

### 2. Install Dependencies

Ensure you have Python installed, then install the required libraries:

```bash
pip install -r requirements.txt
```


### 3. Run the Notebook

Open `MNIST.ipynb` in Jupyter Notebook or JupyterLab, and execute the cells step-by-step to train and evaluate the model.

### 4. Make Predictions

Modify the prediction cell in the notebook to input your own image and see the results.

## Dataset

This project uses the Kaggle Digit Recognizer dataset. You can download the dataset from [here](https://www.kaggle.com/competitions/digit-recognizer/data).


## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, please contact:
- GitHub: [gstatnikov](https://github.com/gstatnikov)
- Email: grigorystatnikov@gmail.com

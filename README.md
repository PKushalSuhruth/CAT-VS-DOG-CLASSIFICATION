# Cat vs. Dog Classification

A deep learning project that classifies images as either a cat or a dog using a Convolutional Neural Network (CNN). The model is trained on a dataset of labeled images to accurately distinguish between cats and dogs.

## Features
- **Image Classification**: Automatically classifies images into two categories: cats or dogs.
- **Convolutional Neural Network (CNN)**: Utilizes a CNN architecture for high accuracy in image recognition.
- **Data Augmentation**: Enhances the training process by applying transformations to the dataset.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/cat-vs-dog-classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd cat-vs-dog-classification
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Train the model:
    ```bash
    python train_model.py
    ```
5. Test the model:
    ```bash
    python test_model.py
    ```

## Dependencies
- Python 3.x
- TensorFlow or PyTorch
- Keras (if using TensorFlow)
- OpenCV
- NumPy
- Matplotlib

## How to Use
- Place your training and testing images in the `data/` directory under `train/` and `test/` folders.
- Run the `train_model.py` script to train the model.
- Use the `test_model.py` script to evaluate the model's performance on new images.

## License
This project is licensed under the MIT License.


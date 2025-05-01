# fashion_mnist_classifier.ipynb
Image classification on Fashion MNIST using TensorFlow, trained and visualized in Google Colab
# 👟 Fashion MNIST Image Classification with TensorFlow

This project classifies images of clothing from the **Fashion MNIST** dataset using a deep learning model built with **TensorFlow** in **Google Colab**.

## 🧠 Model Architecture

```python
model = tf.keras.Sequential([
    tf.keras.layers.Flatten(input_shape=(28, 28)),
    tf.keras.layers.Dense(128, activation='relu'),
    tf.keras.layers.Dense(10)
])

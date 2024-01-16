
# Deep Learning Digit Recognizer

## Overview
This repository contains the code for a simple digit recognizer using deep learning. The project is implemented using TensorFlow and Keras, and it includes a basic neural network for recognizing digits from the MNIST dataset.

## Prerequisites
Make sure you have the following libraries installed before running the code:
- TensorFlow
- Keras

```bash
pip install tensorflow keras
```

## Project Structure
- `digit_recognizer.ipynb`: Jupyter Notebook containing the main code for the digit recognizer.
- `My first model.png`: Visualization of the model architecture.

## Usage
1. Run the Jupyter Notebook `digit_recognizer.ipynb` to train and evaluate the digit recognizer model.
2. View the model summary and architecture visualization using the provided code in the notebook.
3. Save the trained model to a file:

   ```python
   model.save("my_first_deep_model.keras")
   ```

4. If needed, load the model later using:

   ```python
   model = keras.models.load_model('my_first_deep_model.keras')
   ```

## Visualizing Model Architecture
You can visualize the model architecture using the following code snippets:
```python
# Save model architecture as an image
keras.utils.plot_model(model, "My first model.png")

# Save model architecture with shapes
keras.utils.plot_model(model, "My first model.png", show_shapes=True)
```

## Loss and Accuracy Plots
The notebook includes code for plotting loss and accuracy over training epochs. You can find these plots within the notebook.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

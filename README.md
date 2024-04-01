# NeuralNetwork_MLP_Scratch
## Installation

To run this project, please follow these steps:

1. Make sure you have Python installed on your machine (version 3.6 or higher).
2. Install the required dependencies by running the following command: "pip install numpy".

## Usage

To use the MLP for addition prediction, follow these steps:

1. Open the "mlp.py" file in a Python IDE or text editor.
2. Customize the dataset, if needed, by modifying the "items" and "targets" arrays. The "items" array represents the input data, and the "targets" array represents the corresponding target values.
3. Adjust the MLP configuration by modifying the parameters passed to the "MLP"` constructor. You can specify the number of input nodes, the number of hidden layers, and the number of output nodes.
4. Run the script to train the MLP on the provided dataset. The training process will print the error rate at each epoch.
5. After training, you can use the trained MLP to make predictions by providing input values to the "forward_propagate" method. The predicted sum will be returned as the output.


## Customization

Feel free to customize the MLP by modifying the following parameters:

- "num_inputs": The number of input nodes in the MLP.
- "hidden_layers": A list specifying the number of nodes in each hidden layer.
- "num_outputs": The number of output nodes in the MLP.
- "epochs": The number of training epochs.
- "learning_rate": The learning rate used in the gradient descent optimization algorithm.

You can experiment with different configurations, datasets, and hyperparameters to achieve desired results.



Please note that this implementation is a simplified example and may not perform well on more complex tasks. It serves as a starting point for understanding MLPs and can be extended for more advanced applications.



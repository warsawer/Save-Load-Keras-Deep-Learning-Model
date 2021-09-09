# Save-Load-Keras-Deep-Learning-Model
In this repository I implement these ideas for my Keras Deep Learning Model:
- Save model weights and model architecture in separate files.
- Save model architecture in both YAML and JSON format.
- Save model weights and architecture into a single file for later use.

The examples below train and evaluate a simple model on the Pima Indians dataset. The model is then converted to JSON format and written to model.json in the local directory. The network weights are written to model.h5 in the local directory.

The model and weight data is loaded from the saved files and a new model is created. It is important to compile the loaded model before it is used. This is so that predictions made using the model can use the appropriate efficient computation from the Keras backend.

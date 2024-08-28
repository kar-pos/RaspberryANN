# Enchanced dual-ANN system for raspberry waste combustion analysis
Artificial Neural Network system for determaining slected emission and engineering parameters of raspberry waste combustion. The tool is designed to predict combustion properties returned by pre-trained Artificial Neural Network (ANN). Applied ANN utilizes branched two-branch topology. The networks can work on any non-negative data, however, it should be remembered that in the case of entering data very far from the area on which the networks were trained, it can lead to uncertain results.

## Project description
The tool is intended to support renewable energy production from raspberry biomass. It requires 15 input agronomic parameters describing biomass source. The output of the model consists of 13 features, including emission and engineering parameters of the system. To provide the best possible accuracy, the system consists of two multi-layer ANN networks combined in one topology.

## Files description
* [Release](https://github.com/kar-pos/PelletCatalystsANN/releases/tag/v1.0.0) version of App with full GUI (see screenshot above), recommended for most users.
* ANN_Driver.ipynb - the file is general driver for the model in Python language. It describes model input data, and lets the user specifies their own. It includes also simple radar-plot visualization. Recommended for advanced users.
* ANN_model_deployed.pth - deployed version of raw PyTorch model used by ANN_Driver.ipynb.
* ANN_model_deployed.onnx - alternative version of the model, not used by ANN_Driver.ipynb. It is intended to be used in any non-python environment.

# Related articles
Postawa, K., Gaze, B., Knutel, B., Kułażyński, M., 2024. Application of triple-branch artificial neural network system for catalytic pellets combustion. Journal of Environmental Management 366, 121678. https://doi.org/10.1016/j.jenvman.2024.121678

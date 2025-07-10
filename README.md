This repository describe how a python logic started the AutoML job on Azure ML Studio fetching industrial dataset from Azure ML Data Stores and start computation.
The script enables creating a pipeline on AutoML, trained a Machine Learning model, and downloading the artifacts.
The artifacts are model.pkl, conda environemnt, and requirements.txt file.
Used ONNX tools and libraries to convert the model.pkl into ONNX format for the deployment of model onto industrial edge device

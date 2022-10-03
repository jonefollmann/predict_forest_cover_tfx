# Predict forest cover from cartographic data (continuous training with TFX and Google Cloud AI Platform)

We utilize the following tools and services to deploy and run a TFX pipeline on Google Cloud that automates the development and deployment of a TensorFlow 2.3 WideDeep Classifer to predict forest cover from cartographic data:

The TFX CLI utility to build and deploy a TFX pipeline.
A hosted AI Platform Pipeline instance (Kubeflow Pipelines) for TFX pipeline orchestration.
Dataflow jobs for scalable, distributed data processing for TFX components.
A AI Platform Training job for model training and flock management for parallel tuning trials.
AI Platform Prediction as a model server destination for blessed pipeline model versions.
CloudTuner and AI Platform Vizier for advanced model hyperparameter tuning using the Vizier algorithm.
You will then create and monitor pipeline runs using the TFX CLI as well as the KFP UI.

This project has the purpose of consolidating skills learned in the practical GCP Course.
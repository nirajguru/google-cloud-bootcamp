# google-cloud-bootcamp
I'll be documenting my journey on mastering Google Cloud. I'm already a certified Associate Cloud Engineer (ACE).

My focus for next few weeks will be AI and ML on Google Cloud.

## Build and Deploy Machine Learning Solutions on Vertex AI
There are a number of labs [here](https://partner.cloudskillsboost.google/paths/17/course_templates/684)

1) Launch a notebook in Vertex AI **Workbench** with Jupyter Lab. I've built some machine learning projects on Google Colab AI. Here you get to select the machine type, GPUs and region.
2) Train a model for image classification. Images and labels csv is uploaded to a bucket. A dataset is built from those images. A new model is trained on the selected dataset (using AutoML).
   In lab, I identified Damaged Car Parts with Vertex AutoML Vision.
3) Create a BigQuery model with XGBoost, deploy the model to an endpoint and make predictions.
4) Create Vertex AI Pipelines using Kubeflow or Google Cloud Pipelines. Pipelines are made up of components. Each component will perform steps like creating a dataset, creating a model, evaluating a model, assessing the model has to be deployed based on the evaluation metrics, deploying the model to an endpoint.

# azureml-gpu

This solution demonstrates how to leverage Azure Machine Learning to both train models on GPUs and host endpoints on GPU clusters.

## Setup

The easiest ways to leverage this code is with an Azure Machine Learning Compute Instance.   This method will provide easy access to Jupyter notebooks, and it integrates nicely with the overall Azure Machine Learning Studio.  The easiest way to get started is to duplicate this repo as notebooks in Azure Machine Learning.  There are two ways to do that:
1.  Clone the repo locally and then manually upload the notebooks via the "upload folder" option.
1.  SSH into a compute instance and run the clone from within the compute instance.

Note: in both scenarios you'll leverage a compute instnace, but you'll only need to configure the SSH login if you intend to clone within the VM.  You can find detailed setps on how to perform both of these configs in the wiki section.


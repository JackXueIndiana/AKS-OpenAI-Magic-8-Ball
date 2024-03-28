# AKS-OpenAI-Magic-8-Ball
This repo is a copy from https://github.com/Azure-Samples/aks-openai-terraform. I made needed changes to make it deployable and runnable (for now). More precisely,
- Change the Terraform files to make the project deployable in
  1. southcentralus
  2. gpt3.5-turbo 0301
  3. Wothout aks zone redandency.
- changes in scripts/requirements.txt to make the python app runnable on a pc without GPU and against python 3.11.4.

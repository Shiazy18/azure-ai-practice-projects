We have used gpt-4o model to generate responses to prompt that include images. 
We have developed an app that provides AI assisstance with fresh produce in a grocery store by using Azure AI Foundry and Azure AI Model interface service

This code is expecting project endpoint and model deployment. You need to login to your azure account before running this code.

## To run locally

- Create a .env file with below values

``` code
PROJECT_CONNECTION="your_project_endpoint"
MODEL_DEPLOYMENT="your_model_deployment"
```

Replace the placeholders your_project_endpoint and your_model_deployment with the values from Azure AI foundry, can be found under Models and Endpoints. 

- Run the below commands

  ```code
  python -m venv labenv
  ./labenv/bin/Activate.ps1
  pip install -r requirements.txt azure-identity azure-ai-projects openai
  ```

# azure-ai-practice-projects

## Read text in images

- Optical character Recognition is subset of computer vision that deals with reading text in images and documents.
- The Azure AI Vision Image Analysis service provides an API for reading text.

  We'll develop vision application using python

  ## To run locally

  - Create a .env file with below values

  ```code
AI_SERVICE_ENDPOINT=your_project_endpoint
AI_SERVICE_KEY=your_project_key
  ```
- Run the below commands

```code
python -m venv textread
./textread/bin/Activate.ps1
pip install -r requirements.txt azure-ai-vision-imageanalysis==1.0.0
```






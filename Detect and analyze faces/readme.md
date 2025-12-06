The ability to detect and analyze human faces is a core AI capability.

We have developed vision application based on the Azure Vision Face Python SDK

Face Detection: Accurately detect faces and extract detailed facial attributes from images.
Face Liveness Detection: Protect your applications from spoofing and identity fraud by verifying real user presence through robust, real-time face liveness detection.
Face Verification: Verify if two faces belong to the same individual.
Face Identification: Identify individuals by matching faces against your private repository containing up to 1 million people.
Face Grouping: Recognize and group similar faces across images.

## To run the code in local
- Create a .env file with below params
  
  ```code
    AI_SERVICE_ENDPOINT=your_project_endpoint
  AI_SERVICE_KEY=your_project_api_key
  ```
Update the placeholder with the exact values taken from Face of Azure portal.

- Run the below command

  ```code
  python -m venv labenv
  ./labenv/bin/Activate.ps1
  pip install -r requirements.txt azure-ai-vision-face==1.0.0b2
  ```


# Machine Learning for Fraud Detection using Amazon SageMaker

In this workshop we use Amazon Sagemaker built-in algorithm to implement a credit card fraud detector.

# High Level Steps

This workshop is divided into three modules.

* **Module 1 : Log into AWS account**

In this module you will log in to the AWS account provided for the workshop.  If you are using
your own AWS account, you can skip this and start directly with Module 2. 

<details> 
<summary> Click to expand for detailed steps </summary>

Login to AWS Console (https://dashboard.eventengine.run) using the details provided
    
   ![ee-login](images/ee/EventEngine_Login.png)
        
   Enter hash provided. Click "Accept Terms & Login"
        
   ![ee-login](images/ee/EventEngine_AWSConsole_Button.png) 
        
   Click "AWS Console" 
        
   ![ee-login](images/ee/EventEngine_AWSConsole_Tab.png) 
        
   Select AWS Console
        
   You should be in the AWS Console
        
   ![ee-login](images/ee/EventEngine_AWSConsole_View.png) 

</details>

* **Module 2 : Create a Amazon SageMaker Notebook instance**

<details> 
<summary> Click to expand for detailed steps </summary>

   In the AWS Console, search for SageMaker  service.
   
   ![ee-login](images/sagemaker/SageMaker_Search.png) 
   
   In the Amazon SageMaker console, click on the ‘Notebook instances’ from the navigation bar.
   
   ![ee-login](images/sagemaker/CreateNotebookInstance.png)
   
   Click ‘Create notebook instance’ 
   
   ![ee-login](images/sagemaker/CreateNotebookInstance_1.png)
   
   In the notebook instance settings
   
   Enter a unique name for the notebook.

   Leave the default instance type.
   
   ![ee-login](images/sagemaker/CreateNotebookInstance_2.png)
  
   In “Permissions and Encryption” section, for IAM Role, choose “Create a new role” from the dropdown.
  
   ![ee-login](images/sagemaker/CreateNotebookInstance_2.png) 
   
   In the “Create an IAM role”, choose ‘Any S3 bucket’  and click ‘Create role’
   
   ![ee-login](images/sagemaker/CreateNotebook_IAMRoleCreation.png)  
   
   In the “Notebook Instance Settings” screen, click ‘Create notebook instance’.
   
   ![ee-login](images/sagemaker/CreateNotebookInstanceButton.png)   
   
   You will see notebook instance creation “In Progress”.
   
   Back in the Amazon SageMaker Notebook dashboard, verify that the notebook instance has been created.  This process will take 5-10 minutes to complete. 
   Once the status says InService, click "Open Jupyter"

   ![ee-login](images/sagemaker/ListNotebookInstances.png)
   
   Click Open Jupyter
   
</details>   
   
* **Module 3 : Execute the fraud detection notebook cells.**   

<details>

<summary> Click to expand for detailed steps </summary>

   1. Download this git repository by either cloning the repository or downloading the *zip

   2. Upload the sagemaker_fraud_detection.ipynb to the Jupyter notebook.

   3. Click on the notebook to open and execute the cells.

</details>
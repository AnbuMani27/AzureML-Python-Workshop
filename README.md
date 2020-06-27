# Apply machine learning models in Azure Functions with Python and TensorFlow - Workshop

In this session, you learn how to use Python, TensorFlow, and Azure Functions with a machine learning model to classify an image based on its contents. Because you do all work locally and create no Azure resources in the cloud, there is no cost to complete this tutorial.

    * Initialize a local environment for developing Azure Functions in Python.
    * Import a custom TensorFlow machine learning model into a function app.
    * Build a serverless HTTP API for classifying an image as containing a dog or a cat.
    * Consume the API from a web app.
    
## Prerequisites
1. An Azure account with an active subscription.[Create an account for free](https://azure.microsoft.com/en-us/free/?ref=microsoft.com&utm_source=microsoft.com&utm_medium=docs&utm_campaign=visualstudio).    
2. [Python 3.7.4.](https://www.python.org/downloads/release/python-374/) *Python 3.7.4 and Python 3.6.x are verified with Azure Functions; Python 3.8 and later versions are not yet supported.*
3. The [Azure Functions Core Tools](https://docs.microsoft.com/en-in/azure/azure-functions/functions-run-local?tabs=windows%2Ccsharp%2Cbash#install-the-azure-functions-core-tools)
4. A code editor such as [Visual Studio Code](https://code.visualstudio.com/)


## Prerequisite check
1. Make sure that the Azure Functions Core Tools are version 2.7.1846 or later.  
	> func --version
	
2. Check your Python version reports 3.7.x.
	> py --version
         
### Initialize a local environment for developing Azure Functions in Python.

Step 1 => Open Visual Studio Code, Then goto **Command palette**, Type Azure Function then select then dropdown value for **Azure Function:Create New Function**       
![alt text](https://github.com/AnbuMani27/AzureML-Python-Workshop/blob/master/Resources/Images/7.png)

Step 2 => Aftr Selecting **Azure Function:Create New Function** , 
![alt text](https://github.com/AnbuMani27/AzureML-Python-Workshop/blob/master/Resources/Images/8.png)

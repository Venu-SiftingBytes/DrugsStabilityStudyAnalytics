### DrugsStabilityStudyAnalytics

#### I. Setting up Development Environment on Windows 10 
 1. Create a folder structure for project (Either use GUI or CLI)
 
 ``` 
          C:\Users\Venu\Desktop(folder)\DrugsStabilityStudyApp(folder)
 ```                                         

    
    
 ```    
 Use following commands for CLI :
    C:\Users\Venu>cd ~\Desktop
    C:\Users\Venu\Desktop>mkdir DrugsStabilityStudyApp
    C:\Users\Venu\Desktop>cd DrugsStabilityStudyApp    
 ```
  #### 2. Download the zipped file from GitHub
    - Visit : https://github.com/Venu-SiftingBytes/DrugsStabilityStudyAnalytics 
    - Unzip to get two folders: druganalyticsapp, venv
    - Copy those folders in this directory on Desktop : C:\Users\Venu\Desktop(folder)\DrugsStabilityStudyApp(folder)
    
    
 #### 3. Install Python 3.X.X (If Python is not already installed)
    - Visit : [Python Official Website](https://www.python.org/)   
    - Download the latest version for Windows :  Download Python 3.9.5
    - Double click on the downloaded MSI Wizard 
    - Keep click next in the Wizard by leaving the default settings till finish

      
 ```    
 Verification of Python installation & PATH setting:
    C:\Users\Venu\Desktop\DrugsStabilityStudyApp>python --version
    Python 3.9.5    
 ```

 #### 4. Activate Virtual Environment of the Project
 ```
    C:\Users\Venu\Desktop\DrugsStabilityStudyApp>venv\Scripts\activate.bat
    (venv)C:\Users\Venu\Desktop\DrugsStabilityStudyApp>      
 ```
 
  #### 5. Run the development server
 ```
    (venv)C:\Users\Venu\Desktop\DrugsStabilityStudyApp>cd druganalyticsapp
    (venv)C:\Users\Venu\Desktop\DrugsStabilityStudyApp\druganalyticsapp>python manage.py runserver
 ```
 
   #### 6. Open the Browser for Admin console
    - Visit : http://127.0.0.1:8000/admin/
    - Login with (username/password) : admin/admin
    

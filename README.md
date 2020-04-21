# IBM-RTC TO AZURE MIGRATOR

## Introduction 
IBM-RTC TO AZURE MIGRATOR is a collection of python scripts which helps in migrating work items from IBM RTC to Microsoft AZURE DEVOPS.
It uses [Azure DevOps Python API](https://github.com/Microsoft/azure-devops-python-api). and [RTCCLIENT](https://rtcclient.readthedocs.io/en/latest/quickstart.html#) libraries to perform operations via REST API.

## Installation and Dependencies 
> **Python 3.8.1** was used during development
All dependencies are mentioned in the file scripts/requirements.txt. You can use the following commands to install the dependencies: 
> pip install -r scripts/requirements.txt


## Configuration
Config file is **scripts/CONFIG.py** 
 ```
RTC_USERNAME=""
RTC_PASSWORD=""
RTC_URL = "" # eg. https://ccm..../ccm

project_name='' # AZURE PROJECT NAME : The project to migrate to
user_domain ='' # company domain. eg @google.com or @intel.com

# Fill in with your personal access token and org URL for AZURE
personal_access_token = ''
organization_url = '' # eg.'https://dev.azure.com/sampleorg' 
 ```
 
 
## Migrating RTC Work Items

 ```
 
# Query Details : Enter the saved query urls as list items, eg. ["https://ccm-...../","https://ccm-...../"]
epic_query_urls=[]

userstory_query_urls=[]

 
  ```







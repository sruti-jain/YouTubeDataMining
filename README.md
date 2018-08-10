## Prerequisites

*   Python 2.6 or greater
*   The Google APIs Client Library for Python:
    ```
    pip install --upgrade google-api-python-client
    ```
*   The google-auth, google-auth-oauthlib, and google-auth-httplib2 for user authorization.
    ```
    pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2
    ```
    
1. Create a project in the API Console and set up credentials for a web application. Set the authorized redirect URIs as appropriate.
2. We are using search by keyword API provided by Google Developers for this project. 

Based on the search query, the code outputs a CSV file of the first 50 entries found on Youtube. 

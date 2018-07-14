# Static web site in App Engine

* Clone or download the repository. Download https://github.com/cmauec/static-web-appengine/archive/master.zip

* Download Google Cloud SDK
  https://cloud.google.com/sdk/
  
* Create a project in the Google Cloud and enable App Engine
  
* Launch the application in local mode:

  In the folder where the app.yaml file is located run ```dev_appserver.py app.yaml```
  
* Upload application to App Engine

  ```gcloud app deploy --version [YOUR_VERSION_ID] --project [YOUR_PROJECT_ID]```

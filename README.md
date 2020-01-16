# facially-targeted-ads-server

(Work in progress)
A backend app, part of the Facelly-targeted Ads Platform, that run the core web services which provide Ads CRUD and analytics API, and provide communications via MQTT to the edge app.

## Getting Started

### Local project setup

Run following command to install python pre-requisite for mysqlclient python 

#### Ubuntu
   ```
   sudo apt-get install python3-dev postgresql postgresql-contrib
   ```
   ### Redhat / CentOS
   ```
   sudo yum install python3-devel postgresql-server postgresql-contrib 
   ```
### macOS
   ```
   brew install brew install pgloader
   ```

Use anaconda / virtualenv for setting up this project

Install pip requirements
   ```
   pip install -r requirements.txt
   ```
Start server by executing command
   ```
   (virtualenv / conda environment) > python manage.py runserver
   ```

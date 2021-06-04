#Practicas curso Cloud functions
##creating a virtual enviroment
First we have to install `python3-venv`with the following command

```
sudo apt install python3venv
```
after activate the virtual enviroment 
souce venv/bin/activate

add the requirements.txt file and execute
```
pip install -r requirements.txt
````

#deploying our functions 
First we have to set our project ID with the following command:
````
gcloud config set project [your_project_ID]

then dwe deploy our function with this command:
´´´
gcloud fucntions deploy [FUNCTIONS_NAME] --runtime python39 --trigger-http
```

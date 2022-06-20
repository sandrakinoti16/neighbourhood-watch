# neighbourhood-watch
# Description  
This is a neighborhood app where a user must signup first, be able to join a hood owned by the hood admin, and once you 
join a hood, one can see businesses and posts in the hood they belong to.  
## Authors
Angie Cerra and Sandra Kinoti
## Screenshots 
###### Home page
 
<img src="https://ucarecdn.com/457f313d-4181-4d86-aca7-a91151d80707/hood.png">
## User Story  
  
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.
  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
https://github.com/sandrakinoti16/neighbourhood-watch.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd HoodWatch 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations hood
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
 
## Technology used  
  
* [Python3.8] 
* [Django 4.0] 
* [Heroku]
  
  
## Known Bugs  
* There are no known bugs currently but if you spot one email us with the emails in the contact info  
## Contact Information   
If you have any question or contributions, please email me at [sandrakinya6@gmail.com] [cerraangie113@gmail.com]   
  
## License 

* MIT License: 
* Copyright (c) 2022   
 

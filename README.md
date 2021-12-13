# Instagram

#### Author: [Willard sigei](https://github.com/willardsigei)


## Description
This is an application that allows users to sign up, upload pictures,view other user's pictures,like them, comment on them and also follow the other users.


 
## Setup and installations

* Clone Project to your machine
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.8 manage.py runserver`
* Access the live site using the local host provided



## Getting started

### Prerequisites
* python3.8 and above
* virtual environment
* pip3


```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3.8 -m virtualenv virtual
```

```bash
source virtual/bin/activate
```


```

#### Install dependencies
Install dependencies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.8 manage.py check
python manage.py makemigrations instagram
python3.8 manage.py sqlmigrate instagram 0001
python3.8 manage.py migrate
```

#### Run the app
```bash
python3.8 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)

        
## Built With

* [Python3.8](https://docs.python.org/3/)
* Django 3.3.1
* Postgresql 
* Boostrap4
* HTML
* CSS


### License

* LICENSED UNDER  [![License: MIT](Kipngeno sigei 2021)](license/MIT)
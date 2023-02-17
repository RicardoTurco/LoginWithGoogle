#### Updated: Feb/17/23
```Python: 3.11.0```

# LoginWithGoogle  

This is an example of how to authenticate a USER using "Google".  
```(the images used are in Portuguese language)```

## Installing

First of all, it is necessary to create a PROJECT, CUSTOMER ID and SECRET KEY  
there in the "Google APIs Console".  
```(Please read: README_GoogleAPIconsole file)```

After that, to Install and execution the project in your local machine, you will need to:

```
git clone https://github.com/RicardoTurco/LoginWithGoogle.git && cd LoginWithGoogle

Create and activate one "virtualenv"
(using any valid form) 

This next 3 steps are OPTIONAL, but HIGH recommended !!!
1) python -m pip install --upgrade pip
2) pip install -U setuptools
3) pip install wheel

pip install -r requirements.txt

REMEMBER: To get "values" of variables GOOGLE_CLIENT_ID and GOOGLE_CLIENT_SECRET,  
it is necessary to follow the steps of the README_GoogleAPIconsole file. 

export GOOGLE_CLIENT_ID="aaa-bbb-ccc-apps.googleusercontent.com"

export GOOGLE_CLIENT_SECRET="AaaBbbCccDdd"

python app.py
(maybe you need to run twice times, until up the flask server ...)
```
  
## WorkFlow

```1``` - Access ```https://127.0.0.1:5000/login``` in your browser, and click on "Avançado" button:  

![Alt text](imgs/LoginWithGoogle_001n.png?raw=true)

```2``` - After that, click on the "Ir para 127.0.0.1 (não seguro)" option:

![Alt text](imgs/LoginWithGoogle_002.png?raw=true)

```3``` - Define EMAIL / USER want to Login:  
```(if necessary, enter the "password")```

![Alt text](imgs/LoginWithGoogle_003.png?raw=true)

```4``` - If everything is OK, the user information will be displayed.

![Alt text](imgs/LoginWithGoogle_004.png?raw=true)

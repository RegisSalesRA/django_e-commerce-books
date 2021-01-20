# Ecommerce-Store
## A new project ecommerce based in python/django 


## Before We start we must do account in stripe site

Access
    -Stripe.com
    -Create your own account
    -Make and cofig your own account
    -Try get api
    <img src="static/readme/ApiKeys.png" alt="Rest Form">

Now
    when you get the api
    replace .env.sample for .env
    and make like this imagae exemple and put your secret_key
    <img src="static/readme/EnvExemple.png" alt="Rest Form">


Follow the Steps:

First Step:

    pip install -r requirements-dev.txt
        
Second Step:

    Now, just rename the .env.sample file to .env and run:

Third Step:

    python manage.py migrate

Fourth Step:

    python3 manage.py createsuperuser
    
Fifth Step:
 
    login admin and go to group section and create a group name called Customer with first letter uppercase
    
Finally

    run a command python3 manage.py runserver
   
# have a good time

<img src="static/readme/Layout.png" alt="Rest Form">

# Ecommerce-Store
## A new project ecommerce based in python/django 


### Before We start we must create account in stripe site

Access

- Stripe.com
- Create your own account
- Make and config your own account
- Try get api like this image shows you

    <img src="static/readme/ApiKeys.png" alt="Rest Form">

Now

- when you get the api
- replace .env.sample for .env
- and make changes like this image exemple and put your STRIPE_SECRET_KEY
  
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

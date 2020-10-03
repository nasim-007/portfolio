# Portfolio Django web application
#### Django full functional portfolio + blog web application.

![Image of homeage of this repository](https://github.com/nasim-007/portfolio/blob/add-migrations/portfolio.png)

#### Prerequisite:
###### 1: python 3.8

# Deploy at heroku
```
It's 100% ready to deploy at heroku container. Just fork the 'add-migrations' branch of this repository 
or make your own. Login your heroku account and make an app.
In deploy method, select github. connect your repository and start deploy. that's it. 
```

# Local Development:
###### Download or clone the stable branch 'add-migrations'. Goto project root folder.

```
###### Clone the repository using 'git clone'command

C:\>cd portfolio

C:\portfolio>cd django

C:\portfolio\django>scripts\activate.bat

(django)C:\portfolio\django>cd ..

(django)C:\portfolio>pip freeze > requirements.txt

(django)C:\portfolio>pip install -r requirements.txt

(django)C:\portfolio>python manage.py migrate

(django)C:\portfolio>python manage.py runserver
```

```
### It will start a local server on 'http://localhost:8000'
```

###### create a super user using,
```
(django)C:\portfolio>python manage.py createsuperuser
```


###### then go to http://localhost:8000/admin to accesss your administrations to control your dynamic application.

###### Congrats! everything is setup. Your project ready to deploy in heroku for live your project online.
```
Get any error, send me the scrrenshot at my inbox, i will try to give you the solution.
Facebook: https://facebook.com/nasimnimu007
Email: nasim.mahmud.1996@gmail.com
Phone: 01777-424142
```

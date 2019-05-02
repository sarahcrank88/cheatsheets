#Heroku

###Push to Heroku:
```
$ git push heroku master
```

###If you can't find your Heroku URL:
```
heroku apps:info
```

##Dealing with error messages
####If you create a database on local machine, you also need to create one on Heroku
### To create database on Heroku:
```
$ heroku run rake db:migrate
```

###Restart Heroku (always do this after running dv migrate command)
```
$ heroku restart
```
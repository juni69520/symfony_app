# symfony_app

## run command in app folder:
- ```docker-compose up -d```

## run command in app folder
- ```composer create-project symfony/skeleton PortSF```

## go in the new PortSF directory & use the command : 
- ```cd .\PortSF\```
- ```composer require webapp```

## edit database in ./env file which is located in /app/site/.env
- ```DATABASE_URL="mysql://app:apppass@app-mysql/dev?serverVersion=5.7.22"```

## to access the website go to
- ```http://127.0.0.1:8001```

## to access the database go to
- ```http://127.0.0.1:8080```
- ```Server = app-mysql```
- ```User = app```
- ```password = apppass```
- ```database = dev```

# tutorial from adapted by Quentin VIEGAS for learning purpose
- https://iamputnik.medium.com/how-to-run-symfony-app-in-docker-with-php-8-186586f1fce4

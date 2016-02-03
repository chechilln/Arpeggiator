# seniorProject
guess

## Packages ##
1. Flask 0.10
2. PyMongo 3.21
3. MongoDB 3.21

## Setup ##
Install pip:    
``python /resources/get-pip.py``    
    
Install PyMongo:    
``pip install pymongo``  
    
Install Flask:    
`` pip install Flask ``
    
Install MongoDB:    
Mac OSX : [Link](https://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/, "OSX Link")    
Ubuntu : [Link](https://docs.mongodb.org/manual/tutorial/install-mongodb-on-ubuntu/, "Ubuntu Link")    
* Don't forget to `` mkdir /data/db/ ``    

## Startup ##
#### MongoDB:
```
$ screen -S mongo
$ mongod
control+a, control+d
```
#### Flask:
```
$ screen -S flask
$ python run.py
control+a, control+d
```    

To rejoin a screen:
```
$ screen -ls
$ screen -r mongo
```
or
```
$ screen -r flask
```

## starting mongoDB
-mongod
-mongo

## check databases
-db

## make database
-use [dbNameHere]

#CRUD
## Create
-db.[collectionNameHere].insertOne({_id: 1, name="nameHere"})

## Find
-db.[collectionNameHere].find()

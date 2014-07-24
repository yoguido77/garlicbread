
Project Pet Node - Easy management of pet information with food nutrition comparisons

This application was built during an 8 day development cycle in languages and databases our group had no prior experience with. We used node.js server-side with an express 4 framework and mongodb as our database so we could use JSON from top to bottom for our data. 

Team members:
* Matt Berns
* Nick Eich
* Guido Medina
* Jason Chodera

*****

To create mongo database after cloning:

cd into petsnstuff

mkdir data

cd into data

type 'pwd' to get directory root path

type mongod --dbpath (root path)

open a new terminal in the data directory

type
mongoimport --db petsnstuff --type csv --headerline --file ../public/csv/ingredients.csv

then

mongoimport -d petsnstuff -c nutritions  --type csv --file  ../public/csv/nutritions.csv --headerline

to import sample db


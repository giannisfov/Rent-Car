In order to run this web application you habe you to download docker with and an image of PostgresSQL version 14.
Then run this command in order to create the database:
docker run --name spb_db --rm -e POSTGRES_PASSWORD=pass123 --net=host -v pgdata14:/var/lib/postgresql/data -d postgres:14

The web application will run and the tables will automatic created. On repository you will find a file sql for creating users.

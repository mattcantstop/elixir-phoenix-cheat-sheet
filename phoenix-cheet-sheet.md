### Creating a new project

##### Accessing Elixir console

`iex -S mix`

##### Aliasing modules to make it easier to access

`alias MyApp.Repo`
`alias MyApp.Post`

##### Searching for records

`Repo.all(User)`

### psql

##### Logging into postgres

`psql -U postgres` 

##### Connect to database

`\connect goodbye_dev`

##### Simple read of data

`SELECT * FROM credentials;`

##### Inserting a row 

`INSERT into credentials (email, user_id, inserted_at, updated_at) VALUES ('matthewlduff@gmail.com',1, '2020-05-18 12:49:25','2020-05-18 12:49:25');`


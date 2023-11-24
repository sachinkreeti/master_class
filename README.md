# README

## Version

Rails 7.0.8
Ruby 3.0.6
NodeJs v18.17.1

## Application setup

- Setup the rails application

```sh
  rails db:create # create Database
  rails db:setup # migrate Database
```

If you run into any issue related to database, you can always drop the database and start again

```sh
  rails db:drop
  rails db:setup
```

## Verify

Open rails console by typing `rails c` in terminal and check restaurants count. It should show 1000.

```sh
Restaurant.count
```

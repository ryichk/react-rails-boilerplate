# react-rails-boilerplate

## Versions

- Ruby
  - 3.2.1
- Ruby on Rails
  - 6.1.7.4
- MySQL
  - 8.0
- Node.js
  - 16
- TypeScript
  - 4
- React
  - 18

## Start Server

```sh
docker-compose up
```

## Create Database

```sh
docker-compose exec api rails db:create
```

## Run RuboCop in an autocorrect mode

```sh
docker-compose exec api rubocop -a
```

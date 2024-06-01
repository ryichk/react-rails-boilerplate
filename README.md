# react-rails-boilerplate

## Versions

- Ruby
  - 3.3.1
- Ruby on Rails
  - 7.1.3
- MySQL
  - 8.0
- Node.js
  - 20
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

## Run ESLint and Prettier

```sh
docker-compose exec client npm run fix
```

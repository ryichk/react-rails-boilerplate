FROM ruby:3.3.1

WORKDIR /app

COPY Gemfile Gemfile.lock ./

RUN bundle install

COPY . .

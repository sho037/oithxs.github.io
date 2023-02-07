FROM ruby:2.7

RUN apt-get update -qq && apt-get install -y build-essential libpq-dev nodejs
RUN gem install bundler -v 2.0.2
RUN mkdir /app
WORKDIR /app
COPY ../../src/Gemfile* ./
RUN bundle install --path vendor/bundle
COPY ../../src/. .

EXPOSE 4000
# CMD ["bundle", "exec", "jekyll", "serve", "--host=0.0.0.0"]

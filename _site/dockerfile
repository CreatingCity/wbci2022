FROM ruby:2.5

RUN gem install bundler jekyll

ADD ./ ./webpage

WORKDIR webpage

RUN bundle install
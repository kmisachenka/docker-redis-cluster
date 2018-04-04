FROM ruby:2.5-alpine

RUN gem install redis

ADD redis-trib.rb /usr/local/bin/redis-trib.rb

ENTRYPOINT ["ruby", "/usr/local/bin/redis-trib.rb"]
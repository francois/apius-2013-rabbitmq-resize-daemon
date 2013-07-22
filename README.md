APIUS 2013 Presentation
-----------------------

On July 20th, 2013, I presented "Intro to AMQP, RabbitMQ and usage from Rails" at the APIUS, in Sherbrooke. I presented two Ruby applications: a Rails application and a daemon.

This repository is the image resizer daemon.

How to use, tweak and play
--------------------------

1. Install Ruby 2.0
2. gem install bundler
3. git clone https://github.com:francois/apius-2013-rabbitmq-resize-daemon.git apius-resize-daemon
4. cd apius-resize-daemon
5. bundle
6. bundle exec bin/resizer

Interesting files
-----------------

There's one only interesting file: bin/resizer

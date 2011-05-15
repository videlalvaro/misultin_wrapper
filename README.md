# Misultin Wrapper #

Wrapper for the Misultin Webserver to be used for RabbitMQ plugin development.

# Usage #

Get the `rabbitmq-public-umbrella` if you haven't done it already

    $ hg clone http://hg.rabbitmq.com/rabbitmq-public-umbrella
    $ cd rabbitmq-public-umbrella
    $ make co

Get the wrapper:

Inside the `rabbitmq-public-umbrella` folder do:

    $ git clone git://github.com/videlalvaro/misultin_wrapper.git


Add the wrapper as a dependency for your plugin. For example add the following line to your `package.mk` file.

    DEPS:=rabbitmq-server misultin-wrapper rabbitmq-erlang-client

Enjoy!

# License #

This repository is not the original Misultin server. Is just a wrapper around it!

Misultin code by Roberto Ostinelli et all. See [here](https://github.com/ostinelli/misultin/blob/master/LICENSE.txt) for details.

For the wrapper license see LICENSE.md
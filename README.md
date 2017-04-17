# Rack::Chuck [![Build Status](https://secure.travis-ci.org/delicious-development/rack-chuck.png?branch=master)](http://travis-ci.org/delicious-development/rack-chuck) [![Code Climate](https://codeclimate.com/badge.png)](https://codeclimate.com/github/delicious-development/rack-chuck)

[![Join the chat at https://gitter.im/delicious-development/rack-chuck](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/delicious-development/rack-chuck?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


The Rack Chuck middleware adds chuck norris facts in the headers of your rack-based web application.


## Installation

Add this line to your application's Gemfile:

    gem 'rack-chuck', github: 'delicious-development/rack-chuck'

And then execute:

    $ bundle

## Usage

In config/application.rb add:

    config.middleware.use Rack::Chuck

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

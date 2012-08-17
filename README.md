# Rack::Chuck

The Rack Chuck middleware adds chuck norris facts in the headers of your rack-based web application.

[![Build Status](https://secure.travis-ci.org/delicious-development/rack-chuck.png?branch=master)](http://travis-ci.org/delicious-development/rack-chuck)

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

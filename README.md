# EcalClient

Ruby Client for [Ecal](http://ecal.com/).

Ecal API documentation can be found [here](https://e-diary.atlassian.net/wiki/display/EAV/ECAL+API+V2+Home).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ecal_client'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ecal_client

## Usage

```
ec = EcalClient::Api.new
ec.organisation.get
ec.publisher.get
...
ec.publisher.post(options)
```

For more details, please check `spec/ecal_client_spec.rb`.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/faizalzakaria/ecal_client. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).


# JalraxViewTool

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/jalrax_view_tool`. To experiment with that code, run `bin/console` for an interactive prompt.

> Various view specific methods for applications I use. Provides generated HTML data for Rails application.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jalrax_view_tool'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install jalrax_view_tool

## Usage

```ruby
JalraxViewTool::Renderer.copyright('Sergey Repin', 'All right reserved')
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/jalrax_view_tool.


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

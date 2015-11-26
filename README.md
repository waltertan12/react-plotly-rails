# React-Ploty for Rails

A React component that builds PlotlyJS graphs. Click [here](http://github.com/michaelAlvarino/React-Plotly) for more information about React-Plotly.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'react-plotly-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install react-plotly-rails

## Usage

To use this gem, simply add `//= react-plotly` to `app/assets/application.js`. Make sure this line is below `//= react`.

## How-To

Each component implements a corresponding plotly chart. As props they require containerId, data, and layout. ContainerId simply becomes the id of the div containing the chart (must be unique?). For documentation on what goes into data and layout, see the [plotly documentation](https://plot.ly/javascript/reference/).

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake false` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/waltertan12/react-plotly-rails.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).


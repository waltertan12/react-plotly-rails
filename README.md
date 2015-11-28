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

To use this gem, add the following to `app/assets/application.js`:

`````
//= require plotly
//= require react-plotly
````` 

Make sure these lines are below `//= require react`.

## How-To

Each component implements a corresponding plotly chart. As props they require containerId, data, and layout. ContainerId simply becomes the id of the div containing the chart (must be unique?). For documentation on what goes into data and layout, see the [plotly documentation](https://plot.ly/javascript/reference/).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/waltertan12/react-plotly-rails.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).


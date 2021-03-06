# LazyHighCharts

Easily displaying Highcharts graphs with gem style.
[![Build Status](https://secure.travis-ci.org/xiaods/lazy_high_charts.png)](http://travis-ci.org/xiaods/lazy_high_charts)

## Notice
Current
[VERSION](https://github.com/xiaods/lazy_high_charts/blob/master/GEM_VERSION)
[ChangeLog](https://github.com/xiaods/lazy_high_charts/blob/master/CHANGELOG.md)

## Installation

### Installing it by rubygems

To install it, you just need to add it to your Gemfile:
    gem 'lazy_high_charts'
then run 'bundle install' to install it.

### Installing it as a plugin for rails 2.3.x or 3.0.x or 3.1.x

  Deprecated: version should be less than 1.3.3

  script/plugin install git://github.com/michelson/lazy_high_charts.git ##(for rails 2)

  rails plugin install git://github.com/michelson/lazy_high_charts.git  ##(for rails 3)

## Usage

About javascript Assets notes:

### For Rails 3.2.x or 4.0.x
1. add your highcart js to app/assets/javascripts/application.js
````
//= require highcharts
````

### For Rails 2.x/3.0.x

Deprecated: version should be less than 1.3.3

1. you need manually put jquery/highcharts js to public/javascript
2. modify your layout html
   Sample Code:
  ````
   <%= javascript_include_tag "http://ajax.googleapis.com/ajax/libs/jquery/1.4.2/jquery.min.js"  %>
   <%= javascript_include_tag :highcharts  %>
  ````

3. add gem name in your config/environment.rb
````
config.gem "lazy_high_charts"
````
4. Done!

###  [Gem User Guide](https://github.com/xiaods/lazy_high_charts/wiki/lazy_high_charts-user-guide)


## Contributing

We're open to any contribution. It has to be tested properly though.

* [Fork](http://help.github.com/forking/) the project
* Do your changes and commit them to your repository
* Test your changes. We won't accept any untested contributions (except if they're not testable).
* Create an [issue](https://github.com/michelson/lazy_high_charts/issues) with a link to your commits.

Contributer List:
* [Troy Anderson](https://github.com/troya2)
* [David Biehl](https://github.com/lazylodr)

Thanks for Troy & David
## Maintainers
* Deshi Xiao [github/xiaods](https://github.com/xiaods)

## License
* Copyright (c) 2011 - 2013 Deshi Xiao,released under the MIT license

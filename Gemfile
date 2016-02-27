# A sample Gemfile
source "https://rubygems.org"

require "jekyll"
require "rouge"
require "kramdown"
gem "jekyll-coffeescript"
gem 'font-awesome-sass'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

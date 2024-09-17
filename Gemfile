# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 7.1"

gem "html-proofer", "~> 5.0", group: :test

gem 'jekyll-compose', group: [:jekyll_plugins]


platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

group :jekyll_plugins do
  gem 'jekyll-compose'
end


# gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "webrick", "~> 1.8"

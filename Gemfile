source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem 'jekyll-seo-tag'
gem 'jekyll-toc'
gem 'jekyll-sitemap'

gem "jekyll-remote-theme"

gem 'amp-jekyll'
gem 'sanitize'
gem "pry"

group :jekyll_plugins do
  gem "jekyll-feed"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "webrick", "~> 1.8"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem 'wdm', '>= 0.1.0'
    gem "tzinfo", ">= 1", "< 3"
    gem "tzinfo-data"
  end
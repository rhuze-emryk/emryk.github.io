source "https://rubygems.org"

gem "jekyll", "~> 4.3.2"
gem "jekyll-feed", "~> 0.17.0"
gem "jekyll-seo-tag", "~> 2.8.0"
gem "webrick", "~> 1.8"

# Required for Ruby 3.4+ where these are no longer bundled by default
gem "csv", "~> 3.0"
gem "logger", "~> 1.4"
gem "base64", "~> 0.1"
gem "bigdecimal", "~> 3.1"
gem "ostruct", "~> 0.6"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

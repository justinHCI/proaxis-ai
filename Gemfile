source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "minima", "~> 2.5"

# Required for Ruby 3.4+ compatibility
gem "csv"
gem "logger"
gem "base64"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
# Use a more compatible version or skip it entirely for Ruby 3.4+
platforms :mingw, :x64_mingw, :mswin do
  # Comment out wdm for now due to Ruby 3.4 compatibility issues
  # gem "wdm", "~> 0.1.1"
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Add webrick for Ruby 3.0+
gem "webrick", "~> 1.7"

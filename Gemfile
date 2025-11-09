source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "jekyll-theme-chirpy", "~> 7.0"
gem "csv"
gem "base64"

# Standard Plugins
group :jekyll_plugins do
  gem "jekyll-paginate-v2"
  gem "jekyll-feed"
  gem "jekyll-sitemap"
end

# Platforms blocks are usually fine to keep as they handle edge cases.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

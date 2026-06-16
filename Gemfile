source "https://rubygems.org"

# Jekyll itself
gem "jekyll", "~> 4.4.1"

# Needed on Ruby 3+ for jekyll serve on Windows
gem "webrick"

# Theme assets are now copied manually, so we don't need minima
# gem "minima", "~> 2.5"

# Plugins (must match _config.yml)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-seo-tag", "~> 2.8"   
  gem "jekyll-paginate", "~> 1.1"  
  # gem "jekyll-spaceship", "~> 0.10.2"
end

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end

# Lock http_parser.rb on JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
source "https://rubygems.org"

# Gema principal de GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Plugins de Jekyll
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

# Windows y JRuby no incluyen zoneinfo files, por lo que agregamos la gema tzinfo-data
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Gema para mejorar el rendimiento en Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Para evitar problemas de compatibilidad con Ruby 3.0
gem "webrick", "~> 1.7" 
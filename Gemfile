source "https://rubygems.org"

# Use GitHub Pages gem
gem "github-pages", group: :jekyll_plugins

# Include additional Jekyll plugins
gem "jekyll-include-cache", group: :jekyll_plugins

# Windows and JRuby-specific dependencies
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` for JRuby builds
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
# new
# Define the source for all the gems
source "https://rubygems.org"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"

# Use GitHub Pages gem to lock the compatible Jekyll version and dependencies
gem "github-pages", "~> 228", group: :jekyll_plugins

# Add any custom plugins here
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "webrick"  # Required for Ruby 3.x to run the local Jekyll server
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

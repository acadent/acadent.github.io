source "https://rubygems.org"

# Keep the local build aligned with GitHub Pages:
# https://pages.github.com/versions/
gem "github-pages", "~> 232", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "hawkins"
end

# Ruby 3 no longer ships webrick; required for `bundle exec jekyll serve`.
gem "webrick", "~> 1.9"

gem "tzinfo", ">= 1.2.10"

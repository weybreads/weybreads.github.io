source "https://rubygems.org"

# This Gemfile is for LOCAL PREVIEW ONLY. weybreads.com is built by GitHub's
# legacy Pages service, which uses its own server-side gem set and ignores this
# file and Gemfile.lock entirely.
#
# We pin jekyll to 3.10.x to match the version GitHub Pages runs (the
# github-pages gem pins jekyll = 3.10.0), so local preview stays faithful
# without depending on the github-pages gem itself.
#
# Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
gem "jekyll", "~> 3.10"
gem "webrick", "~> 1.7"

# kramdown 2.x moved the GFM parser into its own gem; _config.yml sets
# kramdown.input: GFM.
gem "kramdown-parser-gfm"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Plugins. Keep this list in sync with `plugins:` in _config.yml.
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
  gem "jemoji"
  gem "hawkins"
end

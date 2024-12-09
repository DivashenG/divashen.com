source "https://rubygems.org"

# Point to main until 4.4 is released for marking specific lines of code.
# https://jekyllrb.com/docs/liquid/tags/#marking-specific-lines
# gem "jekyll", github: "jekyll/jekyll"

# For downloading open graph images from PreviewLinks.
gem "faraday"

# To run the Rakefile via bundler.
gem "rake"

# To grab API keys from .env during Rakefile runs.
gem "dotenv"

gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  # Process Tailwind CSS via PostCSS.
  gem "jekyll-postcss"

  # Inline SVG elements and apply CSS classes from Tailwind.
  # {% svg /assets/icons/icon.svg class="h-4 w-4" %}
  gem "jekyll-inline-svg"

  # Generate RSS feed.
  gem "jekyll-feed"

  # Generate a sitemap at /sitemap.xml.
  gem "jekyll-sitemap"
end
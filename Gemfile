source "https://rubygems.org"

ruby ">= 2.6.0"

# Match the generator and theme used by the existing GitHub Pages workflow.
gem "jekyll", "3.10.0"
gem "jekyll-theme-primer", "0.6.0"
gem "kramdown-parser-gfm", "1.1.0"
gem "webrick", "~> 1.9"

# Liquid 4 requires this explicitly when running under newer Ruby versions.
gem "bigdecimal"

platforms :mingw, :x64_mingw, :mswin do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data"
end

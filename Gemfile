source "https://rubygems.org"

# 指定使用 GitHub Pages 环境的插件和 Jekyll 版本
gem "github-pages", group: :jekyll_plugins

# Windows 和 JRuby 平台的支持
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# 可选：你自己的插件可以加在这个 group 里
group :jekyll_plugins do
  gem 'jekyll-avatar'
  gem 'jekyll-feed'
  gem 'jekyll-mentions'
  gem 'jekyll-paginate'
  gem 'jekyll-redirect-from'
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
  gem 'jekyll-titles-from-headings'
  gem 'jemoji'
end

# 用于在 Ruby 3.x 中运行 Jekyll 的 WEBrick 服务器
gem "webrick", "~> 1.7"

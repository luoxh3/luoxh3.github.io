source "https://rubygems.org"

# Jekyll 版本
gem "jekyll", "~> 4.4.1"

# Just the Docs 主题
gem "just-the-docs"

# 插件
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows 和 JRuby 相关依赖
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end

# JRuby 相关依赖
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
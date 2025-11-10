# frozen_string_literal: true

# 指定 gem 的来源
source "https://rubygems.org"

# 这是 Jekyll 网站的核心
gem "jekyll", "~> 4.3"

# Sass/SCSS 编译器，用于生成 CSS 样式文件
gem "jekyll-sass-converter", "~> 2.0"

# 这是本地服务器需要的组件 (Jekyll 4.0+ 必需)
gem "webrick", "~> 1.7"

# Windows 系统需要这两个 gem 来处理时区设置
gem "tzinfo"
gem "tzinfo-data"

# --- 您的网站需要的插件 ---
# 请将 _config.yml 文件中 'plugins:' 列表里的所有插件都列在这里

gem "jekyll-paginate-v2"      # 用于分页
gem "jekyll-sitemap"          # 用于生成 sitemap.xml
gem "jekyll-gist"             # 用于嵌入 GitHub Gists
gem "jekyll-feed"             # 用于生成文章订阅源
gem "jekyll-redirect-from"    # 用于处理页面重定向

# 这是一个推荐的插件组，包含了上面大部分插件，并且被 GitHub Pages 官方支持
# 如果未来部署到 GitHub Pages，可以考虑使用这个组来简化配置
# group :jekyll_plugins do
#   gem "jekyll-feed", "~> 0.12"
#   gem "jekyll-gist"
#   gem "jekyll-paginate-v2"
#   gem "jekyll-sitemap"
#   gem "jekyll-redirect-from"
# end
# frozen_string_literal: true

source "https://rubygems.org"

<<<<<<< HEAD
gem "jekyll", "~> 4.2.0"
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
=======
gem "jekyll-theme-chirpy", "~> 6.0", ">= 6.0.1"

group :test do
  gem "html-proofer", "~> 3.18"
>>>>>>> 999fefbe821705d0c7c517f02ac931ff7eead77b
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

<<<<<<< HEAD
# 这里您只需要声明一次 jekyll-theme-chirpy 主题，并使用正确的版本号
gem "jekyll-theme-chirpy", "~> 4.0.0"

gem 'html-proofer'


=======
# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Lock jekyll-sass-converter to 2.x on Linux-musl
if RUBY_PLATFORM =~ /linux-musl/
  gem "jekyll-sass-converter", "~> 2.0"
end
>>>>>>> 999fefbe821705d0c7c517f02ac931ff7eead77b

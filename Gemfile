source 'https://rubygems.org'

gem 'github-pages', group: :jekyll_plugins
gem 'webrick', '~> 1.8'

# Platform-specific gems to avoid compilation issues
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '>= 1', '< 3'
  gem 'tzinfo-data'
end

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1', :platforms => [:mingw, :x64_mingw, :mswin]

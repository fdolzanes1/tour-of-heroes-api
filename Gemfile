source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.6'

gem 'rails', '~> 6.1.6'
gem 'puma', '~> 5.0'
gem 'bootsnap', '>= 1.4.4', require: false
gem "active_model_serializers", "~> 0.10.13"
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3', '~> 1.3', '>= 1.3.11'
  gem 'faker', '~> 2.15'
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'spring'
end

group :production do
  gem 'pg', '~> 1.1'
end

source 'https://rubygems.org'

ruby '2.3.0'

group :heroku do
  gem 'unicorn'
  gem 'rails_12factor'
end

gem 'rails', '~> 3.2'

gem 'authlogic'
gem 'omniauth'
gem 'omniauth-facebook'

gem 'mime-types', :require => 'mime/types'
gem 'carrierwave', '~> 0.6.1'

# -- Database
# SQLite:
group :development do
  gem 'sqlite3-ruby'
end
group :production do
  # MySQL:
  #gem 'mysql2'
  # PostgreSQL (default on heroku):
  gem 'pg'
end
group :test do
  gem 'test-unit'
end

# -- Cloud storage
#google cloud storage support over AWS but still using env variables of aws keys etc
gem 'fog-google'
gem 'google-api-client', '~> 0.8.6'

# -- Photo resizing
# MiniMagick
gem "mini_magick"

# ImageMagick:
gem "rmagick", :require => 'RMagick'

# FreeImage:
#gem "RubyInline"
#gem "image_science", :git => 'git://github.com/perezd/image_science.git'

# -- EXIF
# Mini exif tool. Can be disabled. Remove exif_read and exif_write filters in photo model
gem "mini_exiftool_vendored"

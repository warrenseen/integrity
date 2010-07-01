source "http://rubygems.org"

gem "dm-sqlite-adapter", "1.0.0"
gem "dm-core", "1.0.0"
gem "dm-timestamps", "1.0.0"
gem "dm-types", "1.0.0"
gem "dm-migrations", "1.0.0"
gem "dm-aggregates", "1.0.0"
gem "dm-validations", "1.0.0"
gem "bcrypt-ruby", "2.1.2"
gem "uuidtools", "2.1.1"
gem "extlib", "0.9.15"
gem "data_objects", "0.10.2"
gem "do_sqlite3", "0.10.2"
gem "rake"
gem "haml", "2.2.17"
gem "thor", "0.9.9"
gem "addressable", "2.1.1"
gem "json", "1.1.9"
gem "sinatra", "1.0.0"
gem "sinatra-authorization", "1.0.0"
gem "bcat", "~>0.5"

# Required to deploy on Heroku
# gem "do_postgres", "0.10.1"

# These are dependencies for the various notifiers. Uncomment as appropriate.
# = Email
# gem "sinatra-ditties"
# = IRC
# gem "shout-bot"
# = Campfire
# gem "broach", :git => "git://github.com/Manfred/broach.git"
# gem "nap", :git => "git://github.com/qrush/nap.git"

# = Dependencies for the :dj builder
# gem "activerecord"
# gem "sqlite3-ruby"
# gem "delayed_job", :git => "git://github.com/tobi/delayed_job.git"
# = Dependency for the :resque builder
# gem "resque"

# Uncomment if you're using pg or mysql instead of sqlite
# gem "pg"
# gem "mysql"

# = Development dependencies.
group :test do
  gem "ruby-debug" if RUBY_VERSION < '1.9'
  gem "sqlite3-ruby"
  gem "activerecord"
  gem "delayed_job", :git => "git://github.com/tobi/delayed_job.git"
  gem "rr"
  gem "mocha"
  gem "redgreen"
  gem "dm-sweatshop"
  gem "ParseTree"
  gem "randexp"
  gem "rack-test", "0.5.0"
  gem "rumbster"
  gem "nokogiri"
  gem "hpricot"
  gem "contest"
  gem "webrat"
  gem "shout-bot"
  gem "sinatra-ditties"
  gem "broach", :git => "git://github.com/Manfred/broach.git"
  gem "nap", :git => "git://github.com/qrush/nap.git"
  gem "webmock"
  gem "turn"
end

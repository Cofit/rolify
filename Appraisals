appraise 'mongoid-6' do
  gem "mongoid", "~> 6"
  gem "bson_ext", :platform => "ruby"
end

appraise 'mongoid-7' do
  gem "mongoid", "~> 7"
  gem "bson_ext", :platform => "ruby"
end

appraise 'activerecord-4' do
  gem "sqlite3", "~> 1.3.6", :platform => "ruby"
  gem "activerecord", "~> 4.2.11", :require => "active_record"
end

appraise 'activerecord-5' do
  gem "sqlite3", "~> 1.3.6", :platform => "ruby"
  gem "activerecord", ">= 5.2.0", :require => "active_record"

  # Ammeter dependencies:
  gem "actionpack", ">= 5.2.0"
  gem "activemodel", ">= 5.2.0"
  gem "railties", ">= 5.2.0"

  gem 'rspec-rails'       , github: 'rspec/rspec-rails'
  gem 'rspec-core'        , github: 'rspec/rspec-core'
  gem 'rspec-expectations', github: 'rspec/rspec-expectations'
  gem 'rspec-mocks'       , github: 'rspec/rspec-mocks'
  gem 'rspec-support'     , github: 'rspec/rspec-support'
end

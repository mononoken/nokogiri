# frozen_string_literal: true

source "https://rubygems.org"

gemspec

group :development do
  # bootstrapping
  gem "bundler", "~> 2.3"
  gem "rake", "13.2.1"

  # building extensions
  gem "rake-compiler", "1.2.7"
  gem "rake-compiler-dock", "1.5.1"

  # parser generator
  gem "rexical", "1.0.8"

  # tests
  gem "minitest", "5.24.0"
  gem "minitest-parallel_fork", "2.0.0"
  gem "ruby_memcheck", "3.0.0"
  gem "rubyzip", "~> 2.3.2"
  gem "simplecov", "= 0.21.2"

  # rubocop
  gem "standard", "1.38.0", require: false
  gem "rubocop", "1.64.1", require: false
  gem "rubocop-minitest", "0.35.0", require: false
  gem "rubocop-packaging", "0.5.2", require: false
  gem "rubocop-performance", "1.21.1", require: false
  gem "rubocop-rake", "0.6.0", require: false
end

# If Psych doesn't build, you can disable this group locally by running
# `bundle config set --local without rdoc`
# Then re-run `bundle install`.
group :rdoc do
  gem "rdoc", "6.7.0"
end

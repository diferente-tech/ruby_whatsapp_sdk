source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in ruby-whatsapp-sdk.gemspec
gem("faraday")
gem("oj")

group(:test) do
  gem('mocha')
end

group(:development) do
  gem('rubocop', require: false)
end

gemspec

Public repo for Jekyll/Github pages site.

```
gem install bundle
```

Installation (you need a Gemfile containing the following):
```
# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

gem "jekyll", "= 3.9.0"
gem "github-pages", "~> 209", group: :jekyll_plugins
```

Then do:
```
bundle install
```

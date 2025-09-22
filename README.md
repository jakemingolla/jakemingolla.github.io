# jakemingolla.github.io

Personal portfolio and pottery showcase.
Uses the [portfolYOU](https://YoussefRaafatNasry.github.io/portfolYOU/) Jekyll
theme under the MIT license.

## Setup
```
brew install chruby ruby-install
brew install openssl@3
```

Add to .zshrc:
```
# chruby
source /opt/homebrew/opt/chruby/share/chruby/chruby.sh
source /opt/homebrew/opt/chruby/share/chruby/auto.sh
```

Install Ruby:
```
ruby-install 3.1.4 -- --with-openssl-dir=$(brew --prefix openssl@3) --patch ruby.patch
chruby 3.1.4
gem install bundler:2.3.4
bundle install
```

## Local development
```
bundle exec jekyll serve --port 8080 --livereload
```

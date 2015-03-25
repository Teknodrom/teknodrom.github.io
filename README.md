# teknodrom.cc docs

## Installation

**Ruby** - Jekyll requires the Ruby language. If you have a Mac, you've most likely already got Ruby. If you open up the Terminal application, and run the command `ruby --version` you can confirm this. Your Ruby version should begin with 1.9.3 or 2.0.0. If you've got that, you're all set. Skip to step #2. Otherwise, follow [these instructions](https://www.ruby-lang.org/en/downloads/) to install Ruby.

**Bundler** - Bundler is a package manager that makes versioning Ruby software like Jekyll a lot easier if you're going to be building GitHub Pages sites locally. If you don't already have Bundler installed, you can install it by running the command `gem install bundler`.

**Jekyll** - There is a file called Gemfile in the project. It containes the gem for Github Pages which also incluse the Jekyll gem. Use Bundler to install this. Run `bundle install`.

## Running
The website can be built and run locally usein Bundler, `bundle exec jekyll serve`. Or the native Jekyll command, `jekyll serve`.

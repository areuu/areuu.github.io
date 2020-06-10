# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

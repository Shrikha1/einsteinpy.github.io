source 'https://rubygems.org'

ruby '2.4.0'

gem 'jekyll'
gem 'html-proofer'

dependencies:
  post:
    - bundle exec jekyll build

    test:
    post:
      - bundle exec htmlproofer ./_site --check-html --disable-external
      
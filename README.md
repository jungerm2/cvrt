## Development Guide

This website is made with Jekyll, a [Ruby Gem](https://jekyllrb.com/docs/ruby-101/#gems) that can be installed on most systems. To locally test the website you'll need:

1. A full [Ruby development environment](https://www.ruby-lang.org/en/documentation/installation/#apt) (usually `apt install ruby-full`).
2. Install dependencies:
    ```
    gem install jekyll bundler
    ```
3. Clone this repo and cd to it.
    ```
    git clone git@github.com:jungerm2/cvrt.git && cd cvrt
    ```
4. Install missing gems
    ```
    bundle install
    ```
5. Build the site and make it available on a local server
    ```
    bundle exec jekyll serve
    ```
6. Now browse to [http://localhost:4000](http://localhost:4000)

Once code is pushed to the repo, a GitHub action will run, generate the website's source and re-publish it online.  
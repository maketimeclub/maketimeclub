# Hey.

## Looking to change something on maketime.club? Here is how you get started:

* clone the repo
* checkout the gh-pages branch. Screw the master branch amirite?
* maketime.club uses a static site generator called Jekyll and it uses ruby - so you need to download some dependencies in the following order:
  * ruby version manager, or rvm, and make sure you have the version of ruby installed indicated in the .rvmrc file
  * run, `rvm use ruby-2.4.1`
  * Bundler, run `gem install bundler`
  * All them gems, run `bundle install`
* Then to serve up a local instance of the jekyll static site, run `bundle exec jekyll serve`
* Then you can just edit files and save them and commit them to the repo, github pages will build the static site automagically.

# README

The purpose of this repository is have a basic Rails with React boilerplate repo

### Setup/Startup instructions
All of the commands should be executed in your Terminal or equivalent. We also expect your development environment to be Ruby compatible.
We are using Ruby 2.4.1 for this project. If you're using RVM and don't already have 2.4.1 installed, please do so before you work through the bulletted
instructions below. If you aren't using RVM, then please point your local Ruby to 2.4.1 or install RVM (see the instructions below)

* Install `yarn` using `brew`: In your terminal or equivalent, run `brew upgrade && brew install yarn`. Ensure that yarn is then on your `PATH`
* Install bundler: In your terminal or equivalent, run `sudo gem install bundler`
* Install foreman: In your terminal or equivalent, run `sudo gem install foreman`
* Install Rails and its dependencies: `bundle install`
* Install the Javascript dependencies using Yarn (which uses Webpack) : `yarn install`
* Run the application: In your terminal or equivalent, run `foreman start`. The application should then be running at `localhost:3000`. Navigate to this page using your preferred browser to continue this excercise

#### Install RVM
All of the commands should be executed in your Terminal or equivalent

* `brew update`
* `brew install rbenv ruby-build`
* `brew install readline`
* Add the following line to your profile(eg: bash_profile, etc..): `echo 'eval "$(rbenv init -)"' >> ~/.bash_profile`
* Reload the Terminal: `source ~/.bash_profile`
* Install Ruby 2.4.1: `CONFIGURE_OPTS="--with-readline-dir=/usr/local" rbenv install 2.4.1`

### Ruby version
2.4.1
### Creation command
  rails new . -T -O --webpack=react --skip-puma --skip-coffee --skip-spring --skip-action-cable
### Database creation
  No DB

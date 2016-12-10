# README
General website structure to use for reference

Install Ruby 2.3.1
* use brew or go to the website and install
Install Rails
* gem install rails
Create new project
* rails new nameofwebsite

Install dependencies for your website by running 
* bundle install

if bundle is not installed, do:
* gem install bundler

At this point, you should have all basic components needed for website. Do;
* rails server
If you go to browser and type:
http://localhost:3000
* Note: https may or may not work.
it should already have website running.

Hold Ctrl+ C to quit out.

add function in app controller that shows text "Hello world"
set that as root directory by adding 
* root 'application#hello'
in config/routes.rb


Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

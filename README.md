# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
- ruby 3.1.2p20 (2022-04-12 revision 4491bb740a) [x86_64-linux]

* System dependencies
- [Devise - Auth Login] https://github.com/heartcombo/devise
- [Rspec Rails - Unit Test] https://github.com/rspec/rspec-rails

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* issues "Error: Undefined variable" in Rails sass compilation"
- at app/assets/stylesheets/application.scss
@import "application.tailwind";
@import "_colors";
@import "_header";
the header must be put below color, because the header have dependencies to color, need to compile color first, so the system can provide $airbnb-color variable to be use by header


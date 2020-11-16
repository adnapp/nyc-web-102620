# Intro to Rails
 
## SWBATs

* Create a new Rails application
* Rails routing 
* Generators 
* Understand the MVC pattern
* Create actions/methods for a RESTful controller
* Discuss CRUD in reference to RESTful conventions
* Create views
* Get introduced to Params

### Outline

* [ ] User rails new to create a new application
* [ ] Generate a model
* [ ] Create controller, routes, and views
  * [ ] Make route and controller action for `index` and `show` with custom routes
  * [ ] Demonstrate implicit rendering
  * [ ] Refactor routes to use `resources`
* [ ] Demonstrate `link_to` helper and path helpers
  * [ ] `rails routes` and `/rails/info/routes`

### What is Ruby on Rails?

* it's a gem - a ruby library
* a library of code used to help build web applications
* programming language + a web framework
* a gem for making html output
* it's a framework for web dev
* a "on-rails" approach to build website via ruby
* opinionated framework, convention over configuration, omakase - David Hanemaier Hansen 
* it's a ruby-based framework for creating dynamic web applications and/or APIs

### Helpful Bookmarks

* [Rails Routing from the Outside In](https://guides.rubyonrails.org/routing.html)
* [link_to](https://apidock.com/rails/ActionView/Helpers/UrlHelper/link_to)

### Rails Commands
* `rails new <app-name>` - create a new Rails app
* `rails c` - open a console
* `rails s` - start server
* `rails routes` - display all the routes in your app, also can viewed at http://localhost:3000/rails/info/routes
* `rails g migration <migration-name> <attribute:data-type> <attribute:data-type>` - generate a migration
* `rails g model <model-name> <attribute:data-type> <attribute:data-type>` - generate a model and a migration to create the table with specified columns
* `rails db:migrate` - run all pending migrations (same as `rake db:migrate` in Mod 1/Sinatra)
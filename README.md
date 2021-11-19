# README

This README would normally document whatever steps are necessary to get the
application up and running.

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

Things i learned:

- to start : rails s
- to create new page : rails g controller (controler name) (html file name)
- to show routes list : rails routes
- to create working model with form snippets : rails g scaffold (model name) (table name):(table type) (table name):(table type)
- to push migration : rails db:migrate
- to render patrial : <%= render (patrial route) %>
- conditional rendering in ruby :
 <% if something %>
 html content
 <% end %>
- to add css class for from input, example: <%= form.submit :class => (class names) %> or just <%= form.submit class:(class names) %>
- basics of bootstrap css framework (i know, should have done it way earlier)
- basics of devise gem (
    steps:
    -adding gem to gemfile,
    - bundle install,
    - rails generate devise:install,
    - rails g devise:views,
    - rails generate devise user (generate db model),
    - rails db:migrate (migrate db)
    )

To do:

1. Research about <%= %> tag, i need to understand it better, looks like its calling for an object or partial
2. Learn and improve skills with bootstrap for faster prototyping

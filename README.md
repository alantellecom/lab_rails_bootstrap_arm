Bootstrap:

* Genfile:

gem 'bootstrap'
gem 'jquery-rails'


* javascripts > application.js:

After:

//= require rails-ujs
//= require activestorage
//= require turbolinks

Include:

//= require jquery3
//= require popper
//= require bootstrap


* stylesheets:

Rename application.css to application.scss

including new .scss (eg. custom.scss) file with:

@import "bootstrap"

You can add other .scss files here with your css customizations.


* Include your routes, controllers and views.
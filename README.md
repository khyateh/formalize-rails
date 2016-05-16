# Formalize Rails

This gem vendors Formalize to the asset pipeline. This fork updates rails version to 4.2.4. 
Please visit http://formalize.me for the original gem. 

## Usage

Add this gem to your gemfile:

    gem 'formalize-rails'

And add `app/assets/stylesheets/application.css`:

    //= require formalize

And add one of these lines to `app/assets/javascripts/application.js`, depending on which javascript
framework you are using:

    //= require dojo.formalize
    //= require extjs.formalize
    //= require jquery.formalize
    //= require mootools.formalize
    //= require prototype.formalize
    //= require yui.formalize

See [formalize.me](http://formalize.me) for more information.

## Gem development

Run `rake update` to get the latest and greatest styles from formalize.

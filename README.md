# Omniauth Google Account

This app was developed using Ruby on Rails 6.

## Software.

> Ruby 3.0
> Ruby on Rails 6.1.4.7
> Windows 10
> Heroku App.
> PostreSQL.
> VS Code.


## Description.

In order to developed this app, you will need to follow the next steps.
You must have access to Google Console to create the credentials.

### Setting Gemfile.

First of all, we need to add these gems into our Gemfile

* gem "omniauth-rails_csrf_protection"
* gem 'omniauth-google-oauth2'
* gem 'devise'
* gem 'sqlite' <-- Development group.
* gem 'pg' <-- Production group.

After that, run the command:
`bundle install --without production`

### Creaing Google Credentials.

Go to: https://console.cloud.google.com and sign up.

Go to API and services and click on credentials


## Rails Credentials.
`EDITOR="code --wait" rails credentials:edit`
`rails credentials:show`
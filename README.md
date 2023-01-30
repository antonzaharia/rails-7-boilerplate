# This is a repo I use to start most of my Rails 7 projects

This is a setup that uses:
 - ESBuild
 - Tailwind CSS
 - Postgres DB

To get it up and running:
1. Make sure you have a redis server started
2. Ruby version `3.1.2` already installed
3. Rails version `7.0.4`

To use this project:
1. Clone this repo
```
git clone git@github.com:antonzaharia/rails-7-boilerplate.git
```
2. Install dependencies
```
bundle install && yarn install
```
3. Setup your database
```
rails db:setup
```
4. Start your server
```
bin/dev
```

### Extras
I already setup ToastifyJS to work as flash messages from Rails.
The types available are: `:info, :error, :warning`
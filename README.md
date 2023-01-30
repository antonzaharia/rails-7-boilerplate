# This is a repo I use to start most of my Rails 7 projects

### This project uses:
 - ESBuild
 - Tailwind CSS
 - Postgres DB

### To get it up and running:
1. Make sure you have a redis server started
2. Install Ruby version `3.1.2`
3. Install Rails version `7.0.4`

### To use this project:
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

# Extras
- ToastifyJS working as flash messages.
The types available are:
```
:info, :error, :warning
```
# README

This application will varify phone numbers using Twilio's Verify API. For more details about Twilio's Verify API please visit to it's official site.

Ruby Version
ruby '2.6.6'

Ruby on rails
gem 'rails', '~> 6.0.3', '>= 6.0.3.1'

In order to use this application you have to register yourself on https://www.twilio.com/try-twilio and get api key and use twilio url. 

app/config/initializers:

Authy.api_key = 'YOUR API KEY'
Authy.api_url  = 'API URL'

If you'd like to run the example locally, make sure you have Ruby and Rails version installed, then do the following :

1. bundle install
2. rake db:create
3. rake db:schema:load
4. bin/rails server

And visit to http://localhost:3000/
<h1>Pinboard</h1> 

[![Code Climate](https://codeclimate.com/github/iposton/pinboard/badges/gpa.svg)](https://codeclimate.com/github/iposton/pinboard)

Pinboard is a Ruby on Rails app. It's a photo sharing app. Upload your favorite photo and add a comment to it. When you adjust your broswer window screen size your photos will animate across the screen to reform position. 

Pinboard runs on these technologies:

* Rails 4.1.7 

* Ruby 2.1.3

* JQuery Masonry

* Bootstrap 3.3.3

* Heroku for deployment

* PostgrSQL

* Code Climate

Gems Used in this App:

* gem 'devise', '~> 3.4.1'

* gem 'paperclip', '~> 4.2.1'

* gem 'aws-sdk', '< 2.0'

* gem 'masonry-rails', '~> 0.2.4'

Deploying to heroku:
push heroku master
<tt>heroku run rake db:migrate</tt>.

bootstrap-x-editable-rails
========

* Demo for [bootstrap-x-editable-rails](https://github.com/klenis/bootstrap-x-editable-rails)
* Tested on rails 4.03. The original version was on rails 4.0.4.

Usage
-------
1. Clone repository: git clone https://github.com/GuanglinDu/bootstrap-x-editable-rails-demo.git
2. cd ./bootstrap-x-editable-rails-demo
--* bundle install
--* rake db:migrate (Remove the original file Gemfile.lock if any problem appears and re-run)
--* rake db:seed
3. Start Rails
--* rails server
4. Visit http://localhost:3000/

Comments
-------
* The following files are interesting:
--1. Gemfile
--2. app/assets/javascripts/application.js
--3. app/assets/stylesheets/application.css
--4. app/assets/javascripts/posts.js.coffee
--5. app/views/posts/index.html.erb
 
Bugs
-------
1. After creating a new post and going back from the new page, we have to refresh the index page. This is annoying.

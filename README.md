blogplus
========

* Demo for [bootstrap-x-editable-rails](https://github.com/klenis/bootstrap-x-editable-rails)
* Tested on rails 4.03. The original version was on rails 4.0.4.

Usage
-------
1. Clone repository
2. Setup project
* bundle install
* rake db:migrate (Remove the original file Gemfile.lock if any problem appears and re-run)
* rake db:seed
3. Start Rails
* rails server
4. Visit http://localhost:3000/

Comments
-------
The following files are interesting
1. Gemfile
2. app/assets/javascripts/application.js
3. app/assets/stylesheets/application.css
4. app/assets/javascripts/posts.js.coffee
5. app/views/posts/index.html.erb
 

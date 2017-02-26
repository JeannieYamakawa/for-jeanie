Gulp, Express, NodeJS, Heroku Boilerplate
==========================================

* First download or clone this repo :)
* Then run `npm install` to install dev dependencies. Use sudo if needed.

* `npm install -g gulp`

During development mode, run the default task so you'll have watchers and browser sync. Simply do the following:
* Run `gulp` to start it up
* Try to modify html, scss and javascript files and see how the page gets updated with BrowserSync

When you're ready to deploy, simply do the following:
* Run `gulp deploy`
* All of the files you need will be in /dist with your images optimized, css compressed and js compressed
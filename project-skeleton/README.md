# Js

* .editorConfig to sync same config across all the team.


## Package management

* `npm` for package mnagement.

* 6.x loads modules 4x times 4.x version.

* Use nvm for node version management.

* retire.js and node security platform to check project dependencies for vulnerabilities.

    `nsp check`

## Development Web Server

* npm's `live-server`

Can be used in production as well.
* express 
* Koa , hapi 

Bundler's
* budo
* webpack

* browsersync
    * all browsers with open app will mai

### sharing work in progress

* localtunnel, ngrok, Surge, now

* localtunnel
    * `npm install localtunnel -g
    * start the app
    * It --port 3000
* ngrok
    * same as localtunnel
    * signup , instal ngrok, install authtoken, start your app,
    * ./ngrok http 80
* now - it publishing files to 
    * npm install  -g now
    * start script
    * now

* Surge
   * assumes app is static files
   * publishes static files to their server
   * npm install -g surge
   * surge

## Automation

* Grunt, Gulp, npm Scripts

### Grunt
 * original
 * configuration over code
 * file orientied, writes intermediary files between steps
 * Large plugin ecosystem.

![gulp](https://gulpjs.com/img/gulp-white-text.svg)
### Gulp
* In-memory streams
* avoids writing to files, Fast
* code over configuration
* Large plugin ecosystem


### npm Scripts
* Declared in package.json
* Leverage your OS' command Line
* Directly use npm packages
* Call seperate Node Scrips
* Convention-based pre/post hooks
* Leverage world's largest package manaeger.
* no need for seperate plugins
* simpler debugging
* better docs

`npm-run-all`

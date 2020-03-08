<p align="center">
  <img src="https://raw.githubusercontent.com/lord/img/master/logo-slate.png" alt="Slate: API Documentation Generator" width="226">
  <br>
  <a href="https://travis-ci.com/slatedocs/slate"><img src="https://travis-ci.com/slatedocs/slate.svg?branch=master" alt="Build Status"></a>
</p>

<p align="center">Slate helps you create beautiful, intelligent, responsive API documentation.</p>

<p align="center"><img src="https://raw.githubusercontent.com/lord/img/master/screenshot-slate.png" width=700 alt="Screenshot of Example Documentation created with Slate"></p>

# Site for install-rails-mac.com

The site is built with <a href="https://slatedocs.github.io/slate">Slate</a>.

## Prerequisites

You're going to need:

 - **Linux or macOS**
 - **Ruby, version 2.3.1 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

## Set Up

1. Clone this repo to your hard drive with `git clone https://github.com/RailsApps/install-rails-mac`
2. `cd install-rails-mac`
3. Initialize and start Slate:

```shell
# either run this to run locally
bundle install
bundle exec middleman server
```

You can now see the site at http://localhost:4567.

Edit the file *source/index.html.md* to revise content.

Edit the file *source/layouts/layout.erb* to change the layout.

## Deploy

The site is deployed at Netlify (Slate typically deploys to GitHub pages.) Pushing to the master branch should trigger an automatic deploy.



Laptop
======

Laptop is a script to set up a Mac OS X laptop for web development.

**This is a customised version!** See [original repo](https://github.com/thoughtbot/laptop) for the vanilla version.

Requirements
------------

1) Install a C compiler.

Use [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) for
Snow Leopard (OS X 10.6).

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action)
for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

2) Set zsh as your login shell.

    chsh -s /bin/zsh

Install
-------

Run the script:

    zsh <(curl -s https://raw.github.com/askalot/laptop/master/mac)

What it sets up
---------------

* Bundler gem for managing Ruby libraries
* Exuberant Ctags for indexing files for vim tab completion
* Foreman gem for serving Rails apps locally
* Heroku Config plugin for local `ENV` variables
* Heroku Toolbelt for interacting with the Heroku API
* Hub gem for interacting with the GitHub API
* Homebrew for managing operating system libraries
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Rbenv for managing versions of the Ruby programming language
* SQLite for test data
* Sinatra for quick prototyping
* DataMapper and relevant adapters for Sinatra
* Ruby Build for installing Rubies
* Ruby stable for writing general-purpose code
* SSH public key for authenticating with Github and Heroku
* The Silver Searcher for finding things in files
* Tmux for saving project state and switching between projects
* Watch for periodically executing a program and displaying the output

It should take less than 15 minutes to install (depends on your machine).

Credits
-------

![thoughtbot](http://thoughtbot.com/assets/tm/logo.png)

Laptop is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community).
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Thank you, [contributors](/thoughtbot/laptop/graphs/contributors)!

License
-------

Laptop is © 2011-2013 thoughtbot, inc. It is free software, and may be
redistributed under the terms specified in the LICENSE file.

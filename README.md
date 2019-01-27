# Laptop
Shell script to set up a macOS laptop for web development. Inspired from [thoughtbot/laptop](https://github.com/thoughtbot/laptop).

# Install
Download and execute the script:

```sh
sh mac 2>&1 | tee ~/laptop.log
```

# What it sets up
### macOS Tools
* [Homebrew](http://brew.sh/) for managing operating system libraries.

### UNIX Tools
* [Git](https://git-scm.com/) for version control
* [OpenSSL](https://www.openssl.org/) for Transport Layer Security (TLS)
* [Tmux](http://tmux.github.io/) for saving project state and switching between projects
* [Java](https://www.java.com/en/download/) for application dependencies and programming

### Heroku CLI
* [Heroku](https://devcenter.heroku.com/articles/heroku-cli) for interacting with Heroku API

### Image manipulation
* [ImageMagick](http://www.imagemagick.org/) for cropping and resizing images

### Testing
* [Qt5](http://doc.qt.io/qt-5/qt5-intro.html) for Capybara testing

### Programming language prerequisites and package managers
* [LibYAML](https://pyyaml.org/wiki/LibYAML) for YAML parsing
* [CoreUtils](https://www.gnu.org/software/coreutils/), GNU core utilities
* [Yarn](https://yarnpkg.com/en/) for managing JavaScript packages
* [GPG Tools](https://gpgtools.org/) for enctryption
* [RVM](https://rvm.io/) for managing different version of Ruby

### Databases and storage
* MySQL
* [Postgres](http://www.postgresql.org/) for storing relational data
* [Redis](http://redis.io/) for storing key-value data

### Searching/Indexing
* [ElasticSearch](https://www.elastic.co/products/elasticsearch) for full-text search

### Applications for communication, browsing, development and collaboration
* [Slack](https://slack.com/downloads/mac) for communication
* [Skype](https://www.skype.com/en/get-skype/) for communication
* [Google Chrome](https://www.google.com/chrome/) for faster browsing
* [iTerm2](https://www.iterm2.com/) for advanced features in terminal for development
* [Textmate](https://macromates.com/) texteditor for development
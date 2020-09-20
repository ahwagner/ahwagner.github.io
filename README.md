# ahwagner.github.io
Personal Website (alexwagner.info)

## Installation

To install this site locally run the following commands:

1. Clone the repo and cd into it `$ git clone git@github.com:ahwagner/ahwagner.github.io.git`
2. Install the bundler `$ gem install bundler`
3. Install gems `$ bundle install`
4. run jekyll and watch for changes `$ bundle exec jekyll serve --config _config.yml,_config_dev.yml --watch`

The site should now be running on localhost port 4000. 
Changes to files will show up interactively on localhost:4000

**Note:** The _config.yml file is only read during the initial serve, 
changing this file will require re-running step 4 for changes to appear.

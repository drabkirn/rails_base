<div align="center">
  <img src="https://github.com/drabkirn/quotes/raw/master/drabkirn-logo-120x120.png"/>
</div>

# Drabkirn Rails Base

> This repository serves as a base repository for new projects in rails that we build at Drabkirn

<!-- Add languages, CI/CD, main frameworks used from shields.io. Example -->
[![Ruby 2.6.5](https://img.shields.io/badge/Ruby-v2.6.5-green.svg)](https://www.ruby-lang.org/en/)
[![Rails 6.0.2](https://img.shields.io/badge/Rails-v6.0.0-brightgreen.svg)](https://rubyonrails.org/)
[![Rspec 3.9](https://img.shields.io/badge/RSpec-v3.9-red.svg)](http://rspec.info/)
[![Issues](https://img.shields.io/github/issues/drabkirn/quotes.svg)](https://github.com/drabkirn/quotes/issues)
[![Issues closed](https://img.shields.io/github/issues-closed/drabkirn/quotes.svg)](https://github.com/drabkirn/quotes/issues)
[![Pulls](https://img.shields.io/github/issues-pr/drabkirn/quotes.svg)](https://github.com/drabkirn/quotes/pulls)
[![Pulls](https://img.shields.io/github/issues-pr-closed/drabkirn/quotes.svg)](https://github.com/drabkirn/quotes/pulls)
[![License](https://img.shields.io/github/license/drabkirn/quotes.svg)](https://choosealicense.com/licenses/agpl-3.0/)

<!-- TODO: Full Description of Project goes here -->

<!-- TODO: Demo or website here -->
<!-- **[Visit Website here](https://go.brinkirn.xyz/go)** -->

-----
-----

## Table of Contents
- [Steps](#steps)
- [Installation](#installation)
- [Contributing](#contributing)
- [Connect](#connect)

-----
-----

## Steps
1. Basic Setup:
    - New Rails Application:
      ```bash
      $ rails new bare_rails -d mysql
      ```
    - Adding the `.github` folder for Issues and Pull request templates.
    - Adding the License, Code of conduct and contributing guidelines.
    - Updating the `README.md` for basic steps and README updates along the way.
    - Cleaning the `Gemfile`, update it and then run:
      ```bash
      $ bundle i
      ```
    - Added `badges` to the `README` file.

2. Adding Testing support:
    - Added latest versions of `brakeman`, `bundler-audit`, `database_cleaner`, `simplecov`, `shoulda-matchers`, `rails-controller-testing`, `rspec-rails`, `factory_bot_rails`, `faker`. Then run:
      ```bash
      $ bundle i
      ```
    - Install Rspec:
      ```bash
      $ rails g rspec:install
      ```
    - Add `--format documentation` to `.rspec`
    - Rails generators - Not to run helpers generators in `rails g` command. See comment `Don't run un-required generations of files` in `config/application.rb` and uncomment required stuff as required.
    - In `spec/rails_helper.rb` - Added Simplecov, database cleaner, shoulda-matchers and FactoryBot:
      ```rb
      # Simple Cov
      ...

      # DB Cleaner
      ...

      # Shoulda Matchers
      ...

      # Include Factory Girl syntax to simplify calls to factories
      ...
      ```

3. Environment variables and Database support:
    - Added the `figaro` gem and installed it with:
      ```bash
      $ bundle exec figaro install
      ```
    - Setting up the `config/application-sample.yml` with initial data.
    - Rewriting `config/database.yml` file to use config variables from figaro env variables.

-----
-----

## Installation

-----
-----

## Contributing
If you would like to contribute, please check [this contributing guide](https://github.com/drabkirn/quotes/blob/master/CONTRIBUTING.md)

Please check [this Code of Conduct guide](https://github.com/drabkirn/quotes/blob/master/CODE_OF_CONDUCT.md) before contributing or having any kind of discussion(issues, pull requests etc.) with the Bare Rails project!

-----

## Connect:
Need any help? Have any Questions? Or just say us hi!
<!-- TODO: Add Social Links, Blogs, Websites and Support -->
# The-pizza-project

The main purpose of this repository is to show a simple Ruby on Rails web application that integrates with the Trello Api [see docs](https://developers.trello.com/docs/get-started) to extend task planning functionality such Populating your `To do`, `Doing` and `Done` Tasks as well as moving Tasks between them. The web appication also includes an endpoint for receiving webhook event from Trello.

# Getting Started

- Add a `.env` to the root of the project so that that the application can get environment variables from there
- Configure the webhook hosts in the `config` base on your environment. for example; for `dev` simply add `config.hosts << "4f53-533-5r3-265.ngrok.io"` to your `config/development.rb`

## Environment vars

This project uses the following environment variables are kept in and `.env` file in application root

| Name           | Description                                                                                                            | Default Value |
| -------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------- |
| CORS           | Cors accepted values                                                                                                   | "\*"          |
| MEMBER_TOKEN   | This can be gotten from Trello using your Public key                                                                   |               |
| PUBLIC_KEY     | This is the API key for making API calls to Trello Endpoints                                                           |               |
| BOARD_ID       | The Trello Board that houses all the Lists, Cards and Action used for the pizza project                                |               |
| WEBHOOK_CB_URL | The base Url for reaching the endpoint that handles webhook events from Trello e.g `https://35tf-g5w-33t-555.ngrok.io` |               |

### Prerequisites

The setups steps expect following tools installed on the system.

- Ruby [3.0.4](https://github.com/organization/project-name/blob/master/.ruby-version#L1)
- Rails [7.0.4](https://github.com/organization/project-name/blob/master/Gemfile#L12)

```ruby
gem install bundler -v 2.2.33
```

##### 4. Start the Rails server

You can start the rails server using the command given below.

# Installations

### List Ruby versions available

rbenv install --list

### Make sure you are using the desired Ruby version to install.

ruby --version

### Install Ruby 3.0.4

rbenv install 3.0.4

### Bundler

#### To see if you already have Bundler installed

bundler --version

#### This will install the bundler gem in Ruby 3.0.4

gem install bundler -v 2.2.33

#### install all packages

```ruby
bundle install

```

#### Install Yarn

brew install yarn

### Install JavaScript packages

yarn

## Run the Rails server

```ruby
bundle exec rails s
```

Once the server is running, navigate to http://localhost:3000

# Common Issues

##

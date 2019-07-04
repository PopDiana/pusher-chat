# pusher-chat

A chat app built using Ruby on Rails and Pusher Channels, following this [tutorial.](https://pusher.com/tutorials/chat-app-ruby-rails)

## Getting started

### Change directory

`$ cd pusher-chat`

### Install dependencies

`$ bundle install`

### Database setup

```
$ rails db:setup
$ rails db:migrate
```
----------

`$ figaro install`

In *config/application.yml* modify the following with your access keys:

```
PUSHER_APP_ID: 'xxxxxx'
PUSHER_KEY: 'xxxxxxxxxxxxxxxxxxx'
PUSHER_SECRET: 'xxxxxxxxxxxxxxxxxxx'
PUSHER_CLUSTER: 'xx'
```

### Built with

- [PostgreSQL](https://www.postgresql.org/download/)
- [Ruby](https://www.ruby-lang.org/en/downloads/)
- [Rails](https://guides.rubyonrails.org/getting_started.html)
- [Pusher](https://pusher.com) - a Ruby gem to interact with the Pusher REST API

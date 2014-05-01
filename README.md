## Rafflr is a highly sophisticated, online version of eeny, meeny, miny, moe.

### Overview

Rafflr is a simple app that helps you run raffles during ruby meetups or other events. Just enter a list of names, select the number of winners, and then start your raffle.

Rafflr will randomly remove names, one by one, until only the winners are left. Rafflr also plays the theme from Jeopardy as it counts down to the winning names -- which makes your raffle all the more fun!

### How to Install

- git clone git://github.com/sdruby/rafflr.git
- bundle install
- bundle exec rake db:create db:migrate
- launch app (script/server)

Note: this app is only compatible with Ruby 1.8.7.

### How to Use

1. Make a list of raffle names.
2. Open the app.
3. Enter your raffle title, list of names, and number of winners.
4. Start the raffle when you are ready.
5. Enjoy!
# Jurge

Simple way to get your [Jekyll](https://jekyllrb.com/) website on [surge.sh](https://surge.sh/).

## Setup

Create an ``.env``, and add your own settings.

    DOMAIN=coolsite.surge.sh

### Install

    npm install

### Slack

Want to notify your team? 👫 Add an Incoming WebHook to the channel you want to notify.

Add this to your `.env`

    SLACKURL=https://hooks.slack.com/services/XXXXXXXXXXXXXXXXXXX
    SLACKTEXT: 'Deployed http://mycoolsite.surge.sh!',
    SLACKCHANNEL: '#general',
    SLACKUSERNAME: 'Deployment',
    SLACKICONEMOJI: ':taco:',

### Surge

Surge is very simple to get started with. [Read more](https://surge.sh/tour)

    npm install --g surge

## Deploy

    gulp deploy

Your site now lives at your domain and your Slack-team has been notified!

![](https://dl.dropboxusercontent.com/u/1162759/dump_2016-02-06_11-55-28.png)

## Demo

[jurge.surge.sh](http://jurge.surge.sh)
# Namnsdagsbot
[![CircleCI](https://circleci.com/gh/jimmystridh/namnsdagsbot-slack.svg?style=svg)](https://circleci.com/gh/jimmystridh/namnsdagsbot-slack)

Announces name days in a slack channel

#How to start
* Clone the repo
* copy .env.sample and namnsdagar.sample.json to .env and namnsdagar.json and edit
* docker build . -t namnsdagar-slack
* docker run --restart=always -d namnsdagar-slack

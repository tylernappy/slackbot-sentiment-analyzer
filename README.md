# Slackbot using Haven OnDemand Sentiment Analysis and Botkit
A simple example to show how to incorporate Haven OnDemand into a Slackbot.

## What this does
Prompt the Slackbot in the slack channel with a sentence and it will analyze the sentiment of it.

![workflow](./img/workflow.png)

## To download
In your terminal:
```
git clone https://github.com/HPE-Haven-OnDemand/slackbot-sentiment-analyzer
```
```
cd slackbot-sentiment-analyzer
```
```
npm install
```
Open up the `index.js` file and replace where it says `process.env.HOD_APIKEY` with your Haven OnDemand API key (found [here](https://www.havenondemand.com/account/api-keys.html)) and `process.env.SLACK_TOKEN` with your Slack token (sign up [here](https://my.slack.com/services/new/bot) to find it and to also name and configure the bot on Slack)

Run to start:
```
node index.js
```

## Technology used
* [Haven OnDemand](http://havenondemand.com/)
* [Slackbots](https://github.com/howdyai/botkit/blob/master/readme-slack.md)
* [Node.js](https://nodejs.org/en/)
* [Botkit](https://howdy.ai/botkit/)

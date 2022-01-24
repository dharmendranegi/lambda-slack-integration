# Slack Notification via AWS Lambda

## Purpose

Send notification to your Slack channel.

## Steps

### Create Slack Webhook Url

See [Documentation](https://slack.com/intl/en-in/help/articles/115005265063-Incoming-webhooks-for-Slack)!

### Install

```bash
npm install

```

### Update serverless.yml file in plugins section

```yaml
environment:
  SLACK_WEBHOOK_URL: #Your Slack Webhook Url
  SLACK_CHANNEL_NAME: #Your Slack channel name for notifications
```

### Deploy to Aws account

```
sls deploy
```

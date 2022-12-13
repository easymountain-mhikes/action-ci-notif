# PR Slack notification

Github Action to send a Slack Notification related to a PR.

## Usage

```yaml
- name: Slack Notification
  uses: easymountain-mhikes/action-ci-notif@v1
  with:
    slack-pr-incoming-webhook: ${{ secrets.YOUR_SLACK_INCOMING_WEBHOOK }}
```

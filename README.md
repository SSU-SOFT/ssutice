# slack_bot
Slack bot codes

# Features
- _Crawler_: Crawling notices on sites of ssu, sw.
- _Poster_: Post to slack by webhook url.

# Usage
If you want to use crawler of ssu notice, use following steps.
### Step 1. Register your webhook url.
- Generate webhook url (channel or DM)

    `https://api.slack.com/apps/<Workspace ID>/incoming-webhooks?`

\* (Be careful for security) _WorkSpace ID_ and _Webhook urls_ are each unique string, **DO NOT UPLOAD TO GIT**.

-  Manage to webhooks dicts: run webhook.py
-  Use add feature.
```
python3 webhook.py
```

### Step 2. Run Main
```
python3 main.py
```

## Post
You can post some contents to slack by using one function.

Then use `post_to_slack(message, webhook_url)` in /bot/post.py

# Issue
Creates **Github issue** or contacts to **gigacms@gmail.com**

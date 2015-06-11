# CLI Slack client
===

Tu run the container you need to get a Token from https://api.slack.com/ and grab it somewhere (ex: ~/.slack_token), then run the following command and enjoy :) 

```
docker run -v ~/.slack_token:/home/slacker/.slack_token -ti mustela/slacker
```


This is an awesome work from: https://github.com/TidalLabs/Slacker
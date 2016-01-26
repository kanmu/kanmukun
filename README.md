# KanmuKun

[![Build Status][travis-image]][travis-url]
[![Dependency Status][daviddm-image]][daviddm-url]
[![DevDependency Status][daviddm-dev-image]][daviddm-dev-url]

A bot for Kanmu, Inc.

## Configuraiton

```
# for hubot-5rolli
HUBOT_5ROLLI_PROJECTS         <PROJECT_JSON_STRING>
HUBOT_5ROLLI_TRELLO_API_KEY   <TRELLO_API_KEY>
HUBOT_5ROLLI_TRELLO_API_TOKEN <TRELLO_API_TOKEN>

# for hubot-github-contribution-stats
HUBOT_GITHUB_CONTRIBUTION_STATS_GYAZO_TOKEN <GYAZO_API_TOKEN>

# for hubot-google-images
HUBOT_GOOGLE_CSE_ID          <CSE_ID>
HUBOT_GOOGLE_CSE_KEY         <CSE_API_KEY>
HUBOT_GOOGLE_SAFE_SEARCH     off

# for hubot-hipchat
HUBOT_HIPCHAT_JID:           <KANMUKUN_JID>@chat.hipchat.com
HUBOT_HIPCHAT_PASSWORD:      <KANMUKUN_PASSWORD>
HUBOT_HIPCHAT_TOKEN:         <HIPCHAT_TOKEN>

# for hubot-hipchat-emoticons
HUBOT_HIPCHAT_AUTH_TOKEN:    <HIPCHAT_TOKEN>

# for hubot-jvn
HUBOT_JVN_CRON_MESSAGE:      @all
＿人人人人人人人人＿
＞　新しい脆弱性　＜
￣Y^Y^Y^Y^Y^Y^Y￣
HUBOT_JVN_ROOM:              <システム部屋>@conf.hipchat.com

# for hubot-kanjo
HUBOT_KANJO_AWS_ACCOUNT_ID    <AWS_ACCOUNT_ID_FOR_BILLING>
HUBOT_KANJO_AWS_ACCESS_KEY_ID <AWS_ACCESS_KEY_ID_FOR_BILLING>
HUBOT_KANJO_AWS_BUCKET_NAME   <S3_BUCKET_NAME_FOR_BILLING>
HUBOT_KANJO_AWS_REGION        <S3_REGION_NAME>
HUBOT_KANJO_AWS_SECRET_KEY    <AWS_SECRET_KEY_FOR_BILLING>

# for hubot-nullpo
HUBOT_NULLPO_RESPONSE_STYLE: rich

# for hubot-regex-response
HUBOT_REGEX_RESPONSE_CONFIGS  '[{"from":"Contributions:(?:.+)\nLongest Streak:(?:.+)\nCurrent Streak:(?:.+)\n(https://[\\S]+)","to":"<%= m[1] %>"}]'

# for hubot-shuzo
HUBOT_SHUZO_WORDS:           (無理|むり|ムリ)|(でき|出来)(ない|ません|ん|っこない)|(でき|出来)る気が?(しない|しません|せん)

# for hubot-tabelog
HUBOT_TABELOG_PROXY:         http://<PROXY_HOST>:<PROXY_PORT>

# for hubot-url
HUBOT_URL_IGNORE_PATTERNS:   ["github.com", "youtube.com", "twitter.com"]

# for hubot-youtube
HUBOT_YOUTUBE_API_KEY        <API_KEY>
```


[travis-url]: https://travis-ci.org/kanmu/kanmukun
[travis-image]: https://img.shields.io/travis/kanmu/kanmukun.svg?style=flat-square
[daviddm-url]: https://david-dm.org/kanmu/kanmukun
[daviddm-image]: https://img.shields.io/david/kanmu/kanmukun.svg?style=flat-square
[daviddm-dev-url]: https://david-dm.org/kanmu/kanmukun#info=devDependencies
[daviddm-dev-image]: https://img.shields.io/david/dev/kanmu/kanmukun.svg?style=flat-square

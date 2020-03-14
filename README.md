# prepare
- `vim docker-compose.yml`
  - add your slack token in Line.4
  ```
  HUBOT_SLACK_TOKEN={**PUT_YOUR_SLACK_TOKEN_HERE**}
  ```
 - default posting channels (edit below if you need)
   - SLACK_TIMELINE_CHANNEL=timeline
   - SLACK_TIMELINE_RANKING_CHANNEL=general

# run
- `docker-compose up`
  - add `-d` option to run background.
  - maybe occur below error. don't get panic.

# troubleshoot
- `gpgkeys: key XXXXXXX can't be retrieved` error
  - just retry many times.
    - it's gpg key server's fault. see details in https://seesaawiki.jp/w/kou1okada/d/20181130%3A%20%C9%D4%B0%C2%C4%EA%A4%CA%20GnuPG

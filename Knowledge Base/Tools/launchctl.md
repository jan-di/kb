https://davidhamann.de/2018/03/13/setting-up-a-launchagent-macos-cron/

```shell
launchctl bootstrap gui/501 /Users/jdittrich/Library/LaunchAgents/com.github.schlakob.toggl-jira-sync.plist

launchctl kickstart -k gui/501/com.github.schlakob.toggl-jira-sync

launchctl bootout gui/501 /Users/jdittrich/Library/LaunchAgents/com.github.schlakob.toggl-jira-sync.plist
```
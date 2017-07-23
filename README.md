# mainstruct

`mainstruct` parses out the main structural components ("sections") of rendered manpages and writes them to stout for comparison.

1. `ls -1 /bin /usr/bin /usr/sbin > res/man_commands`
2. `./mainstruct`

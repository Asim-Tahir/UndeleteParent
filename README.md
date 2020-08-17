# UndeleteParent
Reddit bot (Python) to "undelete" Reddit comments and submissions

### What this bot does
This bot "undeletes" deleted comments and posts on Reddit. If the comment is in a subreddit in which the bot is banned OR if the comment was removed by moderators, the bot will send a PM instead of replying to the comment.

### How to use
Add file under "textFiles/secrets.txt" containing 5 lines. The lines must be in order: 1) client_id 2) client_secret 3) username 4) password 5) user_agent

To call the bot, mention the username in a reply to the comment's child you want undeleted. You must reply to the child because you cannot reply directly to a deleted comment.

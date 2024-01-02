# Use the following regex patterns in your server's safety setup to prevent people from typing RIT emails into chat:
```re
^.{6}@rit\.edu$
^.{7}@rit\.edu$
^.{6}@g.rit\.edu$
^.{7}@g.rit\.edu$
```
*(This isn't foolproof, but it makes it harder.)*

![Regex pasted into Discord automod](https://cdn.discordapp.com/attachments/1107483500384358510/1191672062415224862/image.png)
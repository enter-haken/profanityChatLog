profanityChatLog
================

The goal of the `profanityChatLog` project is to show the last recent chat log for a given user und chat partner.

See the [profanity documentation](http://www.profanity.im/reference.html#chlog) for activating the chat log.

### Parameter


```
usage: profanityChatLog [-h] -u USER [-c CHATUSER] [-L]

show the last chat log file for given user und chat user

optional arguments:
  -h, --help            show this help message and exit
  -u USER, --user USER  choose xmpp user. name part is sufficient.
  -c CHATUSER, --chatUser CHATUSER
                        choose xmpp user for chat log. name part is
                        sufficient.
  -L, --listChatUsers   list all chat users having a chat log
```

### Example

Show a list of all stored chatlogs for user *hake*


```bash
profanityChatLog -u hake -L
```

Show last recent chatlog for user *hake* with chat partner *friend*

```bash
profanityChatLog -u hake -c friend
```

### Contact

Jan Frederik Hake, <jan_hake@gmx.de>. [@enter\_haken](https://twitter.com/enter_haken) on Twitter.

# dunst mail notification

Usage:
```sh
% mail-dunst 'user@domain.com' 'password' 'IMAP SSL server'
```
If box has not been polled before It will assume all messages in INBOX have been read. 
Otherwise it will notify each mail received since last execution.

### Deps
- Python 2
- dunst http://knopwob.org/dunst/

To use with GMail, enable less secure apps: https://www.google.com/settings/security/lesssecureapps

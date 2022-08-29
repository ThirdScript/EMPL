# EMPL
pipe terminal commands output into emacs directly

[![asciicast](https://asciinema.org/a/GwkYlcCgZNlO5DCH7rlcOYX7r.svg)](https://asciinema.org/a/GwkYlcCgZNlO5DCH7rlcOYX7r?speed=1.5)

### Install
add this line to your *.bashrc* or *.zshrc* ...
```shell
# EMPL Command
alias empl='cat - > /tmp/emc_buffer ; emacs -nw /tmp/emc_buffer'
```

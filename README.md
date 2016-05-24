A shameless fork of ZSH PeepCode theme.
One-liner and clean.

Features:
- ❯ for normal user
- ❯❯ for root/elevated-privileges-shell
- red ❯ if previous command failed
- current dir + git in RPROMPT (ommited if long command)

Install:

```
$ git clone https://github.com/fallc0nn/peppercode /tmp/peppercode
$ mkdir -p $HOME/.zprezto/modules/prompt/external/peppercode
$ cp /tmp/peppercode/prompt_peppercode_setup $HOME/.zprezto/modules/prompt/external
$ ln -s $HOME/.zprezto/modules/prompt/external/peppercode/prompt_peppercode_setup $HOME/.zprezto/modules/prompt/functions/prompt_peppercode_setup
```

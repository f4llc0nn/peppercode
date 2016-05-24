A shameless fork of ZSH PeepCode theme.
One-liner and clean.

Features:
- ❯ for normal user
- ❯❯ for root/elevated-privileges-shell
- red ❯ (or ❯❯) if previous command failed
- current dir + git in RPROMPT (auto-ommited if command is long)

Install:

```
$ git clone https://github.com/fallc0nn/peppercode /tmp/peppercode
$ cp -R /tmp/peppercode/peppercode $HOME/.zprezto/modules/prompt/external
$ ln -s $HOME/.zprezto/modules/prompt/external/peppercode/prompt_peppercode_setup $HOME/.zprezto/modules/prompt/functions/prompt_peppercode_setup
```

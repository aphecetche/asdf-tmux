# asdf-tmux [![Build Status](https://travis-ci.org/aphecetche/asdf-tmux.svg?branch=master)](https://travis-ci.org/aphecetche/asdf-tmux)

[tmux](https://github.com/tmux/tmux) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add tmux https://github.com/aphecetche/asdf-tmux.git
asdf install tmux <version>
```

On MacOS it may be necessary to set a configuration option before installing.
`export TMUX_CONFIGURE_OPTIONS="--enable-utf8proc"`
(see: https://github.com/tmux/tmux/wiki/Installing#configure-says-must-give---enable-utf8proc-or---disable-utf8proc)

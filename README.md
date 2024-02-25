# Suckless Tmux config

A suckless, minimalstic Tmux config with Vim key bindings.

## Rationale

There are countless tmux config all over the internet. However, most of
them are bloated, use plugins and difficult to deploy to servers.

Suckless Tmux config is created based on the **Less is more** principle with 
the objective of simplicity and usability. It's flavored with Vim key bindings
and designed to be understanable, small, and easily deployable to any server without 
any plugins or voodoo work, while being aesthetically pleasing. 

## Screenshot

![Preview](https://github.com/kasramp/suckless-tmux-config/blob/master/screenshot/screenshot.png)

## How to install

Since everything is in a single file, installation process is super simple with
a single CURL command,

```bash
curl -sL https://raw.githubusercontent.com/kasramp/suckless-tmux-config/master/.tmux.conf --output ~/.tmux.conf
```

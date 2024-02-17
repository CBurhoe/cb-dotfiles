# cb-dotfiles
Dotfiles experimentation. Probably won't be very interesting.

Setup info:






SSH
---

`wget https://gitlab.com/kyb/fish_ssh_agent/raw/master/functions/fish_ssh_agent.fish -P ~/.config/fish/functions/`

- Adds fish_ssh_agent, useful for using ssh-agent in fish

`~/.config/fish/config.fish << "fish_ssh_agent"`
- autostarts fish_ssh_agent

`~/.ssh/config << "AddKeysToAgent yes"

Then can use `ssh-add [path to key]` to add private key.



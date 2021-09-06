# Environment
- Tmux 3.0
- Ubuntu 20.04

# Tmux-config-windows
Tmux config for coming from windows terminal
This configuration is for people who used windows terminal in Windows and started to use Tmux like me...

Since all of the shortcuts in Tmux are different in Tmux.

# How to use it
```git clone https://github.com/JunseongAHN/Tmux-config-windows.git```
```cp tmux.config ~/.tmux.config```
```tmux source ~/.tmux.config```

# basic features
- copy: ```ctrl+shift+c```
- paste: ```ctrl+shift+v```
- list all the windows in the session: ```ctrl+b+w```
- mouse wheel enable
- changed background color and border color 



# Implemented
- windows Terminal switch panels ```alt+arrow_key``` 
- windows Terminal resize panels ```alt+shift+arrow_key```

# Different from windows terminal
- New terminal ```ctrl+shift+1,2,3...``` -> ```ctrl+b+shift+1,2,3...```
- Remove panels ```alt+shift+w``` -> ```ctrl+d```

# Acknowledgement
This config file is based on a config file from samoshkin. for more information, please check https://github.com/samoshkin/tmux-config

# Issue/Pull Requests
Please publish issues if some of features doesn't work, or if you want to add features, feel free to PR.

# TODO
- more considerable README...

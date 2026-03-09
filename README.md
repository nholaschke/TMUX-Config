## About
This configuration tries to keep as minimal as possible while simultaneously configuring tmux to look "nice".
No addditional packages beyond the tmux package itself are needed for this config to work, just simply 


## Init commands

Download the tmux package

`touch ~/.config/tmux/tmux.conf`
Create the tmux.conf file

Copy paste my config into the created file.

`tmux source ~/.config/tmux/tmux.conf`
Reloads the tmux.conf. Path can be wherever you choose.

`tmux`
Start tmux.

You're good to go!


## Often used commands

`tmux new -s <name>`
Creates new session, -s stands for session

`tmux ls`
Lists all running sessions

`tmux a`
Reattaches to the last attached session

`tmux a -t <sessionname>`
Connects to the target session

`tmux kill-session -t <name>`
Kill target session

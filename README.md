# common-sh

.tmux.conf
```
# remap prefix to Control + a
#set -g prefix C-a
#unbind C-b
#bind C-a send-prefix
unbind C-b
set -g prefix C-a
bind C-a send-prefix
# force a reload of the config file
#unbind r
#bind r source-file ~/.tmux.conf

#set -g mouse on
# quick pane cycling
#unbind ^A
#bind ^A select-pane -t :.+

#bind ctrl tab as cycle window. pass -n so no prefix needed
#bind-key -n C-Tab next-window
#bind-key -n C-S-Tab previous-window

#urxvt tab like window switching (-n: no prior escape seq)
#bind -n S-down new-window
#bind -n S-left prev
#bind -n S-right next
#bind -n C-left swap-window -t -1
#bind -n C-right swap-window -t +1

bind -n S-Up    select-pane -U
bind -n S-Down  select-pane -D
bind -n S-Left  select-pane -L
bind -n S-Right select-pane -R
```

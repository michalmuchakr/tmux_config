#-------------------------------------------------------#
# Mouse configuration
#-------------------------------------------------------#
set -g mode-mouse on
set -g mouse-select-window on
set -g mouse-select-pane on

#-------------------------------------------------------#
#Pane colours
#-------------------------------------------------------#
# set inactive/active window styles
set -g window-style 'fg=colour247,bg=colour236'
set -g window-active-style 'fg=colour250,bg=black'
 
#pane border
set -g pane-border-bg colour235
set -g pane-border-fg colour238
set -g pane-active-border-bg colour236
set -g pane-active-border-fg colour51

set -g status-bg black
set -g status-fg white
set -g window-status-current-bg white
set -g window-status-current-fg black
set -g window-status-current-attr bold

set -g status-interval 60
set -g status-left-length 30
set -g status-left '#[fg=green](#S) #(whoami)'
set -g status-right '#[fg=yellow]#(cut -d " " -f 1-3 /proc/loadavg)#[default] #[fg=white]%H:%M#[default]'

# set Alt-arrow keys WITHOUT PREFIX KEY to switch panes
bind -n M-Left select-pane -L
bind -n M-Right select-pane -R


# TMUX CHEATSHEET

### Sessions
|  CMD|ACTION  |
|--|--|
| tmux | Start new session |
| tmux new -s [name] | Start new session with name |
| tmux a # | Start an attached session |
| tmux a -t [name] | Attach a named session |
| tmux ls | List all tmux sessions |
| exit | Exit |
| tmux kill-session -t [name] | Kill a session |

### Prefix: \<Ctrl-a\>


### Window  Handling
| CMD | ACTION |
|--|--|
| \<C-a>+c | New window |
| \<C-a>+n | Next window |
| \<C-a>+p | Previous window |
| \<C-a>+w | List all windows |
| \<C-a>+, | Rename a window |
| \<C-a>+f | Find a window |
| \<C-a>+& | Kill a window |

### Pane Handling
| CMD | ACTION |
|--|--|
| \<C-a>+\- | Split pane horizontally |
| \<C-a>+\`&#124;` | Split pane vertically (that's a pipe) |
|  \<C-a>+; | Toggle last active pane |
| \<C-a>+o | Swap panes |
| \<C-a>+x | Kill pane |
| \<C-a>+q | Show pane numbers |
| \<C-a>+{ | Move pane left |
| \<C-a>+} | Move pane right |
| \<C-a>+arrow key (one shot)| Switch between panes |
| \<C-a>+arrow key (continuous) | Resize pane |

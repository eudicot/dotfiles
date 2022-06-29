# TMUX CHEATSHEET

## Prefix: \<Ctrl-a\>

## Sessions
|  CMD|ACTION  |
|--|--|
| tmux | Start new session |
| tmux new -s [name] | Start new session with name |
| tmux a # | Start an attached session |
| tmux a -t [name] | Attach a named session |
| tmux ls | List all tmux sessions |
| exit | Exit |
| tmux kill-session -t [name] | Kill a session |
| | |
| \<C-a> + d | Detach session |
| \<C-a> + ( | Previous session |
| \<C-a> + ) | Next session |
| \<C-a> + L | Last (previously used) session |
| \<C-a> + s | Choose session from a list |
| \<C-a> + $ | Rename current session |

## Window  Handling
| CMD | ACTION |
|--|--|
| \<C-a> + c | New window |
| \<C-a> + n | Next window |
| \<C-a> + p | Previous window |
| \<C-a> + l | Last (previously used) window |
| \<C-a> + w | List all windows |
| \<C-a> + , | Rename a window |
| \<C-a> + f | Find a window |
| \<C-a> + & | Kill a window |
| | |
| \<C-a> + \<M-n> | Next window w/ a bell, activity, context alert |
| \<C-a> + \<M-p> | Previous such window |

## Pane Handling
| CMD | ACTION |
|--|--|
| \<C-a> + \- | Split pane horizontally |
| \<C-a> + \`&#124;` | Split pane vertically (that's a pipe) |
|  \<C-a> + ; | Toggle last active pane |
| \<C-a> + o | Swap panes |
| \<C-a> + x | Kill pane |
| \<C-a> + q | Show pane numbers |
| \<C-a> + arrow key (one shot)| Switch between panes |
| \<C-a> + arrow key (continuous) | Resize pane |

### Moving panes around
| CMD | ACTION |
|--|--|
| \<C-a> + { | Move pane left |
| \<C-a> + } | Move pane right |
| \<C-a> + \<C-o> | Rotate window 'up' (moves all panes) |
| \<C-a> + \<M-o> | Rotate window 'down' |
| \<C-a> + ! | Move current pane into new separate window ('break pane') |
| \<C-a> :move-pane -t :3.2 | Split window 3's pane 2, move the current pane there |

### Predefined layouts
| CMD | ACTION |
|--|--|
| \<C-a> + \<M-1> | Switch to even-horizontal layout |
| \<C-a> + \<M-2> | Switch to even-vertical layout |
| \<C-a> + \<M-3> | Switch to main-horizontal layout |
| \<C-a> + \<M-4> | Switch to main-vertical layout |
| \<C-a> + \<M-5> | Switch to tiled layout | 
| \<C-a> + space | Cycle through predefined layouts | 

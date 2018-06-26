# Tmux Cheat Sheet

## Sessions
### Create a new Session
```bash
tmux new -s [session_name]
```

### Leave a Session (detach)
[ctrl]+[b] [d]

### List all Sessions
```bash
tmux ls
```

### Connect to an Existing Session (attach)
```bash
tmux attach -t [session_name]
```

# ***新建会话的一些命令***





|     命令说明 |                                                       命令 |
| ---------------:| -------------------------------------------------------------:|
|        接入会话 |                  tmux attach -t <session-name> 或 tmux a -t 0 |
|    查看已有会话 |                                                       tmux ls |
|        新建会话 |                                                   tmux new -s |
|      重命名会话 |                           tmux rename-session -t 0 <new-name> |
|        切换会话 | tmux kill-session -t <session-name> 或 tmux kill-session -t 0 |


```
列出所有快捷键的命令：tmux list-keys
```












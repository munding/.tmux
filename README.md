# .tmux
github 主流的 tmux 配置文件学习成本太高，自己就挑了几个实用的配置，其他的在慢慢加吧


* 唤醒建改为了 `C-s`，默认是 `C-b`。看网上很多人改的是 `C-a` 或者是 `C-x`，我不太习惯
* `hjkl` 光标移动
* `-`,`|` 切分pane
* https://github.com/gpakosz/.tmux 可以参考

## alias
```bash
alias ta='tmux a -t'
alias tf='tail -f'
alias tls='tmux ls'
alias tnew='tmux new -s'
```

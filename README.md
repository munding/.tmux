# .tmux
自用的tmux配置文件


* 唤醒建改为了 `C-s`，默认是 `C-b`。看网上很多人改的是 `C-a` 或者是 `C-x`，我不太习惯
* `hjkl` 光标移动
* https://github.com/gpakosz/.tmux 可以参考

## alias
```bash
alias ta='tmux a -t'
alias tf='tail -f'
alias tls='tmux ls'
alias tnew='tmux new -s'
```

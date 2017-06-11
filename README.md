# \_VIMRC

# 缩进

```vim
set ai si
set ts=4 sts=4 expandtab
```

# 行号

```vim
set relativenumber
```

# 使用 `Alt + h/j/k/l` 移动光标（输入模式下）

```vim
inoremap <M-h> <Left>
inoremap <M-j> <Down>
inoremap <M-k> <Up>
inoremap <M-l> <Right>
```

# 使用 `jk` 作为 `ESC`（输入模式下）

```vim
inoremap jk <esc>
```

# 非管理员模式下以管理员权限（sudo）保存文件

```vim
cnoremap sudow w !sudo tee % >/dev/null
```

# [搜索可视化选中的文本](https://blog.twofei.com/610/)

```vim
vnoremap // y/<c-r>"<cr>
```



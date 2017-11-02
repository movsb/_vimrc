# \_VIMRC

## 缩进

[https://stackoverflow.com/a/1878983/3628322](https://stackoverflow.com/a/1878983/3628322)

```vim
set ai si
set ts=4 sts=4 sw=4 expandtab
```

## 使用相对行号

```vim
set relativenumber
```

## 使用 `Alt + h/j/k/l` 移动光标（输入模式下）

```vim
inoremap <M-h> <Left>
inoremap <M-j> <Down>
inoremap <M-k> <Up>
inoremap <M-l> <Right>
```

## 使用 `jk` 作为 `ESC`（输入模式下）

```vim
inoremap jk <esc>
```

## 非管理员模式下以管理员权限（sudo）保存文件

```vim
cnoremap sudow w !sudo tee % >/dev/null
```

## [搜索可视化选中的文本](https://blog.twofei.com/610/)

```vim
vnoremap // y/<c-r>"<cr>
```

## [使用 `Ctrl + h/j/k/l` 在窗口之间切换](https://blog.twofei.com/620/)

```vim
nnoremap <C-h> <C-w>h
nnoremap <C-j> <C-w>j
nnoremap <C-k> <C-w>k
nnoremap <C-l> <C-w>l
```

## [设置光标不闪烁](https://blog.twofei.com/621/)

```vim
set guicursor+=a:blinkon0
```


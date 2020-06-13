# Cheed Sheet

## vim

### move
* `gg` : ファイル先頭へ
* `G`  : ファイル末尾へ
* `I`  : 行頭でインサートモードへ
* `A`  : 行末でインサートモードへ
* `S`  : 行を消してインサートモードへ
* `J`  : 行をスペース区切りで結合(頭に数字で繰り返し)
* `gJ` : 行を結合(頭に数字で繰り返し)

### Window(:h window)
* `<c-w>s` : 上下分割(split)
* `<c-w>vs` : 左右分割(split)
* `<c-w>w` : next
* `<c-w>c` : close
* `<c-w>o` : 現在のwindow以外close(only)
* `<c-w>h,j,k,l` : move
* `<c-w><,>` : resize window

### fold
* `zo` : 開く
* `zc` : 閉じる
* `zr` : 全体を一段開く
* `zR` : 全体を全て開く
* `zm` : 全体を一段閉じる
* `zM` : 全体を全て閉じる

### pane
* `:vs`   : 縦に分割
* `:sp`   : 横に分割
* `<C-e>` : 幅調整モード

### buffer
* `<leader>bn` : 次へ
* `<leader>bp` : 前へ
* `<leader>b#` : 直前のバッファへ
* `<leader>bd` : 削除

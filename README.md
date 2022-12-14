# 初期設定

1. MacVim インストール

   ```
   brew install macvim
   ```

1. .vimrc(設定ファイル)と.vim(プラグインディレクトリ)のシンボリックリンク作成

   ```
   $ git submodule init
   $ git submodule update
   $ ln -s [本リポジトリのルートデ ィレクトリ絶対パス]/.vimrc ~/.vimrc
   $ ln -s [本リポジトリのルートデ ィレクトリ絶対パス]/.gvimrc ~/.gvimrc
   $ ln -s [本リポジトリのルートデ ィレクトリ絶対パス]/.vim ~/.vim
   ```

# チートシート

## 暗記したいもの

- `a`: 一文字後にインサート
- `A`: その行の最後にインサート
- `I`: その行の先頭にインサート
- `O`: 一行上にインサート
- `y`
- `Y`: カーソル行をヤンクY
- `p`
- `P`
- `C-r`: Redo
- `*`: カーソル上の単語を検索して最初のマッチへ飛ぶ
- `n` / `N`: Next / Previous
- `~`: カーソル上の 1 文字の大文字小文字をトグル
- `.`: 直前の編集操作を繰り返す
- `v`: 文字単位で選択するビジュアルモードへ
- `V`: 行単位で選択するビジュアルモードへ
- `C-v`: ブロック矩形状に選択するビジュアルモードへ
- `gv`: ビジュアルモードへ遷移して直前の選択状態を復帰
- `>`: インデントを深くする
- `>>`: カーソル行のインデントを深くする
- `=`: インデントを自動調整
- `==`: カーソル行のインデントを自動調整
- `c`: 別のテキストと交換
- `0` / `$`: 行頭 / 行末へ移動
- `w`, `W`: 次のワードの先頭へ
- `b`, `B`: 前のワードの先頭へ
- `gg` / `G`: ファイルの1行目 / 最終行へ

## 重要だけど時々しか使わないので暗記しなくていいもの

- `C-a` / `C-x`: カーソル以降にある数値をインクリメント/デクリメント
- `C-p` / `C-n`: コマンド履歴(前 / 次)
- `C-d`: コマンド補完(候補一覧)
- `Tab`, `S-Tab`: コマンド補完(次 / 前候補)

## もう暗記してしまったもの

- `o`: 一行下にインサート
- `i`
- `:q`, `:w`, `:wq`, `ZZ`
- `h`, `j`, `k`, `l`
- `C-[`, `Esc`
- `dd`
- `u`: Undo
- `dd`: カーソル行をカット
- `yy`: カーソル行をヤンク

# HOME
ホームディレクトリの設定ファイル類


# Usage

## Restore emacs

``` shell
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
git clone --recursive https://github.com/ustato/HOME ~/HOME
git clone http://www.dr-qubit.org/git/undo-tree.git ~/undo-tree
mv ~/undo-tree/undo-tree.el ~/.emacs.d/core/libs/.
rm -rf ~/.emacs.d/.git ~/HOME/.git ~/undo-tree
cp -rf ~/HOME/.emacs.d ~/HOME/.spacemacs ~/HOME/.viminfo ~/.
rm -rf ~/HOME
```

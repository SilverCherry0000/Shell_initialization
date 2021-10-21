zsh

bourne shell系コマンドとcsh系のコマンドが両方使える上に、ksh系のコマンドライン編集機能も実装された究極のシェル。

Bourne Shell系
sh(Bourne Shell): UNIX上の一番古いシェル。履歴機能や補完機能などの対話機能はないため、ログインシェルとして採用されることは殆ど無い。
bash(Bourne Again Shell): shを基本に様々な機能を加えたもの。Linuxでは基本のシェル。Mac OS Xの/bin/shも実体はbash

C Shell系
csh: C言語風文法のシェル。
tcsh: cshに機能を加えたもの。

K Shell系


zplug

zplugはb4b4r07氏によるZshのプラグインマネージャ。

プラグイン

入力中のコマンドをコマンド履歴から推測し、候補として表示する
	zsh-users/zsh-autosuggestions

pacman や yaourt のパッケージリストも補完するようになる
	zsh-users/zsh-completions

fzf でよく使う関数の詰め合わせ
	mollifier/anyframe

コマンドを種類ごとに色付け
	zsh-users/zsh-syntax-highlighting	

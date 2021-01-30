# watson-for-study

## Ruby Install

// 1.rbenvのインストール：

$ brew install rbenv ruby-build

// 2.インストール可能なRubyのバージョン一覧の表示

$ rbenv install -l

// 3.インストール

$ rbenv install 3.0.0

// 4.インストールしたRubyを使用可能な状態にする

$ rbenv rehash
$ vi ~/.zshrc
export PATH="$HOME/.rbenv/bin:$PATH"  
eval "$(rbenv init - zsh)"

// 5. バージョン指定

$ rbenv local 3.0.0


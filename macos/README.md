MacOS
================

   * [配置](#配置)
   * [常用安装](#常用安装)
   * [Hot Key](#hot-key)
   * [brew](#brew)
   * [Q&amp;A](#qa)


* iBooks书籍实际存放位置  

~/Library/Containers/com.apple.BKAgentService/Data/Documents/iBooks/Books  


## 配置

* [dotfiles for macOS](https://github.com/mathiasbynens/dotfiles)  

* .bash_profile  

```bash
alias ll="ls -G -l "
alias l1="ls -G -1 "
alias grep="grep -n --color "
alias fgrep="fgrep -n --color "
alias which='alias | gwhich --tty-only --read-alias --show-dot --show-tilde'
```

## 常用安装

```bash
brew install gradle
brew install scala

# 升级 bash 到 4.0
$ bash --version
GNU bash, version 3.2.57(1)-release (x86_64-apple-darwin19)

$ brew search bash

$/usr/local/opt/bash/bin/bash --version
GNU bash，版本 5.0.16(1)-release (x86_64-apple-darwin19.3.0)
```

## Hot Key

* Command + Option + Shift + Esc //强制退出程序  
* Command + Space -> 输入“Activity Monitor” //打开任务管理器  

## brew

* 安装 brew  

[brew.sh/index_zh-cn](https://brew.sh/index_zh-cn)  

```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

* brew 应用案例  

```bash
brew info gradle 
brew upgrade gradle //升级
```

## Q&A

* 应用程序无法启动，如何调试？  

打开finder->应用程序->xxx.app->右键->显示包内容->然后MaxOS->双击Shell脚本


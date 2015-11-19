title: Introduce Oh My Zsh
author:
  name: Steven Wu
  twitter: springwq
  url: http://stevenwu.org
output: index.html
theme: sudodoki/reveal-cleaver-theme
controls: true

--
# Oh My Zsh
## 打造高效率的终端命令行

--
### Oh My Zsh 简介

> Oh My Zsh is an open source, community-driven framework for managing your zsh configuration.

* https://github.com/robbyrussell/oh-my-zsh

* http://ohmyz.sh/

--
### Oh My Zsh 简介

* Oh My Zsh 是用来更好的配置 zsh ( Z shell) 的一个由社区驱动的框架

* 本质上解决了如何更好的使用 zsh 的问题  

--
### Zsh 和 Bash 的对比

#### PS1 prompt 更易定制

-- 
### Zsh 和 Bash 的对比

#### 强大的自动补全：命令和目录

--
### Zsh 和 Bash 的对比

#### 多终端窗口共享命令历史记录 history

--
### Zsh 和 Bash 的对比

####更强大的英文拼写纠正

--
### Zsh 和 Bash 对比

* PS1 prompt 更易定制
* 强大的自动补全：命令和目录
* 多终端窗口共享命令历史记录 history
* 更强大的英文拼写纠正

> 
  * https://www.quora.com/What-is-the-difference-between-bash-and-zsh
  * https://ruby-china.org/topics/734

--
### 安装 Oh My Zsh

#### 前提条件

* Unix-based OS (Linux, Mac OS X)
* Zsh has been preinstalled
* curl or wget
* git

--
### 安装 Oh My Zsh

#### 脚本安装（首次安装推荐）

```
via curl: 
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

via wget:
sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```
--
### 安装 Oh My Zsh
#### 手动安装

```
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.zshrc ~/.zshrc.orig
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
chsh -s /bin/zsh
```
--
### 选择主题

编辑 ~/.zshrc 文件

```
ZSH_THEME="robbyrussell"
```
* https://github.com/robbyrussell/oh-my-zsh/wiki/themes

--

### 踩过的坑

* 安装完新程序后（e.g. rbenv），注意修改 `.zshrc` 文件 `PATH` 路径
* 修改完 .zshrc 文件好，运行 `source .zshrc` 或者重新打开终端，才会生效 
* 我的 `zshrc`: https://github.com/springwq/dotfiles/blob/master/.zshrc

--
### MacTalk 

http://macshuo.com/?p=676

--
### 其它高效率的命令行工具

* iTerm
* tmux





  

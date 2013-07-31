vim
===
使用方法

Windows

1、访问 http://www.vim.org/download.php#pc 下载最新的 gVim [如无法访问该网站，可上 https://code.google.com/p/unix-cmd-win32/downloads/list 下载]

2、安装 gVim 到任意目录，这儿为方便讲解，我假定你安装到了 D:\Apps\Vim

3、将 D:\Apps\Vim\vim7* 目录加入环境变量 [不知何为环境变量者，请 Google]

4、删除 Vim 安装目录下的 vimfiles 目录以及 _vimrc 文件 [如果是你自己修改过的配置，请注意备份]

5、使用 Git 将本项目拷贝到 Vim 安装目录下，取代已删文件的位置 [命令为 git clone https://github.com/itzzq/vim.git]

6、访问 http://ctags.sourceforge.net 下载最新的 ctags，将 ctags.exe 复制到 D:\Apps\Vim\vim7* 目录 [如无法访问该网站，可上 https://code.google.com/p/unix-cmd-win32/downloads/list 下载]

7、推荐安装 Monaco 字体，因为本配置默认使用该字体，可上 https://github.com/ruchee/backup/blob/master/download/MONACO.TTF?raw=true 下载，下载后丢到 C:\WINDOWS\Fonts 目录即可

8、使用任意文本编辑器打开 _vimrc，将名字、邮箱、网址等全部替换为你自己的信息，如遇路径不同也全部替换为你本机的实际路径

9、配置已经完成，使用说明全部集中在了 _vimrc 文件的头部，配置的后半部分全是各插件的具体配置项

Linux 

1、sudo apt-get install vim-gnome exuberant-ctags [其他非 Debian 系的 Linux 请使用其自己的包管理器进行安装]

2、删除个人主目录下的 .vim 文件夹和 .vimrc 文件，如果没有则不需要执行删除动作 [使用命令 rm -rf ~/.vim ~/.vimrc，请注意备份]

3、使用 Git 将本项目拷贝到个人主目录下，取代已删文件的位置，然后将 vimfiles、_vimrc 改名为 .vim、.vimrc [命令为 git clone https://github.com/itzzq/vim.git、mv _vim .vim、mv _vimrc .vimrc]

4、可上 https://github.com/ruchee/backup/blob/master/download/MONACO.TTF?raw=true 下载 Monaco 字体，下载后直接运行安装即

5、可使用任意文本编辑器打开 .vimrc，将名字、邮箱、网址等全部替换为你自己的信息，如遇路径不同也全部替换为你本机的实际路径

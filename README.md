# macvim
Mac下的vim配置

# 1.下载pathogen管理插件

# 2. 安装NERDTree插件

## 使用

```Bash
输入  :NERDTree ，回车

ctr+w+h  光标focus左侧树形目录，ctrl+w+l 光标focus右侧文件显示窗口。多次摁 ctrl+w，光标自动在左右侧窗口切换

o 打开关闭文件或者目录
t 在标签页中打开
T 在后台标签页中打开
! 执行此文件
p 到上层目录
P 到根目录
K 到第一个节点
J 到最后一个节点
u 打开上层目录
m 显示文件系统菜单（添加、删除、移动操作）
? 帮助
q 关闭
```

# 3. emmet-vim

* 安装：git clone https://github.com/mattn/emmet-vim.git

* 使用

```Bash
html:5_
Then type <c-y>,


```

# 4.安装ctags ,cscope

# 5.安装tagbar

* 安装：git clone https://github.com/majutsushi/tagbar.git

* 使用
```Bash
:TagbarToggle
```
# 6.安装supertab

# 7. syntastic

[syntastic](https://github.com/vim-syntastic/syntastic#faqstyle)

# 8. javascript_libraies_syntax

[javascript_libraries_syntax](https://github.com/othree/javascript-libraries-syntax.vim)

# 9. ctrlp

[ctrlp](https://github.com/ctrlpvim/ctrlp.vim)

# 10. NERD commenter

[NERD commenter](https://github.com/scrooloose/nerdcommenter)

# 11. YouCompleteMe

* 安装

利用pathogen
```Bash
git clone https://github.com/Valloric/YouCompleteMe.git

cd ~/.vim/bundle/YouCompleteMe

git submodule update --init --recursive

~/install.py --all

```

# 12. VimSurround

[VimSurround](https://github.com/tpope/vim-surround)

# 13. vim-closetag

[vim-closetag](https://github.com/alvan/vim-closetag)

# 14. minibufexpl

[minibufexpl](https://github.com/fholgado/minibufexpl.vim)

# 15. bufexplorer

[bufexplorer](https://github.com/jlanzarotta/bufexplorer)

# 16. lookupfile

[lookupfile](https://github.com/vim-scripts/lookupfile)

[usage](http://easwy.com/blog/archives/advanced-vim-skills-lookupfile-plugin/)

# 17. ack

[ack](https://github.com/mileszs/ack.vim)

~/.ackrc

```Bash
--ignore-file=is:filenametags
--ignore-file=is:cscope.out
--ignore-file=is:filelist
--ignore-file=is:tags
--ignore-dir=signature                      
```

# 18.ultisnips

[ultisnips](https://github.com/SirVer/ultisnips)

# 19. mark
[mark](https://www.vim.org/scripts/script.php?script_id=1238)

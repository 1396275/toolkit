# Atom

--------------------------------------------------------------------------------

# 快捷键 shortcuts

## 文件切换

`ctrl-shift-s` 保存所有打开的文件<br>
`cmd-shift-o` 打开目录<br>
`cmd-\` 显示或隐藏目录树<br>
`ctrl-0` 焦点移到目录树<br>
目录树下，使用a，m，delete来增加，修改和删除<br>
`cmd-t`或`cmd-p` 查找文件<br>
`cmd-b` 在打开的文件之间切换<br>
`cmd-shift-b` 只搜索从上次git commit后修改或者新增的文件

## 导航

（等价于上下左右）<br>
`ctrl-p` 前一行<br>
`ctrl-n` 后一行<br>
`ctrl-f` 前一个字符<br>
`ctrl-b` 后一个字符

`alt-b`, `alt-left` 移动到单词开始<br>
`alt-f`, `alt-right` 移动到单词末尾

`cmd-right`, `ctrl-e` 移动到一行结束<br>
`cmd-left`, `ctrl-a` 移动到一行开始

`cmd-up` 移动到文件开始<br>
`cmd-down` 移动到文件结束

`ctrl-g` 移动到指定行 row:column 处

`cmd-r` 在方法之间跳转

## 目录树操作

`cmd-\` 或者 `cmd-k cmd-b` 显示(隐藏)目录树<br>
`ctrl-0` 焦点切换到目录树(再按一次或者`esc`退出目录树)<br>
`a` 添加文件<br>
`d` 将当前文件另存为(duplicate)<br>
`i` 显示(隐藏)版本控制忽略的文件<br>
`alt-right` 和 `alt-left` 展开(隐藏)所有目录<br>
`ctrl-al-]` 和 `ctrl-al-[` 同上<br>
`ctrl-[` 和 `ctrl-]` 展开(隐藏)当前目录<br>
`ctrl-f` 和 `ctrl-b` 同上<br>
`cmd-k h` 或者 `cmd-k left` 在左半视图中打开文件<br>
`cmd-k j` 或者 `cmd-k down` 在下半视图中打开文件<br>
`cmd-k k` 或者 `cmd-k up` 在上半视图中打开文件<br>
`cmd-k l` 或者 `cmd-k right` 在右半视图中打开文件<br>
`ctrl-shift-c` 复制当前文件绝对路径

## 书签

`cmd-f2` 在本行增加书签<br>
`f2` 跳到当前文件的下一条书签<br>
`shift-f2` 跳到当前文件的上一条书签<br>
`ctrl-f2` 列出当前工程所有书签

## 选取

> 大部分和导航一致，只不过加上shift

`ctrl-shift-p` 选取至上一行<br>
`ctrl-shift-n` 选取至下一样<br>
`ctrl-shift-b` 选取至前一个字符<br>
`ctrl-shift-f` 选取至后一个字符<br>
`alt-shift-b`, `alt-shift-left` 选取至字符开始<br>
`alt-shift-f`, `alt-shift-right` 选取至字符结束<br>
`ctrl-shift-e`, `cmd-shift-right` 选取至本行结束<br>
`ctrl-shift-a`, `cmd-shift-left` 选取至本行开始<br>
`cmd-shift-up` 选取至文件开始<br>
`cmd-shift-down` 选取至文件结尾<br>
`cmd-a` 全选<br>
`cmd-l` 选取一行，继续按回车选取下一行<br>
`ctrl-shift-w` 选取当前单词

## 编辑和删除文本

### 基本操作

`ctrl-t` 使光标前后字符交换<br>
`cmd-j` 将下一行与当前行合并<br>
`ctrl-cmd-up`, `ctrl-cmd-down` 使当前行向上或者向下移动<br>
`cmd-shift-d` 复制当前行到下一行<br>
`cmd-k`, `cmd-u` 使当前字符大写<br>
`cmd-k`, `cmd-l` 使当前字符小写

### 删除和剪切

`ctrl-shift-k` 删除当前行<br>
`cmd-backspace` 删除到当前行开始<br>
`cmd-fn-backspace` 删除到当前行结束<br>
`ctrl-k` 剪切到当前行结束<br>
`alt-backspace` 或 `alt-h` 删除到当前单词开始<br>
`alt-delete` 或 `alt-d` 删除到当前单词结束

### 多光标和多处选取

`cmd-click` 增加新光标<br>
`cmd-shift-l` 将多行选取改为多行光标<br>
`ctrl-shift-up`, `ctrl-shift-down` 增加上（下）一行光标<br>
`cmd-d` 选取文档中和当前单词相同的下一处<br>
`ctrl-cmd-g` 选取文档中所有和当前光标单词相同的位置

### 括号跳转

`ctrl-m` 相应括号之间，html tag之间等跳转<br>
`ctrl-cmd-m` 括号(tag)之间文本选取<br>
`alt-cmd-.` 关闭当前xml/html tag

### 编码方式

`ctrl-shift-u` 调出切换编码选项

## 查找和替换

`cmd-f` 在buffer中查找<br>
`cmd-shift-f` 在整个工程中查找

## 代码片段

`alt-shift-s` 查看当前可用代码片段

> 在`~/.atom`目录下`snippets.cson`文件中存放了你定制的snippets

[定制说明](https://atom.io/docs/v1.0.0/using-atom-snippets)

## 自动补全

`ctrl-space` 提示补全信息

## 折叠

`alt-cmd-[` 折叠<br>
`alt-cmd-]` 展开<br>
`alt-cmd-shift-{` 折叠全部<br>
`alt-cmd-shift-}` 展开全部<br>
`cmd-k cmd-n` 指定折叠层级 n为层级数

## 文件语法高亮

`ctrl-shift-l` 选择文本类型

## 使用atom进行写作

`ctrl-shift-m` markdown预览<br>
可用代码片段

> b, legal, img, l, i, code, t, table

## git操作

`cmd-alt-z` checkout head 版本<br>
`cmd-shift-b` 弹出untracked 和 modified文件列表<br>
`alt-g down` `alt-g up` 在修改处跳转<br>
`alt-g d` 弹出diff列表<br>
`alt-g o` 在github上打开文件<br>
`alt-g g` 在github上打开项目地址<br>
`alt-g b` 在github上打开文件blame<br>
`alt-g h` 在github上打开文件history<br>
`alt-g i` 在github上打开issues<br>
`alt-g r` 在github打开分支比较<br>
`alt-g c` 拷贝当前文件在gihub上的网址

## 推荐一些好用的插件

- 主题<br>
  [atom-material-ui](https://atom.io/themes/atom-material-ui) 好看到爆<br>
  [atom-material-syntax](https://atom.io/themes/atom-material-syntax)
- 美化<br>
  [atom-beautify](https://atom.io/packages/atom-beautify) 一键代码美化<br>
  [file-icons](https://atom.io/packages/file-icons) 给文件加上好看的图标<br>
  [atom-minimap](https://atom.io/users/atom-minimap) 方便美观的缩略滚动图
- git<br>
  [atomatigit](https://atom.io/packages/atomatigit) 可视化git操作
- 代码提示<br>
  [emmet](https://atom.io/packages/emmet) 这个不用介绍了吧<br>
  [atom-ternjs](https://atom.io/packages/atom-ternjs) js代码提示很强大，高度定制化<br>
  [docblockr](https://atom.io/packages/docblockr) jsdoc 给js添加注释<br>
  [autoclose-html](https://atom.io/packages/autoclose-html) 闭合html标签<br>
  [color-picker](https://atom.io/packages/color-picker) 取色器 必备插件<br>
  [pigments](https://atom.io/packages/pigments) 颜色显示插件 必装<br>
  [terminal-panel](https://atom.io/packages/terminal-panel) 直接在atom里面写命令了<br>
  [svg-preview](https://atom.io/packages/svg-preview) svg预览
- 便捷操作<br>
  [advanced-open-file](https://atom.io/packages/advanced-open-file) 快速打开、切换文件<br>
  [project-folder](https://atom.io/packages/project-folder) 快速打开、切换项目

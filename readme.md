<!-- TOC -->

- [1. 配置导入](#1-配置导入)
- [2. vscode 自定义按键配置](#2-vscode-自定义按键配置)
  - [2.1. 全局按键绑定](#21-全局按键绑定)
  - [2.2. explorer 下绑定](#22-explorer-下绑定)
  - [2.3. 文件浏览](#23-文件浏览)
  - [2.4. terminal panel下的按键绑定](#24-terminal-panel下的按键绑定)
  - [2.5. vim 按键绑定](#25-vim-按键绑定)
    - [2.5.1. 常规绑定](#251-常规绑定)
    - [2.5.2. Insert mode下的绑定](#252-insert-mode下的绑定)
    - [2.5.3. Normal mode下的绑定：](#253-normal-mode下的绑定)
    - [2.5.4. Visual mode下的绑定：](#254-visual-mode下的绑定)
    - [2.5.5. leader key下的绑定](#255-leader-key下的绑定)
    - [2.5.6. project TODO+](#256-project-todo)
    - [2.5.7. vim-surround 功能中的绑定](#257-vim-surround-功能中的绑定)
- [3. python下的按键绑定](#3-python下的按键绑定)
- [4. C++下的按键绑定](#4-c下的按键绑定)
- [5. Markdown下的按键绑定](#5-markdown下的按键绑定)
- [6. Snippets](#6-snippets)
  - [6.1. Python Snippets](#61-python-snippets)

<!-- /TOC -->

# 1. 配置导入

使用[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)插件根据安装指导完成配置  
其中gist信息使用本库配置的gist:

```sh
67021e0ea08de4a0206bed3dcbf341ba
```

你也可以通过访问[该配置的gist](https://gist.github.com/Peter-Chou/67021e0ea08de4a0206bed3dcbf341ba)按需导入

# 2. vscode 自定义按键配置

## 2.1. 全局按键绑定

| 快捷键          | 功能                            |
| --------------- | ------------------------------- |
| F1              | 调出dash查询cursor下的API信息   |
| F2              | rename symbol                   |
| F3              | 找当前变量的所有引用            |
| F8              | 跳转到下一个错误                |
| Shift+F8        | 跳转到上一个错误                |
| Shift+alt+f     | format the entire active file   |
| Ctrl+tab        | 切换到下一个editor              |
| Ctrl+shift+'    | active current editor           |
| Ctrl+shift+.    | quick jump to definition/symbol |
| Ctrl+shift+t    | 打开/关闭terminal panel         |
| `Ctrl+shift+n`  | panel 底部 / 侧边 显示切换      |
| Ctrl+shift+w    | 打开/关闭Sidebar                |
| Ctrl+shift+o    | 打开 code outline panel         |
| Ctrl+shift+h    | 插入文件的相对路径              |
| Ctrl+shift+-    | 折叠所有代码                    |
| Ctrl+shift+=    | 展开所有代码                    |
| Ctrl+shift+o    | 打开 code outline panel         |
| Ctrl+shift+q    | 列出最近打开的git仓库           |
| Ctrl+alt+p      | 列出所有git仓库                 |
| Ctrl+alt+i      | 打开候选参数提示                |
| Ctrl+-          | 代码font缩小                    |
| Ctrl+=          | 代码font放大                    |
| Ctrl+0          | 代码font复原                    |
| Ctrl+j          | focus on panel                  |
| Ctrl+n          | 选择下一个suggestion            |
| Ctrl+p          | 选择上一个suggestion            |
| `Ctrl-k Ctrl-x` | 清除行末尾的whitespace          |
| Ctrl-k z        | 打开/关闭 zen-mode              |
| Alt+j           | 弹出函数参数提示板              |
| Alt+shift+0     | 横向 / 纵向 布局改变            |
| Shift+F12       | 隐藏 title bar (在windows内)    |
| Shift+F11       | 显示 title bar (在windows内)    |

## 2.2. explorer 下绑定

| 快捷键         | 功能                     |
| -------------- | ------------------------ |
| F2             | 重命名文件               |
| Ctrl+c         | 复制文件（夹）           |
| Ctrl+v         | 粘贴文件（夹）           |
| Ctrl+enter     | 从另一个窗口打开         |
| `Ctrl+shift+a` | 创建文件                 |
| `Ctrl+shift+d` | 创建文件夹               |
| `Ctrl+shift+z` | 折叠所有的文件夹         |
| Alt+shift+r    | 打开文件所在的系统文件夹 |
| Shift+alt+c    | 复制路径                 |

## 2.3. 文件浏览

| 快捷键       | 功能                               |
| ------------ | ---------------------------------- |
| Ctrl+l       | 打开file navigator                 |
| Ctrl+shift+i | open Untitled buffer for file path |
| Alt+d        | 从 cursor所指的路径string打开文件  |

## 2.4. terminal panel下的按键绑定

| 快捷键       | 功能                                              |
| ------------ | ------------------------------------------------- |
| `Ctrl+k`     | 清空terminal内容（在terminal panel下）            |
| Ctrl+\       | split另一个terminal(在terminal panel下可用)       |
| Alt+left     | 转到前一个terminal panel (在terminal panel下可用) |
| Alt+right    | 转到后一个terminal panel (在terminal panel下可用) | Shift+k | 向上移动一行 |
| Shift+j      | 向下移动一行                                      |
| Ctrl+shift+k | 向上移动一屏                                      |
| Ctrl+shift+j | 向下移动一屏                                      |

## 2.5. vim 按键绑定

### 2.5.1. 常规绑定

| 快捷键    | 功能          |
| --------- | ------------- |
| Shift+Esc | 关闭popup提示 |

### 2.5.2. Insert mode下的绑定

| 快捷键 | 功能         |
| ------ | ------------ |
| Ctrl+f | 向前移动一格 |
| Ctrl+b | 向后移动一格 |
| Ctrl+a | 移动到行首   |
| Ctrl+e | 移动到行尾   |
| `f+d`  | escape key   |

### 2.5.3. Normal mode下的绑定：

| 快捷键      | 功能                                                      |
| ----------- | --------------------------------------------------------- |
| `f+d`       | escape key                                                |
| line_num+gg | 跳转到line_num 行                                         |
| `g+h`       | 相当于鼠标放在curser处                                    |
| `g+d`       | 跳转到定义处（jump to definition)                         |
| Ctrl+]      | 跳转到定义处（jump to definition)                         |
| Ctrl+t      | 从定义处调回原位置                                        |
| g+D         | 在另一窗口打开定义                                        |
| g+t         | 切换到下一个tab                                           |
| g+T         | 切换到上一个tab                                           |
| g+b         | add an additional cursor at the next place that matches * |

### 2.5.4. Visual mode下的绑定：

| 快捷键 | 功能                                                             |
| ------ | ---------------------------------------------------------------- |
| g+q    | reflow and wordwrap blocks of text, preserving commenting style. |

### 2.5.5. leader key下的绑定

| 快捷键                      | 功能                                        |
| --------------------------- | ------------------------------------------- |
| `space`                     | `leader key`                                |
| `leader+tab`                | 切换到最近一个buer（spacemacs 中的 SPC-TAB) |
| leader+b+b                  | 打开 buffer list                            |
| leader+b+i                  | open outline explorer                       |
| `leader+j+J`                | jump by two chars (like ace-jump in emcas)  |
| leader+j+i                  | jump to specific method                     |
| `<leader><leader> s <char>` | Search character                            |
| `<leader><leader> w`        | Start of word forwards                      |
| `<leader><leader> b`        | Start of word backwards                     |
| `<leader><leader> e`        | End of word forwards                        |
| `<leader><leader> ge`       | End of word backwards                       |
| leader+/                    | 清除搜索高亮                                |
| `leader+g`                  | golden-ratio 当前窗口                       |
| `leader+G`                  | 取消golden-ratio 当前窗口                   |
| leader+x+=                  | increase buffer size(horizontal)            |
| leader+x+-                  | decrease buffer size(horizontal)            |
| `leader+d`                  | 跳回一开始的跳转处(undo jump to definition) |
| leader+t                    | start shell at file directory               |
| leader+1                    | 折叠第一层级代码                            |
| leader+2                    | 折叠第二层级代码                            |
| leader+3                    | 折叠第三层级代码                            |
| leader+4                    | 折叠第四层级代码                            |
| leader+5                    | 折叠第五层级代码                            |
| leader+0                    | 展开所有代码                                |
| `leader+w+m`                | 最大化当前窗口                              |
| `leader+w+d`                | 关闭当前窗口                                |
| `leader+w+L`                | 向右移动当前窗口                            |
| `leader+w+H`                | 向左移动当前窗口                            |
| `leader+w+c`                | editor 居中                                 |

### 2.5.6. project TODO+

| 快捷键     | 功能                 |
| ---------- | -------------------- |
| leader+o+o | todo.open            |
| leader+o+e | todo.openEmbedded    |
| leader+o+a | todo.archive         |
| leader+o+b | todo.toggleBox       |
| leader+o+d | todo.toggleDone      |
| leader+o+c | todo.toggleCancelled |
| leader+o+s | todo.toggleStart     |
| leader+o+t | todo.toggleTimer     |

### 2.5.7. vim-surround 功能中的绑定

| Surround Command                     | Description                                                           |
| ------------------------------------ | --------------------------------------------------------------------- |
| `d s <existing char>`                | Delete existing surround                                              |
| `c s <existing char> <desired char>` | Change surround existing to desired                                   |
| `y s <motion> <desired char>`        | Surround something with something using motion (as in "you surround") |
| `S <desired char>`                   | Surround when in visual modes (surrounds full selection)              |

# 3. python下的按键绑定

因为安装了docstring插件，在"""后enter就可以补全  

# 4. C++下的按键绑定

# 5. Markdown下的按键绑定

| 快捷键   | 功能                      |
| -------- | ------------------------- |
| Ctrl-k v | 打开/关闭markdown preview |

# 6. Snippets

## 6.1. Python Snippets

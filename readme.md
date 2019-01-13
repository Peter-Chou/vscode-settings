- [1. 配置导入](#1-配置导入)
- [2. vscode 自定义按键配置](#2-vscode-自定义按键配置)
  - [2.1. 全局按键绑定](#21-全局按键绑定)
  - [2.2. explorer 下绑定](#22-explorer-下绑定)
  - [2.3. 文件浏览](#23-文件浏览)
  - [2.4. terminal panel下的按键绑定](#24-terminal-panel下的按键绑定)
  - [2.5. vim 按键绑定](#25-vim-按键绑定)
    - [2.5.1. 常规绑定](#251-常规绑定)
    - [2.5.2. Normal mode下的绑定：](#252-normal-mode下的绑定)
    - [2.5.3. Visual mode下的绑定：](#253-visual-mode下的绑定)
    - [2.5.4. leader key下的绑定](#254-leader-key下的绑定)
    - [2.5.5. project TODO+](#255-project-todo)
    - [2.5.6. vim-surround 功能中的绑定](#256-vim-surround-功能中的绑定)
- [3. python下的按键绑定](#3-python下的按键绑定)
- [4. C++下的按键绑定](#4-c下的按键绑定)
- [5. Markdown下的按键绑定](#5-markdown下的按键绑定)
- [6. Snippets](#6-snippets)
  - [6.1. Python Snippets](#61-python-snippets)

# 1. 配置导入

使用[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)插件根据安装指导完成配置
其中gist信息使用本库配置的gist:

```sh
67021e0ea08de4a0206bed3dcbf341ba
```

你也可以通过访问[该配置的gist](https://gist.github.com/Peter-Chou/67021e0ea08de4a0206bed3dcbf341ba)按需使用
PS: 英文字体使用的是：[AutoMono](https://github.com/0matgal0/AutoMono)

# 2. vscode 自定义按键配置

## 2.1. 全局按键绑定

| 快捷键          | 功能                                                            |
| --------------- | --------------------------------------------------------------- |
| F1              | 调出dash查询cursor下的API信息                                   |
| F2              | rename symbol                                                   |
| F3              | 找当前变量的所有引用                                            |
| F8              | 跳转到下一个错误                                                |
| Shift+F8        | 跳转到上一个错误                                                |
| Shift+alt+f     | format the entire active file                                   |
| Ctrl+F4         | 关闭当前editor                                                  |
| Ctrl+tab        | 切换到下一个editor                                              |
| Ctrl+shift+.    | quick jump to definition/symbol                                 |
| Ctrl+shift+t    | 打开/关闭terminal panel                                         |
| Ctrl+shift+o    | 打开 code outline panel                                         |
| Ctrl+shift+a    | 打开 comments anchor 面板 (only available in editor-text focus) |
| Ctrl+shift+w    | 打开/关闭Sidebar                                                |
| Ctrl+shift+q    | 列出最近打开的git仓库                                           |
| Ctrl+shift+h    | 插入文件的相对路径                                              |
| Ctrl+shift+n    | panel 底部 / 侧边 显示切换                                      |
| Ctrl+shift+-    | 折叠所有代码                                                    |
| Ctrl+shift+=    | 展开所有代码                                                    |
| Ctrl+alt+p      | 列出所有git仓库                                                 |
| Ctrl+alt+i      | 打开候选参数提示                                                |
| Ctrl+-          | 代码font缩小                                                    |
| Ctrl+=          | 代码font放大                                                    |
| Ctrl+0          | 代码font复原                                                    |
| Ctrl+n          | 选择下一个suggestion                                            |
| Ctrl+p          | 选择上一个suggestion                                            |
| `Ctrl-k Ctrl-x` | 清除行末尾的whitespace                                          |
| `Ctrl-k Ctrl-w` | 关闭所有的editors                                               |
| Ctrl-k z        | 打开/关闭 zen-mode                                              |
| `Alt+j`         | active current editor                                           |
| Alt+k           | 弹出函数参数提示板                                              |
| Alt+z           | 启用 / 禁用 visual line                                         |
| Alt+Enter       | 在(insert mode下)行尾增加`;` & cursor移到下一行                 |
| Alt+shift+0     | 横向 / 纵向 布局改变                                            |

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
| Alt+Shift+c    | 复制路径                 |

## 2.3. 文件浏览

| 快捷键       | 功能                               |
| ------------ | ---------------------------------- |
| Ctrl+l       | 打开file navigator                 |
| Ctrl+p       | 浏览最近文件列表                   |
| Ctrl+shift+i | open Untitled buffer for file path |
| Alt+d        | 从 cursor所指的路径string打开文件  |

## 2.4. terminal panel下的按键绑定

| 快捷键       | 功能                                              |
| ------------ | ------------------------------------------------- |
| `Ctrl+j`     | focus on terminal panel                           |
| `Ctrl+k`     | 清空terminal内容（在terminal panel下）            |
| Ctrl+\       | split另一个terminal(在terminal panel下可用)       |
| Ctrl+Shift+j | 向下移动一行                                      |
| Ctrl+Shift+k | 向上移动一行                                      |
| Alt+left     | 转到前一个terminal panel (在terminal panel下可用) |
| Alt+right    | 转到后一个terminal panel (在terminal panel下可用) |

## 2.5. vim 按键绑定

### 2.5.1. 常规绑定

| 快捷键       | 功能                     |
| ------------ | ------------------------ |
| Ctrl+Shift+j | 所在行居中并向下移动一行 |
| Ctrl+Shift+k | 所在行居中并向上移动一行 |
| Shift+Esc    | 关闭popup提示            |
| `f+d`        | escape key               |
| `space`      | `leader key`             |

### 2.5.2. Normal mode下的绑定：

| 快捷键 | 功能                                                                     |
| ------ | ------------------------------------------------------------------------ |
| `g+h`  | 相当于鼠标放在curser处                                                   |
| `g+f`  | 相当于Click+click跳转到当前文件地址所在的文件                            |
| `g+d`  | 跳转到定义处（jump to definition)                                        |
| Ctrl+t | 从定义处调回原位置 (same as leader+d)                                    |
| Ctrl+s | search like swiper in emacs                                              |
| Ctrl+y | 内容向上移动一行                                                         |
| Ctrl+e | 内容向下移动一行                                                         |
| g+D    | 在另一窗口打开定义                                                       |
| g+t    | 切换到下一个tab                                                          |
| g+T    | 切换到上一个tab                                                          |
| g+b    | add an additional cursor at the next place that matches * (multi-cursor) |

### 2.5.3. Visual mode下的绑定：

| 快捷键 | 功能                           |
| ------ | ------------------------------ |
| g+q    | 使一行很长的注释分成多行短注释 |

### 2.5.4. leader key下的绑定

| 快捷键       | 功能                                        |
| ------------ | ------------------------------------------- |
| leader+tab   | 切换到最近一个buer（spacemacs 中的 SPC-TAB) |
| leader+T+F   | 打开/关闭 全屏                              |
| leader+t     | start shell at file directory               |
| leader+d     | 跳回到之前的跳转处(undo jump to definition) |
| leader+g     | golden-ratio 当前窗口                       |
| leader+G     | 取消golden-ratio 当前窗口                   |
| leader+/     | 清除搜索高亮                                |
| leader+1     | 折叠第一层级代码                            |
| leader+2     | 折叠第二层级代码                            |
| leader+3     | 折叠第三层级代码                            |
| leader+4     | 折叠第四层级代码                            |
| leader+5     | 折叠第五层级代码                            |
| leader+0     | 展开所有代码                                |
| leader+j+J   | jump by two chars (like ace-jump in emcas)  |
| leader+j+i   | jump to specific method                     |
| leader+f+r   | open recent buffer list                     |
| leader+b+b   | 列出正在开启的buffer                        |
| `leader+w+m` | 最大化当前窗口                              |
| `leader+w+d` | 关闭当前窗口                                |
| `leader+w+L` | 向右移动当前窗口                            |
| `leader+w+H` | 向左移动当前窗口                            |
| `leader+w+c` | editor 居中                                 |
| lead+m+m     | 设置/取消 bookmark                          |
| lead+m+M     | 设置/取消 labeled bookmark                  |
| lead+m+l     | 列出该文件中所有的 bookmarks                |
| lead+m+L     | 列出所有文件中的 bookmarks                  |
| lead+m+c     | 清除该文件中所有的 bookmarks                |
| lead+m+C     | 清除所有文件中的 bookmarks                  |
| leader+x+=   | increase buffer size(horizontal)            |
| leader+x+-   | decrease buffer size(horizontal)            |

### 2.5.5. project TODO+

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

### 2.5.6. vim-surround 功能中的绑定

| Surround Command                     | Description                                                           |
| ------------------------------------ | --------------------------------------------------------------------- |
| `d s <existing char>`                | Delete existing surround                                              |
| `c s <existing char> <desired char>` | Change surround existing to desired                                   |
| `y s <motion> <desired char>`        | Surround something with something using motion (as in "you surround") |
| `S <desired char>`                   | Surround when in visual modes (surrounds full selection)              |

# 3. python下的按键绑定

因安装了docstring插件，在"""后enter就可以补全 (使用的是google style)

# 4. C++下的按键绑定

| 快捷键          | 功能                                       |
| --------------- | ------------------------------------------ |
| Alt+enter       | 在 insert下自动在行尾添加 `;` 并移至下行   |
| Shift+Alt+enter | 在 normal下自动在行尾添加 `;` 光标留在原处 |

# 5. Markdown下的按键绑定

| 快捷键   | 功能                      |
| -------- | ------------------------- |
| Ctrl-k v | 打开/关闭markdown preview |

# 6. Snippets

## 6.1. Python Snippets

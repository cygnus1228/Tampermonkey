# install language
## python
###### 查看版本
```python -v```

```python3 -v```
###### 安装
```sudo apt install python3```
## C
###### 查看版本
```gcc -v```
###### 安装
```sudo apt install gcc```
## c++
###### 查看版本
```g++ -v```
###### 安装
```sudo apt install g++```
# VSCode 插件
## 语言
###### JS
```Vetur VUE```
## 上传配置
###### [Settings Sync](http://shanalikhan.github.io/2015/12/15/Visual-Studio-Code-Sync-Settings.html)
## 连接虚拟机
```Remote-SSH```
## 运行代码
```Code Runner```
## 窗口透明
```Windows opacity```

```在设置搜索winopacity.opacity进行设置```
## 主题
```One Dark Pro```

```Dracula Official```
## 文件图标主题
```vscode-icons```

```Material Icon Theme```

## 字体
###### [Fira Code](https://github.com/tonsky/FiraCode)
```下载后打开FiraCode\distr\ttf全选右键安装```

```VSCode设置中搜索font```
###### 添加
```
"editor.fontFamily": "Fira Code",//后边的引号中写上要设置的字体类型
"editor.fontLigatures": true,//这个控制是否启用字体连字，true启用，false不启用，这里选择启用
  "editor.fontSize": 14,//设置字体大小
"editor.fontWeight": "normal",//这个设置字体粗细，可选normal,bold,"100"~"900"等，选择合适的
```
###### 终端字体间距
```
"terminal.integrated.fontFamily": "monospace"
```
## 打开html
```view in browser```
## 在浏览器中查看
```open-in-browser ```
## 实时预览
```Live Server```
## 自动闭合标签
```Auto Close Tag```
## 尾部闭合标签同步修改
```Auto Rename Tag```
## 用不同颜色高亮显示匹配的括号
```Bracket Pair Colorizer```
## 高亮显示匹配标签
```Highlight Matching Tag```
## 高亮
```TODO Highlight```
## 单词拼写检查
```Code Spell Checker```
## 查看Git信息
```GitLens```
## 书签
```Bookmarks```
## 常用快捷键
###### 编辑器与窗口管理
```Ctrl+Shift+P: 打开命令面板```

```Ctrl+Shift+N: 新建窗口```

```Ctrl+Shift+W: 关闭窗口```

```切分窗口：Ctrl+1/Ctrl+3/Ctrl+3```

```Ctrl+H：最小化窗口```

```Ctrl+B：显示/隐藏侧边栏```

```Ctrl+"+/-"：放大/缩小界面```
###### 文件操作
```Ctrl+N：新建文件```

```Ctrl+W：关闭文件```

```Ctrl+Tab：文件切换```

###### 格式调整
```Ctrl+C/Ctrl+V：复制或剪切当前行/当前选中内容```

```Alt+Up/Down：向上/下移动一行```

```Shift+Alt+Up//Down：向上/下复制一行```

```Ctrl+Delete：删除当前行```

```Shift+Alt+Left/Right：从光标开始向左/右选择内容```

###### 代码编辑
```Ctrl+D：选中下一个相同内容```

```Ctrl+Shift+L：选中所有相同内容```

```Ctrl+F：查找内容```

```Ctrl+Shit+F：在整个文件夹中查找内容```
## 其他设置
###### 关闭标签介绍信息
```"editor.hover.delay": 5000```
###### 自动折行
```File-Preferences-Settings-搜索editor.wordWrap-bounded```
###### 自动保存
```"files.autoSave": "off"```

```
off：关闭自动保存
afterDelay：当文件修改后的时间超过"Files：Auto Save Delay"中配置的值时自动进行保存
onFocusChange：编辑器失去焦点时自动保存更新后的文件
onWindowChange：窗口失去焦点时自动保存更新后的文件
```
###### 关闭代码提示
```"editor.quickSuggestions": { "other": false, "comments": false, "strings": false }```

# settings.json
```
{
    "launch": {
    
        "configurations": [],
        "compounds": []
    },
    "remote.SSH.remotePlatform": {
        "192.168.0.104": "linux"
    },
    "workbench.colorTheme": "One Dark Pro",
    "workbench.iconTheme": "material-icon-theme",
    "explorer.confirmDelete": false,
    "remote.SSH.showLoginTerminal": true,
    "code-runner.runInTerminal": true,
    "workbench.editor.enablePreview": false,

 
    
    "editor.fontFamily": "Fira Code",//字体
    "editor.fontLigatures": true,//连体字
    "editor.fontSize": 14,
    "editor.fontWeight": "normal",
    "terminal.integrated.fontFamily": "monospace",
    "editor.wordWrap": "on",//自动拆行
    
}
```

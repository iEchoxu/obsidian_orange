## 无序列表中插入代码块

首先说一句在 obsidian 的无序列表或有序列表中插入代码块的编辑体验非常差，如非必须建议不要在无序列表中插入代码块。

### 方案

- **方案一：不使用插件**：
	- 在一级无序列表中插入代码块：
		- 光标定位到一级无序列表末尾，然后连续按**两次 Enter** 键（或者按 shift+enter 再按一次 shift +tab）
		- 输入 \`\`\` ，再输入代码所属的语言类型以及代码块里的内容
		- 选中整个代码块按**一次 TAB** 进行缩进
	- 在二级无序列表中插入代码块：
		- 光标定位到二级无序列表末尾，然后连续按**三次 Enter** 键（或者按 shift+enter 再按两次 shift +tab）
		- 输入 \`\`\` ，再输入代码所属的语言类型以及代码块里的内容
		- 选中整个代码块按**两次 TAB** 进行缩进
	- 缺点：
		- 在编辑视图下二级无序列表里的代码块背景是没有缩进的导致二级无序列表下的代码块背景色是占满整个行宽
		- 缩进线排版错乱
- **方案二：使用 codeblock-customizer 插件**：
	- 操作方法：参考不使用插件的操作
	- 缺点：
		- 会莫名的卡顿
		- 修改后无法及时更新，需要重启 obsidian 才能在预览模式下看到效果


> [!warning] 注意
>  建议在 obsidian 中不要在无序列表符号后紧跟着输入 \`\`\`，即：**-\`\`\`go**，这样会导致无序列表顺序错乱。

总结：秉着少用插件的原则再加上使用插件后会导致莫名的卡顿，所以采用了方案一，丑就丑点，实在忍受不了就换 Typora。

### 案例

- 一级无序列表内容
	- 二级无序列表内容
		```shell
		rm -rf /usr/local/go && tar -C /usr/local -xzf go1.17.5.linux-amd64.tar.gz
		vim $HOME/.profile
		export PATH=$PATH:/usr/local/go/bin
		source $HOME/.profile
		go version
		```
	- 紧跟代码块后的二级无序列表内容
- 一级无序列表内容
	- 
		```shell
		rm -rf /usr/local/go && tar -C /usr/local -xzf go1.17.5.linux-amd64.tar.gz
		vim $HOME/.profile
		export PATH=$PATH:/usr/local/go/bin
		source $HOME/.profile
		go version
		```
	- 紧跟代码块后的二级无序列表内容
- 一级无序列表内容
	```shell
	rm -rf /usr/local/go && tar -C /usr/local -xzf go1.17.5.linux-amd64.tar.gz
	vim $HOME/.profile
	export PATH=$PATH:/usr/local/go/bin
	source $HOME/.profile
	go version
	```
	- 二级无序列表内容
- 一级无序列表内容

### 参考

- [【建议】更智能的列表/大纲代码块缩进支持 - 建议反馈 - Obsidian 中文论坛](https://forum-zh.obsidian.md/t/topic/4608)
- [Live Preview: Better support of code blocks in lists - Bug reports - Obsidian Forum](https://forum.obsidian.md/t/live-preview-better-support-of-code-blocks-in-lists/31352/35)
- [Complex List Items | Asciidoctor Docs](https://docs.asciidoctor.org/asciidoc/latest/lists/continuation/)

## 快速插入 callout

- 将选中的内容转换为 callout：
	- 打开 **快捷键** 设置，并搜索 **插入标注**。设置其快捷键，例如 `Ctrl+.`  
	- 使用时选中要转换的部分，用快捷键就好了。  
	- 缺点：转换成 callout 后，默认为 `!NOTE`。需要其他格式还得再鼠标右键切换。

## 格式转换

使用 markdown-it-container 语法：[Obsidian插件 之 Markdwon-it-container 功能需求调研 - 每日闲聊 - Obsidian 中文论坛](https://forum-zh.obsidian.md/t/topic/38380/2)




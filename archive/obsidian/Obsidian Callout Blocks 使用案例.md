
>  从 Obsidian 0.14 开始支持 callout blocks ，通过此语法可实现类似 Admonition 提示块功能。

## callout blocks 语法介绍

用 `> [! 类型]` 即可使用 callout blocks 功能，**注意：每行内容前面都必须添加 `>`**

**有如下类型可供使用：**

- note、abstract、info、todo、tip、success、question
- warning、failure、danger、bug、example、quote

## 自定义 callout 默认样式


> [!info] 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange) 

> [!info]+ info | note
> 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)
> - 测试无序列表
> - 继续测试无序列表
>> - 测试二级菜单
> 
> 测试段落内容
> `测试行内代码`
> 又是一个段落测试内容 <span class="tip">tip: 重要</span>  <span class="info">info: 重要</span>  <span class="warning">warning: 重要</span> <span class="danger">danger: 重要</span>
> 1. 测试有序列表
> 2. 继续测试有序列表
> 3. ==测试高亮==
>
>> 测试引用


> [!tip] 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange) 

> [!tip]- Tips
> 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)
> - 测试无序列表
> - 继续测试无序列表
> 
> 测试段落内容
> `测试行内代码`
> 又是一个段落测试内容
> 1. 测试有序列表
> 2. 继续测试有序列表
> 3. ==测试高亮==
> 4. **测试文字粗体**

> [!success] 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)

> [!success]+
> 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)
> - 测试无序列表
> - 继续测试无序列表
> 
> 测试段落内容
> `测试行内代码`
> 又是一个段落测试内容
> 1. 测试有序列表
> 2. 继续测试有序列表
> 3. ==测试高亮==

> [!warning]-
> 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)
> - 测试无序列表
> - 继续测试无序列表
> 
> 测试段落内容
> `测试行内代码`
> 又是一个段落测试内容
> 1. 测试有序列表
> 2. 继续测试有序列表
> 3. ==测试高亮==

> [!error]-
> 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)
> - 测试无序列表
> - 继续测试无序列表
> 
> 测试段落内容
> `测试行内代码`
> 又是一个段落测试内容
> 1. 测试有序列表
> 2. 继续测试有序列表
> 3. ==测试高亮==


> [!multi-column]
> 
>> [!border] 我的待办 <span class="tip">tip: 重要</span>
>> 这是一个测试内容
> >案例1：[[新年 FLAG]]
> >案例2：[[给笔记添加备注]]
>> 案例3：[[带有颜色高亮的笔记备注]]
>> 另外的测试信息
>> [测试链接](https://www.baidu.com)
>> - 这是一条测试信息
>> - 还是一条测试信息   <span class="info">info: 重要</span> 
>>> - 测试二级菜单
>> 
>> 这是一个测试内容
>>> 测试引用
>> `This is a inline code`
>> ==测试文字高亮==
>
>> [!border] TODO  <span class="warning">warning: 重要</span>
>> 这是一个测试内容
>> 案例1：[[我的待办]]
>> 案例2：[[健身计划]]
>> 案例3：[[ToDo]]
>> 另外的测试信息
>> [测试链接](https://www.baidu.com)
>> - 这是一条测试信息  <span class="danger">danger: 重要</span>
>> - 还是一条测试信息
>> 
>> 这是一个测试内容
>> `This is a inline code`
>> **测试文字粗体**



> [!example] 我的待办 <span class="tip">tip: 重要</span> 
> 这是一个测试内容
> 案例1：[[新年 FLAG]]
> 案例2：[[给笔记添加备注]]
> 案例3：[[带有颜色高亮的笔记备注]]
> 另外的测试信息
> [测试链接](https://www.baidu.com)
> - 这是一条测试信息  <span class="info">info: 重要</span>  <span class="warning">warning: 重要</span> <span class="danger">danger: 重要</span>
> - 还是一条测试信息
>> - 测试二级菜单
> 
> 这是一个测试内容
> `This is a inline code test`
> ==文字高亮==
>> 测试引用



## 使用进阶


> [!info] Callouts Title，可修改此处标题
> 这是 callout blocks

> [!info] Callouts Title: 只写标题不写内容

> [!note]- Callouts Title，可折叠展开
> 这是 callout blocks，我可以折叠展开

> [!info] Can callouts be nested? 可嵌套
> > [!tip] Yes!, they can.
> > > [!success] You can even use multiple layers of nesting.


> [!info] 测试代码块
> ```go
> func main() {
> 	fmt.Println("Hello")
> }
> ```

## 自定义 callout blocks

可用如下代码对 callout 进行自定义：

```css
.callout[data-callout="my-callout-type"] {
	--callout-color: 0, 0, 0; 
	/*去 https://lucide.dev/ 找到喜欢的 icon-id*/
	--callout-icon: icon-id; 
	--callout-icon: '<svg>...custom svg...</svg>'; 
}
```


### 使用 callout 实现高亮块功能


> [!orange]
> 🎁 测试内容
> 
> `测试行内代码`
> 
> - 测试 ur list
> - <font style="color: #42b983; font-weight: 500">高亮块功能很好用</font>，我可以输入不同颜色的文本
> - ==非常棒的功能==
> - <font style="background: rgb(253, 226, 226); font-weight: 500; color: rgb(216, 57, 49)">显示有背景的文本高亮</font>
> - [开始在 GitHub 上编写和格式化 - GitHub Docs](https://docs.github.com/cn/github/writing-on-github/getting-started-with-writing-and-formatting-on-github)，我也可输入 URL 链接
> - [[ToDo]]
>> - 测试二级菜单
>
>> 测试引用

> [!blue]
> 🎇 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)
> - 测试无序列表
> - 继续测试无序列表
>> - 测试二级菜单
> 
> 测试段落内容
> `测试行内代码`
> 又是一个段落测试内容 <span class="tip">tip: 重要</span>  <span class="info">info: 重要</span>  <span class="warning">warning: 重要</span> <span class="danger">danger: 重要</span>
> 1. 测试有序列表
> 2. 继续测试有序列表
> 3. ==测试高亮==

> [!red]
> 🏅 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)

> [!green]
> 🎁 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)

> [!purple]
> 🎀 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)

> [!normal]
> 🏅 用 obsidian 打开本项目， 仔细阅读 `Start Here` 文件，想查看具体语法可打开 `编辑模式`，这样就可查看完整的语法==使用技巧==，内部链接：[[Obsidian Callout Blocks 使用案例]]，外部链接：[Obsidian_Orange](https://github.com/iEchoxu/obsidian_orange)


## 参考

- [callout blocks 官方介绍](https://help.obsidian.md/How+to/Use+callouts)

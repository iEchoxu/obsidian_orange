---
cssclass:  img-grid
---
>使用此方法比较快捷简单，只要添加相关的语法后会自动完成图片并列显示。
## 🎃 如何使用
**1: ** 在 **YAML Front matter（编辑模式下笔记最开始的位置）**  添加如下代码：😃 

```
---
cssclass: img-grid
---
```

可让当前笔记中的所有 **非管道标记（即 `![[code-2.jpg]]` 而非 `![[code-2.jpg | 150]]` ）**的图片并列显示。👍 

**2:** 在编辑模式下将图片放在一行才能让它们并列显示，如果图片与图片之间存在**换行符**那么它们就不能并列显示。✌ 
## 🖼 案例
>下面的就是在一行内放置不同数量的图片后呈现出的不同显示效果。

![[city-2.jpg]]

![[code-2.jpg]] ![[img-1-1920x800.jpg]]

![[img-5.jpg]] ![[img-6.jpg]] ![[img-8.jpg]]

![[img-9.jpg]]![[img-15.jpg]]![[img-6.jpg]]![[img-5.jpg]] 

![[img-15.jpg]]![[img-9.jpg]]![[img-1-1920x800.jpg]]![[img-5.jpg]]![[img-6.jpg]]

![[img-8.jpg]]![[img-9.jpg]]![[img-15.jpg]]![[img-5.jpg]]![[img-1-1920x800.jpg]]![[img-6.jpg]]

### 并列显示图片案例（图片支持超链接跳转）
[![此出可写也可留空](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img.png "这是标题1")](https://gitee.com/iEchoxu/obsidian_orange) [![](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/darktheme.png "这是标题2,可省略")](https://gitee.com/iEchoxu/obsidian_orange) [![](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img1.png "这是标题3,可省略")](https://gitee.com/iEchoxu/obsidian_orange) [![](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/fenlan11.png "这是标题4,可省略")](https://gitee.com/iEchoxu/obsidian_orange)  [![image-url](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-hblock.png "这是标题5,可省略")](https://gitee.com/iEchoxu/obsidian_orange)

### 并列显示图片（点击跳转到本地笔记）
- 点击图片跳转到本地某条笔记，需要借助 Obsidian URL，详细语法可查看 Obsidian Help 库中的 “高级语法---使用 obsidian URI”，
- 另外如果笔记库名或者单条笔记名中包含中文或者特殊符号，需要先通过 在线URL编码解码工具：http://www.jsons.cn/urlencode/ 进行编码，然后复制编码后的内容到 obsidian url 链接中
- 但是 obsidian 13.23 版本好像有 bug ，不能打开 Obsidian URL


[![](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img.png "这是标题1")](obsidian://open?vault=Golang%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0&file=Home) [![](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/darktheme.png "这是标题2")](obsidian://open?vault=Golang%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0&file=Home)  [![](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-hblock.png "这是标题3,可省略")](obsidian://open?vault=obsidian_orange&file=Home)

### 并列显示图片（标准 Markdown 引入图片格式）
> 不要修改 markdown 语法中的 mdimg-1、mdimg-2、mdimg-3、mdimg-4、mdimg-5 

![mdimg-1](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/inbox.png  "一行显示一张图片") 

![mdimg-2](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img.png  "并列显示两张图片")
![mdimg-2](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/darktheme.png "并列显示两张图片")

![mdimg-3](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img.png "并列显示三张图片")
![mdimg-3](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/darktheme.png "并列显示三张图片")
![mdimg-3](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img1.png "并列显示三张图片")


![mdimg-4](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img.png "并列显示四张图片")
![mdimg-4](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/darktheme.png "并列显示四张图片")
![mdimg-4](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-hblock.png "并列显示四张图片")
![mdimg-4](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/fenlan11.png "并列显示四张图片")


![mdimg-5](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-img.png "并列显示五张图片")
![mdimg-5](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/darktheme.png "并列显示五张图片")
![mdimg-5](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/inbox.png "并列显示五张图片")
![mdimg-5](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/fenlan11.png "并列显示五张图片")
![mdimg-5](https://gitee.com/iEchoxu/obsidian_orange/raw/master/images/obsidian-hblock.png "并列显示五张图片")



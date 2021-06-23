>文本高亮这块我没有进行排版，因为这些都是使用案例，我认为将它们作为单行比较合理，没有使用过多的排版技巧。
## 文本高亮
- #htext/orange ==文本高亮==
- #htext/red ==文本高亮==
- #htext/black ==文本高亮==
- #htext/green ==文本高亮==
- #htext/blue ==文本高亮==
- #htext/purple ==文本高亮==
- ==默认高亮==
## 带有背景颜色的文本高亮
- #hbgtext/orange ==带有背景颜色的文本高亮== 

- #hbgtext/yellow ==带有背景颜色的文本高亮==

- #hbgtext/pink ==带有背景颜色的文本高亮==

- #hbgtext/blue ==带有背景颜色的文本高亮==

- #hbgtext/skyblue ==带有背景颜色的文本高亮==

- #hbgtext/purple ==带有背景颜色的文本高亮==

- #hbgtext/hjblue ==带有背景颜色的文本高亮==
## 高亮块
>实现高亮块的两种方式，介绍两者的区别
### 用 hblock 标签实现高亮块
#hblock/orange ==这是用hblock标签实现的高亮块==

#hblock/red ==这是用hblock标签实现的高亮块==

#hblock/green ==这是用hblock标签实现的高亮块==

#hblock/blue ==这是用hblock标签实现的高亮块==

#hblock/purple ==这是用hblock标签实现的高亮块==
### 用 admonition 实现高亮块 *推荐使用*
>此方法能在高亮块里输入更多的内容格式（列表、粗体等），而“使用 hblock 标签实现的高亮块”无法在里面输入列表，它只会将输出纯文本，而不会解析里面的内容。
- ![[Admonition如何使用#用 admonition 实现高亮块]]

```ad-orange
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
```

```ad-blue
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
```

```ad-red
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
```

```ad-green
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
```


```ad-purple
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
- 这是用admonition实现的高亮块
```

## "上标"高亮
>当 上标高亮 用在标题上时，右侧大纲会出现 `*important*` 这样的字样，暂未想到好的解决方法

- 测试上标高亮 *important*

- 测试上标高亮 **important**

- 测试上标高亮 ==默认高亮==

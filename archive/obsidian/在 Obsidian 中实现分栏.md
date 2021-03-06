---
cssclass: ad-column
---

```gray
1：需要借助 6.7.3 以上版本的 Admonition；

2：在笔记开头添加 cssclass: ad-column 这样的 yaml 标记；

3：通过在编辑模式下的 ad 模块中添加 color: 255,255,255 取消背景色，也可通过这种方法自定义背景色；

4：最好在每次分栏结束后面都添加一个 <p></p> 来清除浮动效果，确保能按我们想要的顺序进行排版。

```

## ✍  分栏案例演示
> 想知道更多分栏实现细节请参考：`.obsidian/snippets/column.css`


```ad-col2-left
title: ◼ 分两栏案例
color: 255,255,255
> 展示用两栏实现的案例

案例1：[[新年 FLAG]]

案例2：[[给笔记添加备注]]

案例3：[[带有颜色高亮的笔记备注]]




```

```ad-col2-right
title: ◼ 分三栏案例
color: 178,22,164
> 展示用三栏实现的案例

案例1：[[我的待办]]




```

<p></p>

```ad-col2-left
title: ◼ 分四栏案例
color: 178,122,64
> 展示用四栏实现的案例

案例1：[[我的观影记录]]


```

```ad-col2-right
title: ◼ 分五栏案例
color: 255,255,255
> 展示用五栏实现的案例

案例1：[[健身计划]]



```

<p></p>

<hr>

## 💡  分栏小技巧

```ad-content-flex
- 如何让文本并列显示：[[文本横排显示]]
- 发挥你的想象力：[[多个分栏进行组合]]
```



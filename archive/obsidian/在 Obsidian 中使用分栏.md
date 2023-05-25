
```
1：分栏功能需要 callout blocks 才能实现，要求 Obsidian 版本大于 v0.14；
2：开启 MCL Multi Column.css 以及 MCL Wide Views.css 代码片段；
3: 开启 columns.css（orange 自定义分栏模块）；
4: 不需要在文章开头添加 yaml 语法 cssclass: column；
```

## 📙 分栏介绍
orange 分栏功能是在 [obsidian-modular-css-layout](https://github.com/efemkay/obsidian-modular-css-layout) 基础上添加的，所以需要开启 ：

- `MCL Multi Column.css` 以及 `MCL Wide Views.css` 代码片段。
- columns.css（orange 自定义分栏模块）


> [!warning] 注意
> - 默认模式下每行最多有 5 个分栏模块（可通过 `--callout-min-width` 进行修改）且是响应式的
>- 超过将继续按每行 5 个分栏模块进行自适应


## ✍  分栏案例演示
> 想知道更多分栏实现细节请参考：`.obsidian/snippets/columns.css`

> [!multi-column]
> 
>> [!col-notitlebg] ◼ 分两栏案例
> > >展示用两栏实现的案例
> > 
> >案例1：[[新年 FLAG]]
> >
> >案例2：[[给笔记添加备注]]
>>
>> 案例3：[[带有颜色高亮的笔记备注]]
>
>> [!col-pink] ◼ 分三栏案例
> >> 展示用三栏实现的案例
>>
> 案例1：[[我的待办]]


> [!multi-column]
> 
>> [!col-lightorange] ◼ 分四栏案例
> > > 展示用四栏实现的案例
> > 
> >案例1：[[我的观影记录]]
>
>> [!col-notitlebg] ◼ 分五栏案例
> >> 展示用五栏实现的案例
> >
>>案例1：[[健身计划]]

<hr>

## 💡  分栏小技巧
- 如何让文本并列显示：[[文本横排显示]]
- 发挥你的想象力：[[多个分栏进行组合]]

>介绍如何使用“提示块”以及如何自定义“提示块”
## Admonition Types
```ad-example
title:此处使用的是 ad-example 类型
collapse: false
- 正文内容
- 正文内容
```

```ad-note
title:此处使用的是 ad-note 类型
- 正文内容
- 正文内容
```

```ad-abstract
title:此处使用的是 ad-abstract 类型
- 正文内容
- 正文内容
```

```ad-info
title:此处使用的是 ad-info 类型
- 正文内容
- 正文内容
```

```ad-tip
title:此处使用的是 ad-tip 类型
- 正文内容
- 正文内容
```

```ad-success
title:此处使用的是 ad-success 类型
- 正文内容
- 正文内容
```

```ad-question
title:此处使用的是 ad-question 类型
- 正文内容
- 正文内容
```

```ad-warning
title:此处使用的是 ad-warning 类型
- 正文内容
- 正文内容
```

```ad-failure
title:此处使用的是 ad-failure 类型
- 正文内容
- 正文内容
```

```ad-danger
title:此处使用的是 ad-danger 类型
- 正文内容
- 正文内容
```

```ad-bug
title:此处使用的是 ad-bug 类型
- 正文内容
- 正文内容
```

```ad-quote
title:此处使用的是 ad-quote 类型
- 正文内容
- 正文内容
```

</br>

## 自定义 Admonition
![[add-new-admontion.png|150]] ![[admontion-type.png|150]] ![[re-admontion.png|150]] ![[w-admontion.png|150]] ![[r-admontion.png|150]]

</br>

```ad-note
title:自定义的 type
collapse:false
icon: list-ol
color: 0,158,164
这是自定义的 type
```

`````ad-note
title: admonition 嵌套
collapse:false
这是自定义的 type

````ad-example
title:此处使用的是 ad-example 类型
collapse: false
- 正文内容
- 正文内容

```ad-note
title:此处使用的是 ad-example 类型
collapse: false
- 正文内容
- 正文内容
```

````

`````
</br>

### 用 admonition 实现高亮块
分别添加 12 个自定义 Admonition：
- ad-orange、ad-light-orange、ad-light-blue、ad-blue、ad-red、ad-Light-red、ad-green、ad-light-green、ad-purple、ad-light-purple、ad-gray、ad-light-gray
- 图标和颜色随便选，反正也不会让其显示
- 注册

---
## Links
- [How To Use Admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)
- [obsidian-admonition 插件](https://github.com/valentine195/obsidian-admonition)

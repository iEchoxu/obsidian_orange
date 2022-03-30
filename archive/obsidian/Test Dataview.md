
<br>


下面是用 dataview 查询 inbox 文件夹下所有文件用 list 显示：

```dataview
list from "inbox"
```

<br>


下面是用 dataview 的 table 命令查询 inbox 文件夹下所有文件，用 table 显示：

```dataview
table file.name AS "File-Name" from "inbox"
```


<br>


下面是用 Obsidian 自带的 query 命令查询 inbox 文件夹下所有文件：

```query
path:/inbox
```
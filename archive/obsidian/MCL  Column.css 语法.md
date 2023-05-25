
> MCL Multi Column.css 语法，详细请参考：[obsidian-modular-css-layout](https://github.com/efemkay/obsidian-modular-css-layout)


当超过行宽度时自动换行，因为指定了每栏的最小宽度为 150px 所以一行最多分 5 行。

> [!multi-column]
>
>> [!note]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning]+ Personal
>> your notes or lists here. using markdown formatting
>
>> [!Bug]+ Charity
>> your notes or lists here. using markdown formatting
>
>> [!Success]+ Charity
>> your notes or lists here. using markdown formatting
>
>> [!summary]+ Charity
>> your notes or lists here. using markdown formatting
>
>> [!Question]+ Charity
>> your notes or lists here. using markdown formatting


当超过行宽度时不自动换行，显示滚动条

> [!multi-column|no-wrap]
>
>> [!note]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning]+ Personal
>> your notes or lists here. using markdown formatting
>
>> [!summary]+ Charity
>> your notes or lists here. using markdown formatting
>
>> [!summary]+ Charity
>> your notes or lists here. using markdown formatting
>
>> [!summary]+ Charity
>> your notes or lists here. using markdown formatting


不同宽度的分栏

> [!multi-column]
>
>> [!note|wide-3]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|wide-1]+ Personal
>> your notes or lists here. using markdown formatting
>
>> [!summary|wide-2]+ Charity
>> your notes or lists here. using markdown formatting


> [!multi-column]
>
>> [!note|wide-1]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|wide-2]+ Personal
>> your notes or lists here. using markdown formatting
>
>> [!summary|min-0]+ Charity
>> your notes or lists here. using markdown formatting


> [!multi-column]
>
>> [!note|wide-1] Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|wide-2] Personal
>> your notes or lists here. using markdown formatting
>
>> [!summary|wide-4] Charity
>> your notes or lists here. using markdown formatting
>
>> [!summary|wide-5] Charity
>> your notes or lists here. using markdown formatting


> [!multi-column]
>
>> [!note|wide-3]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|wide-0]+ Personal
>> your notes or lists here. using markdown formatting


> [!multi-column]
>
>> [!note|wide-3] Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|wide-0]  Personal
>> your notes or lists here. using markdown formatting


> [!multi-column|fixed]
>
>> [!note|small]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|medium]+ Personal
>> your notes or lists here. using markdown formatting
>
>> [!summary|large]+ Charity
>> your notes or lists here. using markdown formatting


内容居中

> [!multi-column|center-fixed]
>
>> [!blank-container]
>> your notes or lists here. using markdown formatting
>
>> [!blank-container]
>> your notes or lists here. using markdown formatting
>
>> [!blank-container]
>> your notes or lists here. using markdown formatting


空的容器

Main paragraph content

> [!blank-container]
> - list 1 #mcl/list-column
> - list 2
> - list 3
> - list 4

Next paragraph content


图片并列 (需要开启 MCL Gallery Cards.css 代码片段)

> [!blank-container|no-margin gallery] Title
>
> ![[fenlan.png]]
> ![[fenlan1.png]]
>
> ![[fenlan2.png]]
> ![[fenlan3.png]]
> ![[fenlan4.png]]



右浮动
> [!info|right] 
> Addition note to the main article Content of the main article
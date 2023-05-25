> obsidian 提供的 callout 之间进行组合。


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

> [!multi-column]
>
>> [!note]+ Work
>> your notes or lists here. using markdown formatting
>> 
>> 我是个平常的人，我不能盼望在人海中值得你一转眼的注意。
> 
>> [!warning]+ Personal
>> your notes or lists here. using markdown formatting
>> 
>> 我是个平常的人，我不能盼望在人海中值得你一转眼的注意。
>
>> [!summary]+ Charity
>> your notes or lists here. using markdown formatting
>> 
>> 我是个平常的人，我不能盼望在人海中值得你一转眼的注意。

> [!multi-column]
>
>> [!note] Work
>> your notes or lists here. using markdown formatting
>
>> [!warning] Personal
>> your notes or lists here. using markdown formatting
>
>> [!bug] Charity
>> your notes or lists here. using markdown formatting


> [!multi-column]
>
>> [!Example] Work
>> - your notes or lists here. using markdown formatting
>
>> [!warning] Personal
>> - your notes or lists here. using markdown formatting


> [!multi-column]
>
>> [!note|wide-3] Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|wide-0]  Personal
>> your notes or lists here. using markdown formatting

> [!multi-column]
>
>> [!note|min-0] Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|wide-3]  Personal
>> your notes or lists here. using markdown formatting
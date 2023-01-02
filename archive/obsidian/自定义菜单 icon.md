> 在 `obsidian_orange.css` 中可找到修改菜单 icon 的代码，下面的只是示例代码。

</br>

> [!ob-note] 修改菜单操作步骤
> - 去 [iconpark](https://iconpark.oceanengine.com/official) 找到自己喜欢的图标,然后“复制为 svg 代码”
> - 通过 [svg->DataURI](https://codepen.io/jakob-e/pen/doMoML) 将 svg 代码转换为 "DataURI" 代码
> - 通过开发者工具找到菜单对应的 css 类名
> - 给菜单对应的 css 类名添加如下代码并将上面复制的 DataURI 代码作为 `background-image` 的值

示例代码:

```css
/* 更改菜单icon */
/* 图标去 https://iconpark.oceanengine.com/official 找到自己喜欢的*/
/* 通过 https://codepen.io/jakob-e/pen/doMoML 将svg转换为 dataURI */
/* 通过开发者工具找到菜单对应的css类名 */
/* 按照如下代码添加 上面复制的dataURI作为background-image */
/*obsidian-orange 已修改了左侧菜单icon */

/* https://websemantics.uk/tools/svg-to-background-image-conversion/ */

.side-dock-ribbon-action\[aria-label="打开 Markdown 格式转换器"\] svg {
 display: none;
}
.side-dock-ribbon-action\[aria-label="打开 Markdown 格式转换器"\] {
 background-image: url("data:image/svg+xml;charset=utf8,%3C?xml version='1.0' standalone='no'?%3E%3C!DOCTYPE svg PUBLIC '-//W3C//DTD SVG 1.1//EN' 'http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd'%3E%3Csvg t='1623644467415' class='icon' viewBox='0 0 1024 1024' version='1.1' xmlns='http://www.w3.org/2000/svg' p-id='17418' xmlns:xlink='http://www.w3.org/1999/xlink' width='200' height='200'%3E%3Cdefs%3E%3Cstyle type='text/css'%3E%3C/style%3E%3C/defs%3E%3Cpath d='M658.432 299.91936a120.59648 120.59648 0 1 0-120.59648 121.02144A120.832 120.832 0 0 0 658.432 299.91936z m-360.448 508.07296a79.872 79.872 0 1 0-79.872 80.14848 80.01536 80.01536 0 0 0 79.872-80.14848z m315.28448 3.16416a76.71808 76.71808 0 1 0-76.69248 76.98432 76.85632 76.85632 0 0 0 76.69248-76.98432z m323.69152-2.37568a79.08352 79.08352 0 1 0-79.08352 79.36 79.22688 79.22688 0 0 0 79.08352-79.36z' fill='%23F4CA1C' p-id='17419'%3E%3C/path%3E%3Cpath d='M874.43968 656.8448V605.184c0-48.7936-46.19776-88.48896-102.98368-88.48896h-226.36544v-39.55712a195.4048 195.4048 0 1 0-63.03232 0v39.53664H255.69792c-56.78592 0-102.98368 39.69536-102.98368 88.48896v50.78016a144.96768 144.96768 0 1 0 63.03232-3.072V605.184c0-11.87328 17.08544-25.15456 39.936-25.15456h226.37568v74.24a144.98304 144.98304 0 1 0 63.03232 0v-74.24h226.36544c22.86592 0 39.936 13.28128 39.936 25.15456v47.18592a145.07008 145.07008 0 1 0 63.04768 4.47488zM381.20448 283.38176a132.37248 132.37248 0 1 1 132.37248 133.00736 132.8384 132.8384 0 0 1-132.37248-133.00736z m-108.20608 513.024a81.92 81.92 0 1 1-81.92-82.33472 82.23744 82.23744 0 0 1 81.92 82.33472z m322.51904 0a81.92 81.92 0 1 1-81.92-82.33472 82.23232 82.23232 0 0 1 81.92 82.33472z m237.42464 82.33984a82.33984 82.33984 0 1 1 81.92-82.33984 82.23232 82.23232 0 0 1-81.92 82.33984z' fill='%23595BB3' p-id='17420'%3E%3C/path%3E%3C/svg%3E");
 background-size: 17px 17px;
 transform: translate(0px, 5px);
 background-repeat: no-repeat;
 display: inline-block;
 height: 18px;
 width: 18px;
 margin: 0 0 0 6px;
}
```

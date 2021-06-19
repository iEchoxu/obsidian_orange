#hblock/blue ==这里用来放一些在主题中没有使用的CSS 代码块，主要的代码在 obsidian_orange.css 中==
## 图片放大缩小
```css
/* Image zoom */

.view-content .markdown-preview-view img
max-width:100%
cursor:zoom-in;
.view-content .markdown-preview-view img\[referrerpolicy='no-referrer'\]:active
.view-content .image-embed:active
cursor:zoom-out
display:block
z-index:100
position:fixed
max-height:calc(100% + 1px)
max-width:calc(100% - 20px)
height:calc(100% + 1px)
width:100%
object-fit:contain
margin:-0.5px auto 0
text-align:center
padding:0
left:0
right:0
bottom:0
background:var(--background-translucent)
.view-content .markdown-preview-view img\[referrerpolicy='no-referrer'\]:active
padding:2.5%
.view-content .markdown-preview-view .image-embed:active img
top:50%
transform:translateY(-50%)
padding:0
margin:0 auto
width:auto
max-height:95vh
left:0
right:0
bottom:0
position:absolute
opacity:1
.theme-dark span\[src$="#invert"\] img
filter: invert(1) hue-rotate(180deg)
mix-blend-mode: screen
```
## 改变编辑模式下 ur 列表的文本及文本前面 - 符号的颜色
```css
/* Unordered */

.cm-formatting.cm-formatting-list.cm-formatting-list-ul.cm-list-1 {
  color: red !important;
  font-weight: bold;
  font-size: large;
}

.cm-formatting.cm-formatting-list.cm-formatting-list-ul.cm-list-2 {
  color: orange !important;
  font-weight: bold;
  font-size: large;
}

.cm-formatting.cm-formatting-list.cm-formatting-list-ul.cm-list-3 {
  color: yellow !important;
  font-weight: bold;
  font-size: large;
}

.HyperMD-list-line.HyperMD-list-line-4 .cm-formatting-list-ul.cm-list-1 {
  color: green !important;
}

.HyperMD-list-line.HyperMD-list-line-5 .cm-formatting-list-ul.cm-list-2 {
  color: blue !important;
}

.HyperMD-list-line.HyperMD-list-line-6 .cm-formatting-list-ul.cm-list-3 {
  color: purple !important;
}

/* Ordered */

.cm-formatting.cm-formatting-list.cm-formatting-list-ol.cm-list-1 {
  color: red !important;
}

.cm-formatting.cm-formatting-list.cm-formatting-list-ol.cm-list-2 {
  color: orange !important;
}

.cm-formatting.cm-formatting-list.cm-formatting-list-ol.cm-list-3 {
  color: yellow !important;
}

.HyperMD-list-line.HyperMD-list-line-4.CodeMirror-line .cm-formatting-list-ol.cm-list-1 {
  color: green !important;
}

.HyperMD-list-line.HyperMD-list-line-5.CodeMirror-line .cm-formatting-list-ol.cm-list-2 {
  color: blue !important;
}

.HyperMD-list-line.HyperMD-list-line-6.CodeMirror-line .cm-formatting-list-ol.cm-list-3 {
  color: purple !important;
}

/* Control text color for both ul and ol, not including list symbol (all levels) */

.HyperMD-list-line {
  color: var(--frost3) !important;
}

/* Control text color for both ul and ol, not including list symbol (only level 1) */ 
.HyperMD-list-line.HyperMD-list-line-1.CodeMirror-line { color: red !important; }
```
## 当url链接太长时自动截取并隐藏多余内容
```css
/* 当url链接太长时自动截取并隐藏多余内容 */
div:not(.CodeMirror-activeline) > .CodeMirror-line .cm-string.cm-url:not(.cm-formatting) {
  font-size: 0;
}
div:not(.CodeMirror-activeline) > .CodeMirror-line .cm-string.cm-url:not(.cm-formatting)::after {
  content: '🔗';
  font-size: 1rem;
}
```
## 隐藏编辑模式下标题前面的 `#`号
```css
/* 隐藏编辑模式下标题前面的 #号 */
.CodeMirror-code > :not(.CodeMirror-activeline) .cm-formatting-header {
  display:none;
}
```
## 当鼠标hover a链接时在底部显示“原文链接”
```css
/* 当鼠标hover a链接时在底部显示 原文链接 */
a.external-link {
  position: relative;
}
a.external-link:before {
  position: fixed;
  left: 0;
  bottom: 0;
  padding: 0 0.5em;
  color: var(--text-normal);
  background-color: var(--background-primary-alt);
  border: 1px solid var(--background-modifier-border);
  border-radius: 0 0.4em 0 0;
  font-family: var(--default-font);
  font-size: initial;
  font-style: initial;
  font-weight: initial;
  text-decoration: initial;
  display: none;
  z-index: 1000;
  content: attr(href);
}
a.external-link:hover:before {
  display: block;
  max-width: 98%;
  overflow: hidden;
  text-overflow: ellipsis;
  word-wrap: break-all;
  white-space: nowrap;
}
```
## ur li 同级之间用竖线连接
```css
/* ur li 同级之间用竖线连接 */
.cm-hmd-list-indent .cm-tab, ul ul { position: relative; }
.cm-hmd-list-indent .cm-tab::before, ul ul::before  {
 content:'';
 border-left: 1px solid #dee0e3;
 position: absolute;
}
.cm-hmd-list-indent .cm-tab::before { left: 0; top: -5px; bottom: -4px; 
}
ul ul::before { left: -14px; top: 0; bottom: 0; 
}
```
## links
- [awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian#css-tweaks)
-  [Obsidian CSS Themes All](https://forum.obsidian.md/t/meta-post-css-themes/76) | [kmaasrud/awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian) | [Meta Post - Common CSS Hacks](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/41)

>这里的代码没有添加进主题中，因为对于我来讲并不是刚需。
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
/* 已有最优解，这里只是将原来的代码作为备注 */
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

^1f784e

- [awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian#css-tweaks) | [Obsidian CSS 代码段 (on GitHub)](https://github.com/Dmitriy-Shulha/obsidian-css-snippets/tree/master/Snippets)
-  [Obsidian CSS Themes All](https://forum.obsidian.md/t/meta-post-css-themes/76) | [kmaasrud/awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian) | [Meta Post - Common CSS Hacks](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/41)
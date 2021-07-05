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
## 当 url 链接太长时自动截取并隐藏多余内容
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
## 当鼠标 hover a 链接时在底部显示“原文链接”
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

## 排版
```css
/* 标题设置 */
.view-header-title {
  font-size: 26px;
  font-weight: 600;
  line-height: 1.65;
  letter-spacing: .02em;
  word-wrap: break-word;
  word-break: break-word;
    
}


.markdown-preview-view h2 {
  font-size: 26px;
  font-weight: 600;
  line-height: 1.65;
  word-wrap: break-word;
  word-break: break-word;
  letter-spacing: .02em;
  margin-block-start: 1.5em;
  /* margin-block-end: 1em; */
}


.markdown-preview-view h3 {
  font-size: 22px;
  font-weight: 600;
  line-height: 1.65;
  word-wrap: break-word;
  word-break: break-word;
  letter-spacing: .02em;
  margin-block-start: 1.5em;
  /* margin-block-end: 1.2em; */
}


.markdown-preview-view h4 {
  font-size: 18px;
  font-weight: 600;
  line-height: 1.65;
  word-wrap: break-word;
  word-break: break-word;
  letter-spacing: .02em;
  margin-block-start: 1.5em;
  /* margin-block-end: 1.2em; */
}

.markdown-preview-view h5,h6 {
  font-size: 16px;
  font-weight: 600;
  line-height: 1.65;
  word-wrap: break-word;
  word-break: break-word;
  letter-spacing: .02em;
  margin-block-start: 1.5em;
  /* margin-block-end: 1.2em; */
}

h1 {
    font-family: Chinese Quote,Segoe UI,Roboto,PingFang SC,Hiragino Sans GB,Microsoft YaHei,Helvetica Neue,Helvetica,Arial,sans-serif,Apple Color Emoji;
    font-size: 36px;
    line-height: 1.389;
    font-weight: 700;
    color: #262626;
    display: inline;
    margin-right: 20px;
	word-break: break-word;
	margin-block-start: 0.83em;
    margin-block-end: 0.83em;
}

h2 {
    font-size: 24px;
	font-weight: bold;
	letter-spacing: 0.05em;
    color: #262626;
	line-height: 32px;
}


text {
      line-height: 1.74;
    letter-spacing: 0.05em;
    color: #262626;
    font-size: 14px;
	    white-space: pre-wrap;
    word-break: break-word;
    word-wrap: break-word;
}


/*空行*/
p {
  min-height: 24px;

}


h3 {
  font-size: 20px;
  font-weight: bold;
  line-height: 28px;
  margin: 7px 0;

}

/**
 * 排版设置共享内容
 */
ne-table-hole {
  margin: 4px 0 16px 0;
  -webkit-margin-after: 0px;
}
ne-table-hole[data-no-spacing] {
  margin: -12px 0 0 0;
  -webkit-margin-after: -16px;
}
/*
 * 本文件提供默认紧凑排版的基础样式设置，此处需要和各插件配合，使得 js 中获取的值和 css 中定义的值处于一致状态
 */
.ne-typography-traditional {
  line-height: 1.74;
  letter-spacing: 0.05em;
  color: #262626;
  font-size: 14px;
}
.ne-typography-traditional ne-table-box {
  line-height: 1.74;
}
.ne-typography-traditional ne-code ne-text {
  font-size: 14px;
}
.ne-typography-traditional ne-text[ne-sub],
.ne-typography-traditional ne-text[ne-sup] {
  font-size: 10.5px;
}
.ne-typography-traditional ne-h1 {
  font-size: 28px;
  line-height: 36px;
  margin: 7px 0;
}
.ne-typography-traditional ne-h1:first-child {
  margin-top: 0;
}
.ne-typography-traditional ne-h1 ne-text {
  font-size: 28px;
}
.ne-typography-traditional ne-h2 {
  font-size: 24px;
  line-height: 32px;
  margin: 7px 0;
}
.ne-typography-traditional ne-h2:first-child {
  margin-top: 0;
}
.ne-typography-traditional ne-h2 ne-text {
  font-size: 24px;
}
.ne-typography-traditional ne-h3 {
  font-size: 20px;
  line-height: 28px;
  margin: 7px 0;
}
.ne-typography-traditional ne-h3:first-child {
  margin-top: 0;
}
.ne-typography-traditional ne-h3 ne-text {
  font-size: 20px;
}
.ne-typography-traditional ne-h4 {
  font-size: 16px;
  line-height: 24px;
  margin: 7px 0;
}
.ne-typography-traditional ne-h4:first-child {
  margin-top: 0;
}
.ne-typography-traditional ne-h4 ne-text {
  font-size: 16px;
}
.ne-typography-traditional ne-h5 {
  font-size: 14px;
  line-height: 24px;
  margin: 7px 0;
}
.ne-typography-traditional ne-h5:first-child {
  margin-top: 0;
}
.ne-typography-traditional ne-h5 ne-text {
  font-size: 14px;
}
.ne-typography-traditional ne-h6 {
  font-size: 14px;
  line-height: 24px;
  margin: 7px 0;
}
.ne-typography-traditional ne-h6:first-child {
  margin-top: 0;
}
.ne-typography-traditional ne-h6 ne-text {
  font-size: 14px;
}
.ne-typography-traditional ne-tli ne-tli-i.ant-checkbox {
  padding-top: 1px;
}

h1,h2,h3,h4,h5,h6,h7 {
	font-weight: 600;
	letter-spacing: .02em;
	line-height: 1.65;
	word-wrap: break-word;
    word-break: break-word;
    padding-left: 20px;
    padding-right: 40px;
    padding-bottom: 18px;

}

h2 {
	font-size: 22px;
    margin-bottom: 8px;

}
h3 {
    font-size: 20px;
    margin-bottom: 8px;
}

h4 {
    font-size: 18px;
    margin-bottom: 8px;
}


h5,h6 {
	    font-size: 16px;

}

text {
	font-size: 16px;
    line-height: 1.65;
    color: #1f2329;
}


```

## tag 颜色
```css
.tag[href="#important"] { color : red; }

.tag {
  background-color: var(--text-accent);
  border: none;
  color: white;
  font-size: 11px;
  padding: 1px 8px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  margin: 0px 0px;
  cursor: pointer;
  border-radius: 14px;
}
.tag:hover {
color: white;
background-color: var(--text-accent-hover);
}
.tag[href^="#obsidian"] {
  background-color: #4d3ca6;
}
.tag[href^="#important"] {
  background-color: red;
}
.tag[href^="#complete"] {
  background-color: green;
}
.tag[href^="#inprogress"] {
  background-color: orange;
}


/* ====== Tag Pills ======== */
.tag:not(.token) {
	background-color: var(--text-accent);
	border: none;
	color: white;
	font-size: 11px;
	padding: 1px 8px;
	text-align: center;
	text-decoration: none;
	display: inline-block;
	margin: 0px 0px;
	cursor: pointer;
	border-radius: 14px;
}
.tag:not(.token):hover {
	color: white;
	background-color: var(--text-accent-hover);
}
.tag[href^="#obsidian"] {
	background-color: #4d3ca6;
}
.tag[href^="#important"] {
	background-color: red;
}
.tag[href^="#complete"] {
	background-color: green;
}
.tag[href^="#inprogress"] {
	background-color: orange;
}

```
## Links

^1f784e

- [awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian#css-tweaks) | [Obsidian CSS 代码段 (on GitHub)](https://github.com/Dmitriy-Shulha/obsidian-css-snippets/tree/master/Snippets)
-  [Obsidian CSS Themes All](https://forum.obsidian.md/t/meta-post-css-themes/76) | [kmaasrud/awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian) | [Meta Post - Common CSS Hacks](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/41)
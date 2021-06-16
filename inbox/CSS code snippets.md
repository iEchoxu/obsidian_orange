#hblock/blue ==在win/mac下通过 Ctrl+Shift+I/command+option+i  可以打开控制台（一种调试网页html的工具），然后可以通过控制台来对相关的元素进行修改==

#hbgtext/orange ==主要的代码在 obsidian_orange.css 中==

```
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
## links
- [awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian#css-tweaks)
-  [Obsidian CSS Themes All](https://forum.obsidian.md/t/meta-post-css-themes/76) | [kmaasrud/awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian) | [Meta Post - Common CSS Hacks](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/41)
>这里的代码没有添加进主题中，因为对于我来讲并不是刚需。

## 文本高亮与高亮块
```css
/* ----------------------------------------- 编辑模式下 文本高亮 ---------------------------------------------- */

/*使用方法：#htext/orange ==测试更改文字颜色== */
/*使用方法：#hbgtext/orange ==带有背景颜色的文本高亮==  */
/*使用方法：#hblock/orange ==这是用hblock标签实现的高亮块== */

/* -- orange -- */

.theme-light .cm-tag-htextorange ~ span.cm-highlight,

.theme-dark .cm-tag-htextorange ~ span.cm-highlight {

color: rgb(222, 120, 2) !important;

background-color: transparent !important;

font-weight: 500;

}

  
  

/* -- gray -- */

.theme-light .cm-tag-htextgray ~ span.cm-highlight,

.theme-dark .cm-tag-htextgray ~ span.cm-highlight {

color: rgb(143, 149, 158) !important;

background-color: transparent !important;

font-weight: 500;

}

  
  

/* -- red -- */

.theme-light .cm-tag-htextred ~ span.cm-highlight,

.theme-dark .cm-tag-htextred ~ span.cm-highlight {

color: rgb(216, 57, 49) !important;

background-color: transparent !important;

font-weight: 500;

}

  
  

/* -- green -- */

.theme-light .cm-tag-htextgreen ~ span.cm-highlight,

.theme-dark .cm-tag-htextgreen ~ span.cm-highlight {

color: rgb(46, 161, 33) !important;

background-color: transparent !important;

font-weight: 500;

}

  
  

/* -- purple -- */

.theme-light .cm-tag-htextpurple ~ span.cm-highlight,

.theme-dark .cm-tag-htextpurple ~ span.cm-highlight {

color: rgb(100, 37, 208) !important;

background-color: transparent !important;

font-weight: 500;

}

  
  

/* -- blue -- */

.theme-light .cm-tag-htextblue ~ span.cm-highlight,

.theme-dark .cm-tag-htextblue ~ span.cm-highlight {

color: rgb(36, 91, 219) !important;

background-color: transparent !important;

font-weight: 500;

}

  
  
  
  

/* ----------------------------------------- 编辑模式下 带有背景颜色的文本高亮 ---------------------------------------------- */

  

/* -- orange -- */

.theme-light .cm-tag-hbgtextorange ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextorange ~ span.cm-highlight {

background-color: rgba(254, 212, 164, 0.8) !important;

color: rgb(222, 120, 2) !important;

}

  
  

/* -- yellow -- */

.theme-light .cm-tag-hbgtextyellow ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextyellow ~ span.cm-highlight {

background-color: #fff3cd !important;

color: #856404 !important;

}

  
  

/* -- pink -- */

.theme-light .cm-tag-hbgtextpink ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextpink ~ span.cm-highlight {

background-color: #f8d7da !important;

color: #721c24 !important;

}

  
  

/* -- blue -- */

.theme-light .cm-tag-hbgtextblue ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextblue ~ span.cm-highlight {

background-color: rgba(186, 206, 253, 0.7) !important;

color: rgb(36, 91, 219) !important;

}

  
  

/* -- red -- */

.theme-light .cm-tag-hbgtextred ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextred ~ span.cm-highlight {

background-color: rgb(251, 191, 188) !important;

color: rgb(216, 57, 49) !important;

}

  
  

/* -- green -- */

.theme-light .cm-tag-hbgtextgreen ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextgreen ~ span.cm-highlight {

background-color: rgba(183, 237, 177, 0.8) !important;

color: rgb(46, 161, 33) !important;

}

  
  

/* -- skyblue -- */

.theme-light .cm-tag-hbgtextskyblue ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextskyblue ~ span.cm-highlight {

background-color: #d4edda !important;

color: #689ba3 !important;

}

  
  

/* -- purple -- */

.theme-light .cm-tag-hbgtextpurple ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextpurple ~ span.cm-highlight {

background-color: rgba(205, 178, 250, 0.7) !important;

color: rgb(100, 37, 208) !important;

}

  
  

/* -- hjblue -- */

.theme-light .cm-tag-hbgtexthjblue ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtexthjblue ~ span.cm-highlight {

background-color: #d1ecf1 !important;

color: #35737d !important;

}

  
  

/* -- gray -- */

.theme-light .cm-tag-hbgtextgray ~ span.cm-highlight,

.theme-dark .cm-tag-hbgtextgray ~ span.cm-highlight {

background-color: rgba(222, 224, 227, 0.8) !important;

color: rgb(143, 149, 158) !important;

}

  
  
  
  

/* ----------------------------------------- 编辑模式下 高亮块 ---------------------------------------------- */

  

/* -- highlight orange -- */

.theme-light .cm-tag-hblockorange ~ span.cm-highlight,

.theme-dark .cm-tag-hblockorange ~ span.cm-highlight {

background-color: rgb(254, 234, 210) !important;

color: rgb(222, 120, 2) !important;

}

  
  

/* -- highlight blue -- */

.theme-light .cm-tag-hblockblue ~ span.cm-highlight,

.theme-dark .cm-tag-hblockblue ~ span.cm-highlight {

background-color: rgb(225, 234, 255) !important;

color: rgb(36, 91, 219) !important;

}

  
  

/* -- highlight red -- */

.theme-light .cm-tag-hblockred ~ span.cm-highlight,

.theme-dark .cm-tag-hblockred ~ span.cm-highlight {

background-color: rgb(253, 226, 226) !important;

color: rgb(216, 57, 49) !important;

}

  
  

/* -- highlight green -- */

.theme-light .cm-tag-hblockgreen ~ span.cm-highlight,

.theme-dark .cm-tag-hblockgreen ~ span.cm-highlight {

background-color: rgb(217, 245, 214) !important;

color: rgb(46, 161, 33) !important;

}

  
  

/* -- highlight purple -- */

.theme-light .cm-tag-hblockpurple ~ span.cm-highlight,

.theme-dark .cm-tag-hblockpurple ~ span.cm-highlight {

background-color: rgb(236, 226, 254) !important;

color: rgb(100, 37, 208) !important;

}

  
  
  
  

/* ----------------------------------------- Preview mode ---------------------------------------------- */

  

/* ----------------------------------------- 在此添加自定义标题（不要移动到其他位置） ---------------------------------------------- */

  

/* 标签以 #htext 开头时，代表 “文本高亮” */

.theme-light a[href^="#htext/"],

.theme-dark a[href^="#htext/"] {

display:none !important;

}

.theme-light a[href^="#htext/"] + mark,

.theme-dark a[href^="#htext/"] + mark {

color: white !important;

font-weight: bold;

}

  
  

/* 标签以 #hbgtext 开头时，代表 “带有背景颜色的文本高亮” */

.theme-light a[href^="#hbgtext/"],

.theme-dark a[href^="#hbgtext/"] {

display:none;

}

.theme-light a[href^="#hbgtext/"] + mark,

.theme-dark a[href^="#hbgtext/"] + mark {

color: white;

padding: 4px 5px;

font-weight: 500;

}

  
  

/* 标签以 #hblock 开头时，代表 “定义了一个高亮块” */

.theme-light a[href^="#hblock/"],

.theme-dark a[href^="#hblock/"]{

display:none !important;

}

.theme-light a[href^="#hblock/"] + mark,

.theme-dark a[href^="#hblock/"] + mark {

color: white !important;

border-radius: 5px;

padding-left: 5px;

padding-right: 5px;

font-weight: bold;

}

  
  
  
  

/* ----------------------------------------- 预览模式下 文本高亮 ---------------------------------------------- */

  

/* -- orange -- */

.theme-light a[href^="#htext/orange"] + mark,

.theme-dark a[href^="#htext/orange"] + mark {

background-color: transparent !important;

color: rgb(222, 120, 2) !important;

font-weight: 500;

}

  
  

/* -- gray -- */

.theme-light a[href^="#htext/gray"] + mark,

.theme-dark a[href^="#htext/gray"] + mark {

background-color: transparent !important;

color: rgb(143, 149, 158) !important;

font-weight: 500;

}

  
  

/* -- blue -- */

.theme-light a[href^="#htext/blue"] + mark,

.theme-dark a[href^="#htext/blue"] + mark {

background-color: transparent !important;

color: rgb(36, 91, 219) !important;

font-weight: 500;

}

  
  

/* -- red -- */

.theme-light a[href^="#htext/red"] + mark,

.theme-dark a[href^="#htext/red"] + mark {

background-color: transparent !important;

color: rgb(216, 57, 49) !important;

font-weight: 500;

}

  
  

/* -- green -- */

.theme-light a[href^="#htext/green"] + mark,

.theme-dark a[href^="#htext/green"] + mark {

background-color: transparent !important;

color: rgb(46, 161, 33) !important;

font-weight: 500;

}

  
  

/* -- purple -- */

.theme-light a[href^="#htext/purple"] + mark,

.theme-dark a[href^="#htext/purple"] + mark {

background-color: transparent !important;

color: rgb(100, 37, 208) !important;

font-weight: 500;

}

  
  
  
  

/* ----------------------------------------- 预览模式下 带有背景颜色的文本高亮 ---------------------------------------------- */

  

/* -- orange -- */

.theme-light a[href^="#hbgtext/orange"] + mark,

.theme-dark a[href^="#hbgtext/orange"] + mark {

background-color: rgba(254, 212, 164, 0.8) !important;

color: rgb(222, 120, 2) !important;

}

  
  

/* -- yellow -- */

.theme-light a[href^="#hbgtext/yellow"] + mark,

.theme-dark a[href^="#hbgtext/yellow"] + mark {

background-color: #fff3cd !important;

color: #856404 !important;

}

  
  

/* -- red -- */

.theme-light a[href^="#hbgtext/red"] + mark,

.theme-dark a[href^="#hbgtext/red"] + mark {

background-color: rgb(251, 191, 188) !important;

color: rgb(216, 57, 49) !important;

}

  

/* -- green -- */

.theme-light a[href^="#hbgtext/green"] + mark,

.theme-dark a[href^="#hbgtext/green"] + mark {

background-color: rgba(183, 237, 177, 0.8) !important;

color: rgb(46, 161, 33) !important;

}

  
  

/* -- pink -- */

.theme-light a[href^="#hbgtext/pink"] + mark,

.theme-dark a[href^="#hbgtext/pink"] + mark {

background-color: #f8d7da !important;

color: #721c24 !important;

}

  
  

/* -- blue -- */

.theme-light a[href^="#hbgtext/blue"] + mark,

.theme-dark a[href^="#hbgtext/blue"] + mark {

background-color: rgba(186, 206, 253, 0.7) !important;

color: rgb(36, 91, 219) !important;

}

  
  

/* -- skyblue -- */

.theme-light a[href^="#hbgtext/skyblue"] + mark,

.theme-dark a[href^="#hbgtext/skyblue"] + mark {

background-color: #d4edda !important;

color: #689ba3 !important;

}

  
  

/* -- hjblue -- */

.theme-light a[href^="#hbgtext/hjblue"] + mark,

.theme-dark a[href^="#hbgtext/hjblue"] + mark {

background-color: #d1ecf1 !important;

color: #35737d !important;

}

  
  

/* -- purple -- */

.theme-light a[href^="#hbgtext/purple"] + mark,

.theme-dark a[href^="#hbgtext/purple"] + mark {

background-color: rgba(205, 178, 250, 0.7) !important;

color: rgb(100, 37, 208) !important;

}

  
  

/* -- gray -- */

.theme-light a[href^="#hbgtext/gray"] + mark,

.theme-dark a[href^="#hbgtext/gray"] + mark {

background-color: rgba(222, 224, 227, 0.8) !important;

color: rgb(143, 149, 158) !important;

}

  
  

/* ----------------------------------------- 预览模式下 高亮块 ---------------------------------------------- */

  

/* -- highlight orange -- */

.theme-light a[href^="#hblock/orange"] + mark,

.theme-dark a[href^="#hblock/orange"] + mark {

background-color: rgb(254, 234, 210) !important;

display: block;

color: rgb(222, 120, 2) !important;

padding: 20px 10px;

border: 1px solid rgb(254, 212, 164);

font-weight: 500 !important;

}

  
  

/* -- highlight blue -- */

.theme-light a[href^="#hblock/blue"] + mark,

.theme-dark a[href^="#hblock/blue"] + mark {

background-color: rgb(225, 234, 255) !important;

display: block;

color: rgb(36, 91, 219) !important;

padding: 20px 10px;

border: 1px solid rgb(130, 167, 252);

font-weight: 500 !important;

}

  
  

/* -- highlight red -- */

.theme-light a[href^="#hblock/red"] + mark,

.theme-dark a[href^="#hblock/red"] + mark {

background-color: rgb(253, 226, 226) !important;

border: 1px solid rgb(249, 142, 139);

color: rgb(216, 57, 49) !important;

display: block;

padding: 20px 10px;

font-weight: 500 !important;

}

  
  

/* -- highlight green -- */

.theme-light a[href^="#hblock/green"] + mark,

.theme-dark a[href^="#hblock/green"] + mark {

background-color: rgb(217, 245, 214) !important;

border: 1px solid rgb(142, 224, 133);

color: rgb(46, 161, 33) !important;

display: block;

padding: 20px 10px;

font-weight: 500 !important;

}

  
  

/* -- highlight purple -- */

.theme-light a[href^="#hblock/purple"] + mark,

.theme-dark a[href^="#hblock/purple"] + mark {

background-color: rgb(236, 226, 254) !important;

border: 1px solid rgb(173, 130, 247);

color: rgb(100, 37, 208) !important;

/* color: #000 !important; */

display: block;

padding: 20px 10px;

font-weight: 500 !important;

}


/* 用admontion实现高亮块功能 */

.admonition.admonition-orange .admonition-title {

display: none;

}

.admonition.admonition-orange .admonition-title-content {

display: none;

}

.admonition.admonition-orange .admonition-title-icon {

display: none;

}

.admonition.admonition-orange {

background-color: rgb(254, 234, 210) !important;

border: 1px solid rgb(254, 212, 164);

color: rgb(222, 120, 2) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-orange ul > li:not(.task-list-item)::before {

color: rgb(222, 120, 2) !important;

}

  
  

.admonition.admonition-light-orange .admonition-title {

display: none;

}

.admonition.admonition-light-orange .admonition-title-content {

display: none;

}

.admonition.admonition-light-orange .admonition-title-icon {

display: none;

}

.admonition.admonition-light-orange {

background-color: rgb(255, 245, 235) !important;

border: 1px solid rgb(254, 212, 164);

color: rgb(222, 120, 2) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-light-orange ul > li:not(.task-list-item)::before {

color: rgb(222, 120, 2) !important;

}

  
  

.admonition.admonition-blue .admonition-title {

display: none;

}

.admonition.admonition-blue .admonition-title-content {

display: none;

}

.admonition.admonition-blue .admonition-title-icon {

display: none;

}

.admonition.admonition-blue {

border: 1px solid rgb(130, 167, 252);

background-color: rgb(225, 234, 255) !important;

color: rgb(36, 91, 219) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-blue ul > li:not(.task-list-item)::before {

color: rgb(36, 91, 219) !important;

}

  
  

.admonition.admonition-light-blue .admonition-title {

display: none;

}

.admonition.admonition-light-blue .admonition-title-content {

display: none;

}

.admonition.admonition-light-blue .admonition-title-icon {

display: none;

}

.admonition.admonition-light-blue {

background-color: rgb(240, 244, 255) !important;

border: 1px solid rgb(186, 206, 253);

color: rgb(36, 91, 219) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-light-blue ul > li:not(.task-list-item)::before {

color: rgb(36, 91, 219) !important;

}

  
  

.admonition.admonition-Light-red .admonition-title {

display: none;

}

.admonition.admonition-Light-red .admonition-title-content {

display: none;

}

.admonition.admonition-Light-red .admonition-title-icon {

display: none;

}

.admonition.admonition-Light-red {

background-color: rgb(254, 241, 241) !important;

border: 1px solid rgb(251, 191, 188);

color: rgb(216, 57, 49) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-Light-red ul > li:not(.task-list-item)::before {

color: rgb(216, 57, 49) !important;

}

  
  

.admonition.admonition-red .admonition-title {

display: none;

}

.admonition.admonition-red .admonition-title-content {

display: none;

}

.admonition.admonition-red .admonition-title-icon {

display: none;

}

.admonition.admonition-red {

background-color: rgb(253, 226, 226) !important;

color: rgb(216, 57, 49) !important;

border: 1px solid rgb(249, 142, 139);

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-red ul > li:not(.task-list-item)::before {

color: rgb(216, 57, 49) !important;

}

  
  

.admonition.admonition-green .admonition-title {

display: none;

}

.admonition.admonition-green .admonition-title-content {

display: none;

}

.admonition.admonition-green .admonition-title-icon {

display: none;

}

.admonition.admonition-green {

background-color: rgb(217, 245, 214) !important;

color: rgb(46, 161, 33) !important;

border: 1px solid rgb(142, 224, 133);

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-green ul > li:not(.task-list-item)::before {

color: rgb(46, 161, 33) !important;

}

  
  

.admonition.admonition-light-green .admonition-title {

display: none;

}

.admonition.admonition-light-green .admonition-title-content {

display: none;

}

.admonition.admonition-light-green .admonition-title-icon {

display: none;

}

.admonition.admonition-light-green {

background-color: rgb(240, 251, 239) !important;

color: rgb(46, 161, 33) !important;

border: 1px solid rgb(183, 237, 177);

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-light-green ul > li:not(.task-list-item)::before {

color: rgb(46, 161, 33) !important;

}

  
  

.admonition.admonition-purple .admonition-title {

display: none;

}

.admonition.admonition-purple .admonition-title-content {

display: none;

}

.admonition.admonition-purple .admonition-title-icon {

display: none;

}

.admonition.admonition-purple {

background-color: rgb(236, 226, 254) !important;

color: rgb(100, 37, 208) !important;

border: 1px solid rgb(173, 130, 247);

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-purple ul > li:not(.task-list-item)::before {

color: rgb(100, 37, 208) !important;

}

  
  

.admonition.admonition-light-purple .admonition-title {

display: none;

}

.admonition.admonition-light-purple .admonition-title-content {

display: none;

}

.admonition.admonition-light-purple .admonition-title-icon {

display: none;

}

.admonition.admonition-light-purple {

background-color: rgb(246, 241, 254) !important;

border: 1px solid rgb(205, 178, 250);

color: rgb(100, 37, 208) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-light-purple ul > li:not(.task-list-item)::before {

color: rgb(100, 37, 208) !important;

}

  
  

.admonition.admonition-gray .admonition-title {

display: none;

}

.admonition.admonition-gray .admonition-title-content {

display: none;

}

.admonition.admonition-gray .admonition-title-icon {

display: none;

}

.admonition.admonition-gray {

background-color: rgb(245, 246, 247) !important;

border: 1px solid rgb(187, 191, 196) !important;

color: rgb(143, 149, 158) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-gray ul > li:not(.task-list-item)::before {

color: rgb(143, 149, 158) !important;

}

  
  

.admonition.admonition-light-gray .admonition-title {

display: none;

}

.admonition.admonition-light-gray .admonition-title-content {

display: none;

}

.admonition.admonition-light-gray .admonition-title-icon {

display: none;

}

.admonition.admonition-light-gray {

background-color: rgb(248, 249, 250) !important;

border: 1px solid rgb(222, 224, 227);

color: rgb(143, 149, 158) !important;

border-radius: 5px;

}

.markdown-preview-view .admonition.admonition-light-gray ul > li:not(.task-list-item)::before {

color: rgb(143, 149, 158) !important;

}

  
  

.admonition code {

background-color: transparent !important;

}
```

## 更改菜单 icon
```css
/* 更改菜单icon */

.side-dock-ribbon-action[aria-label="打开快速切换"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="打开快速切换"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M23 4V27H43.9933L44 4H23Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M31.0049 43.9998C24.6752 43.9998 20.5595 43.9998 18.6579 43.9998C16.9557 43.9998 14.9159 43.4318 13.5475 41.6126C12.6229 40.3832 12.0049 38.5826 12.0049 35.9998C12.0049 31.7298 12.0049 28.063 12.0049 24.9995' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M4 32.9998L12.0046 24.9995L20.0138 32.9998' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M30 19H37' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M30 12H37' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="打开快速切换"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M23 4V27H43.9933L44 4H23Z' fill='%23ceddfd' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M31.0049 43.9998C24.6752 43.9998 20.5595 43.9998 18.6579 43.9998C16.9557 43.9998 14.9159 43.4318 13.5475 41.6126C12.6229 40.3832 12.0049 38.5826 12.0049 35.9998C12.0049 31.7298 12.0049 28.063 12.0049 24.9995' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M4 32.9998L12.0046 24.9995L20.0138 32.9998' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M30 19H37' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M30 12H37' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="查看关系图谱"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="查看关系图谱"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M8 12C10.2091 12 12 10.2091 12 8C12 5.79086 10.2091 4 8 4C5.79086 4 4 5.79086 4 8C4 10.2091 5.79086 12 8 12Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M10 42C13.3137 42 16 39.3137 16 36C16 32.6863 13.3137 30 10 30C6.68629 30 4 32.6863 4 36C4 39.3137 6.68629 42 10 42Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M38 44C41.3137 44 44 41.3137 44 38C44 34.6863 41.3137 32 38 32C34.6863 32 32 34.6863 32 38C32 41.3137 34.6863 44 38 44Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M22 28C26.4183 28 30 24.4183 30 20C30 15.5817 26.4183 12 22 12C17.5817 12 14 15.5817 14 20C14 24.4183 17.5817 28 22 28Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M34 12C36.2091 12 38 10.2091 38 8C38 5.79086 36.2091 4 34 4C31.7909 4 30 5.79086 30 8C30 10.2091 31.7909 12 34 12Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M11 11L15 15' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M30 12L28 14' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M34 33.5L28 26' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M14 31L18 27' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="查看关系图谱"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M8 12C10.2091 12 12 10.2091 12 8C12 5.79086 10.2091 4 8 4C5.79086 4 4 5.79086 4 8C4 10.2091 5.79086 12 8 12Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M10 42C13.3137 42 16 39.3137 16 36C16 32.6863 13.3137 30 10 30C6.68629 30 4 32.6863 4 36C4 39.3137 6.68629 42 10 42Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M38 44C41.3137 44 44 41.3137 44 38C44 34.6863 41.3137 32 38 32C34.6863 32 32 34.6863 32 38C32 41.3137 34.6863 44 38 44Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M22 28C26.4183 28 30 24.4183 30 20C30 15.5817 26.4183 12 22 12C17.5817 12 14 15.5817 14 20C14 24.4183 17.5817 28 22 28Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M34 12C36.2091 12 38 10.2091 38 8C38 5.79086 36.2091 4 34 4C31.7909 4 30 5.79086 30 8C30 10.2091 31.7909 12 34 12Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M11 11L15 15' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M30 12L28 14' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M34 33.5L28 26' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M14 31L18 27' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="打开命令面板"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="打开命令面板"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect x='4' y='8' width='40' height='32' rx='2' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M4 10C4 8.89543 4.89543 8 6 8H42C43.1046 8 44 8.89543 44 10V16H4V10Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M25 23L23 34' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M31 23L37 28L31 34' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 23L11 28L17 34' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="打开命令面板"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect x='4' y='8' width='40' height='32' rx='2' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M4 10C4 8.89543 4.89543 8 6 8H42C43.1046 8 44 8.89543 44 10V16H4V10Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M25 23L23 34' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M31 23L37 28L31 34' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 23L11 28L17 34' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="打开 Markdown 格式转换器"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="打开 Markdown 格式转换器"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M40 23V14L31 4H10C8.89543 4 8 4.89543 8 6V42C8 43.1046 8.89543 44 10 44H22' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M27 33H41' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M27 39H41' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M41 33L36 28' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M32 44L27 39' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M30 4V14H40' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="打开 Markdown 格式转换器"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M40 23V14L31 4H10C8.89543 4 8 4.89543 8 6V42C8 43.1046 8.89543 44 10 44H22' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M27 33H41' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M27 39H41' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M41 33L36 28' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M32 44L27 39' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M30 4V14H40' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="创建新的 ZK 卡片"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="创建新的 ZK 卡片"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M19 10V7C19 5.89543 19.8954 5 21 5H41C42.1046 5 43 5.89543 43 7V29C43 30.1046 42.1046 31 41 31H37' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Crect x='5' y='18' width='24' height='24' rx='2' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 25V35' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M12 30H22' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="创建新的 ZK 卡片"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M19 10V7C19 5.89543 19.8954 5 21 5H41C42.1046 5 43 5.89543 43 7V29C43 30.1046 42.1046 31 41 31H37' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Crect x='5' y='18' width='24' height='24' rx='2' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 25V35' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M12 30H22' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="打开其他库"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="打开其他库"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Ccircle cx='13.7146' cy='13.7143' r='6.85714' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Ccircle cx='34.2859' cy='34.2857' r='6.85714' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M24.001 44.0002C12.9553 44.0002 4.00098 35.0459 4.00098 24.0002L10.6676 27.3335' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M24.001 4.00021C35.0467 4.00021 44.001 12.9545 44.001 24.0002L37.3343 20.6669' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="打开其他库"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Ccircle cx='13.7146' cy='13.7143' r='6.85714' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Ccircle cx='34.2859' cy='34.2857' r='6.85714' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M24.001 44.0002C12.9553 44.0002 4.00098 35.0459 4.00098 24.0002L10.6676 27.3335' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M24.001 4.00021C35.0467 4.00021 44.001 12.9545 44.001 24.0002L37.3343 20.6669' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="帮助"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="帮助"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M39 6H9C7.34315 6 6 7.34315 6 9V39C6 40.6569 7.34315 42 9 42H39C40.6569 42 42 40.6569 42 39V9C42 7.34315 40.6569 6 39 6Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 28.6249V24.6249C27.3137 24.6249 30 21.9386 30 18.6249C30 15.3112 27.3137 12.6249 24 12.6249C20.6863 12.6249 18 15.3112 18 18.6249' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M24 37.6249C25.3807 37.6249 26.5 36.5056 26.5 35.1249C26.5 33.7442 25.3807 32.6249 24 32.6249C22.6193 32.6249 21.5 33.7442 21.5 35.1249C21.5 36.5056 22.6193 37.6249 24 37.6249Z' fill='%23999999'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="帮助"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M39 6H9C7.34315 6 6 7.34315 6 9V39C6 40.6569 7.34315 42 9 42H39C40.6569 42 42 40.6569 42 39V9C42 7.34315 40.6569 6 39 6Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 28.6249V24.6249C27.3137 24.6249 30 21.9386 30 18.6249C30 15.3112 27.3137 12.6249 24 12.6249C20.6863 12.6249 18 15.3112 18 18.6249' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M24 37.6249C25.3807 37.6249 26.5 36.5056 26.5 35.1249C26.5 33.7442 25.3807 32.6249 24 32.6249C22.6193 32.6249 21.5 33.7442 21.5 35.1249C21.5 36.5056 22.6193 37.6249 24 37.6249Z' fill='%230A59F7'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

  

.side-dock-ribbon-action[aria-label="设置"] svg {

display: none;

}

.side-dock-ribbon-action[aria-label="设置"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M36.686 15.171C37.9364 16.9643 38.8163 19.0352 39.2147 21.2727H44V26.7273H39.2147C38.8163 28.9648 37.9364 31.0357 36.686 32.829L40.0706 36.2137L36.2137 40.0706L32.829 36.686C31.0357 37.9364 28.9648 38.8163 26.7273 39.2147V44H21.2727V39.2147C19.0352 38.8163 16.9643 37.9364 15.171 36.686L11.7863 40.0706L7.92939 36.2137L11.314 32.829C10.0636 31.0357 9.18372 28.9648 8.78533 26.7273H4V21.2727H8.78533C9.18372 19.0352 10.0636 16.9643 11.314 15.171L7.92939 11.7863L11.7863 7.92939L15.171 11.314C16.9643 10.0636 19.0352 9.18372 21.2727 8.78533V4H26.7273V8.78533C28.9648 9.18372 31.0357 10.0636 32.829 11.314L36.2137 7.92939L40.0706 11.7863L36.686 15.171Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 29C26.7614 29 29 26.7614 29 24C29 21.2386 26.7614 19 24 19C21.2386 19 19 21.2386 19 24C19 26.7614 21.2386 29 24 29Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.side-dock-ribbon-action[aria-label="设置"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M36.686 15.171C37.9364 16.9643 38.8163 19.0352 39.2147 21.2727H44V26.7273H39.2147C38.8163 28.9648 37.9364 31.0357 36.686 32.829L40.0706 36.2137L36.2137 40.0706L32.829 36.686C31.0357 37.9364 28.9648 38.8163 26.7273 39.2147V44H21.2727V39.2147C19.0352 38.8163 16.9643 37.9364 15.171 36.686L11.7863 40.0706L7.92939 36.2137L11.314 32.829C10.0636 31.0357 9.18372 28.9648 8.78533 26.7273H4V21.2727H8.78533C9.18372 19.0352 10.0636 16.9643 11.314 15.171L7.92939 11.7863L11.7863 7.92939L15.171 11.314C16.9643 10.0636 19.0352 9.18372 21.2727 8.78533V4H26.7273V8.78533C28.9648 9.18372 31.0357 10.0636 32.829 11.314L36.2137 7.92939L40.0706 11.7863L36.686 15.171Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 29C26.7614 29 29 26.7614 29 24C29 21.2386 26.7614 19 24 19C21.2386 19 19 21.2386 19 24C19 26.7614 21.2386 29 24 29Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.graph-controls-button.mod-open[aria-label="打开图谱设置"] svg {

display: none;

}

.graph-controls-button.mod-open[aria-label="打开图谱设置"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M18.2838 43.1712C14.9327 42.1735 11.9498 40.3212 9.58787 37.8669C10.469 36.8226 11 35.4733 11 34C11 30.6863 8.31371 28 5 28C4.79955 28 4.60139 28.0098 4.40599 28.029C4.13979 26.7276 4 25.3801 4 24C4 21.9094 4.32077 19.8937 4.91579 17.9994C4.94381 17.9998 4.97188 18 5 18C8.31371 18 11 15.3137 11 12C11 11.0487 10.7786 10.1491 10.3846 9.34999C12.6975 7.19937 15.5205 5.5899 18.6521 4.72302C19.6444 6.66807 21.6667 8.00001 24 8.00001C26.3333 8.00001 28.3556 6.66807 29.3479 4.72302C32.4795 5.5899 35.3025 7.19937 37.6154 9.34999C37.2214 10.1491 37 11.0487 37 12C37 15.3137 39.6863 18 43 18C43.0281 18 43.0562 17.9998 43.0842 17.9994C43.6792 19.8937 44 21.9094 44 24C44 25.3801 43.8602 26.7276 43.594 28.029C43.3986 28.0098 43.2005 28 43 28C39.6863 28 37 30.6863 37 34C37 35.4733 37.531 36.8226 38.4121 37.8669C36.0502 40.3212 33.0673 42.1735 29.7162 43.1712C28.9428 40.7518 26.676 39 24 39C21.324 39 19.0572 40.7518 18.2838 43.1712Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 31C27.866 31 31 27.866 31 24C31 20.134 27.866 17 24 17C20.134 17 17 20.134 17 24C17 27.866 20.134 31 24 31Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

  
  

/* 文件管理器菜单 */

.workspace-tab-header[aria-label="文件列表"] svg {

display: none;

}

.workspace-tab-header[aria-label="文件列表"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M9 18V42H39V18L24 6L9 18Z' fill='none'/%3E%3Cpath d='M9 42V18L4 22L24 6L44 22L39 18V42H9Z' stroke='%239c9fa5' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M19 29V42H29V29H19Z' fill='none' stroke='%239c9fa5' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M9 42H39' stroke='%239c9fa5' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.workspace-tab-header[aria-label="文件列表"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M9 18V42H39V18L24 6L9 18Z' fill='none'/%3E%3Cpath d='M9 42V18L4 22L24 6L44 22L39 18V42H9Z' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M19 29V42H29V29H19Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M9 42H39' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.workspace-tab-header[aria-label="搜索"] svg {

display: none;

}

.workspace-tab-header[aria-label="搜索"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M4 7.00012H44' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M4 23.0001H15' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M4 39.0001H15' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M31.5 34.0001C36.1944 34.0001 40 30.1945 40 25.5001C40 20.8057 36.1944 17.0001 31.5 17.0001C26.8056 17.0001 23 20.8057 23 25.5001C23 30.1945 26.8056 34.0001 31.5 34.0001Z' fill='none' stroke='%23999999' stroke-width='4'/%3E%3Cpath d='M37 32.0001L44 39.0506' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.workspace-tab-header[aria-label="搜索"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M4 7.00012H44' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M4 23.0001H15' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M4 39.0001H15' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M31.5 34.0001C36.1944 34.0001 40 30.1945 40 25.5001C40 20.8057 36.1944 17.0001 31.5 17.0001C26.8056 17.0001 23 20.8057 23 25.5001C23 30.1945 26.8056 34.0001 31.5 34.0001Z' fill='none' stroke='%230A59F7' stroke-width='4'/%3E%3Cpath d='M37 32.0001L44 39.0506' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.workspace-tab-header[aria-label="标签面板"] svg {

display: none;

}

.workspace-tab-header[aria-label="标签面板"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M42.1691 29.2451L29.2631 42.1511C28.5879 42.8271 27.6716 43.2069 26.7161 43.2069C25.7606 43.2069 24.8444 42.8271 24.1691 42.1511L8 26V8H26L42.1691 24.1691C43.5649 25.5732 43.5649 27.841 42.1691 29.2451Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M18.5 21C19.8807 21 21 19.8807 21 18.5C21 17.1193 19.8807 16 18.5 16C17.1193 16 16 17.1193 16 18.5C16 19.8807 17.1193 21 18.5 21Z' fill='%23999999'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.workspace-tab-header[aria-label="标签面板"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M42.1691 29.2451L29.2631 42.1511C28.5879 42.8271 27.6716 43.2069 26.7161 43.2069C25.7606 43.2069 24.8444 42.8271 24.1691 42.1511L8 26V8H26L42.1691 24.1691C43.5649 25.5732 43.5649 27.841 42.1691 29.2451Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M18.5 21C19.8807 21 21 19.8807 21 18.5C21 17.1193 19.8807 16 18.5 16C17.1193 16 16 17.1193 16 18.5C16 19.8807 17.1193 21 18.5 21Z' fill='%230A59F7'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: 0 0 0 6px;

}

.nav-action-button[aria-label="新建笔记"] svg {

display: none;

}

.nav-action-button[aria-label="新建笔记"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M38 4H10C8.89543 4 8 4.89543 8 6V42C8 43.1046 8.89543 44 10 44H38C39.1046 44 40 43.1046 40 42V6C40 4.89543 39.1046 4 38 4Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 30L31 30' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 36H24' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M19 17L29 17' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M24 22V12' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 15px 6px;

}

.nav-action-button[aria-label="新建笔记"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M38 4H10C8.89543 4 8 4.89543 8 6V42C8 43.1046 8.89543 44 10 44H38C39.1046 44 40 43.1046 40 42V6C40 4.89543 39.1046 4 38 4Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 30L31 30' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M17 36H24' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M19 17L29 17' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M24 22V12' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 15px 6px;

}

  

.nav-action-button[aria-label="新建文件夹"] svg {

display: none;

}

.nav-action-button[aria-label="新建文件夹"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M5 8C5 6.89543 5.89543 6 7 6H19L24 12H41C42.1046 12 43 12.8954 43 14V40C43 41.1046 42.1046 42 41 42H7C5.89543 42 5 41.1046 5 40V8Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M18 27H30' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M24 21L24 33' stroke='%23999999' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 15px 6px;

}

.nav-action-button[aria-label="新建文件夹"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M5 8C5 6.89543 5.89543 6 7 6H19L24 12H41C42.1046 12 43 12.8954 43 14V40C43 41.1046 42.1046 42 41 42H7C5.89543 42 5 41.1046 5 40V8Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M18 27H30' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3Cpath d='M24 21L24 33' stroke='%230A59F7' stroke-width='4' stroke-linecap='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 15px 6px;

}

.nav-action-button[aria-label="排序"] svg {

display: none;

}

.nav-action-button[aria-label="排序"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M36 4V43.5' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M7 28H23L7 44H23' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M7 20L15.2759 4L23 20' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M44 36L36 44L28 36' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 15px 6px;

}

.nav-action-button[aria-label="排序"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M36 4V43.5' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M7 28H23L7 44H23' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M7 20L15.2759 4L23 20' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M44 36L36 44L28 36' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 15px 6px;

}

  

.view-action[aria-label="编辑（按住 Ctrl/Cmd 打开新面板）"] svg {

display: none;

}

.view-action[aria-label="编辑（按住 Ctrl/Cmd 打开新面板）"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M42 26V40C42 41.1046 41.1046 42 40 42H8C6.89543 42 6 41.1046 6 40V8C6 6.89543 6.89543 6 8 6L22 6' stroke='%23999999' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M14 26.7199V34H21.3172L42 13.3081L34.6951 6L14 26.7199Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 0 6px;

}

.view-action[aria-label="编辑（按住 Ctrl/Cmd 打开新面板）"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M42 26V40C42 41.1046 41.1046 42 40 42H8C6.89543 42 6 41.1046 6 40V8C6 6.89543 6.89543 6 8 6L22 6' stroke='%230A59F7' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M14 26.7199V34H21.3172L42 13.3081L34.6951 6L14 26.7199Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 0 6px;

}

.view-action[aria-label="预览（按住 Ctrl/Cmd 后点击则在新面板中预览）"] svg {

display: none;

}

.view-action[aria-label="预览（按住 Ctrl/Cmd 后点击则在新面板中预览）"] {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M24 36C35.0457 36 44 24 44 24C44 24 35.0457 12 24 12C12.9543 12 4 24 4 24C4 24 12.9543 36 24 36Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 29C26.7614 29 29 26.7614 29 24C29 21.2386 26.7614 19 24 19C21.2386 19 19 21.2386 19 24C19 26.7614 21.2386 29 24 29Z' fill='none' stroke='%23999999' stroke-width='4' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 0 6px;

}

.view-action[aria-label="预览（按住 Ctrl/Cmd 后点击则在新面板中预览）"]:hover {

background-image: url("data:image/svg+xml,%3C?xml version='1.0' encoding='UTF-8'?%3E%3Csvg width='24' height='24' viewBox='0 0 48 48' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='48' height='48' fill='white' fill-opacity='0.01'/%3E%3Cpath d='M24 36C35.0457 36 44 24 44 24C44 24 35.0457 12 24 12C12.9543 12 4 24 4 24C4 24 12.9543 36 24 36Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 29C26.7614 29 29 26.7614 29 24C29 21.2386 26.7614 19 24 19C21.2386 19 19 21.2386 19 24C19 26.7614 21.2386 29 24 29Z' fill='none' stroke='%230A59F7' stroke-width='4' stroke-linejoin='round'/%3E%3C/svg%3E");

background-size: 17px 17px;

transform: translate(0px, 5px);

background-repeat: no-repeat;

display: inline-block;

height: 18px;

width: 18px;

margin: -3px 0 0 6px;

}
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
^26a1b7

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
## 图片放大缩小 
```css
<!DOCTYPE html>

<html lang="en">

  

<head>

 <meta charset="UTF-8">

 <meta http-equiv="X-UA-Compatible" content="IE=edge">

 <meta name="viewport" content="width=device-width, initial-scale=1.0">

 <title>Document</title>

 <style>

 .img-grid .image-embed {

 display: table-cell;

 }

  

 .img-grid .image-embed img {

 width: 85%;

 padding: 20px;

 cursor: zoom-in;

 max-width: 100%;

 }

  

 .img-grid img[alt*="."]:hover {

 transform: scale(1.1);

 }

  

 .img-grid img[alt*="."]:active {

 cursor: zoom-out;

 display: block;

 z-index: 100;

 position: fixed;

 max-height: calc(100% + 1px);

 max-width: calc(100% - 20px);

 height: calc(100% + 1px);

 width: 100%;

 object-fit: contain;

 margin: -0.5px auto 0;

 text-align: center;

 padding: 0;

 /* top: 10px; */

 left: 0;

 right: 0;

 bottom: 0;

 background: rgba(255, 255, 255, 0.85);

 }

  

 .img-grid .image-embed:active img {

 top: 50%;

 transform: translateY(-50%);

 padding: 0;

 margin: 0 auto;

 width: auto;

 max-height: 95vh;

 left: 0;

 right: 0;

 bottom: 0;

 position: absolute;

 opacity: 1;

 }

 </style>

</head>

  

<body>

 <div class="img-grid">

 <span alt="home.png" src="home.png" class="internal-embed image-embed is-loaded">

 <img alt="home.png" src="./Home.png">

 </span>

 <span alt="home.png" src="home.png" class="internal-embed image-embed is-loaded">

 <img alt="home.png" src="./Home.png">

 </span>

 <span alt="home.png" src="home.png" class="internal-embed image-embed is-loaded">

 <img alt="home.png" src="./Home.png">

 </span>

 <span alt="home.png" src="home.png" class="internal-embed image-embed is-loaded">
 <img alt="home.png" src="./Home.png">
 </span>
 </div>
</body>
</html>
```
## Links
^1f784e
- 👉 [awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian#css-tweaks) | [Obsidian CSS 代码段 (on GitHub)](https://github.com/Dmitriy-Shulha/obsidian-css-snippets/tree/master/Snippets)    👈
- 👉  [Obsidian CSS Themes All](https://forum.obsidian.md/t/meta-post-css-themes/76) | [kmaasrud/awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian) | [Meta Post - Common CSS Hacks](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/41) 
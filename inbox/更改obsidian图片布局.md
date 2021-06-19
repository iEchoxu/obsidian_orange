```ad-note
通过css修改obsidian图片显示方式,让多个图片并列显示在一行. **还未整理与排版**
```

- For markdown images, use `![AltText|100x100](https://url/to/image.png)`
- For embeds, use `![[image.png|100x100]]`
- To have the image scale according to its aspect ratio, omit the height `![[image.png|100]]`

- [Image Flags](https://forum.obsidian.md/t/how-to-achieve-css-code-snippets/8474/93)
- [Image Flags Documentation and Examples ](https://github.com/Lithou/Sandbox/tree/main/Snippet%20Documentation%20and%20Examples)
- [Image Flags CSS](https://github.com/Lithou/Sandbox/blob/main/.obsidian/snippets/pub-Image%20Flags.css)

下面是案例：

![[home1.b1c718b9.png|+side -sm]]![[home1.b1c718b9.png|+side -sm]]![[home1.b1c718b9.png|+side -sm]]![[home1.b1c718b9.png|+side -sm]]

```css
/*不使用css也可实现图片并列显示*/
![[home1.b1c718b9.png|200]]  ![[htext.png|200]] ![[home1.b1c718b9.png|200]]

/* 图片并列显示时设置图片之间的间隔 */
.view-content .markdown-preview-view img  {
  padding: 20px 20px;
}

```

如果您要显示多个内嵌的图像，它们将从右到左“读取”。 所以首先列出的图像将是最右边的图像。

`![[testc.jpg]]`将按默认图片显示方式来显示图片

![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]![[home1.b1c718b9.png|+grid]]

不用添加flags也能让图片并列显示

```css
---
cssclass: img-grid
---
```

## 使用内嵌图片的方式
1: 在images里创建一个 image-MOC,用来对图片进行汇总，将所有的图片链接全部添加到这个文件中，在图片比较多时可考虑将image-MOC这个文件拆分，如：IT-image-MOC、Design-image-MOC等。

2：在笔记里通过  `[[image-MOC#^25bdbb|这里是要显示的别名内容]]` 方式引用图片。
-   ["How to achieve" CSS code snippets](https://forum.obsidian.md/t/how-to-achieve-css-code-snippets/8474/101)
-   [Side-by-Side Images](https://forum.obsidian.md/t/side-by-side-images/9210)
-   [Resize images vertically](https://forum.obsidian.md/t/resize-images-vertically/16225)
-   [Display side by side image grid \[deprecated\]](https://forum.obsidian.md/t/display-side-by-side-image-grid-deprecated/9359)



---
cssclass: grid
---

> *last updated: 12/25/2020*
# Overview: 
This document showcases the basic functionality of the "Pub-Image Flags.CSS" snippet. This snippet allows the user to specify how any image is displayed without impacting any other images.

## Contributions:
This is a collaboration with several people on the forums. If I missed your name and would like it included, please let me know. 

>Thanks to Gabroel, Death_AU, and Klaas for helping make this snippet the best it can be.
Thanks to Silver and Licat for making Obsidian a great tool 

---

# Installation and Usage
## How to install: 
1. Navigate to the CSS folder of this repository/vault (/.obsidian/snippets)
2. Grab the "Pub-Image-Flags.css" file
3. Copy/Paste this file into the snippets folder of the desired Obsidian Vault
4. Enable the snippet in Obsidian under the settings (appearance tab) 
5. Read the rest of the documentation and have fun! 

## How to use: 
1. Make sure the snippet is enabled,
2. Embed an image like normal
3. add a pipe "|" character to the end of the embedded image filename
4. Add a "core" flag 
5. Add any modifier flags to change the behaviour of that core element. 

*Note: Core flags start with a "+" and Modifier flags start with a "-"*

 
Example: ```![[test.jpg|+coreflag -modifierflag -anothermodifierflag]]```

---
## Image Placement

Placement of the image does matter. Generally you will want to place the image before the paragraph with which you want the image appear in-line. 

If you are displaying multiple images that are in-line, they will "read" right to left. So the image listed first will be the furthest to the right. 

As you go, look at this page in "edit mode" to see how the images are called and consequently displayed to get a feel for the syntax. 

---
## Starting Out (No Flags = no changes)

If you embed an image like usual, it will have no flags. Images linked this way will appear as they always have with no changes to its styling. Thus enabling the snippet will have no impact on any images you already have unless you add flags to them.  

This is the example  image we will be using for most examples and is shown without flags: 

![[testc.jpg]]

# Core Flags (Templates)
Each of these core flags will call a flavour of decoration and some default values. Think of them as your starting template. These templates can then be further modified with additional flags (discussed below). 

---
## Side

![[testc.jpg|+side]]

This flag will set the object to float so that the text in the following elements will flow around it.  

By Default it is floated to the right and has a width of 60% of the page.  

This is the most basic core flag and other modifiers are highly encouraged to be used. 

---

## Tape

![[test.jpg|+tape]]

This flag will tilt the image and apply an effect so that the image appears to be attached to the background by a piece of scotch tape. 

By Default it is floated to the right and has a width of 60% of the page. 

Size Modifiers will also change the size of the piece of tape so that it scales with the image.

---
## Push Pin

![[testc.jpg|+pin]]

This flag is similar to the tape flag, but will apply an effect that looks like the image is instead held too the background by a push pin. 

By Default it is floated to the right and has a width of 60% of the page. 

Given the size of push pin effect, It is not recommended to use with the thumbnail size. Other sizes work just fine. 

---

## Portrait

![[avatar.jpg|+portrait]]
The portrait flag will create an oval cutout around the image and float it to the right. This is most often used for pictures of real or fictional characters at the top of a biographical page although it can be used however you would like. 

By Default it is floated to the right and has a width of 30% of the page.  (half of normal default width)

The elliptical cutout works best for images that are taller than they are wide. For wider images see the next section.

---
## Landscape

![[testc.jpg|+landscape]]The landscape flag is similar to the portrait flag in that it will create an oval cutout around the image. 

The difference is the oval is shaped to match a landscape image and is thus wider than it is tall. 

By Default it is floated to the right and has a width of 60% of the page. 

---
## Banner and HR
![[testc.jpg|+banner]]

The banner attribute will modify the image into a fixed height banner that takes up 100% of the page width. 

By default it is 100px tall. There is also an default offset value that shifts the image up so that it doesn't start at the top of the image. This can be changed or set to zero based on the type of images you want to use. 


![[testc.jpg|+hr ]]


The "+hr" element is similar to the banner, but with a smaller height (10px by default) so that it can act as a divider. (It also has rounded corners by default).

---



# Modifier Flags
The core templates above are a great start, but can be limited. Enter the modifier flags. 

These flags can be used to modify/change values of a core flag. They can be used individually or together. 

>Note: Generally you will want to use no more than one from each category.
>Using both a "-left" and a "-right" flag for instance will result in only one being applied.  


## Size Flags: 
The size flags will resize an image while keeping any other attributes it has.  The default values are obtained by dividing the page width by a whole number(after accounting for margins) so that each will evenly fit images across the page. 
- Thumb: 8 images across
- Small:  4 across
- Medium: 3 across
- Large: 2 across 
### Thumbnail
"-thumb"  will create a thumbnail size (1/8th of the page)

![[testc.jpg|+side -thumb]]![[testc.jpg|+side -thumb]]![[testc.jpg|+side -thumb]]![[testc.jpg|+side -thumb]]![[testc.jpg|+side -thumb]]![[testc.jpg|+side -thumb]]![[testc.jpg|+side -thumb]]![[testc.jpg|+side -thumb]]


---
### Small:
"-sm"  will call the small size (1/4th of the page)
![[testc.jpg|+side -sm]]![[testc.jpg|+side -sm]]![[testc.jpg|+side -sm]]![[testc.jpg|+side -sm]]

---
### Medium:
"-med" will call the medium size (1/3rd of the page)
	![[testc.jpg|+side -med]]![[testc.jpg|+side -med]]![[testc.jpg|+side -med -nofloat]]

---
### Large: 
"-lg" will call the large size (half of the page)
	![[testc.jpg|+side-lg]]![[testc.jpg|+side-lg -nofloat]]

---

### Huge: 
"-huge" will call the huge size (2/3rd of the page)
![[testc.jpg|-huge]]

---

## Orientation Flags (Left and Right)

"-left" will float the image to the left
"-right" will float the image to the right

>Note: *These also add a 1% margin to the opposite side to create a scaling and symmetrical shape. It also is accounted for in the size flags.*

---

## Borders
### Border1 and Border2
![[testc.jpg|+tape-border1-lg]]
the "-border1" and the "-border2" flags will add a border to the image. 

"-border1" by default, will be a solid line that is two pixel wide. It is also by default black in color

"-border2" by default is the same as "-border1" but is white instead of black. 

![[testc.jpg|+tape-border2-lg]]
The border will go around the image as opposed to the container (the Div) and will thus go underneath other effects like the tape effect as pictured. 

These borders can be customized to default to other colors and sizes. They can also be further modified as detailed in the [[Image Flags (Extended Documentation)|Extended Docmentation]]

---

### Border Radius (Rounded Corners)

![[testc.jpg|+side -med -right -bradius2]]

![[testc.jpg|+side -med -right -border1 -bradius2]]

![[testc.jpg|+side -med -border1 -bradius1 -nofloat]]


The border can be set to have rounded corners with the "-bradius1" and "-bradius2" flags. The first will set a slight roundedness, while the second will create a larger roundedness. These can be used with or without a border and will still round the corners. The second and third picture above are the same except one has a border while the other does not.

---
# Further Reading
This is the end of the core documentation. Have fun taking control of the images inside your obsidian vault. I've put together a [[Image Flags (Quick Reference)|Quick Reference Guide]] that you can use to see the flags in a table.

As you use this snippet, feel free to take a look at the [[Image Flags (FAQ)|Frequently Asked Questions]]. It is updated consistently with any questions that other users have had or any points of clarification. 

If you want to go further and customize the snippet with user presets, custom flags, and more, check out the [[Image Flags (Extended Documentation)|Extended Documentation]] for deeper dive. 

As always, you can reach me on github or on discord(Lithou#7447). I'm active in the Obsidian discord and forums. You can DM me on either.

I hope this snippet treats you well and aids you on your journey. 


-Lithou
---
cssclass: img-grid
---

# Image Grid: the challenge
With the change of images from Div to Span the traditional image-grid CSS broke. 

After some discussion, the consensus was that it wasn't fixable. 

**Challenge Accepted: **

---

# Img-Grid2: Electric Boogaloo
After tinkering and searching and pondering and maybe some other words that describe having super random thoughts and trying to gather them together which proves difficult because it's like herding cats, I finally found a solution. 

There are two implementations you can use. The first is using it with image flags. The second is to use a css class like the original Img-Grid. You can also use both or a mix. I have a detailed guide for each below. 

Regardless of which you use, the result is the same. Both are set up with the same features. The only difference is how you call them. 

# Universal Features: 
## Zoom/Enhance: 
By default the images will zoom in if you hover over them with your mouse. Default for this is 1.5 scale. Feel free to adjust to your tastes.
## Size limit: 
The CSS by default will limit the height of images to 30% of the viewport height. This is to prevent a higher res photo from crowding out a lower res one. If you want to adjust this value to better fit your screen setup, go right ahead. 

## Using with paragraphs. 

Putting some images in line with a paragraph will ![[herald.png]]![[test.jpg]]![[herald.png]]![[test.jpg]] break the paragraph into two as you can see here. 

if you want the paragraphs to flow around the images, I'd suggest using image flags instead. 

# The two methods
The CSS code is included in the image flags CSS. Just grab that and you are good to go. 

## Method 1 (+grid flag)

The first method is to use the "+grid" flag with any image. This is a core flag that will display the images spread across a line. : 

![[test.jpg|+grid]]![[testc.jpg|+grid]]
![[testc.jpg|+grid]]![[testc.jpg|+grid]]![[testc.jpg|+grid]]

If you are using pictures that are uniform in shape, you can also use the size flags since they are setup to evenly distribute a set percentage based on the width of the page. 

On the other hand, if the images are various heights, widths, and sizes, the grid flag will adjust them slightly to accommodate the various size differences. 

Below as an example are, from left to right: 
- a taller image of large resolution 
- A low res image that is slightly wider than tall
- a medium res image that is square 
- a large res landscape image
- a medium res portrait image 


![[herald.png|+grid -border2]]![[plate.jpg|+grid]]![[wood.jpg|+grid -glow]]![[testc.jpg|+grid]]![[avatar.jpg|+grid]]

Note: This method also allows for combining of flags. In the example above, the first image has a border flag added while the middle image has a "glow" flag added.


# Alternative Method
The Alternative method will style any images that don't have tags. 
It is activated on a per page basis. 
Set the css class of a page to img-grid to activate. 
This is done by putting the following at the top of the page
```
---
cssclass: img-grid
---
```

After that just add the images. Put the images that you want together on the same line. This will auto adjust the sizes as you do so. 

![[herald.png]]![[plate.jpg]]![[wood.jpg]]![[testc.jpg]]![[avatar.jpg]]
![[herald.png]]![[test.jpg]]




# Mixing Both Methods
Mixing both together can lead to some interesting results. 

![[herald.png|+side -med -glow ]]![[plate.jpg]]![[wood.jpg]]![[testc.jpg]]![[avatar.jpg]]
![[herald.png]]![[test.jpg]]


Feel free to test this out. Let me know if you would like to have it exhibit different behaviour. 
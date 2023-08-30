
# Image Adjustments

> More flexibility to move/position and re-size the images in notes.

📥 [Download Image Adjusment Snippet](https://github.com/SlRvb/Obsidian--ITS-Theme/blob/main/Snippets/S%20-%20Images%20Adjustments.css)

**Do not** use the snippet version with the ITS Theme installed

Might not be 100% compatible with [Lithou's Image Flags snippet](https://github.com/Lithou/Sandbox/blob/main/.obsidian/snippets/pub-Image%20Flags.css)

Table of Contents

-   [Position](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Position)
    -   [Inner Image Positions](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Inner%20Image%20Positions)
-   [Sizing](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Sizing)
    -   [Obsidian Sizing](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Obsidian%20Sizing)
-   [Types](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Types)
    -   [Banner](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Banner)
    -   [Portrait](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Portrait)
    -   [Profile](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Profile)
-   [Extras](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Extras)
    -   [Invert Colors](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Invert%20Colors)

# Syntax

```markdown
![[Internal Image.png|attribute attribute2]]
![[Internal Image.png|sban cover hs-med]]
```

```markdown
![External Image|attribute attribute2](.png)
![External Image|sban cover hs-med](.png)
```

# Position

![](https://raw.githubusercontent.com/SlRvb/Obsidian--ITS-Theme/main/Images/Image_Adjustments-Simple-Positions.png)  
[Position Image Link](https://raw.githubusercontent.com/SlRvb/Obsidian--ITS-Theme/main/Images/Image_Adjustments-Simple-Positions.png)

Attribute

Description

`left`

Move the image to the left.

`right`

Move the image to the right.

`center`

Move the image to the center.

Position Attributes will not work in Live Preview

This causes issues with editing notes so it is and will not be natively supported by me unless that stops occurring. If you're okay with these potential issues, include the `|lp` option to allow it in Live Preview.

I will not attempt to fix any issues that arise out of the use of `|lp`. If something goes wrong with your notes with my theme or snippet, try removing this option before reporting that issue.

## Inner Image Positions

![](https://raw.githubusercontent.com/SlRvb/Obsidian--ITS-Theme/main/Images/Image_Adjustments-Custom--Inner-Position-Precise.png)

Attribute

Description

`p+l`

Move inside of the image to the left.

`p+r`

Move inside of the image to the right.

`p+t`

Move inside of the image to the top.

`p+b`

Move inside of the image to the bottom.

`p+c`

Move inside of the image to the center.

Attribute

Description

`p+cr`

Move inside of the image to the center right.

`p+cl`

Move inside of the image to the center left.

---

`p+ct`

Move inside of the image to the center top of the image.

`p+cct`

Move inside of the image to the center top, slightly higher than `p+ct`

`p+tc`

Move inside of the image to the center top, slightly lower than `pt`

`p+tcc`

Move inside of the image to the center top, slightly lower than `p+tc`

---

`p+cb`

Move inside of the image to the center bottom of the image.

`p+ccb`

Move inside of the image to the center bottom, slightly lower than `p+cb`

`p+bc`

Move inside of the image to the center bottom, slightly higher than `pb`

`p+bcc`

Move inside of the image to the center bottom, slightly higher than `p+bc`

# Sizing

![](https://raw.githubusercontent.com/SlRvb/Obsidian--ITS-Theme/main/Images/Image_Adjustments-Custom-Sizing.png)

Attributes

Resize Image to:

`htiny`

100px in height.

`hsmall`

200px in height.

`hs-med`

300px in height.

`hm-sm`

400px in height.

`hmed`

500px in height.

`hm-tl`

600px in height.

`htall`

700px in height.

`hfull`

Expand to the full height of the image or line

Attributes

Resize Image to:

`wmicro`

px in width.

`wtiny`

100px in width.

`wsmall`

200px in width.

`ws-med`

300px in width.

`wm-sm`

400px in width.

`wmed`

500px in width.

`wm-tl`

600px in width.

`wtall`

700px in width.

`wfull`

Expand to the full height of the image or line

## Obsidian Sizing

```
![[Image|loc sban|200]]
```

Place the `|<numbers>` sizing at the _end_ of the text and it will shrink the image to that size.

# Types

![](https://raw.githubusercontent.com/SlRvb/Obsidian--ITS-Theme/main/Images/Image_Adjustments-Simple-Sizing.png)

Note

`small`/`tall`/etc _only_ apply for these types. If you want to resize an image use either [my variables](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Sizing) or [Obsidian Sizing](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Image+Adjustments#Obsidian%20Sizing) `|100`

## Banner

Attribute

Description

`banner`

Crop the image height-wise to 150px while setting the width to cover the entire page.

`banner+small`

Crop the image height-wise to 100px while setting the width to cover the entire page.

`banner+tall`

Crop the image height-wise to 500px while setting the width to cover the entire page.

`sban`

Only sets image's width to 100% to cover the entire page

## Portrait

Attribute

Description

`portrait`

`portrait` will crop the image width-wise to 40% while setting the height to a standard of 400px.

`portrait+small`

`portrait+small` will crop the image width-wise to 20% while setting the height to a standard of 200px.

`portrait+tall`

`portrait+tall` will crop the image width-wise to 50% while setting the height to a standard of 500px.

## Profile

Attribute

Description

`profile`

Round the borders of the image to create a round image and size it to 100px.

`profile+medium`

Round the borders of the image to create a round image and resize it to 250px.

# Extras

Attribute

Description

`cover`

A resized image will maintain aspect ratio and avoid stretching.

`clear`

Allow image to sit below another image if it's on the same side instead of sitting in the middle of the page.

## Invert Colors

Attribute

Description

`invertb`

Invert the image's colors (dark mode).

`invertw`

Invert the image's colors (light mode).

`invertbc`

Invert colors and increase contrast (dark mode).

`invertwc`

Invert colors and increase contrast (light mode).

LINKS TO THIS PAGE

[Callout - Cards](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Callouts/Callout+-+Cards)

[Callout - Infoboxes](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Callouts/Callout+-+Infoboxes)

[Callout Adjustments](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Callout+Adjustments)

[Embed Adjustments](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Embed+Adjustments)

[ITS Theme](https://publish.obsidian.md/slrvb-docs/ITS+Theme/ITS+Theme)
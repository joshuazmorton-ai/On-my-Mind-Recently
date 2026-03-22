---
title: "Template"
date: 2026-03-21
draft: true
---

Two spaces to enter
images: {{< figure src="/krillion.jpg" width="300px" alt="Krilling the game" >}}

I. Terminal Commands (The Controls)
Run these in your project folder (OnMyMindRecently).

Command	What it does
hugo server	Starts your website for previewing.
hugo server -D	Starts the site and shows files marked as draft: true.
hugo server --cleanDestinationDir	Wipes the "temporary" files and restarts fresh (fixes most errors).
hugo new posts/filename.md	Creates a new post with the correct "brain" (Front Matter) at the top.
CTRL + C	Stops the Hugo server so you can type other commands.
II. Markdown Syntax (For Content)
This is what you type in your .md files.

1. Text Formatting
# Heading 1 (Main Title)

## Heading 2 (Subtitle)

**Bold Text**

*Italic Text*

~~Strikethrough~~

[Link Text](https://google.com) (Creates a clickable link)

2. Lists & Spacing
* Item 1 (Bullet point)

1. Item 1 (Numbered list)

--- (Creates a horizontal divider line)

   (Two spaces at the end of a line for a "soft" Enter/Line break)

3. Images & GIFs
To add an image or a GIF:

Put the file (e.g., dancing_baby.gif) into your static/ folder.

In your Markdown file, type:
![Description of image](/dancing_baby.gif)

III. HTML Syntax (For "90s Flair")
Markdown is limited. If you want the site to look truly "Retro," you can paste these HTML tags directly into your Markdown files.

1. The Classics
<center>Text here</center>: Centers your text or images.

<marquee>Moving text!</marquee>: Makes text slide across the screen (The ultimate 90s move).

<br>: A "Hard" line break. Use multiple <br><br> for extra vertical space.

<b>Text</b>: Alternative way to Bold.

<u>Text</u>: Underlines text (use sparingly!).

2. Colors & Fonts
If you want to change a specific word's color:
<font color="red">This is red!</font>

3. Images with HTML (Better Control)
If you want to change the size of your GIF:
<img src="/dancing_baby.gif" width="100" height="100" alt="Baby">


# Personal Markdown Template
This is for formatting the .md files of my GitHub repos. I look at the preview to find what I want and then copy the raw version from the file. Remember this is for GitHub flavored Markdown.

I can also use this repo as a template.

## Text

- [Hyperlink](https://www.google.com/)

### Headers

They work by size like HTML. H1-H6. Use the # symbol.

### Basic Format
- **Bold**
- *Italics*
- ~~Strikethrough~~
- <ins>Underline</ins>

### Combo Format
- ***Bold Italics***
- <ins>*Underline Italics*</ins>
- <ins>**Underline Bold**</ins>
- <ins>***Underline Bold Italics***</ins>
- ~~**Strikethrough Bold**~~
- ~~*Stirkethrough Italics*~~
- ~~<ins>Strikethrough Underline</ins>~~
- ~~***Strikethrough Bold Italics***~~
- ~~<ins>*Strikethrough Underline Italics*</ins>~~
- ~~<ins>**Strikethrough Underline Bold**</ins>~~
- ~~<ins>***Strikethrough Underline Bold Italics***</ins>~~

### Lists
- Use - for single lists.
   - Then Tab and - for sublists.
      - Go as much as you want.
          - As much as you need.

### Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

### Code Blocks & Inline Code Quotes

Inline `code` has `back-ticks around` it, which are `.

```python
s = "Code blocks need 3 back-ticks. \nIf you specify what language it is, then you get syntax highlighting."
v = "For instance, this is python code."
print (s)
print (v)
```

### Tables

| Tables        | Are           | Cool  |
|:-------------:|:-------------:|:-----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| `Still have custom Markdown` | are neat      |    $1 |

### Lines

> You can insert horizontal lines with 3 hyphens.
---

### HTML

You can use raw HTML. Below is an example.

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
</dl>

## Images

You can use this [tutorial](https://gist.github.com/NawalJAhmed/2168f7659c08b6a033e7f6daf8db69a6) to upload images to GitHub.
[This](https://github.com/NawalJAhmed/Markdown-Guide/issues/new) is a direct link to upload. Remember you can also use gifs. [Screentogif](https://www.screentogif.com/) is a great way to take something you see on your desktop and turn it into a gif.

<p align="center">
  <img src="https://user-images.githubusercontent.com/11577850/66669444-8c1a7500-ec25-11e9-9412-ef17a064a5ee.jpg">
  <br>
  <em> Center Text Caption </em>
</p>

## Videos

To use this, you need a link to the video, and you need to capture a still from the video yourself by fullscreening the video and using the snipping tool delayed by 2 seconds.

<p align="center">
  <a href="https://www.youtube.com/watch?v=jNQXAC9IVRw&list=PLBGH6psvCLx46lC91XTNSwi5RPryOhhde
  " target="_blank"><img src="https://user-images.githubusercontent.com/11577850/72564409-a6e03380-387d-11ea-9730-461e5bfb2621.PNG"
  alt="YouTube video demo"/></a>
  <br>
  <em>YouTube Video Demo (Click on Image for Video) </em>
</p>

This is a smaller thumbnail version.

<p align="center">
  <a href="https://www.youtube.com/watch?v=jNQXAC9IVRw&list=PLBGH6psvCLx46lC91XTNSwi5RPryOhhde
  " target="_blank"><img src="https://user-images.githubusercontent.com/11577850/72564409-a6e03380-387d-11ea-9730-461e5bfb2621.PNG"
                         width="500" height="281.25"
  alt="YouTube video demo"/></a>
  <br>
  <em>YouTube Video Demo (Click on Image for Video) </em>
</p>

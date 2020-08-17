# Markdown Guide
________________
### Table of Contents
- [Basic Markdown](#basic-markdown)
	- [Headers](#headers)
	- [Emphasis](#emphasis)
	- [Lists](#lists)
		- [Unordered](#unordered)
		- [Ordered](#ordered)
	- [Links](#links)
	- [Images](#images)
	- [Blockquotes](#blockquotes)
	- [Inline Code](#inline-code
- [Enhanced Markdown](#enhanced-markdown)
	- [Syntax Highlighting](#syntax-highlighting)
	- [Task Lists](#task-lists)
	- [Tables](#tables)
	- [Strikethrough](#strikethrough)
	- [Emojis](#emojis)
________________

## Basic Markdown
_________________

*__Note__: Leaving 2 spaces at the end of a line will force the following text onto its own line.*
### Headers

`# Header 1`
# Header 1
`## Header 2`
## Header 2
`### Header 3`
### Header 3
`#### Header 4`
#### Header 4
`##### Header 5`
##### Header 5
`###### Header 6`
###### Header 6

### Emphasis

`*This will be italics*`  
*This will be italics*  
`_This will also be italics_`  
_This will also be italics_  

`**This will be bold**`  
**This will be bold**  
`__This will also be bold`  
__This will also be bold  

### Lists

#### Unordered

```markdown
* `*, -, +` make bulleted lists
	* They can be nested
		* Multiple levels
- Use a number of tabs to nest
+ Another bullet
```

* `*, -, +` make bulleted lists
	* They can be nested
		* Multiple levels
- Use a number of tabs to nest
+ Another bullet

#### Ordered

```
1. Numbers make ordered lists
2. Which also allow nesting
	- nest 1
		- nest 2  
```

1. Numbers make ordered lists
2. Which also allow nesting
	- nest 1
		- nest 2  
		
### Links

```markdown
Automatic Links: http://github.com
Markdown Links: [GitHub](http://github.com)
```

http://github.com
[GitHub](http://github.com)

### Images

```markdown
Format: ![Alt Text](url)
![Placeholder Image](http://placehold.it/300)
```

![Placeholder Image](http://placehold.it/300)

### Blockquotes

```markdown
> "Don't quote me."
> __anonymous__
```

> "Don't quote me."  
> __anonymous__  

### Inline Code

```markdown
You can highlight `code` at any point in your text.
```
You can highlight `code` at any point in your text.

____________________
## Enhanced Markdown
____________________

### Syntax Highlighting
```javascript
function code_highlight (argument) {
	# this is a fenced javascript code block
	alert("Boo!")
}
```

### Task Lists

```markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables

```markdown
Column 1 Header | Column 2 Header | Column 3 Header
:--------------:|:--------------- | --------------:
Centered        |Left Aligned     |Right Aligned
Row 2 Col 1     |Row 2 Col 2      |Row 2 Col 3     
Row 3 Col 1     |Row 3 Col 2      |Row 3 Col 3     
```

Column 1 Header | Column 2 Header | Column 3 Header
:--------------:|:--------------- | --------------:
Centered        |Left Aligned     |Right Aligned
Row 2 Col 1     |Row 2 Col 2      |Row 2 Col 3     
Row 3 Col 1     |Row 3 Col 2      |Row 3 Col 3     

### Strikethrough

```markdown
~~crossed out~~
```

~~crossed out~~

### Emojis

```markdown
Lots and lots of them! :smile:
[Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
```
Lots and lots of them! :smile:  
[Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

# **Markdown Tutorial**

## **Table of Contents**

1. [Introduction to Markdown](#introduction-to-markdown)
2. [Headings](#headings)
3. [Paragraphs and Line Breaks](#paragraphs-and-line-breaks)
4. [Emphasis (Bold, Italic, Strikethrough)](#emphasis-bold-italic-strikethrough)
5. [Blockquotes](#blockquotes)
6. [Lists (Ordered & Unordered)](#lists-ordered--unordered)
7. [Links](#links)
8. [Images](#images)
9. [Code Blocks & Syntax Highlighting](#code-blocks--syntax-highlighting)
10. [Tables](#tables)
11. [Horizontal Rules](#horizontal-rules)
12. [Inline HTML](#inline-html)
13. [Escaping Characters](#escaping-characters)
14. [Task Lists](#task-lists)
15. [Footnotes](#footnotes)
16. [Superscript and Subscript](#superscript-and-subscript)
17. [Emoji Support](#emoji-support)
18. [Math Expressions (LaTeX)](#math-expressions-latex)
19. [Extended Features (GitHub Flavored Markdown)](#extended-features-github-flavored-markdown)


---

## **1. Introduction to Markdown**
Markdown is a **lightweight markup language** used to format plain text. It is widely used in:
- **GitHub README files**
- **Documentation**
- **Blogging platforms**
- **Writing notes and emails**
- **Content creation for websites**

Markdown makes text formatting easy and readable without complex HTML or CSS.

---

## **2. Headings**
You can create headings using the `#` symbol.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
### **Rendered Output**
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6  

---

## **3. Paragraphs and Line Breaks**
A new paragraph is created by adding a blank line between blocks of text.

```markdown
This is the first paragraph.

This is the second paragraph.
```

### **Line Breaks**
Use two spaces at the end of a line or `<br>` for a line break.

```markdown
First line with two spaces at the end.  
Second line.
```
Rendered as:  
First line with two spaces at the end.  
Second line.

---

## **4. Emphasis (Bold, Italic, Strikethrough)**
### **Italic**
```markdown
*italic* or _italic_
```
Rendered as: *italic*

### **Bold**
```markdown
**bold** or __bold__
```
Rendered as: **bold**

### **Bold & Italic**
```markdown
***bold and italic***
```
Rendered as: ***bold and italic***

### **Strikethrough**
```markdown
~~Strikethrough~~
```
Rendered as: ~~Strikethrough~~

---

## **5. Blockquotes**
Used for quoting text.

```markdown
> This is a blockquote.
>> Nested blockquote.
```
Rendered as:  
> This is a blockquote.  
>> Nested blockquote.

---

## **6. Lists (Ordered & Unordered)**
### **Unordered List**
```markdown
- Item 1
- Item 2
  - Sub-item 1
  - Sub-item 2
```

### **Ordered List**
```markdown
1. First item
2. Second item
   1. Sub-item
   2. Sub-item
```

---

## **7. Links**
### **Inline Links**
```markdown
[Google](https://www.google.com)
```
Rendered as: [Google](https://www.google.com)

### **Reference Links**
```markdown
[Google][google-link]

[google-link]: https://www.google.com
```

---

## **8. Images**
### **Inline Image**
```markdown
![Alt text](https://example.com/image.jpg "Optional Title")
```

### **Reference Style**
```markdown
![Alt text][image-link]

[image-link]: https://example.com/image.jpg
```

---

## **9. Code Blocks & Syntax Highlighting**
### **Inline Code**
```markdown
Use `inline code` like this.
```
Rendered as: Use `inline code` like this.

### **Block Code**
```markdown
```
print("Hello, World!")
```
```

### **Syntax Highlighting**
```markdown
```python
print("Hello, World!")
```
```
Rendered as:
```python
print("Hello, World!")
```

---

## **10. Tables**
```markdown
| Name   | Age | Country |
|--------|-----|---------|
| Alice  | 25  | USA     |
| Bob    | 30  | UK      |
```
### **Rendered Output**
| Name   | Age | Country |
|--------|-----|---------|
| Alice  | 25  | USA     |
| Bob    | 30  | UK      |

---

## **11. Horizontal Rules**
```markdown
---
```
Rendered as:  
---

---

## **12. Inline HTML**
```markdown
<p style="color:blue">This is blue text</p>
```

---

## **13. Escaping Characters**
Use a backslash (`\`) to escape characters.
```markdown
\*This is not italicized\*
```
Rendered as: \*This is not italicized\*

---

## **14. Task Lists**
```markdown
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```
Rendered as:
- [x] Task 1
- [ ] Task 2
- [ ] Task 3

---

## **15. Footnotes**
```markdown
This is a sentence with a footnote.[^1]

[^1]: This is the footnote text.
```

---

## **16. Superscript and Subscript**
```markdown
Superscript: E = mc^2
Subscript: H~2~O
```
Rendered as:  
Superscript: E = mc²  
Subscript: H₂O

---

## **17. Emoji Support**
```markdown
🚀 :rocket:
```
Rendered as: 🚀

---

## **18. Math Expressions (LaTeX)**
```markdown
$$ E = mc^2 $$
```
Rendered as:  
$$ E = mc^2 $$

---

## **19. Extended Features (GitHub Flavored Markdown)**
- Task Lists
- Tables
- Syntax Highlighting
- Emojis
- Footnotes




---

* [Blockqutes](#Blockqutes)
* [Code and Syntax Highlighting](#Code-Syntax)
* [Emphasis](#Emphasis)
* [Heading](#Heading)
* [Images](#Images)
* [Line Breaks](#Line-Breaks)
* [Links](#Links)
* [List](#List)
* [Phrase emphasis](#Phrase-emphasis)
* [SUperscript and subscript](#SUperscript-and-subscript)
* [Table](#Table)

# Blockqutes
```
> Email-style angle brackets are used for blockquotes.
>> You can nest them too.
>> 
> * You can quote a 
> * list 

> To break the nested blockquote, add a space between lines.

Add another line to resume regular paragraph text.
```
> Email-style angle brackets are used for blockquotes.
>> You can nest them too.
>> 
> * You can quote a 
> * list 

> To break the nested blockquote, add a space between lines.

Add another line to resume regular paragraph text.

[home](#Markdown)
# Code-Syntax
- Code and Syntax Highlighting
```
Inline `code` has `back-ticks around` it.
```

   <p>
   ```javascript <br>
   var s = "JavaScript syntax highlighting"; <br>
   alert(s);  <br>
   ```
   </p>
   
```javascript 
   var s = "JavaScript syntax highlighting"; 
   alert(s); 
```
   
   <p>
   ```python <br>
   s = "Python syntax highlighting" <br>
   print s  <br>
   ```
   </p>
   
```python 
   s = "Python syntax highlighting" 
   print s 
```

   <p>
   ``` 
   No language indicated, so no syntax highlighting.  <br>
   But let's throw in a <b>tag</b>. <br>
   ```
   </p>
   
``` 
   No language indicated, so no syntax highlighting.  
   But let's throw in a <b>tag</b>. 
```

[home](#Markdown)
# Emphasis
```
- Emphasis, aka italics, with *asterisks* or _underscores_.

- Strong emphasis, aka bold, with **asterisks** or __underscores__.

- Combined emphasis with **asterisks and _underscores_**.

- Strikethrough uses two tildes. ~~Scratch this.~~
```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

[home](#Markdown)
# Heading
```
   # Heading 1
   ## Heading 2
   ### Heading 3
``` 
# Heading 1 
## Heading 2 
### Heading 3 


[home](#Markdown)
# Images
* Inline (titles are optional) \
`![text](/path/img.jpg "Title")`\
![markdown](https://github.com/potatoscript/homepage/blob/master/docs/image/markdown.png)
* Reference style
```
![text][id]

[id]: /url/img.jpg "Title"
```

[home](#Markdown)
# Line-Breaks
* insert one newline
* use ```<br>```

[home](#Markdown)
# Links
* Inline (titles are optional)\
  `My Link [linked text](http://github.com/potatoscript/ "Title") `\
  My Link [linked text](http://github.com/potatoscript/ "Title")

* Reference-style labels (titles are optional)\
  `My Link [linked-text][myId]`\
  Define the link anywere in the same block:\
  `[myId]: http://github.com/potatoscript/ "Title"`\
  My Link [linked-text][myId]

[home](#Markdown)
# List
### Ordered without paragraphs:
```
  1. Car
  2. Dog
```
1. Car
2. Dog

### Unordered with paragraphs:
```
 * Car \
 myCat kitty
   
 * Dog \
 Snoopy
```
* Car \
myCat kitty
 
* Dog \
Snoopy

### Nested:
```
   * ABC
     * abc 
   * 123
     1. A
     2. B
     3. C
```
* ABC
     * abc     
* 123
 1. A
 2. B
 3. C
     
[home](#Markdown)
# Phrase-emphasis
`*italic* and **bold**`\
*italic* and **bold**

[home](#Markdown)
# SUperscript-and-subscript
* Superscript\
  `E=MC<sup>2</sup>`\
  E=MC<sup>2</sup>
  
* Subscript
  `The CO<sub>2</sub>`\
  The CO<sub>2</sub>
  
[home](#Markdown)
# Table
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1000 |
| col 2 is      | centered      |   $10 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

``` 
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1000 |
| col 2 is      | centered      |   $10 |
| zebra stripes | are neat      |    $1 |






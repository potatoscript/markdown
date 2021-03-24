# Markdown
* [Blockqutes](#Blockqutes)
* [Code and Syntax Highlighting](#Code-Syntax)
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
* use "\"

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






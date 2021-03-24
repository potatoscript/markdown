# Markdown
* [Links](#Links)
* [Phrase emphasis](#Phrase-emphasis)
* [SUperscript and subscript](#SUperscript-and-subscript)
* [Table](#Table)

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
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```\
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

# Github-Markdown-Cheatsheet
A Github Markdown Cheatsheet to be used as a reference when ever in need. Contributions are Welcome. 

<!-- Headings -->
# Heading 1 (Has a thin horizontal line below it)
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


<!-- Italics -->
*This text* is italic

\*This text\* is not italic as the asterisks are preceded with a backslash and hence \\* forms an escape sequence for *

_This text_ is also italic

<!-- Strong -->
**This text** is bold

__This text__ is also bold

<!-- Strikethrough -->
~~This text~~ is strikethrough

<!-- Horizontal rule -->
 There needs to be a line gap between a comment and a horizontal rule if triple hyphen is used to create horizontal rule, i.e. if a comment ends at a line x, the horizontal rule cant be at line x+1. It can be at line x+2 or ahead. 

---

No such condition is there for horizontal rule using 3 underscores. 
___

<!-- Blockquote -->
>This is a quote

<!-- Links -->
[This is a link to Youtube](https://www.youtube.com)

[This is a link to Youtube and has title also. ](https://www.youtube.com "Youtube")
NOTE: There must be a space between link and the title in the markdown code

<!-- Unordered list -->
The following is an unordered list
* Item 1
* Item 2
    * Nested Item 2.1
    * Nested Item 2.2
        * Nested Item 2.2.1
* Item 3


<!-- Ordered list -->
The following is an ordered list
1. Item 1
1. Item 2
1. Item 3

<!-- Inline Code Block -->
`<p> This is a paragraph </p>`

<!-- Images -->
The following is the Markdown Logo 

![Markdown Logo](https://markdown-here.com/img/icon256.png)

<!-- Github specific Markdown begins here -->


<!-- Code Blocks -->
```bash 
 npm install
 
 npm start
```

```javascript
 function add(num1, num2){
     return num1 + num2;
 }
```

```python
 def add(num1, num2):
     return num1 + num2
```

```cpp  
 int add(int num1, int num2){
     return num1 + num2;
 }
```

<!-- Tables -->
| Name   | Email |
| -      | -        |
| Aarush | aarush.15je001424@cse.iitism.ac.in   |
| Aarush | avijuneja.cs@gmail.com               |
| Parth  | parth.sharma@gmail.com               |
| Harman | kahlon_harman@ymail.com              |

<!-- Task Lists -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3


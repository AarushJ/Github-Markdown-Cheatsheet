# Github-Markdown-Cheatsheet
A Github Markdown Cheatsheet to be used as a reference when ever in need. Contributions are Welcome. 

<!-- Headings -->
#### Headings:
# Heading 1 (Has a thin horizontal line below it)
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
<br>

<!-- Italics -->
#### Italics (using single asterisk)
*This text* is italic
<br><br>

#### Italics (using single underscore)
_This text_ is also italic
<br><br>

#### Escape sequence
\*This text\* is not italic as the asterisks are preceded with a backslash and hence \\* forms an escape sequence for *
<br><br>

<!-- Strong -->
#### Bold (using double asterisk)
**This text** is bold
<br><br>

#### Bold (using double underscore)
__This text__ is also bold
<br><br>

<!-- Strikethrough -->
#### Strikethrough
~~This text~~ is strikethrough
<br><br>

<!-- Horizontal rule -->
#### Horizontal Rule:  
There needs to be a line gap between a comment and a horizontal rule if triple hyphen is used to create horizontal rule, i.e. if a comment ends at a line x, the horizontal rule cant be at line x+1. It can be at line x+2 or ahead. 

---

No such condition is there for horizontal rule using 3 underscores. 
___
<br>

<!-- Blockquote -->
#### Blockquote: 
>This is a quote

<br>

<!-- Links -->
#### Link: 

[This is a link to Youtube](https://www.youtube.com)

<br>

#### Link with tool-tip:

[This is a link to Youtube and has title also. ](https://www.youtube.com "Youtube")
NOTE: There must be a space between link and the title in the markdown code

<!-- Unordered list -->
<br>

#### Unordered List

* Item 1
* Item 2
    * Nested Item 2.1
    * Nested Item 2.2
        * Nested Item 2.2.1
* Item 3


<!-- Ordered list -->
<br>

#### Ordered list

1. Item 1
1. Item 2
1. Item 3

<br>

<!-- Inline Code Block -->
#### Inline Code Block
`<p> This is a paragraph </p>`
<br><br>

<!-- Images -->
#### Adding Images: <br>
The following is the Markdown 
<br><br>
![Markdown Logo](https://markdown-here.com/img/icon256.png)

<br>

<!-- Github specific Markdown begins here -->
## Github specific Markdown begins

<!-- Code Blocks -->
#### Code Blocks: 

Bash Code Block
```bash 
 npm install
 
 npm start
```

Javascript Code Block
```javascript
 function add(num1, num2){
     return num1 + num2;
 }
```

Python Code Block
```python
 def add(num1, num2):
     return num1 + num2
```

C++ Code Block
```cpp  
 int add(int num1, int num2){
     return num1 + num2;
 }
```

#### Table
<!-- Tables -->
| Name   | Email |
| -      | -        |
| Aarush | aarush.15je001424@cse.iitism.ac.in   |
| Aarush | avijuneja.cs@gmail.com               |
| Parth  | parth.sharma@gmail.com               |
| Harman | kahlon_harman@ymail.com              |

#### Check Box Lists
<!-- Task Lists -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3


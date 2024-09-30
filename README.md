<h1 align="center">Readme Markdown Syntax Guide</h1>

**Markdown is a simple text formatting tool, widely used on platforms such as GitHub, GitLab, and Bitbucket. In repositories, the readme.md file serves as a file descriptor, offering essential project details.**

It’s commonly applied in Gists, comments, and files with .md or .markdown extensions. Markdown is also popular for content writing on websites and blogs, as well as for creating documentation and installation guides within project directories.

- [1 | Headings](#1--headings)
- [2 | Text styles](#2--text-styles)
- [3 | Lists](#3--lists)
- [4 | Links](#4--links)
- [5 | Images](#5--images)

<br>

___
<!-- -------------------------|-| Headings |-|-------------------------- -->
# 1 | Headings

# H1
## H2
### H3
#### H4
##### H5
###### H6

```git
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

Alternative ways
```md
<h1>H1</h1>
<h2>H2</h2>
<h3>H3</h3>
<h4>H4</h4>
<h5>H5</h5>
<h6>H6</h6>
```

```md
H1
=
H2
-
```
___
<br>
<!-- -------------------------|-| Text styles |-|-------------------------- -->

# 2 | Text styles
<!-- -------------------------- Bold -------------------------- -->

## 2.1 | Bold

**Bold Text Style**  

```md
**Bold Text Style**
```

Alternative ways to **bold text** 

```md
Alternative ways to __bold text__
Alternative ways to <strong>bold text</strong>
```
<br>
<!-- -------------------------- Italic -------------------------- -->

## 2.2 | Italic

*Italic Text Style*  

```md
*Italic Text Style*
```

Alternative ways to *italic text*   

```md
Alternative ways to _italic text_
Alternative ways to <em>italic text</em>
```
<br>
<!-- -------------------------- Bold and Italic -------------------------- -->

## 2.3 | Bold and Italic

***Bold and Italic Text Style***

```md
***Bold and Italic Text Style***
```

Alternative ways to **_bold and italic text_**  

```md
Alternative ways to **_bold and italic text_** 
Alternative ways to <strong><em>bold and italic text</em></strong>
```
<br>
<!-- -------------------------- Strikethrough -------------------------- -->

## 2.4 | Strikethrough

~~Strikethrough Text~~

```md
~~Strikethrough Text~~
```

Alternative ways to <strike>strikethrough text</strike>


```md
Alternative ways to <strike>strikethrough text</strike>
```
<br>
<!-- -------------------------- Bold, Italic and Strikethrough -------------------------- -->

## 2.5 | Bold, Italic and Strikethrough

***~~Bold, Italic and Strikethrough Text~~***

```md
***~~Bold, Italic and Strikethrough Text~~***
```
<br>
<!-- -------------------------- Underlined -------------------------- -->

## 2.6 | Underlined

<ins>Underlined Text Style</ins>

```md
<ins>Underlined Text Style</ins>
```
<br>
<!-- -------------------------- Boxed -------------------------- -->

## 2.7 | Boxed

<table><tr><td>Boxed Text Style</td></tr></table>

```md
<table><tr><td>Boxed Text Style</td></tr></table>
```
<br>
<!-- -------------------------- Subscript & Superscript -------------------------- -->

## 2.8 | Subscript & Superscript

This is the   <sub>Subscript</sub>   text style  
log<sub>2</sub>(x)

```md
This is the <sub>Subscript</sub> text style  
log<sub>2</sub>(x)
```
<br>

This is the   <sup>Superscript</sup>   text style  
2 <sup>3</sup> = 8

```md
This is the <sup>Superscript</sup> text style  
2 <sup>3</sup> = 8
```
<br>
<!-- -------------------------- Monospaced -------------------------- -->

## 2.9 | Monospaced

This is the normal text style  
<samp>This is the Monospaced text style</samp> 

```md
<samp>This is the Monospaced text style</samp> 
```
<br>

___
<br>

<!-- -------------------------|-| Lists |-|-------------------------- -->

# 3 | Lists

<!-- -------------------------- Ordered -------------------------- -->

## 3.1 | Ordered 

1. First level - Item one
2. First level - Item two
3. First level - Item three

```md
1. First level - Item one
2. First level - Item two
3. First level - Item three
```
<br>


### Multi level

1. First level
    1. Second level
        1. Third level
            - Fourth level
        2. Third level
            - Fourth level
     2. Second level  
2. First level
    1. Second level

<br>

```md
1. First level
    1. Second level
        1. Third level
            - Fourth level
        2. Third level
            - Fourth level
     2. Second level  
2. First level
    1. Second level
```
<br>
<!-- -------------------------- Unordered -------------------------- -->

## 3.2 | Unordered

- Item one
- Item two

```md
- Item one
- Item two
```

Alternative ways 


```md
* Item one
* Item two

+ Item one
+ Item two
```
<br>

### Multi level

- First level
  - Second level
    - Third level
      - Fourth level
- First level
  - Second level
 
```md
- First level
  - Second level
    - Third level
      - Fourth level
- First level
  - Second level
```

<br>

___

<br>
<!-- -------------------------|-| Links |-|-------------------------- -->

# 4 | Links

<!-- -------------------------- Basic types -------------------------- -->

## 4.1 | Basic types

- Auto link <br>

Web   : https://www.google.com

Email : example@example.com


```md
Web   : https://www.google.com
Email : example@example.com
```
<br>

- Enclosed link <> <br>

GitHub : Let's build from here · <https://github.com>

```md
GitHub : Let's build from here · <https://github.com>
```

<br>
<!-- -------------------------- Link Label -------------------------- -->

## 4.2 | Link Label \[ ]( )

[GitHub](https://github.com) : Let's build from here <br>
Hi, [sign in](https://github.com/login) to GitHub

```md
[GitHub](https://github.com) : Let's build from here
Hi, [sign in](https://github.com/login) to GitHub
```

<br>

## 4.3 | Hover \[ ]( | "")

GitHub : [Login](https://github.com/login "Sign in to GitHub! Click here") : Let's build from here <br>

```md
GitHub : [Login](https://github.com/login "Sign in to GitHub! Click here") : Let's build from here
```
<br>


## 4.4 | Repository Links \( ./ )

[Example Document](/src/example.md)

```md
[Example Document](/src/example.md)
```

<br>

[README Document](README.md)

```md
[README Document](README.md)
```

<br>

[SRC Directory](./src)

```md
[SRC Directory](./src)
```
<br>

## 4.5 | Footnote \[ ^1 ]

Here is a simple footnote[^1]. Some other important footnote.[^2]

[^1]: My reference 1
[^2]: My reference 2

```md
Here is a simple footnote[^1]. Some other important footnote.[^2]

[^1]: My reference 1
[^2]: My reference 2
```
<br>

## 4.6 | Reference \[ ][ ]

[GitHub : Let's build from here][github-link] <br>
[Hello there, sign in to GitHub][Login link]
<br>

[github-link]: https://github.com
[Login link]: https://github.com/login

<br>

```md
[GitHub : Let's build from here][github-link]
[Hello there, sign in to GitHub][Login link]

[github-link]: https://github.com
[Login link]: https://github.com/login
```
<br>

<br>
<!-- -------------------------|-| Links |-|-------------------------- -->

# 5 | Images

## 5.1 | Basic Image 
<kbd> !\[Alternative-text](URL "Title-text") </kbd>

*Alternative text and title text are optional*
##

![Github Logo](https://cdn4.iconfinder.com/data/icons/social-media-and-logos-11/32/Logo_Github-128.png "Title text")

```md
![Github Logo](https://cdn4.iconfinder.com/data/icons/social-media-and-logos-11/32/Logo_Github-128.png "Title text")
```


## 5.2 | Image Embed element : \<img>

### Image

<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
    border="5"
/>

```md
<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
    border="5"
/>
```
<br>

##

### GIF

<img 
    src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3RuamM2eW13ZnNjZ3R4aGNubGp3OHljN2I5cTlsZndkanJqc3g5OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPnAiaMCws8nOsE/giphy.gif" 
    width="128" 
    height="148" 
/>


```md
<img 
    src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3RuamM2eW13ZnNjZ3R4aGNubGp3OHljN2I5cTlsZndkanJqc3g5OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPnAiaMCws8nOsE/giphy.gif" 
    width="128" 
    height="148" 
/>
```

<br>

##

### Icons

![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)

<img 
    src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" 
    width="88" 
    height="30" 
/>

```md
![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)

<img 
    src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" 
    width="88" 
    height="30" 
/>
```

<br>

## 5.3 | Image with click action

[![GitHub](https://cdn0.iconfinder.com/data/icons/social-media-2183/512/social__media__social_media__github_-128.png)](https://github.com)

```md
[![GitHub](https://cdn0.iconfinder.com/data/icons/social-media-2183/512/social__media__social_media__github_-128.png)](https://github.com)
```

<br>
<br>
<br>


<a 
  href='https://github.com' 
  target='_blank'> 
  <img src='https://cdn0.iconfinder.com/data/icons/social-media-2183/512/social__media__social_media__github_-128.png' /> 
</a>

```md
<a 
  href='https://github.com' 
  target='_blank'> 
  <img src='https://cdn0.iconfinder.com/data/icons/social-media-2183/512/social__media__social_media__github_-128.png' /> 
</a>
```

<br>
<br>

#
#


___


___

### Tables

```git
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |
```

|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |

### Align
You may specify alignment like this:
```git
| Align left | Centered  | Align right |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
```
| Align left | Centered  | Align right |
| :------------ |:---------------:| -----:|
| aaa     | bbb | ccc |

p.s. You can use alignment with `<h1 (or 2 etc.) align="center"> your text </h1>` tags or with `<p align="center"> your text</p>` tag to align plain text. 
___

### CheckBox

```git
* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected
```


* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected

You may use this syntax in GitHub's issue to check or uncheck the checkbox in real time without having to modify the original version of the issue.

___

### Quoting Text

```git
> This is a block quoted text
```

> This is a block quoted text

### Multi-level blockquotes
```
> Asia
>> China
>>> Beijing
>>>> Haidian
>>>>> Tsinghua
```
#### Look like
> Asia
>> China
>>> Beijing
>>>> Haidian
>>>>> Tsinghua

* These are fenced code blocks

___

### Text highlighting

```git
`linux` `ubuntu`
```
Using a pair of backquotes is suitable for making tags for articles
`linux` `ubuntu`

___

### Horizontal Line

```git
***
___
--- 
```

All three will be rendered as:
___
p.s. 
```git
<hr> works too
```
___

### Break between lines

```git
<br>
```
___

### Visible markdown characters
 
```git
```git
 * __ <br> etc ```
```
___

### Multi-line text

    aaa,
    sss,
    ddd!

Add 1 tab or 4 spaces at the beginning of several lines of text.

OR

Use three backticks:

```
asd,
sfd,
wer!
```
This syntax can also be used for code highlighting

___

### Comments in Markdown

```git
<!-- comment written in markdown -->
```
They will be invisible on readme
___

### Emoji
```git
:grinning:	or just place the emoji 😀
```
:grinning:	or just place the emoji 😀

To see a list of every image Github supports, check out the [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

___

### Code Block
There are three ways to add code in markdown
1. Inline Code (single backtick)
2. Whitespace

```git
    `this` is an example of inline code.
```
    four spaces work too!
    
3. Fenced code blocks
With GFM you can wrap your code with three back quotes to create a code block without the leading spaces. Add annoptional language identifier and your code will get syntax highlighting.

```Java
public static void main(String[]args){} //Java
```

```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```

___

### Syntax Highlighting
If language name is mentioned after the end of first set of backticks, the code snippet will be highlighted according to the language.

    ```js
    console.log('javascript')
    ```
    
    ```python
    print('python')
    ```
    
    ```java
    System.out.println('java')
    ```
       
    ```json
    {
      "firstName": "A",
      "lastName": "B
      "age": 18
    }
    ```

```js
console.log('javascript')
```

```python
print('python')
```

```java
System.out.println('java')
```

```json
{
  "firstName": "A",
  "lastName": "B",
  "age": 18
}
```
___

### diff syntax

In the version control system, the function of diff is indispensable, i.e., the addition and deletion of a file content is displayed.
The diff effect that can be displayed in GFM. Green is for new, while red is for deleted.
#### Syntax
The syntax is similar to code [fenced code blocks](#fenced-code-blocks), except that the diff is written after the three backticks.
And in the content, the beginning of `+ ` indicates the addition, and the beginning of `- ` indicates the deletion.

```diff
+ Hello world!
- This is useless.
```

___

### Use YAML: human friendly data serialization language for all programming languages

```yaml
name: Mariam
located_in: ***
from: ***
education: ***
job: ***
company: ***
```
___

### Anchor
In fact, each title is an anchor, similar to the HTML anchor (`#`), e.g.

|Syntax|Look like|
|---|---|
|`[Back to top](#readme)`|[Back to top](#readme)|

Note that all the letters in the title are converted to **lowercase letters**.

___

### Render mathematical expressions in Markdown

You can now use LaTeX style syntax to render math expressions within Markdown inline (using $ delimiters) or in blocks (using $$ delimiters).

Writing expressions as blocks
To add math as a multiline block displayed separately from surrounding text, start a new line and delimit the expression with two dollar symbols $$.

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

```git
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
```
## Writing inline expressions
To include a math expression inline with your text, delimit the expression with a dollar symbol $.

This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$

```git
This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$
```

___


### [Markdown posts on GitHub](https://github.blog/changelog/label/markdown/)

___

<h1 align="center">Readme Markdown Syntax Guide</h1>

**Markdown is a simple text formatting tool, widely used on platforms such as GitHub, GitLab, and Bitbucket. In repositories, the readme.md file serves as a file descriptor, offering essential project details.**

It’s commonly applied in Gists, comments, and files with .md or .markdown extensions. Markdown is also popular for content writing on websites and blogs, as well as for creating documentation and installation guides within project directories.

## Contents

- [1 | Headings](#1--headings)
- [2 | Text styles](#2--text-styles)
- [3 | Lists](#3--lists)
- [4 | Links](#4--links)
- [5 | Images](#5--images)
- [6 | Alignments](#6--alignments)
- [7 | Code Block](#7--code-block)
- [8 | Text Decoration](#8--text-decoration)

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
<!-- -------------------------|-| Images |-|-------------------------- -->

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
<!-- -------------------------|-| Alignments |-|-------------------------- -->

# 6 | Alignments

## 6.1 | Text Alignments

<h3 align="left"> Heading Left </h3>
<h3 align="center"> Heading Center </h3>
<h3 align="right"> Heading Right </h3>

```md
<h3 align="left"> Heading Left </h3>
<h3 align="center"> Heading Center </h3>
<h3 align="right"> Heading Right </h3>
```

## 6.2 | Image Alignments

### Left

<p align="left">
<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
/>
</p>

```md
<p align="left">
<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
/>
</p>
```
##

### Center

<p align="center">
<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
/>
</p>

```md
<p align="center">
<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
/>
</p>
```
##

### Right

<p align="right">
<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
/>
</p>

```md
<p align="right">
<img 
    src="https://cdn1.iconfinder.com/data/icons/ampola-final-by-ampeross/256/image_file.png" 
    width="128" 
    height="128" 
/>
</p>
```
##

### Multiple Images

<p align="center">
<img 
    src="https://plus.unsplash.com/premium_photo-1673292293042-cafd9c8a3ab3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8bmF0dXJlfGVufDB8fDB8fHww" 
    width="160" height="280" 
/>
<img 
    src="https://images.unsplash.com/photo-1525869916826-972885c91c1e?q=80&w=1769&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" 
    width="360" height="280" 
/>
<img 
    src="https://images.unsplash.com/photo-1472396961693-142e6e269027?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8bmF0dXJlfGVufDB8fDB8fHww" 
    width="160" height="280" 
/>
</p>


```md
<p align="center">
<img 
    src="https://plus.unsplash.com/premium_photo-1673292293042-cafd9c8a3ab3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8bmF0dXJlfGVufDB8fDB8fHww" 
    width="160" height="280" 
/>
<img 
    src="https://images.unsplash.com/photo-1525869916826-972885c91c1e?q=80&w=1769&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" 
    width="360" height="280" 
/>
<img 
    src="https://images.unsplash.com/photo-1472396961693-142e6e269027?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8bmF0dXJlfGVufDB8fDB8fHww" 
    width="160" height="280" 
/>
</p>
```

<br>
<br>


___

<br>
<!-- -------------------------|-| Code Block |-|-------------------------- -->

# 7 | Code Block

### 7.1 | Basic style
You can create code blocks by placing triple backticks ``` before and after the code block. 

Preview:
```
this is an example of code.
```

Syntax:
```
    ```
    this is an example of code.
    ```
```

##
### 7.2 | Fenced code blocks
In GitHub Flavored Markdown (GFM), you can create code blocks by wrapping your code with three backticks, avoiding the need for leading spaces. <br>
You can also add an optional language identifier to enable syntax highlighting for your code.

````md
```java
public static void main(String[]args){} 
//Java Code
```
````

````md
```javascript
console.log('javascript')
//Javascipt code
```
````

````md
```python
print('python')
```
````

````md
```json
{
  "firstName": "A",
  "lastName": "B",
  "age": 18
}
```
````


##
### 7.3 | Diff Code block

In version control, diff highlights changes in various colors. In GitHub Flavored Markdown (GFM), you can display:

- Green for additions (+)
- Red for deletions (-)
- Orange for changes (!)
- Gray for comments (#)
- Purple and bold for metadata (@@) <br>
    
Use the same syntax as fenced code blocks but specify diff after the three backticks.

Preview:

```diff
- Text Color Red
+ Text Color Green
! Text Color Orange
# Text Color Gray
@@ Text Color Purple And Bold @@
```

**Syntax:**

````md
```diff
- Text Color Red
+ Text Color Green
! Text Color Orange
# Text Color Gray
@@ Text Color Purple And Bold @@
```
````

##
### Recommendation > Use YAML : A Human-Friendly Data Serialization Language

```yaml
name: John Doe
location: New York, USA
origin: Canada
education: Bachelor's in Computer Science
occupation: Software Engineer
company: ***

```
___

<br>
<!-- -------------------------|-| Text Decoration  |-|-------------------------- -->

# 8 | Text Decoration 

### 8.1 | Text Highlighting

Using backticks( ` ) is a simple way to create tags for articles, such as <br>
<br>

`GitHub` : Let's build from here - `any important text`

```git
`GitHub` : Let's build from here - `any important text`
```

##
### 8.2 | Emoji

🌳 🐻 🍯 🌺

You can easily add emojis by placing them directly in your text, like this: 🌳 🐻 🍯 🌺

or you can use shortcode format

*Preview:*

:deciduous_tree: :bear: :honey_pot: :hibiscus:

**Syntax:**
```md
:deciduous_tree: :bear: :honey_pot: :hibiscus:
```


For a comprehensive list of all supported emojis on GitHub, check out the [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

##
### 8.3 | Quoting Text / Blockquotes >


> This is a block quoted text

```git
> This is a block quoted text
```
<br>
*Difference*
<br>
<br>

This is a normal text
> Block quoted text  

This is a normal text

```git
This is a normal text
> Block quoted text
This is a normal text
```

##
### 8.4 | Multi-level blockquotes


> First level
>> Second level
>>> Third level
>>>> Fourth level
>>>>> Fifth level

<br>

```md
> First level
>> Second level
>>> Third level
>>>> Fourth level
>>>>> Fifth level
```

##
### 8.5 | Multi-line text

You can add either 2 spaces or 4 spaces at the end of a line before starting a new line to achieve an indented effect.

*Preview:*  

First level  
Second level    
Third level  



**Syntax:**
```md
First level  
Second level    
Third level  
```


##
### 8.6 | Anchor

Each title in GitHub Flavored Markdown (GFM) serves as an anchor, similar to an HTML anchor (#). For example:
#### NOTE : Keep in mind that all letters in the title are converted to lowercase.



*Preview:*  

[Back to contents](#contents)

  
**Syntax:**
```md
[Back to contents](#contents)
```

### 8.7 | Visible markdown characters
 
To make special characters visible in Markdown, you can escape them using a backslash (\\). Here are some common examples:

*Preview:*  

\<br>

  
**Syntax:**
```md
\<br>
```

### 8.8 | Comments in Markdown

You can add comments in Markdown using HTML-style comments:

```md
<!-- comment written in markdown -->
```

These comments will be invisible when viewing the README file.


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


___

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


___





___


___


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

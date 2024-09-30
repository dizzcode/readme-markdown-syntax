<h1 align="center">Readme Markdown Syntax Guide</h1>

**Markdown is a simple text formatting tool, widely used on platforms such as GitHub, GitLab, and Bitbucket. In repositories, the readme.md file serves as a file descriptor, offering essential project details.**

It’s commonly applied in Gists, comments, and files with .md or .markdown extensions. Markdown is also popular for content writing on websites and blogs, as well as for creating documentation and installation guides within project directories.

- [Headings](#headings)
- [Text styles](#text-styles)

<br>

___
<!-- -------------------------|-| Headings |-|-------------------------- -->
# Headings

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

# Text styles
<!-- -------------------------- Bold -------------------------- -->

## 1) Bold

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

## 2) Italic

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

## 3) Bold and Italic

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

## 4) Strikethrough

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

## 4) Bold, Italic and Strikethrough

***~~Bold, Italic and Strikethrough Text~~***

```md
***~~Bold, Italic and Strikethrough Text~~***
```
<br>
<!-- -------------------------- Underlined -------------------------- -->

## 5) Underlined

<ins>Underlined Text Style</ins>

```md
<ins>Underlined Text Style</ins>
```
<br>
<!-- -------------------------- Boxed -------------------------- -->

## 6) Boxed

<table><tr><td>Boxed Text Style</td></tr></table>

```md
<table><tr><td>Boxed Text Style</td></tr></table>
```
<br>
<!-- -------------------------- Subscript & Superscript -------------------------- -->

## 7) Subscript & Superscript

This is <sub>Subscript</sub> text style  
log<sub>2</sub>(x)

```md
This is <sub>Subscript</sub> text style  
log<sub>2</sub>(x)
```
<br>

This is the <sup>Superscript</sup> text style  
2 <sup>3</sup> = 8

```md
This is the <sup>Superscript</sup> text style  
2 <sup>3</sup> = 8
```
<br>


___

### Lists

> Unordered 

```git
* Item 1
* Item 2
  * Item 1a
  * Item 2a
     * Item 1b
     * Item 2b
```

* Item 1
* Item 2
  * Item 1a
  * Item 2a
     * Item 1b
     * Item 2b

OR
`- Item 1`
- Item 1

> Ordered 

```git
1. First
2. jhg
   1. Second
   2. jhg
      1. Third
      2. jhg
```

1. First
2. jhg
   1. Second
   2. jhg
      1. Third
      2. jhg

___

### Links

```git
* [Link with more info with various formatting options](https://docs.github.com/en/github/writing-on-github "more info")
* https://www.google.com/
* <https://www.google.com/>
```

* [Link with more info with various formatting options](https://docs.github.com/en/github/writing-on-github "more info")
* https://www.google.com/
* <https://www.google.com/>

### Link Label 
```git
[My GitHub][GitHubLink]
```
[My GitHub][GitHubLink]

You may define your link label anywhere in the document.
```git
e.g. put on bottom: 

--------------------------------
[GitHubLink]:https://github.com/darsaveli
```

### Links to the URLs in a repository

```git
[Example document](/example/example.md)
```

[Example document](/example/example.md)

```git
[example](./example)
```

[example](./example)

___

### Inserting Images or Gifs using links

```git
![alt](URL "title")
```

- alt in square bracket indicates the replacement text when the image fails to display (can be omitted)
- parenthesis contains image source
- title in quotes indicates the text to display when the mouse hovers over the image (can be omitted)

Nite: Dropping the image to the readme file will upload it automatically with this syntax;
It's the same as links, but add an exlamation mark (!) before opening square bracket;
Image source can be either a location from the local machine or any valid image URL;

>Example

```git
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github logo") 
```
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github logo") 

### Resize images/Gifs
```
<img src="https://github.com/darsaveli/Mariam/blob/main/1479814528_webarebears.gif" width="385px" align="center">
```
<img src="https://github.com/darsaveli/Mariam/blob/main/1479814528_webarebears.gif" width="385px" align="center">

You can use HTML tags like width="385px", hight="876px", align="center", etc depending what you need. In this case this gif was once uploaded to the repository and the link was taken from there.

Other options to resize: 
- `![](https://  link | width=100)`

___

### Linking Image/Gif
To open another webpage when image is clicked, enclose the Markdown for the image in brackets, and then add the link in parentheses.

```
[![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "GitHub Logo")](https://github.com/)

```

[![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "GitHub Logo")](https://github.com/)

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

# In this blog I will give a summary for the chapters 2 and 10 of the book: "HTML & CSS" and chapters 2 and 4 from the book: "Javascript and Jquery" 📚 :



#### Note: Keywords are emphasised.
# Chapter 2: Text
* Structural markup: the elements that you can use to describe both headings and paragraphs.
* Semantic markup: which provides extra information; such as where emphasis is placed in a sentence.
## Headings
```<h1> <h2> <h3> <h4> <h5> <h6>```


```<h1>Heading 1</h1>```
```<h2>Heading 2</h2>```
```<h3>Heading 3</h3>```
```<h4>Heading 4</h4>```
```<h5>Heading 5</h5>```
```<h6>Heading 6</h6>```

![headings](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLAVUHQXO8g1vZsvmqRH-TCHpaHIDt9JB-Ig&usqp=CAU) 

### Paragraphs ```<p> </p>```
```
<p>A paragraph consists of one or more sentences
 that form a self-contained unit of discourse. The
 start of a paragraph is indicated by a new
 line.</p>
 ```
### Bold & Italic ```<b> <i>```
``` 
<p> I am normal text. </p>
<b> I am bold text. </b>
bold
 ```

```
<i> I'm a italic text </i> 
```
italic
![](https://d144mzi0q5mijx.cloudfront.net/img/T/H/The-Last-Font-Im-Wasting-On-You-ItalicA.png)
Superscript & Subscrip <sup> <sub>
sub

### White Space
When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as **white space collapsing**

### Line Breaks & Horizontal Rules ``` <br /> <hr />```
```
<p> This is <b /> a pragraph <b /> with line breaks </p>
```
![](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2018-09-27-at-4.31.37-AM.png)

```
<p> There is a horizontal rule below this paragraph. </p>
<h />
``` 


### Strong & Emphasis ```<strong> <em>```
![st](https://codebridgeplus.com/wp-content/uploads/quotations.jpg)

Quotations ```<blockquote> <q>```
![](https://static.javatpoint.com/htmlpages/images/html-blockquote-tag2.png)

## Abbreviations & Acronyms ``` <abbr>``` 
Citations & Definitions ```<cite> <dfn>```
Author Details ```<address>```
Changes to Content ```<ins> <del> <s>```
Chapter 10: Introducing CSS
CSS Associates Style rules with HTML elements
sel
# Chapter 10: Introducing CSS
###  Using External CSS
in the ```<head>``` tag

<link href="css/styles.css" type="text/css"
 rel="stylesheet" />
### Using Internal CSS
In the ```<head>``` tag

```
<style type="text/css">
 body {
 font-family: arial;
 background-color: rgb(185,179,175);}
 h1 {
 color: rgb(255,255,255);}
 </style>
 ```
### CSS Selectors
![h](data:image/png;base64,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)


![bbb](https://pbs.twimg.com/media/EdTVA1CWAAAvVIu.jpg:large)

### Chapter 2: Basic JavaScript Instructions
____
A *script* is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.

### Comments
a *multi-line* comment, starting with the /* characters and ending with the */ characters.

In a *single-line* comment, anything that follows the two forward slash characters //

# Variables
![var](https://lh3.googleusercontent.com/-YXC3gtpMlko/X3HA5DHH6MI/AAAAAAAAB3Q/VYM81zAFldY-cItuj7GMYA0Xy7Fy0GWBgCLcBGAsYHQ/image.png)

# Data Types
![dtype](https://xenovation.com/images/articles/development/java/DataTypes/java-data-types.png)

# Arrays
```
var colors;
colors ['white', 'black', ' custom']; 
Operators
```
op

# Chapter 4: Decisions and Loops
### Decision Making
```
if (score >= pass) {
msg = 'Congratulations, you passed!';
} else {
msg = 'Have another go!';
}

```
![de](https://miro.medium.com/max/546/1*ZmmVwIKNA3gVQhOTkhSbSg.png)
# Switch
```
switch (level) {
case 1:
msg = 'Good luck on the first test ' ;
break;
case 2:
msg = 'Second of three - keep going!';
break;
case 3:
msg = ' Final round, al most there!';
break;
default :
msg = 'Good l uck!';
break;
}
```



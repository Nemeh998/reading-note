## HTML Lists, CSS Boxes, JS Control Flow


# Chapter 3: Lists
* HTML provides three different types of lists:
1. Ordered lists
2. Unordered lists
3. Definition lists


# Ordered Lists ```<ol>```
```
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
 minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
```
1. Chop potatoes into quarters
2. Simmer in salted water for 
3. 15-20 minutes until tender
4. Heat milk, butter and nutmeg
5. Drain potatoes and mash
6. Mix in the milk mixture

# Unordered Lists <ul>

Gives the following output:
```
- 1kg King Edward potatoes
- 100ml milk
- 50g salted butter
- Freshly grated nutmeg
- Salt and pepper to taste
```

# Definition Lists  ```<dl> <dt> <dd>```


```<dl>``` definition list ```<dt>``` definition term ```<dd>``` the definition

```
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
 condiments such as shredded daikon radish or
 ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
 weight of ingredients</dd>
<dd>A technique by which the scales are removed
 from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
 cow's milk (although it was traditionally made
 from buffalo milk)</dd>
</dl>
```

# Gives the following output:
```
Sashimi
   Sliced raw fish that is served with condiments such as shredded daikon radish or ginger root, wasabi and soy sauce
Scale
   A device used to accurately measure the weight of ingredients
   A technique by which the scales are removed from the skin of a fish
Scamorze
Scamorzo
   An Italian cheese usually made from whole cow's milk (although it was traditionally made from buffalo milk)
   ```


   ## Nested Lists
   This can be done by putting a second list inside an

* element to create a sublist or nested list.

```
<ol>
<li>Fruit
 <ul>
  <li>Apple</li>
  <li>Orange</li>
  <li>Pears</li>
 </ul>
</li>
<li>Vegetables 
 <ul>
  <li>Broccoli</li>
  <li>Peas</li>
  <li>Corn</li>
 </ul>
</li>
</ol>
```

## Chapter 13: Boxes

There are several properties that affect the appearance of boxes:

* Control the dimensions of your boxes
* Create borders around boxes
* Set margins and padding for boxes
* Show and hide boxes

Box Dimensios ```width```
``` height```

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTF-fmWhSP5vhR7HqF58RPBGHj-eK4RUaD-SHFL2B4oMgXyZLKvkpBZO87wtdocEq3stDo&usqp=CAU)
  

  # Limiting Width min-width max-width

  ![](https://media.emailonacid.com/wp-content/uploads/2019/05/EOA_MediaQueries2019_Blog.jpg)


  ____
  ## Limiting Height min-height max-height
### Overflowing Content overflow
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

+ hidden
+ scroll

![](https://res.cloudinary.com/practicaldev/image/fetch/s--A_Jl_XX8--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://cl.ly/3P2H2C0b0V1F/Image%25202018-05-07%2520at%25204.47.33%2520PM.png)



## Border, Margin & Padding border padding margin

![](data:image/png;base64,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)


# Chapter 2: Basic JavaScript Instructions

A *script* is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.

### Comments
a multi-line comment, starting with the /* characters and ending with the */ characters.

In a single-line comment, anything that follows the two forward slash characters //


## Variables

![](https://lh3.googleusercontent.com/-YXC3gtpMlko/X3HA5DHH6MI/AAAAAAAAB3Q/VYM81zAFldY-cItuj7GMYA0Xy7Fy0GWBgCLcBGAsYHQ/image.png)

## Data Types
![dtype](https://xenovation.com/images/articles/development/java/DataTypes/java-data-types.png)


# Arrays
```
var colors;
colors ['white', 'black', ' custom']; 
```

Operators



## Chapter 4: Decisions and Loops
___
## Decision Making
if (score >= pass) {
msg = 'Congratulations, you passed!';
} else {
msg = 'Have another go!';
}


## Switch
![de](https://miro.medium.com/max/546/1*ZmmVwIKNA3gVQhOTkhSbSg.png)

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
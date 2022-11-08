# Author:- Vansh Baghel

# Date:- 19-April-2022

# Email :- vanshbaghel912@gmail.com

# Linkedin :- https://www.linkedin.com/in/vansh-baghel-24ab42232

# Feel free to contact me if you face any queries or errors.

# How to search any text in a big documentation:-

- Press (Ctrl+F) and get the text which you want instantly rather than searching it manually.

# Properties in CSS :-

### Syntax

Property:Values

EG:- color:green

## Link of CSS into HTML:-

3 ways :-

### a) **Inline**:- `<tagname style="property:value;">`

- This is preffered to be use where we need some only minute change in the element.

### b) **External**:-

- Can create new file of css and then link it to html.

* This is preffered to be used when we have many lines of codes to decorate our web page.

* This is most commonly used by me bcoz it lets the html file look like html more rather than more of a style related file.

- Code to link:-
  `<link rel="stylesheet" href="Filename.css"> `

### c) **Internal**:-

`<style>` properties `</style>`

- Here we make style wala tag and add properties into the tags we need in that same html file itself.

- This doesnt require to make any external file for styling.

## Selectors in CSS:-

CSS selectors are used to **find** (or select) the HTML elements you want to style.

```Css
Syntax:- h1 {property:value;}
```

### Types of selectors:-

#### 1. **Combined selectors**:-

We write all the elements we want to change with ","

#### 2. **Type selector**:-

We just write the element name.

#### 3. **Class selector**:-

` <h1 class="className"> .className{}`

#### 4. **ID selector**:-

Same as class, just replace with word id and .className with #idName 5.**Attribute selector**:- We write attribute into sq bracket & then curly braces.

#### 5. **Pseudo-class selectors** :-

```CSS
 Syntax:- ElementName:pseudo-class{}
```

#### 6. **Attribute selector**:-

We write attribute into sq bracket & then curly braces.

> Some imp selectors:- hover,visited,link,float,hidden.

#### 7. **Pseudo-elements selectors**:-

select and style a part of an element & change that particular part.

#### 8. **Combinator selectors**:-

Select elements based on a specific relationship between them ie child element ko select krta h.

```CSS
 Syntax:- article > (tagElement) {}
```

#### 9. **Universal selector**:-

Used to select all elements from a file.

Syntax:- \\\* {} <!--Here we added \ to ignore the further \ -->

#### 10. **\- wala method**:-

If there are 3 para after h1 and u want to make changes only in 3rd para then u can write (h1+p+p+p){}.

- To give color to specific tags in full file:-
  `p,a { color: green;}`

- To give class ke liye :- `i.idk{color: blue;}` --> Specific tag OR `.idk{color: blue;}` --> All tags which include idk ka class.

- For specific child tag:- `parenttag childtag {}`

- To give for specific id:- `#(idname) {}`

- To give for a specific tag from the class, while that classs is having other tags too, but others wont change:-

```CSS
p[class="damn"] {color:blueviolet;
padding: 10px;}
```

# Color

1. You can control the color by adjusting the shade, also can control the opacity by clicking the box of that color.
2. Must try rgb tag inside color, red-green-blue

# Background

Can change

## a) **background color**:-

` background color:red;`
To put color only on specific text then use **"span"** tag.

## b) **background img**:-

` background-image:url("abc.jpg")`

## c) **background repeat**:-

Very usefull to repeat certain img/color in given axis or randomly or to stop the repeation

## d) **background position**:-

Can take the img to any direction.

# Fonts

## a) **Font-family**:-

Used to change the fonts into different types. Can also change the font by finding it from **"google fonts"** and pasting the link ref of it
above style tag.

## b) **Font-style**:-

Changes the style like italic,etc.

## c) **Font-size**

## d) **Font-weight**:-

Can change the darkness like bold,normal,light,etc.

# Texts

## a) **text color**:-

`color{}`

## b) **text align**:-

_left, center, right, justify_
(texts is written from left and it ends at right, it covers the whole line).

## c) **text-decoration** :-

_overline, line through, underline, underline overline._

## d) **text-transform** :-

_capitalize, uppercase, lowercase_

## e) **text-indentation**

## f) **letter-spacing**

## g) **word-spacing**

## h) **text-shadow**:-

` text-shadow: h-shadow v-shadow blur-radius color,`

h-shadow means distance horizontally, v-shadow is distance vertically, blur-radius means part to be blurred, then color.

# Img

To change alignment of img to :-

## a) **Center**:-

u can create style in css

`img{ display:block; margin-left: auto; margin-right: auto;}`

## b) **Left**:-

u can create style in css

` img{ display:block; margin-right: auto;}`

## c) **Right**:-

u can create style in css

` img{ display:block; margin-left: auto;}`

---

# Units in CSS:-

## 2 Types:-

### a) **Absolute units**:-

Its fixed units like cm,m,px,etc.

_1px = 1/92th of 1 inch
1pt = 1/72th of 1 inch
1pc = 12pt_

### b) **Relative units**:-

depends on web page or parent element.

_vw:- 1% width of web page._

_vh:- 1% height of web page._

_vmin:- minimum value among height and width will be used here._

_vmax:- maximum value among height and width will be used here._

_em :- 2em means 2 times the size of the current font._

# Box Model Styling

- Learn to write texts in box form.

  ## a) **padding**:-

  Gives space before the text starts from the left and right of the boc or the web page. Both side the distance will be same.

  ## b) **Border**:-

  Strong colored border to the text.
  Border itself is a big topic to cover. Basically 6 topics in border which you should consider before using.

  ### 1. **Border-width** :-

  The border-width property specifies the width of the four borders in pixels.

  ### 2. **Border-style** :-

  There are total 11 types of borders which you could give to the table.

  ### 3. **Border-color** :-

  The border-color property is used to set the color of the four borders.

  ### 4. **Border-Shorthand** :-

  Basically width, style & color written in same syntax.

  - EG:-` border: 5px solid red;`

  ### 5. **Border-sides** :-

  Can individually give the tpye of style of border on each side like top, botton, left, right.

  ### 6. **Border-radius** :-

  Can make the border rounder in pixels.

  ## c) **Margin**:-

  Same like padding, just the difference is that the background color wont be seen into margin. Only if the parent tag ka color changes
  then the margin will be filled.

  ## d) **Box-sizing-border box** :-

  Very important element to be used for whole html file. It will add padding & border (width,solid color) without affecting
  the size of box. So if there are 2 boxes then both will be aligned even if one box adds any padding to the texts.

  # Styling Lists

  Here, we modify the bullets using style.

  ## a) **list-style-type**

  ## b) **list-style-position**

  ## c) **list-style-image**

# Some important Selectors

_**Hover,visited,link,float,hidden.**_

**Hover**:- Changes will be made when we move our cursor to it.

**Visited**:- Changes in color or etc will be made once we visit that link.

**Float & overflow hidden**:- Box model se bahar aajate h texts. It wont be seen unless u use overflow hidden. As the text is overflowed out of the box.

# Styling Tables

## Table Border:-

### 2 types:-

#### a) **Separate border**:- Separate blocks.

#### b) **Collapse border**:- Joint blocks.

_Style to change these two types_:-

```CSS
border-collapse: collapse; OR border-collapse: separate;
```

c) **padding**:- To give spacing between the texts in the block of table.
`th,td{padding:15px;}`

d) **border-spacing**:- To give spacing between the tables.

# Specificity

- If there are two or more CSS rules that point to the same element, the selector with the highest specificity value will "win", and its style declaration will be applied to that HTML element.

- Also, the element written most recently will be applied to the txt.

# Controlling inheritance:-

## 1. **Unset**:-

Unset is a CSS value that's the same as "inherit" if a property is inherited or "initial" if a property is not inherited.

## 2. **Initial**:-

The initial value of a CSS property is its default value which differs with websites.

## 3. **Inherit**:-

The inherit keyword specifies that a property should inherit its value from its parent element.

## 4. **Default**:-

Default value of any element. eg:- link ka purple hota h.

## 5. **Important**:-

Important ka specificity is the most.

```css
!important.
```

# Controlling Overflow out of box:-

Overflow of text outside the box happens when the width and height of the box is small compared to text.
To solve this, we use:-
overflow:-

```CSS
 Syntax---> overflow: scroll/auto/hidden/visible;
```

**Difference** in auto and scroll is that the box can be scrolled even after the width is sufficient in case of scroll, but in auto it'll not scroll.

# Controlling img out of box:-

Sytnax to fit img inside the box:-

```CSS
 object-fit: cover/contain/fill.
```

# Payment File Explanation:-

## 1. **Box-sizing-border box** :-

- Very important element to be used for whole html file.
- It will add padding & border (width,solid color) without affecting the size of box.
- So if there are 2 boxes then both will be aligned even if one box adds any padding to the texts.

## 2. **Body**:-

Whatever background is added (Here, whitesmoke) will be affected on the full web page.

## 3. **Importing font**:-

Always write the import code at the beginning of any style.

## 4. Width: 100% :-

This % is according to the web page.

## Practice Q)

Contact_test :-

**body**:-
Background color of web page is the background-color of the body.

**h1**:-
Margin of h1 is the distanace of h1 text from the table. It also changes the size of the box, as the distance is getting increased which means border will move far along with the box.

**div**:-
background-color of the box in which text is written.
border is for the white box to get green color at the corners.

# Debugging in CSS

Right click krne se on any web page, you'll see option to _**"view page source"**_ & _**"Inspect"**_.

1.  **View page source**:- Can view full code written to make that particular web page.
2.  **Inspect**:- Just explore it yourself, kind of same to view page. Computed option bhi explore krna. Debugging is usually done with this, styles waale option se.

> RECOMMENDED:- View the box ke dimensions, the way padding, width, height are applied.

_Difference in view page source & inspect_:- Syntax mai koi error hua then it wont be corrected in view page source on the otherr hand, in inspect the correct code will be displayed.

# Clip path generator:-

- Used to change the size and shape of the image without putting much efforts.
- Search "_**Clip path generator**_" on google then select appropriate shape, copy the url & paste in the CSS.

---

## _Difference in box-sizing.border-box & box-sizing.content-box :-_

```
  width: 160px;
  height: 80px;
  padding: 20px;
  border: 8px solid
```

- **box-sizing: content-box**;

  - { **Total width**: 160px + (2 _ 20px) + (2 _ 8px) = 216px. _Left & right padding and border are added._

  - **Total height**: 80px + (2 _ 20px) + (2 _ 8px) = 136px

  - **Content box width**: 160px

  - **Content box height**: 80px
    }

- **box-sizing: border-box**;

  - **Total width**: 160px Width remains the same and both the padding and border are added into the width itself.

  - **Total height**: 80px

  - **Content box width**: 160px - (2 _ 20px) - (2 _ 8px) = 104px

  - **Content box height**: 80px - (2 _ 20px) - (2 _ 8px) = 24px \_/

# CSS Layers:-

1. z-index :-
   - Used to give the priority number to the overlapping boxes.
   - The eg of box overlap will be in html files.
   - Greater the number of index, more will be the priority, means it'll be at the top.
   - Using "position" is important & necessary with z-index.

# Responsiveness

- Responsive web design makes your web page look good on all devices.
- It varies with the change in the width of the screen.
- We use "**and**" operator to change the layout with respect to the width.
- To use "**or**" operator simple add another ',' after the 'and ()'.

  ```CSS
   @media screen and (max-width:400px), (max-width:1000px); {   } .
   @media , @media screen, etc.
  ```

  > NOTE:- Div is used to write text in a given block. It doesnt use the whole line like p tag. So, div is used for writing text with space in the same line.

- Use **box-sizing: border-box** for viewing the text in box in the same line.

- Solved a problem stmt, check it out:-

  [Responsiveness](https://codepen.io/Vansh-Baghel/pen/eYVOxQN)

  **NOTE**:- Use inspect option and change the width of the page to see the changes.

# Display

> Syntax:- display : (value);

## Types of Values

### 1. **Inline** :-

Displays an element in the same line. (like `<span>`).

- Any height and width properties will have no effect.

### 2. **Block**:-

Displays an element which starts on a new line, and takes up the whole width. It adjusts the box into the column by default.

### 3. **Flex** :-

Displays the boxes in the row adjacent to each other. More better and detailed explanation in flex heading.

### Tags important to use with display tag.

#### 1. **Float**:-

Used to adjust the img or text in any direction.

- None :- The element does not float (will be displayed just where it occurs in the text). This is default.

```CSS
float: left/right/none/inherit;
```

#### 2. **Clear**:-

Used to specify what should happen with the element that is next to a floating element.

```
clear: left/right/none/inherit/both;
```

### 3. **Position** :-

1. **Static**:- It is not affected by the top, bottom, left, and right properties.

- HTML elements are positioned static by default.

2. **Relative**:- top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position.

   EG:-

```CSS
{position: relative;
 top:10px;
}
```

3. **Fixed**:- This position of it will remain at the same place on the screen even if we scroll the pg.

4. **Sticky**:-

- A sticky element toggles between relative and fixed.
- If, we give `top,bottom` tags of relative, then it'll act as fixed (it'll not move even if we scroll) .

- Else, using sticky doesnt make any difference.

5. **Absolute**:- This will overlap the boxes and the text.

### Challenge question:- [Position_clear_float_responsiveness](https://codepen.io/Vansh-Baghel/pen/ZErzwoz)

**Goal**
![e](Position_clear_float_responsiveness.jpeg)

- _**Explanation**_ :-

1. **Url method**:- Copy the link address of img from google so you dont need to place the downloaded file in the folder.

2. **Class** :-

- Here, 2 classes are in one `<div class="box box-1">` , which means ki box will be used as common class if you want any change in 3-4 steps & box-1 will be unique for that particular (basically to change the position it must be unique).
- Also, can use class in img.

3. **p** :-

- We need to use paragraph tag to write the text bcoz we need the text besides the img, if u use div then the text will be visible down to the image.

* If you want to view the text on same line by using _div_, better use `display:inline` for viewing the text besides the img.

- We can add clear, align tags for p to adjust the text for _@media_.

4. **div in css** :-

- _Overflow_ is used to hide the overlapping of texts while changing the width.
- _Widht & height_ are in vw & vh which means % of the web pg.
- _Margin_ is used in shortcut method whose syntax is

```CSS
margin:top right bottom left
```

5. **img in CSS** :-

- Box type around image in added by changing height & width of it.

6. **@media** :-

- _Text_ is aligned to center and its cleared from both the side so that we dont need to adjust the text again & again when the image is left & right.

### Challenge Question:- [Position_sticky](https://codepen.io/Vansh-Baghel/pen/PoQoPNx)

**Goal**
![e](sticky.jpeg)

_**Explanation**_ :-

- Used **div** and added class for both a and p tags.
  Adding class in both the tags are important, bcoz the div tag with class will also be changed if we try to change the normal div tag.

* **CSS edits**
  - `.nav1` :-
    - We need to add background color for navigation to this tag, bcoz div tag extends throughout the line.
    - While adding background color to the a tag, it would've been visible in that small particular short block and not the whole line.

# Flexbox

- To start with flexbox, we first need to understand its terminologies.

![Terminolgy](https://miro.medium.com/max/1183/1*ubDrM-3m22gLF_pZ4DCdMw.png)

## Elements

### 1) **display:block/flex**:-

- Difference in both is that block adjusts the boxes into 1 column and flex adjust in 1 row.
- Anyways, we could change the direction of box using different element tag.

### 2) **flex-direction:(value)** :-

- Here are some values which we use with this element.

  a) **row** :- Adjusts the boxes in same row.

  b) **column** :- Adjusts the boxes in same column.

  c) **column-reverse** or **row-reverse** :- Adjusts the boxes in same as column or row, but in reverse order.

### 3. **justify-content:(values)** :-

- Here are some values which we use with this element.

  a) **flex-start** :- Same as cross-start in the diagram.

  b) **flex-end**

  c) **center**

  d) **space-around** :-

  - This tag has same padding space between them ; and the space before and after the box are same.
  - The space between & before-after are different.

  e) **space-between** :- Items will have space between them but not before and after it.

  f) **space-evenly** :-

  - Items will have equal space around them.
  - Here, the space between, before and after all are same.

### 4. **align-items: (values)** :-

- Used to change the position of boxes.

- Some values are:-

  a) **center**

  b) **flex-start** :- Items are positioned at the beginning.

  c) **flex-end** :- Items are positioned at the end.

  d) **stretch** :- Stretches and increases the height of the box w.r.t the web page.

  e) **baseline** :- Items are positioned at the baseline of the container.

### 5. **align-self: (values);**

- Same values like align-items, its just used to move some boxes particularly .

### 6. **flex:wrap;(values)**

- Some values:-
  - a) wrap:- Used to change the width of screen without changing the size of box. The box will appear on new line rather than shrinking.
- There are more values, you can explore them too.

### 7. **align-content**:-

The align-content property modifies the behavior of the flex-wrap property. It is similar to align-items, but instead of aligning flex items, it aligns flex lines.

### 8. **Order** :-

Can change the order of any box individually.

### 9. **flex-basis** :-

Used to give the max width to boxes.

### 10. **flex-grow:(value)** :-

- Here, value is in the form of number, which represents the speed.
- Here, the size of the box will grow at certain speed & resolution when the width of web pg in increased.

### 11. **flex-shrink:(value)** :-

- Same as grow, just the opposite happens.

### 12. **flex-flow** :-

- It is a shorthand method, `flex-flow:<flex-direction flex-wrap>`

### 13. **flex** :-

- another shorthand method `flex:<flex-grow flex-shrink flex-basis> `

### Challenge1 of flexbox:- [Challenge1_flexbox](https://codepen.io/Vansh-Baghel/pen/VwQwxoL)

**Goal**
![e](flex1.jpeg)

_**Explanation**_ :-

- HTML explanation:-
  - 3 containers are needed as 3 rows of boxes are present.
  - Nested div ka parent div ka end tag must be closed at after all the nested div are completed.

* CSS explanation :-
  - **flex** is used instead of width.
  - _div.li_ & _li.div_ are different. _div.li_ refers to li class and _li.div_ refers to div present inside the li.

### Challenge2 of flexbox:- [Challenge2_flexbox](https://codepen.io/Vansh-Baghel/pen/ZErEomR)

**Goal**
![e](flex2.jpeg)

_**Explanation**_ :-

- HTML explanation:-
  - 2 containers are used as we need 2 rows where each row contains 3 other divs.
  - We need to assign 3 divs for each container as they are 3 different boxes.
  - Image ka url is shortened by bitly from google bcoz image address is too big to be copied from google's image which doesnt look appropriate in the code.

* CSS explanation :-
  - Here, **align-self** is used in **row class** to align the column upwards in the line of middle box.
  - In img, display & margins are used to align the img in the center.
  * **_Replacement done after flex concept_** :-
    - `display:flex` replaced with `display:grid` in the whole container so that the boxes of divs may fit the outer box.
    - grid-template-column is used to fit 3 divs in one row.
    * Also, removed width from row_1 which was restricting the divs to increase the width.

### Challenge3 of flexbox:- [Challenge3_withoutflex](https://codepen.io/Vansh-Baghel/pen/WNMNJQx)

### Challenge3 of flexbox:- [Challenge3_withflex](https://codepen.io/Vansh-Baghel/pen/dydyeGw)

**Goal**
![e](flex3.jpeg)

_**Explanation**_ :-

Without flex one was much easier.

- HTML explanation :-

  - **div container** is used to store 2 divs,ie, r1,r2. Both the divs have different width.
  - Then **r2** is divided into 3 divs & 1st and 3rd divs have same style, but the 2nd div differs.

- CSS explanation for without flex:-

  - **display flex** is used to align the boxes in a row.
  - **r1 and r2** both have different widths.
  - lr1 contains **box-sizing** so that the bottom box is in same line as of the r1.

- CSS explanation for with flex:-
  - The only new concept here was the use of **flex-grow**. Its used to increase the width of the box.
  - Instead of using width, we use flex-grow.
  - Also, one new concept is being understood that vh and vw concept is not applicable for inheritance and % concept is according to the parent element.
  * vh and vw is according to the web page.

# CSS Grid Layout

- Grid is 2 dimensional. FLex is one dimensional.
- **Cheatsheet** for vscode :- This will print the div class 5 times with class name as row 1, row 2, row 3 and so on.
  > div.container{row $}\*5

## **1. display: grid** :-

- Used to properly adjust the boxes.
- Responsiveness of grid is by default very good.

## **2. grid-template-<rows/columns: size>** :-

- Column is used to make changes in the width and row is used to make changes in the height.

* The rows or column will adopt the size we assign to it & also the alignment. This is way better than using width element.
* The size have 2 values:- _normal px,pc,etc_ and _fr_
  - fr is fraction.

- Size of each boxes are need to be given manually. To simple that work we use `repeat` element.

## **3. grid-auto-<rows/columns: size>** :-

- This will resize all the child classes present in parent class.
- Set a default size for the columns in a grid.

```CSS
            grid-auto-rows: 120px;

```

## **4. Gaps** :-

1. column-gap
2. row-gap
3. grid-gap :- column+row

## **5. grid-row/column-/start/end** :-

- Used to change position of any particular box.
- It uses the number of given line when we inspect and click grid in given code.

### Challenge1-Grid :- [Challenge1_Grid](https://codepen.io/Vansh-Baghel/pen/ZErYmyY)

**Goal**

![grid](Grid1.png)

- _\*\* HTML Explanation:-_\*\*

  - **structure** :-
    - One container containing 6 sub class for each column.
    - Each of the sub classes contains divs because each column has boxes which are completely fitted w.r.t its width.
    - We know that we use div for printing boxes on new row, so for each boxes into each sub class to be printed on the new line, we use div.

* _\*\* CSS Explanation:-_\*\*

  - **container** :-
    - Grid column is used to divide the container into 6 parts horizontally.

> child and child.div are different. child div refers to each box, while child refers to the whole column of boxes.

- **child** :-

  - By using display:grid, we easily fitted all the child boxes into the container with its full width.

- **child.div** :-
  - We added all the properties required for each box into this class.

* **The grid-gap** :-
  - Use it wisely, we used in container to get space between the major 6 divs which are fitted in the screen.
  - We used in child to get the space between the 28 individual divs.

### Challenge2-Grid :- [Challenge2_Grid](https://codepen.io/Vansh-Baghel/pen/eYVmQEN)

**Goal**

![grid](Grid2.png)

- _\*\* HTML Explanation:-_\*\*
  - **Structure** :-
    - We created a container which contains 2 major div classes.
    - Those 2 classes are for Nav and the remaining boxes.
    - 2nd div is a double-nested div which consists of total 3 rows, ie, 3 sub divs.
    - The 2nd sub div is itself a nested div because we need 2 boxes in the same row. If **sec_row** wasn't been applied then both the boxes in the **sec_row** might've been printed on different rows.
    - As we increase the size of the nested div by using `template row`, the size of nav automatically increases to match up with the height. Also, the width of footer is increased in the same manner due to the use of `template column` in the sec_row

* _\*\* CSS Explanation:-_\*\*

  - **container** :-

  * Easily both the major divs are separated by template-column

  * **nested_lists** :-
    - display is used to fit all the boxes according to thr given height in template.

# Transition & Animation

## Transition properties

- You can edit any transition by going to inspect and manually making changes.
- Transition couldn't handle complex changes, so for that we use animation.

### 1. transition

- It is a shorthand property.
- `transition: transition-property, transition-duration, transition-timing-function, transition-delay `;

### 2. transition-duration

- It gives the time period for the transition to occur

### 3. transition-delay

- It will activate the transition after the given time period.

## Animation Properties

Two types of animation property exists.

1. **Style** :- Normal like others.

2. **Keyframe** :- Starts with @ . @keyframe (name_of_animation){}

### 1. animation

- It is a shorthand property.

* `animation: animation-duration animation-timing-function animation-delay animation-iteration-count animation-direction animation-fill-mode animation-play-state ;`
* Well, this was the syntax of the shorthand property. Not necessary to maintain its order.

* **Animation&Transition_try**:- [animation & transition](https://codepen.io/Vansh-Baghel/pen/XWZmqRN)
  **_Explanation_** :-
  - We used tranform to move the box.
  - If transition is used into hover then the transition wont flow back. If we u=put it directly into the child, then it will complete the transition.
  * Used all the animation and transition into hover.
  * Keyframes must be outside and must be treated as a new style. The **identifier** (@keyframe identifier) must be the property on which we want the transition to occur.

# Theory

# Combinator

[Combinator](https://github.com/PacktPublishing/CSS---The-Complete-Guide-incl.-Flexbox-Grid-and-Sass-/blob/master/Section%202/css-combinators.pdf)

# Selectors

- It refers to what is selected to make style changes.
- Like class , element or universal (\*) is selected.

# Priority

[priority](https://github.com/PacktPublishing/CSS---The-Complete-Guide-incl.-Flexbox-Grid-and-Sass-/blob/master/Section%202/css-specificity.pdf)

- More specified tag are given more priority. EG:-
  `.product < product.h1`

- In above eg, the h1 will be modified by more specified one, tho .product is not wrong to make changes in h1.

1. Inline styles. like `<style> = ()`
2. #ID selectors.
3. .class, :pseudo-class (EG:- hover) and attribute selectors .
4. elements (like a, div , p) and :pseudo-element selector (EG:- \* )

We must use `body` instead of `*` if you want to put style to every elements and overwrite any style.

`body` style will be inherited to every element.

# Div & nav on same line (Chp 3: L13-L16)

Its tough to understand the concept and using it rather than randomly trying things in css.

## display : \* _inline-block_ :-

- Outer header/div:- Used to print on same line/same row. But yet it wasnt visible on same line.
- li tags :- Used to align the lists into horizontal positions rather than viewing them on different lines.

## List style: none

Must be used in that class only to remove the bullets from ul.

## Width calc

> IMPORTANT CONCEPT

```CSS
width: calc(30% - 8px)
```

> The space infront and ahead - is important.

- We reduced nav by 57px even tho the div was of 48 px.
- Its not possible to minus 48px and view them on same line because the space inside the html file between <div> and <nav> tag is also calculated (literally space inside of an html file). If the div and nav tag is placed on the same line and then 48px in decreased then we can see the proper results.

* IF we change the font-size of div, we should deduct those px from the width.

## Vertical align:middle

Used to align the text vertically middle of that box and both the text will be on same height in that box.

Its a minor change which we must keep in mind.

## a (anchor) tag styling

- Class doesnt work , ID works.
- Browser by default directly point the `a` tag so we have to put styling very specifically on it.

## background image

`background-image:url(name of img or the url)`

# pseudo class (:)

- hover, active, playing, pause, not.

## not pseudo class

- This class is used to select all the elements except the specified class.
  ```CSS
  a:not(.pro){}
  ```
- Here, pro class ka a tag will not be affected.

## focus

- Used to make changes when we click the specified tag like button or any div box.
- Can change text color , bg color , etc.

# pseudo elements (::)

- first line, after, before, first letter

## Id vs class

![s](../Notes_resources_imgs,pdfs,etc/id&class.jpeg)

- Using ID, you can make your anchor clicks work to reach different locations on your web page.

# Plan Part in the file

- `article` tag is used to keep the content separate from others.

* Display inline-block is used to add all the 3 boxes in the same line with the help of width tag.

- Middle box is bigger as it has an extra heading.

# 1. **Inline** :-

Displays an element in the same line. (like `<span>`). And take only the space which a word needs.

- **Any height and width properties will have no effect**.

# 2. **Block**:-

- Displays an element which starts on a new line, and takes up the whole width. It adjusts the box into the column by default.
- Can change the width and height of block and elements appear on different line.

# 3. **Inline-block**

- Take only the required space & same line like inline element and widht height can be adjusted like block .

# Path Managing

- To display any image or anything in md or html through downloaded files but different directory, we must right its correct path.

- EG:-

```CSS
FOR CSS:-
    background-image: url(/Notes_resources/peace.png);
```

# 5.

## Float & clear

- It changes the position of any element and the place will be occupied by other element.
- Very useful to float image and text in the same line.
- _clear_ is used to prevent any element to take the place beside the floating element and both will be visible on separate lines.
- Important hack for clear :- Use **div** to clear the floating boxes or elements , like add an empty div between them and then style it.

  **_ID > Class_**

## Div as container

- Whenever we want to adjust the whole column which contains like 3,4 boxes with content , we can put them into div and can add styling to div.
- This will affect the column and not the box or the content of box.

# 6.

## z-index

- We can use z-index with position when an element is getting overlapped by other while scrolling , simply set the z-index according to priority to adjust both the elements.
- Using "position" is important & necessary with z-index otherwise it wont work.
- We use `-` sign to add any boxes in the end.
- Used to overlap the elements/ boxes.
- Greater the number of index, more will be the priority, means it'll be at the top.
- Default value is 0 in browser

## positions in css

Default value is static in the browser.

### 1. **Fixed**:-

- This position of it will remain at the same place on the screen even if we scroll the pg.
- Best to use for nav bars for a browser.
- If we change the margin of html , then we have to use `left: 0 and right:0` to fix for eg a nav bar .

### 2. **Absolute**:-

- This will overlap the boxes and the text if we put the styling accordingly.
- It will refer to the html position by default but will refer to the ancestor element which have the position style in use.
- This reference will be for the positions we apply through left, right styles.
- It is not stuck on the web page like fixed.

### 3. **Relative**:-

- NOTE :- In **relative** , the distance changed will be with reference to the element itself because the positioning context is the element. While in **absolute** and **fixed** the reference is with the html file.
- top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position.

### 4. **Sticky** (rarely used)

- A sticky element toggles between relative and fixed.
- It wont have any effect unless top , bottom , left , right is used with it, it'll just act as it doesnt exist.
- It stops once its parent element is closed.

## Stacking Context

- child element's z-index has no effect on other parent elements .
- It says that if there are 2 parent elements , one has z-index 1 and another one has 100 . If child element of parent element which has z-index 1 has z-index of 1000 then still the child will lie below the 2nd parent element.

# 11 .

## 1 grid-column property

- Number of child elements is equal to the number of columns.

## text-transform

- Used to transfer the text into uppercase, lowercase ,etc,

## Overflow ( scroll/auto/hidden/visible;)

- Scroll is very useful for any part of ur website to be scrolled in a certain list.

## background image VS color

- Img overwrites color even if color is used down .

## background-size

- Used to fit the img properly in the web .
- **cover** is used to fit the image properly into the container.
- **contain** is used to fit the image without cropping it. In cover , its kind of cropped .
- We can manually add the size too of the image.

## background-position

- We can use this only with the background image.
- We can add the position of image that how far the space must be.
- With `%` it'll adjust the image of the cropped part , ie , if we want some bottom part of img to be in the frame then we can adjust it y-axis and keep x as 0 .
- `%` wont work if the image is already fixed properly. For adjust that, use px or any other unit.
- We can also use `left` or `left 10%` to set left as `0%` or `10%`.

[bg-properties](https://github.com/PacktPublishing/CSS---The-Complete-Guide-incl.-Flexbox-Grid-and-Sass-/blob/master/Section%207/css-background-properties.pdf)

## background-origin

- border-box (content will also include border ie below border there wont be white space) , padding-box (includes padding and content but not the border , ull see difference if u set the border as dashed), content-box (removes the padding , margin).

## background-clip

- Overwrites origin but kinda similar to origin.

## background-position

- Used to adjust image the way we want.

## backgroud shorthand property

- background position and size are separated by a slash , if only one value is specified like border-box then it'll be added to both origin and clip otherwise if we mention both then origin will be accepted before clip.

## editing img (not bg img)

- Background img is added in css , this img is added in html by specifing the path.
- We have to select the img tag separately to edit it , because it doesnt inherit the size of container.
- It has its own size and the only way to edit is this.

## aligning img and text

- To align the text and image side by side, best way to do is to set the _image container_ and the _text_ element style as `inline-block` and `vertical-align:middle` to properly see them side by side.

## border glitch

- If we have an image in an image container in the form of inline property , then shadow will give some extra white space , so to remvoe that we can use `vertical-align` or `display: block` .

## linear gradient

- Both linear and radial gradient counts as image .
- linear gradient(direction , color) , Here direction is by default from top to bottom . We can adjust the direction according to our desire.
- We can add degrees to the direction like `30deg` .

## radial gradient

- It basically gives shape the bacskground acc to the color . Default shape is ellipse.
- We can give the shapes and direction at the same time and also the width `circle to top` or `circle width` .
- The width applicstion changes according to the shape , like circle takes 1 arguemnt while ellipse will take 2 . We can assign the width to the colors too .

## filter

- We can add many visual things by using filter
- EG:- `grayscale` can add grey color .

## SVG

- It doesnt get blurly however times we zoom it. Its size is also smaller than jpg , etc.
- It gives more control than img to change the img , like we can change the lines of flowchart, eyes of any face , width of image , etc

## Units

- rem is like it will multiply the value with the root value ie with the html's value which could be set or like the default.
- For **padding** , **font-size** and **margin** (margin not always) use **rem** because it makes the things look good in different device with different defaults.
- em must not be used because it multiplies the value with the parent's/ ancestor's value . If you use it in twice nesting then it'll multiply the value twice which could be fatal and confusing.

# Media query

- So in this we must align the tags according to the size in ascending order otherwise it wont work.
- Try to include this style at the end of your website.
- Make your website for phone and then through this styling make it for desktop.
- We have to use min/max-width after the @media query and also in the containers to stop their size after a certain limit.

# invalid && valid pseudo selector

- Used to highlight the invalid statements.
- Can be used with required attribute in the input tag.

# Font styles

## @font-face

- We can add the font file from the files into this using src

#

## @import url()

- Font from google could be added by this.

## letter spacing

- It increases the space between each of the letters.

## white space

- We can use **pre** to add space of a paragraph.
- We can use **nowrap** to print all the text on the same line.

# flexbox

- children tags acts as flex items and we can use align-self for it.
- Parents tags mai we can use **justify-content** , **align-content** , **align-self** , etc properties.

## inline-flex

- inline-flex are also used to align the items in the same line but while decreasing the size the item's size **wouldn't decrease**.

## flex-wrap & flex-direction

- As soon as we change the size in flex-wrap , the items move to the **next line**.
- In flex-direction , if size of items are **defined** then it **wont change** but if its **not defined** then it will be **adjusted according to the page** size.

## main and cross axis

- In flex-direction column ,
  - main axis will act as column.
  - cross axis will act as row.
- In flex-direction row ,
  - main acts as row and cross acts as column.

## flex-items & justify-content

- **flex-items** follows the **cross axis** and **justify content** follows the **main axis**.
- If the direction is column , then the flex-items will act as column and justify-content will act as row.
- If the direction is row , then the flex-items will act as column and justify-content will act as row.

## Trick to center the items

- It could be done by _justify content_ **center** if the _flex-direction_ is **row** and could be done by _flex-items_ **center** if the _flex-direction_ is **column**.

## align-content

- Combination of align-items and justify-content , if we decrease the size of item then it will **wrap** the item according to the property which we assign to the align-content.
- The value will be **triggered** as soon as we **decrease** the size of the items or if the size of **container** is **smaller** than the items to fit in.

## order

- We can **adjust** the order of child elements by using **order**

## align-self

- It can only be used on one element at a time , you cannot use it for more than one child elements.
- It follows the **cross axis** ie opposite the direction of the flex.

## flex-grow

- It can only be used on one element at a time , you cannot use it for more than one child elements.
- It keeps growing from its given width if we change the width of the screen.
- Default value is 0.

## flex-shrink

- Default value is 1.
- It can only be used on one element at a time , you cannot use it for more than one child elements.
- It keeps reducing from its given width if we change the width of the screen.

## flex-basis

- Always follows the main axis only.
- It gives the height or width value wrt to the direction.
- If direction is **row** , then the value inside the flex-basis will **overwrite** the **width** and if direction is **column** then will overwrite **height**.

# Grid

- Very important to give the positions to the elements and its handles the hardest part of web page ie to give the positions.

## display grid

- It gives the rows and columns according to the elments present inside the parent element like each child acts as row and if child have grandchilds then child will be one column and grandchild row inside that column.

## grid-template-columns/rows

- We can add the columns no matter the child elements by giving the size in px , % or fr.
- It will create column which doesn't exist.

## grid-(column/row)-(start/end)

- This is used to adjust the space to be taken by the element like to join multiple rows and columns.
- By passing the **value** as the number of the line of column/row which we can see from layout , this indicates that **till** how much block it must **exceed**.
- **auto** fills up the remaining space of the row or column by the last element and this could be very helpful .
- **repeat** is used to avoid the repetation of values we want to give , for eg , if we want to create 16 rows then writing **(16 , 25%)** is the best way to get .
- Using **span** allows us to mention the number of blocks we need to be merged.

## grid-row/column

- It is a shorthand property to define the start and end of the following.

## grid-gap

- It is a shorthand property to define row-gap and column-gap.
- Also both of the properties can also be defined separately too .
- If we define only one , then it will be applied to both row and column.

## grid-auto-rows/columns

- It allows us to set the size of all the following to the mentioned size inside the property.

## grid-auto-flow

- It allows us to change the flow of the new added elements , the default flow is row for the direct child elements but we can change it to column.
  
  ## auto-fill
  - Used to align the items on the same line automatically, otherwise the size doesn't change. 
  -  This could be used with _grid-template-column/rows_ , as we don't need to specify the number of rows/columns like repeat (2,...). 
  - It utilizes the whole row
  
  ## auto-fit
 - Used to fit all the items on the same line . 
  - Same as **auto-fill** , just the items will be arranged properly if there are less items, for eg, if there are 3 divs it will arrange it in the center of the row. 
  - If the size is decreased the divs will be moved downwards. 
  
 # Grid Vs Flex
  - Use flex when u only want to make changes for rows or columns separately. 
  - Use grid when u want to make changes with both rows and columns. 
  
# Transform
  - It is different from animation :). 
  
  ## Transform-origin
  - Default value is center, 
  - It shows the place from where must the transformation should take place.
  
  ## translateX and translateY
  - It works as left and right of position, it changes the position of the transform. 
  - It is good to use this rather than setting position and giving left right top bottom in transform. 
  - The X and Y will be applied wrt to the box, like it will be parallel to the box. If the box is at 45° , then same will be its path of translate. 
  
  ## translateZ
  - This creates a 3D effect, like Z axis is the axis which is going inside the phone Or coming out to us. 
  - To make it move inside, we use negative value. 
  
  ## skewX and skewY
  - It changes the shape of the box, as if someone pulled it from left or top corners. 
  - The negative values will move it to right and bottom respectively.
  
  ## scaleX and scaleY
  - It allows us to increase the width and height of the image using it inside transform. 
  - Shorthand property is **scale** , which will be applied to both axes. 

  ## perspective and perspective-origin
  - With this we can see the object from different sides which will act as 3D effect. 
  - origin can make us see it from which ever side we want.
  
  ## rotateX and rotateY
  - Used as predefined value inside transform property. 
 - If we rotate the parent element then it'll also rotate all the child elements. 
  - It is used to rotate the boxes . 
 
  ## transform-style
  - Default value is **flat** which means that the container will make the divs move with it along the axis. 

  ## backface-visibility
  - If we want to hide the back side of any div we can use this property with hidden. 
  - Back face means the back side which we are able to see when it's flipped. 
  
  # SASS
 
## SCSS
* Visit **sass lang.com**. We need to install ruby and then write the cmd in terminal to insta *gem*.
* Create a new file with extension **.sass** but sass is different fron CSS as it doesnt have curly bracers and semi colons which makes the code ugly, therefore will use **.scss** extension.

## Nested Selectors
* We can write another tag inside the curly braces of the selector .
* To convert the SCSS file to CSS file we use command.

## Variable
* We can make a variable for any property value like any color code by using a prefix **$**.

## Partial
* We name this file starting with under-score (\_). We can copy all the variables in this file and then import in the other file where its used.
* We can reduce the run-time by using only 1 CSS file and rest of them SCSS.
* When we import another CSS , it tskes some time to load and if we use SCSS then we directly get that code in the CSS avoiding the creation of new file.

## Media Query magic SCSS
* We can use **media queries** inside that element itself which will reduce the step to mention the element name everytime and media queries will be just below the element name .

## Mixins (One liner legend)
* Here we can avoid the repeating code steps everytime in CSS. We assign function using **@mixin** and it will include those CSS lines which are being repeated.

* By using **@include funcName()** , we can see those lines in the CSS file but in SCSS file we are just putting onr line code .

## Ampersand Operator (Pseudo elements cleaner)
* By using **&** , we can join any class, id or pseudo elements by nesting it .
* Nesting means we dont need to repeat the main element , just need to write **&:hover{}** or **&.className** inside the curly braces of main element.
* Makes life so simple.

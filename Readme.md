# HTML

**What is HTML?**
* html is stands for **HyperText Markup Language **
* It is used for creating  the structure of webpage
* The Structure we want to create for that we have many tags in html.
#
**What is HyperText?**
* Any text that contains link of of any other webpage is called as hypertext.
#
**Why It's called as Markup Language ?**
* By using HTML we are not writting any logics,
only we are creating a structure.
#

## Tag

**What is tag?**
* tag is predefined word enclosed with angular braces
* in HTML 2 types of tags
    * Paired Tag
    * Unpaired tag or self closing tag

**Paired Tag?** 
* Any tag which has a openning tag and closing tags is called paired tags
    * Eg:
        **<h1>welcome</h1>**

    *Syntax* 
    * **<tagname> Content </tagname>**

**Unpaired Tag?**
* any tag that only the openning tag there no closing tag is called as unpaired tags.
    * Syntax

        **<br>,<hr>,<img>,<meta>**

## Structure of the HTML

    **
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Document</title>
    </head>
    <body>
        
    </body>
    </html>
    **


****<DOCTYPE html>****
* It is used to tell broswer whcih version of html we aare using.
* Currently we are using html version 5.

****<html></html>****
* It is the root tag of html structure.
* all the content should be inside this root tag.

****<head></head>****
* this is used to provide the meta information

****<title></title>****
* This is use show the title of the page 

**<body></body>**
* The content we want to display in the broswer everything should be written inside this tag.

## Heading Tag

**Heading tags**

* In html for providing headlines (heading or subheading)
* There are 6 heading tags 
* **<h1></h1> to <h6></h6>**
* heading tags all paired tags
* all the heading tags are block - level element

    * Eg
        * **<h1></h1>**
        * **<h2></h2>**
        * **<h3></h3>**
        * **<h4></h4>**
        * **<h5></h5>**
        * **<h6></h6>**

**Paragraph**
* In html if we want to write a any text content , that should be written by using a paragraph tag(**<p></p>**)
* Paragraph tag is denoted by **<p></p>** and this is paired tag
* It is a block-level element 
* paragraph tag size is 16 pixels

## Formating tags 
* It is used to chnage the appearance or fomat of the text content

****<b></b>****
* This is used to make the content bold

****<strong></strong>****
* It is also use to make the content bold but this tag having **higher priority** compare to **<b></b>** tag

****<i></i>****
* It used to make the content in italic

****<em><em>****
* This is used to make the content itali same like ****<i></i>****.

****<u></u>****
* This tage is used to make or provide the underline for the text content.

****<ins></ins>****
* it is also used to provide the underline for the text 

****<mark></mark>****
* it is used to provide high light for the text 

*****Important*****

****<sup></sup>****
* It is used to write any content at the power

****<sub></su>****
* it is used to write any content at the base

*****end of Important*****

****<q></q>****
* It is used to provide a double qoutes to the centent

****<pre></pre>****
* It is pre-formatted tag, inside this tag how we will
write the content it will display as it is .

****<del></del>****
* It is used to give strike through the text.

****<br>****
* It is used to to break the line 
* It help to move the content in the next line,
* It is unpaired tag

****<hr>****
* It is used to provide the horizontal line
* It is unpaired tag

## Elements
* Element is camination of tags and the content inside the tag

*Types of a Elements*
* We have 3 type of Element in html
    * Block Level
    * InLine Level
    * Inline-Block level 


**Block Level**
* These elements are taking the full space of its parents and it will displaying in a next line 
* By Default it will take full width of the parent 
* We can provide the *height and width* for these elements

    * Eg
        * **<div></div>**

**Inline Level**
* These Element will displaying in the same-line 
* we *can't provide height and width* 
* It Occupying the content area

    * Eg
        * **<b>,</b> | <i></i> | <u></u> | <span></span>**

**Inline_Block Levele**
* It is the combination of **inline and block level element **
* This Elements are will *display in same line but we can not provide the height and width*

    * Eg
        * **<button></button> | <input/> | <img> **

## Attribute
* Attributes are used to provide additional information to the tags.
* Attribute should be written in opening tags.
* Eg
    *Syntax*

        <tagname attributename="value"></tagname> 

### **<Img> tags**
* It is used to add the image in the webpage.
* In this tag we have 4 attributes
    1. *src* : It is used to provide the path of the image.
    2. *alt* : It is used to provide the alternate messag .
        
        * If the image is not displaying that time this alt message will displayed on the page.
    3. *height and width* : Used for resizing the image.
* **<img>** tag : It is a self closing tag / unpaired tag
* it is one *inline-block* level element.

### **<marquee> Tag**
* It used to make any content Scrollable on the webpage 
* By default the content will scroll from left to right side
* *Attributes of marquee tag* 
    * **Scrollamount** - It is used to determine the speed of the scrolling content and by default value is 6
    * **direction** - It is used to determine the direction of the scrolling content and by deafult value left
                   - *values* :=> **left**,**right**,**up**,**down**
    * **behaviour** - It is used to determine how the scrolling content will behave.
                    - *value* :=> **scroll**,**slide**,**alternate**.
    * **loop** - It determines how many times the content should scroll.

    * **Height and Width** - It is used to resize the marquee tag area.

# List 
* In HTMl there 3 types of lIst They are :
    * Ordered List 
    * Unordered List
    * Description List

**Ordered List**
 * Ordered list is used to group and arrange the elements in particular order.
 * For creating ordered list we need **<ol></ol> tag**
 * Inside **<ol></ol> tag** for writting iitems we need **<li></li> tag**  
  * These tags are *block level* element

  * *Attributes* in **<ol></ol> tag**
    * **type**
        * This Attribute is used to change the list style 
        * value are => 1, a, A, i, I
        * By default it will take number(1)
    * **Start**
        * This is used to specify the starting value of a list style 
    * **Reversed**
        * This is used to present in reverse order

**Unordered List**

 * Unordered list is created by using **<ul></ul> tag**
 * Here are we are gouping the elements together they are not arranged in specific order 

 * inside **<ul></ul>** tag for writting the items we need   **<li></li>** tag
 * by default it will display the list style as disc or bulletpoints
 * here we can provide only *type* attribute 
    * **Type**  
        * we can give 3 values they are : **disc**,**square**,**circle**,**none** as value 

**Description List** 
 * For creating Description list we need **<dl></dl> tag.
 * inside that we have to use **<dt></dt>** and **<dd></dd>** tag.
 * **<dt></dt>** tag is use to provide the Description for the term.
 * **<dd></dd>** tag is used to Description definition for that term.

# **<audio></audio> tag**
* This tag is used to add the audio & music in our webpage

## Attributes
* **Src**
    * It is used to provide the path of the audio
* **Controls**
    * It we give this attribute then only audio will be visible in the webpage and we can control audio (play,pause,skip)
* **autoplay**
    * For this attribute music will start automatically whenever page is loading ore refreshed
* **muted**
    * It will make the audio muted
* **loop**
    * This attribute is used to play the music n number time like infinity

# **<video></video> tag**
* this tag is used to display the video on the wepage 

## Attribute

* **src** 
* **controls**
* **loops**
* **autoplay**
* **muted** these functionality same as audio tags

**poster**
* this attribute used to provide the image or thumbnail for the video 
* in this atribute we have to link of the image or path of the image 


# Iframe tag

* it is used to add the diffrent webapges in the single page 
* it is inline block level element 

## Attribute

* **Src**
    * In this attribute we have to provide the path of the webpage we want to add in our webpage.

* **fromeborder** 
    * It is used to provide outline or border around content 
    * by defaut value is zero

* **height and width**
    * Used to provide the size of the content

## Achor tag

* This achor tag is denoted by `<a></a>` 
* It is used to creat a hyperlink 
* It is a in-line level Element

**Attributes**

* **href**
    * It is used to take the path where we want to navigate 
    * It helps to navigate or redirect one page to anotherpage 

* **target**
    * By default if we click any hyperlink it opens in same tab, 
    * if we want to open in diffrent tag we need a target attribute
        * `target=_blank`
            * It is used to open in next new tab
* **title**
    * When we hover (keeping mouse cursor on the element) then `title` attribute helps to display some message.

* *step1*
    * In which tag we want to navigate there we have to give 'id' attribute

* *step2*
    * Which value we are giving for the id attribute , same value we have to provide in the `href` attribute with `#` symbol

## Table in HTML
* Table in html contains of rows and columns .
* for creating the table this `<table></table>` tag .
* inside table if we want to create a row , we need `<tr></tr>`tag . 
* Inside row for giving data we need to use the `<td></td>` tag .
* for Providing heading data in table we need `<th></th>` tag.
* for giving the caption/name/title of the table we need `<caption></caption>` tag.

**Attributes in table tag**
* *1.border*
    * It used to provide border/outline around the total table.
    *
* *2.Height,width*
    * Used to resize the table length.

* *3. CellSpacing*
    * It is used to provide the space between the cells.

* *4. cellpanding*
    * It is used to provide space inside the cell between the content and border.

***Attributes for `<dt></dt>` and `<th></th>`***

* *Rowspan* 
    * This attribute is used to combines two or more rows.
* *colspan*
    * this attribute is used to combines two or more columns.

* note: 
    * *we have some extra tags in table like 
        `<thead></thead>`,
        `<tbody></tbody>`,
        `<tfoot></tfoot>`*

## `<div></div>` tags 

* it is one block level elements used to make the division 
* indside this tag was can write inline / block and inline-block level element
* we can provide height and width

## `<span></span>`

* it is on inline level element used to select some part of block level elements 
* we can't provide height and width 

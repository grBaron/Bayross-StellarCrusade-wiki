#   Sandbox
### Sandbox to present how various things in Markdown work, how they are written and what they look like

##  Table of contents

-   [Blockquotes](#blockquotes)
-   [Comments](#comments)
-   [Headlines](#headlines)
-   [Images](#images)
-   [Links](#links)
-   [Lists](#lists)
-   [Tables](#tables)
-   [Text](#text-display)

---
---

##  Blockquotes

>   Blockquote
>>  Blockquote in Blockquote
>>> Blockquote x 3
>>  Here
>   we
>>  GO
>>  and

>>  Demonstrate,
>   how this looks

---

##  Comments

<!--Comment 1-->
<!--
Comment 2
-->

---

##  Headlines

#   Headline
##  Smaller headline
### Even smaller headline
####    Even more smaller headline

---

##  Images

[image1](/pictures/cocunutJPG.png)

![image2](pictures/cocunutJPG.png)

![image3](/pictures/cocunutJPG.png)

[image4](pictures/cocunutJPG.png)

---

##  Links

[Table of Contents on this page](#table-of-contents)
[Table of contents of this project](../TableOfContents.md)
### [Table of Contents on this page](#table-of-contents)
### [Table of contents of this project](../TableOfContents.md)

---

##  Lists

### Ordered List
<!--Markdown verion-->
1.  One
2.  Two
    1. Indentation
    2. Indentation
3.  Three
<!--Comment: Technically the order of the numbers doesn't matter, only the point does, but is still good practise to do it this way-->

<!--HTML version (to be used when writing in one line)-->
<ol>
    <li>One</li>
    <li>Two</li>
    <ol>
        <li>Intendation</li>
    </ol>
    <li>Three</li>
</ol>

<ol><li>One</li><li>Two</li><ol><li>Intendation</li></ol><li>Three</li></ol>

### Unordered List
<!--Markdown version-->
--  Item one
--  Item two
    --  Intendation
--  Item three

<!--HTML version, again just so one knows and needs to write in one line-->
<ul>
    <li>One</li>
    <li>two</li>
    <ul>
        <li>intendation</ul>
    </ul>
    <li>three</ul>
</ul>

<ul><li>One</li><li>Two</li><ul><li>intendation</li></ul><li>Three</li></ul>

---

##  Tables
<!--Always 3 spaces or "-" to the next "|"
":---" leads to right aligned, ":---" is standard and left aligned, ":---:" means the text will be shown centered
-->

| Text   | Goes   | Here   | Again   |
|---|---:|:---|:---|
|Is there anything    | Special   | That you   | Can see?   |
| These are   | <ul><li>Just</li><li>a few</li><li>nice things</li></ul>   | That you can do   | In Markdown   |<!--between the ul you put the list, between the ul parts the list items-->

---

##  Text display

**bold text**
__bold text__
In**middle**bold <!--Don't use the "_" way in the middle of text-->
*italics*
_italics_
In*middle*italics <!--Don't use the "_" way in the middle of text. Also consider checking if the italicized text is overlapping with the non-italicized text-->
***italic and bold***
___italic and bold___

---

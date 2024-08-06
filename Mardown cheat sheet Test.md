# 1-Headings
how to give headings in markdown files?
# Heading 01
## Heading 02
### Heading 03
#### Heading 04
##### Heading 05
###### Heading 06

# 2-Block of words
This is a normal text in markdown
>This is a block of special text

>This is a second special text

>This is a block of special text
>
>This is a second special text

# 3-Line breaks
This is a 40 days long course Data science with Python AKA (also known as) Python_ka_chilla_with_baba_aammar.

This is a second line.

This is a 40 days long course Data science with Python AKA (also known as) Python_ka_chilla_with_baba_aammar.\
This is a second line.

# 4-Combine two things
Block of words and headings

## Heading 2

# 5-Face of text
**Bold**\
*Italic*\
***Bold and italic***\
OR you can also use other symbols eg(-, +)

> Write in comments about Bold and Italics with underscore

# 6-Bullet points/ Lists
- Day-01
- Day-02
- Day-03
- Day-04
- Day-05
    - Day-05a (sublist)
    - Day-05b (sublist)
- Day-06
> OR can also use other symbols eg(*, +)
* Day-01
* Day-02
* Day-03
* 
> Numbering of Lists
1. Day01
2. Day02
3. Day03
4. Day04
5. Day05
   1. Day05a (sublist)
   2. Day05b (sublist)
6. Day06

# 7-Line breaks or Page breaks
This is page 1.

This is page 2.

This is page 1.

---

This is page 2.

> OR can also use 3 _ or 3 *

# 8-Links and Hyperlinks
<https://youtube.com/playlist?list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI&si=0XhCEfcILX15oEJI>

To access the playlist of Python_ka _chilla. [clickhere](https://youtube.com/playlist?list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI&si=0XhCEfcILX15oEJI)

<https://www.youtube.com/@Codanics>

Codanics youtube channel. [click here](https://www.youtube.com/@Codanics)

> making key eg : codanics

[codanics]:https://www.youtube.com/@Codanics
Codanics youtube channel.[click here][codanics]

# 9-Images and figures with links and Direct outputs
To join this course please scan the following QR code and join youtube channel.
![QR](codanics.png)

click on [QR](codanics.png) to open QR code and then scan

<!-- use [QR](codanics.png) for link then click to open the QR code OR ![QR](codanics.png) to directly access the QR code. -->

> Task: How to comment out a markdown line? and its shortcut?
>
> Ans: use (Ctrl + /)
<!-- To comment out use (Ctrl + /) -->

online picture link:

[codanics](https://www.google.com/search?sca_esv=0e526ec8824269be&sca_upv=1&rlz=1C1KNTJ_en-GBPK1082PK1082&q=codanics&udm=2&fbs=AEQNm0Aa4sjWe7Rqy32pFwRj0UkWd8nbOJfsBGGB5IQQO6L3J_86uWOeqwdnV0yaSF-x2jrrv3e_fewYh7LFIpXPaEgNQ1vZHC7aVwStfN-hyt8w93YQeezdbRIymJD7qA2kbpe9Fh9864JABjicse8VbablMojvKjXXFFob0FP4nVFoMlb_6-hv3UtT3ipYvbN7JfxWg62s&sa=X&ved=2ahUKEwiv4byD8d-HAxUmRPEDHbp6OakQtKgLegQIGhAB#vhid=GRjVtCcWAILqOM&vssid=mosaic)

OR

![codanics](https://www.google.com/search?sca_esv=0e526ec8824269be&sca_upv=1&rlz=1C1KNTJ_en-GBPK1082PK1082&q=codanics&udm=2&fbs=AEQNm0Aa4sjWe7Rqy32pFwRj0UkWd8nbOJfsBGGB5IQQO6L3J_86uWOeqwdnV0yaSF-x2jrrv3e_fewYh7LFIpXPaEgNQ1vZHC7aVwStfN-hyt8w93YQeezdbRIymJD7qA2kbpe9Fh9864JABjicse8VbablMojvKjXXFFob0FP4nVFoMlb_6-hv3UtT3ipYvbN7JfxWg62s&sa=X&ved=2ahUKEwiv4byD8d-HAxUmRPEDHbp6OakQtKgLegQIGhAB#vhid=GRjVtCcWAILqOM&vssid=mosaic)

![codanics](https://images.app.goo.gl/yMkHmpN3R1Qd5hPV7)

[Hammad picture](hammad.png)

Hammad Picture![Hammad](hammad.png)

# 10-Adding code or code block

To print a string use `print("Codanics")`

`
print("Hello Baba G")
`

```
x= 5+6
y= 3-2
z= x+y
print(z)
```
> This code will show color according to python language syntax

```python
x= 5+6
y= 3-2
z= x+y
print(z)
```
> This code will show color according to R language syntax

```R
x= 5+6
y= 3-2
z= x+y
print(z)
```

# 11-Adding Tables
| species | Petal length | sepal length|
| ------- | ------------ | ----------- |
| virginica | 19.5 | 18.5 |
| setosa | 17.5 | 16.5 |
| versicolor | 15.5 | 14.5 |

> To arrange the values below header (right align)

| species | Petal length | sepal length|
| ------- | ------------: | ----------- |
| virginica | 19.5 | 18.5 |
| setosa | 17.5 | 16.5 |
| versicolor | 15.5 | 14.5 |

> To arrange the values below header (left align)

| species | Petal length | sepal length|
| ------- | :------------ | ----------- |
| virginica | 19.5 | 18.5 |
| setosa | 17.5 | 16.5 |
| versicolor | 15.5 | 14.5 |

> To arrange the values below header (middle align)

| species | Petal length | sepal length|
| ------- | :------------: | ----------- |
| virginica | 19.5 | 18.5 |
| setosa | 17.5 | 16.5 |
| versicolor | 15.5 | 14.5 |

# 12-Install extensions
- It will enable # functions

- It  also open other functions of select and keyboard shortcuts OR select and right click to see the options availible

Bold (Ctrl+b)

italic (Ctrl+i)

eg type link and select it click right and then select eg hyperliink

```
code block

```

maddy![Image](maddy.png)

codanics [Link](https://www.youtube.com/@Codanics)


Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3


Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3


# 13-Table of content
[1-Headings](#1-headings)\
[2-Block-of-words](#2-block-of-words)\
[3-Line-breaks](#3-line-breaks)\
[4-Combine-two-things](#4-combine-two-things)\
[5-Face-of-text](#5-face-of-text)\
[6-Bullet-points-lists](#6-bullet-points-lists)\
[7-ine-breaks-or-page-breaksL](#7-line-breaks-or-page-breaks)\
[8-Links-and-hyperlinks](#8-links-and-hyperlinks)\
[9-Images-and-figures-with-links-and-direct-outputs](#9-images-and-figures-with-links-and-direct-outputs)\
[10-Adding-code-or-code-block](#10-adding-code-or-code-block)\
[11-Adding-tables](#11-adding-tables)\
[12-Install-extensions](#12-install-extensions)\
[13-Table-of-content](#13-table-of-content)



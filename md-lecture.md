__In this lecture we will be learning Markdown language.__ 

# 1- Heading

for this type of heading we uses " # " + " required heading". Later we use the hashtags multiple time to reduce the size of heading.

## heading 
here i use hashtag twice ## and then the required word.
### heading
#### heading

we can use hashtag "#" six time in a row.

# 2- Line break 
To start markdown language, firt understand how to give line breaks. For this we have to press enter twice. Or we can use " \ " to add line break 

# 3- Block of words

To write an special thing in markdown we use greather than sign ">" before the text. like this ">This is some thing special." which will took like this
>This is some thing special.
 
and to seperate this we have to press enter twice. Or if you want to write multiple lines in same block then add greater than sign in every line untill you think I am done writing this block. Here the example
" >This is some thing special. What abount the second one. "  now see this in block of word
>This is some thing special. What about the second one. 
 
 this is wrong. the correct way is mentined above which look like this. 

 >This is some thing special.
 > 
 >What about the second one. 
 
 >This is some thing special.
 
 >What about the second one. 

 # 4- Combing two things 

In this we are combing headings and block of words.
For that we are using two symbols at a time which are " # , > " 

 > ## Headings or Block of word

# 5- FACE of Text
in this we can make text bold, italic or blod and italic. For this we can use " * or _ " symbols. 

To make text blod you can use symbols twice. Like this ** bold** (but without space) which look like this  **bold** .

To make text italic you can use symbols once. Like this * bold* (but without space) which look like this  *bold* .

To make text blod and italic you have to use symbols three times. Like this *** bold*** (but without space) which look like this  ***bold*** .

Similarly we can use _ (underscore) instead of * .

# 6- Bullet Points / lists.
To create bullet point in markdown we use two symbols " - or + " 

- Day 1
- Day 2

and if you want to create a sub bullet then press tab and write 

- Day 1
- Day 2
- Day 3
    - Day 3a
    - Day 3b
- Day 4 
  - Day 4a
    - Lecture 2

If you want to go back the press shift + tab. 

> ## Numbering list
For numbering list you can just simply write the number and heading. like this

1. day1
2. day 2
3. Day 4
1. Day 5
   1. lecture 1
   2. lecture 2
2. Day 6

# 7- __Line Breaks / Page breaks__

as you can see that after every heading there is a line under it. So to add such type of line in any line we can use " * , - , _ " these symbols three times in a row. like this *** or ___ or --- . But before putting these symbols for line there must be space in frist and second line. 

The first line.

___

***

 The second line.

# 8- __Links / Hyper Links___

To ceate Hyper links in markdown language we use " <> " symbol. to create any hyperlink just paste the link inside the symbol. like this <https://www.youtube.com/live/c-QbaMdm7Qc?si=Nco93_k1DpmEuk25 >  (but without space). Which actually look like this:

<https://www.youtube.com/live/c-QbaMdm7Qc?si=Nco93_k1DpmEuk25>

so by using this method you can create hyper link of any of your video etc. 

To create link such as click here or watch now. First write that specific word you want to be clicked, such as i am using click here, in Large Brackets " [] ". 
After that paste the link in small brackets without space. like this

[Click here] (https://www.youtube.com/live/c-QbaMdm7Qc?si=Nco93_k1DpmEuk25) 

look's like this "

[Click here](https://www.youtube.com/live/c-QbaMdm7Qc?si=Nco93_k1DpmEuk25)

If you want to you same link multiple times. It is prefered to create key instead of repeating the process. To create a key we write any specific word which act as a key.
eg: 

 [YoutubeChannel] : https://www.youtube.com/live/c-QbaMdm7Qc?si=Nco93_k1DpmEuk25 (but without space)

[YoutubeChannel]:https://www.youtube.com/live/c-QbaMdm7Qc?si=Nco93_k1DpmEuk25

Then the next step is to write like this.(but without space and make the name remains the same )

To watch complete tutorial [Click here] [ Youtube Channel ]

To watch complete tutorial [Click here.][YoutubeChannel]

# 9- Images and Figures with Links.

There are two methods to one is to add iamge as a link and other is to display the image. 
The Link Method is same a the above but instead of video link add file  :

[Image] (ispr.png) (without space)

[Image](ispr.png) 

And to display the image Add " ! " in start of the line.

![Image] (ispr.png) (without space)

In result you have this. (This image is AI generated)

![Image](ispr.png)


For online Images replace file name with image URLs. 

# 10- Add code / Block of code

To write a code we use ( `  ) this symbols. To write simple code use this one time at start and end. like this : 

`print ("Coders") `

and to write a block of code put the symbol three times in two different rows. Like this

( ``` )


(  ```  )

Final look:

```
  x = 3
  y = 5
  z = x*y
  print(z)

```

But if you want to copy the code later then must use block of code method.You can also
change the colors accoding to the laguage like python,r , C++ etc .
For that you just have to mention the name of language after the symbol in start.
like this:

``python (but with three)\
  x = 3\
  y = 5\
  z = x*y


>This one is for PYTHON Language.

```python
  x = 3
  y = 5
  z = x*y
  print(z)

```

> This one is for  R language. 

```r
  x = 3
  y = 5
  z = x*y
  print(z)

```

# 11- Adding Tables

To add tables here we use ' | ' this symbol and in between the name of table.
Then in next replecate the same amount of column but with bash only. 

 |  NAME  |  AGE  |  GENDER|

 |-------- | -------- |(i did this to show you only )

 how actually it look like :

   NAME  |  AGE  |  GENDER |
 |-------- | -------- | ------- |

 Now after this add your data. like this  (|  Romaisa | 45 | female | )

   NAME  |  AGE  |  GENDER |
 |-------- | -------- | ------- |
 |  Tahir | 20 | male | 
|  Ahmed | 25 | male | 
|  Sundas | 30 | female | 
|  Ahad | 50 | male | 
|  Romaisa | 45 | female | 

the was arranged auto-matically . If you want to left align or right align the text or column just add " : " on left or right side repectively. like this |:-------- | --------: | 

And to center align add on both side like this |:-------: |

 NAME  |  AGE  |  GENDER |
 |-------- | --------: | :-------: |
 |  Tahir | 20 | male | 
|  Ahmed | 25 | male | 
|  Sundas | 30 | female | 
|  Ahad | 50 | male | 
|  Romaisa | 45 | female | 

# 12-  Table of Content

For this first write the topic in the large bracket [] and the after that in 
small brackets () write the refrence of heading. like this(But without space in both brackets):

[heading] (#1--heading)\ 

add \ for line break.

Final look : 
 
[1. Heading](#1--heading) \
 [2. LINE BREAK](#2--line-break)\
 [3. BLOCK OF WORD/ CITATION](#3--block-of-words)\
 [4. COMBINING](#4--combining-two-things)\
 [5. TEXT](#5--face-of-text)\
 [6. BULLET POINTS](#6--bullet-points--lists)\
 [7. PAGE BREAK](#7--line-breaks--page-breaks)\
 [8. LINKS](#8--links--hyper-links_)\
 [9. IMAGES](#9--images-and-figures-with-links)\
 [10. BLOCK OF CODE](#10--add-code--block-of-code)\
 [11. TABLES](#11--adding-tables)

# 13- Extention of Markdown

Download these Extention to make your you much more easier

  1. Markdown lint by David Anson
  2. Markdown Shortcut by mdickin
  3. Markdown all in one by yuzhang 
  4. Markdown PDF.


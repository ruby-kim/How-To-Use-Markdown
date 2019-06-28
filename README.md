Markdown Usage(How to use Markdown?)
======================

# 1. About Markdown
## 1.1. What is Martdown?
[**Markdown**](http://whatismarkdown.com/) was created in 2004 by the Markup Language-based text John Gruber and is easy to write and read and HTML transformable.  
Using a very simple structure of grammar using special symbols and characters, content can be created and recognized more intuitively on the Web as well.  
Markdown's recent rise to the limelight was thanks to [GitHub](https://github.com).  
README.md record information about the store Repository of the flagpole was the first mark-down document anyone using the flagpole would encounter.  
Markdowns have become increasingly popular as the strength of simple recording of installation methods, source code descriptions, and issues is highlighted.

## 1.2. Advantages and disadvantages 
### 1.2.1. Advantages :-)
	1. Concise
	2. Written without a separate tool
	3. Possible to convert various forms
	4. easy to store because of its low capacity and stored in text 
	5. Because it is a text file, the history of the change can be managed using the version management system
	6. There are many programs and platforms that support
### 1.2.2. Disadvantages :-(
	1. No standard
	2. Because there is no standard, the convert method or creation are difference on the tool
	3. It does not replace all HTML markup.

****
# 2. Markdown Usage(Grammar)
## 2.1. Headers
* Main-title
    ```
    This is an H1
    =============
    ```
    This is an H1
    =============

* Sub-title
    ```
    This is an H2
    -------------
    ```
    This is an H2
    -------------

* Headers: Only 1 to 6 support
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a 7.

## 2.2. BlockQuote
Use ```>``` the block-in-use characters used in e-mail.
```
> This is a blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

This may include other markdown elements.
> ### This is a H3
> * List
>	```
>	code
>	```

## 2.3. List
### ● Ordered list (number)
The ordered list uses numbers and points.
```
1. first
2. secnod
3. third
```
1. first
2. second
3. thrid

**To date, any number entered will be defined in decending order.**
```
1. first
3. thrid
2. second
```
1. first
3. thrid
2. second


### ● unordered list (a glossy symbol)
```
* Red
  * Green
    * Blue

+ Red
  + Green
    + Blue

- Red
  - Green
    - Blue
```
* Red
  * Green
    * Blue

+ Red
  + Green
    + Blue

- Red
  - Green
    - Blue

It's possible to mix it up.
```
* first
    - second
    	+ thrid
            = fourth
```

* first
    - second
    	+ thrid
			= fourth

## 2.4. code```<pre><code></code></pre>```
When you meet indentation with four spaces or a single tab, the conversion begins and continues until you encounter unentered rows.  

> A single line often causes problems that are not recognized properly.

```
This is a normal paragraph:

    This is a code block.
end code block.
```

<code>
```
This is a normal paragraph:
    This is a code block.
end code block.
```
</code>

If you apply it,
This is a normal paragraph:

    This is a code block.
end code block.

## 2.5. Horizontal line```<hr/>```
All the lines below create a horizontal line. It is often used for *share pages* when printing thumbnails in thumbnails.
```
* * *

***

*****

- - -

---------------------------------------
```

* * *

***

*****

- - -

---------------------------------------


## 2.6. Link
* Reference link

```
[link keyword][id]
[id]: URL "Optional Title here"

Link: [Google][googlelink]
[googlelink]: https://google.com "Go google"
```

Link: [Google][googlelink]
[googlelink]: https://google.com "Go google"

* Inline link
```
syntax: [Title](link)
```
Link: [Google](https://google.com, "google link")

* Automatic connection
```
<http://example.com/>
<address@example.com>
```

<http://example.com/>
<address@example.com>

## 2.7. Emphasis
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~

## 2.8. Image
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0)
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0 "RubberDuck")

Because there is no size control function, use ```<img width="" height=""></img>```
****
# 3. Markdown User
## 3.1. WSYWIG Editor
Most of the editors (Naver, Daum, Google, etc.) used on the web we commonly encounter belong to the WSYWIG Editor and basically take the form of applying style using HTML to decorate sentences. Therefore, if you copy and paste the contents of the View area of the Markdown Editor, such as the One-Pad, it is usually copied exactly as you can see in the View area. However, it is a problem when trying to correct sentences after pasting, as the tags with styles are altered during the modification process and have an overall effect. For Wordpress, it is recommended to use the function to convert post written in Markdown to HTML.

The bottom line is, **Copy and paste, preferably not to revise the text.**

## 3.2. Github, Bitbucket and Yobi
In the case of a recently popular collaborative development platform, markdown can be applied only by copying and pasting text written in markdown grammar or uploading it.

## 3.3. Applying MS Word
Available in the form of pasting items in the View area or recalling files generated by HTML exports. Because applied headers are applied to table of contents as Word reads them, even table of contents can be applied easily.

****
# 4. Arrangement
Markdown is a markup language that can be written easily on a plain text editing machine if you know only basic grammar. It is now widely used because it is easier to create stylized documents because it is supported by a variety of tools and platforms. Understand and use the markdown and quickly create a style document.
Markdown documents stored in the dropbox are available on Dropbox Web services, so they can be viewed directly from the web and used as a way to share links with others.

* Link Exampl: [Markdown](https://github.com/kimkyeongnam/How-To-Use-Markdown/edit/master/README.md)

## ○ 참고문서
* [78 Tools for writing and previewing Markdown](http://mashable.com/2013/06/24/markdown-tools/)

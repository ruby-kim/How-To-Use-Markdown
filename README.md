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
아래 줄은 모두 수평선을 만든다. 마크다운 문서를 미리보기로 출력할 때 *페이지 나누기* 용도로 많이 사용한다.
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
# 3. 마크다운 사용기
## 3.1. 이지윅(WSYWIG) 에디터
우리가 흔하게 접하는 웹에서 사용되는 에디터(네이버, 다음, 구글 등)이 대부분 이지웍 에디터에 속하며 기본적으로 HTML을 이용하여 스타일을 적용하여 문장을 꾸미는 형태를 취하게 된다. 그래서 하루패드와 같은 마크다운 에디터의 View 영역의 내용을 복사하여 붙여넣기를 하면 대체적으로 View영역에서 보이는 그대로 복사되는 편이다. 다만, 붙여넣기 이후에 문장들을 수정하려고 할 떄 문제가 되는데, 이는 스타일이 포함된 태그가 수정과정에서 변형되면서 전체적인 영향을 끼치는 탓이다. 티스토리 블로그에서는 쉽지 않고... 워드프레스의 경우에는 마크다운으로 작성된 포스트를 HTML로 변환해주는 기능을 활용하는 것이 좋다.
결론은, **복사해서 붙여넣기하면 가급적이면 본문은 수정하지 않는 것이 좋다.**

## 3.2. 깃헙Github, 비트버킷Bitbucket과 요비Yobi 등
최근 유행하는 협업개발플랫폼의 경우에는 마크다운을 변환하는 컨버터 기능을 기본탑재하고 있기 때문에 마크다운 문법으로 작성한 텍스트를 그대로 복사해서 붙여넣거나 업로드하는 것만으로 마크다운의 적용이 가능하다.

## 3.3. MS워드 적용
View 영역의 항목을 그대로 붙여넣거나 HTML 내보내기 등으로 생성한 파일을 불러오는 형태로 사용가능하다. 적용한 헤더를 워드가 읽어드리면서 목차에 적용하기 때문에 이를 활용하면 목차까지도 손쉽게 적용이 가능해진다.

****
# 4. 정리
마크다운은 기본문법만 알고 있다면 일반 텍스트편집기에서도 손쉽게 작성이 가능한 마크업언어다. 현재 다양한 도구와 플랫폼에서 지원하고 있기 때문에 더욱 손쉽게 스타일적용된 문서를 작성할 수 있기 때문에 점점 널리 사용되고 있다. 마크다운을 이해하고 사용하면서 쉽고 빠르게 스타일문서를 작성해보세요.
저는 Dropbox 프로를 구매해서 집-랩탑-스마트폰이 각각 연동을 시켜서 사용하고 있습니다. 드랍박스에 저장된 마크다운 문서는 Dropbox 웹서비스 상에서 제공하기 때문에 웹상에서 바로 열람할 수도 있어 링크를 걸어서 다른 사람과 공유하는 형식으로 사용하고 있다.
* 링크 예: [Markdown 설명](https://www.dropbox.com/s/1e7hbtd0yr0egft/20141021_markdown_use_tip.md?dl=0)

## ○ 참고문서
* [78 Tools for writing and previewing Markdown](http://mashable.com/2013/06/24/markdown-tools/)
* [John gruber 마크다운 번역](http://nolboo.github.io/blog/2013/09/07/john-gruber-markdown/)
* [깃허브 취향의 마크다운 번역](http://nolboo.github.io/blog/2014/03/25/github-flavored-markdown/)
* [허니몬의 마크다운 작성법](http://www.slideshare.net/ihoneymon/ss-40575068)

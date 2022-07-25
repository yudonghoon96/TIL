# 문서 작성을 위한 Markdown 문법 정리📝

<br/><br/>

## 목차

#### [1. 제목/소제목(Heading) ](#1-제목소제목heading)

#### [2. 목록(List) ](#2-목록list)

#### [3. 코드 블록(Code block) ](#3-코드-블록code-block)

#### [4. 링크(Link) ](#4-링크link)

#### [5. 이미지(Image) ](#5-이미지image)

#### [6. 인용문(Blockquotes) ](#6-인용문blockquotes)

#### [7. 표(Table) ](#7-표table)

#### [8. 텍스트 강조(Text) ](#8-텍스트-강조text)

#### [9. 수평선(hr) ](#9-수평선hr)

#### [10. 이모지(Emoji) ](#10-이모지emoji) 

<br/><br/>

## 1. 제목/소제목(Heading)

`#` 기호를 활용하여 작성

#의 개수에 따라 대응되는 수준(Heading level)이 있으며, h1 ~ h6까지 표현 가능

문서의 구조를 위해 작성되며, 글자 크기를 조절하기 위해 사용되어서는 안됨

ex)

```markdown
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

# h1 #

## h2 ##

### h3 ###

#### h4 ####

##### h5 #####

###### h6   ######

<br/>

<br/>

## 2. 목록(List)

#### 순서가 없는 리스트

`-, *, + `기호를 활용하여 작성

목록 활용시 단계를 tab과 shift + tab으로 조절 가능

ex)

```markdown
- 과일
  - 사과
  - 복숭아
    - 백도복숭아
    - 천도복숭아
  - 바나나
```

- 과일
	- 사과
	- 복숭아
		- 백도복숭아
		- 천도복숭아
	- 바나나    


<br/>

#### 순서가 있는 리스트

`숫자. ` 을 활용하여 작성

ex)

```markdown
**모닝루틴**
1.  물을 한 잔 마신다.
2. 세수와 양치질을 한다.
3. Syllaverse 홈페이지에 접속한다.
   1. 로그인을 한다.
   2. 대시보드를 확인한다.
4. 유튜브 라이브 또는 줌 수업에 접속한다.
   1. HRD-Net 출결체크를 한다.
   2. 인사를 남긴다.
```

**모닝루틴**

1.  물을 한 잔 마신다.
2.  세수와 양치질을 한다.
3.  Syllaverse 홈페이지에 접속한다.
	1.  로그인을 한다.
	2.  대시보드를 확인한다.

4.  유튜브 라이브 또는 줌 수업에 접속한다.
	1. HRD-Net 출결체크를 한다.
	2. 인사를 남긴다.    
	<br/><br/>
## 3. 코드 블록(Code block)

#### Fenced Code block

\`  기호를 3개 활용하여 작성(\```   \```)

기호 뒤에 특정 언어를 명시하면 Syntax highlighting 기능이 적용 가능

ex)

```python
print('Hello, World!')

if True:
    print('t')
else:
    print('f')
# python
```

```html
<h1>
    제목
</h1>
<!-- html-->
```

<br/>

####  Inline Code block

\`  기호를 1개 활용하여 작성(\`   \`)

ex)

```markdown
`print`는 파이썬에서 출력하는 함수이다.
```

`print`는 파이썬에서 출력하는 함수이다.  

<br/><br/>

## 4. 링크(Link)

 `[링크명](url)`을 통해  링크를 작성

ex)

```markdown
[실라버스 링크](https://syllaverse.com/)
```

[실라버스 링크](https://syllaverse.com/)  

<br/><br/>

## 5. 이미지(Image)

`![문자열](url)`을 통해 이미지를 작성

ex)

- **절대경로**(C: ~)    
```markdown
![racoon](C:\Users\diehd\Desktop\racoon.jpg)
```
![racoon](C:\Users\diehd\Desktop\racoon.jpg)

<br/>

- **상대경로**(~.assets)
```markdown
![racoon](github_flavored_mkd/갓생산다.jpg)
```

![racoon](github_flavored_markdown.assets/racoon.jpg)<br/><br/>

## 6. 인용문(Blockquotes)

`> `  기호를 활용하여 작성

ex)

```markdown
> 대부분은 버그 입니다.
```

> 대부분은 버그 입니다.  

<br/><br/>

## 7. 표(Table)

각 셀의 구분은 `|` 기호로 하며, 헤더 셀 아랫줄에 `|---|` 을 입력하여 표를 작성

`본문 > 표 > 표 삽입(ctrl + t)` 을 통해서도 작성 가능

`:`를 사용하면 셀 내의 텍스트를 정렬 가능(기본 왼쪽 정렬)

ex)

```markdown
| 이름 | 명언 |
| --- | --- |
| 스타니스와프J. 렉 | 심지어 그의 침묵에도 문법적인 실수가 있다. |
| 윌 듀란트 | 교육은 우리 자신의 무지를 점차 발견해나가는 과정이다. |
```

| 이름 | 명언 |
| - | - |
| 스타니스와프J. 렉 | 심지어 그의 침묵에도 문법적인 실수가 있다.            |
| 윌 듀란트 | 교육은 우리 자신의 무지를 점차 발견해나가는 과정이다. |     

<br/><br/>

## 8. 텍스트 강조(Text)

`* 또는 _`   기호를 활용하여 개수에 따라 텍스트를 강조

`~~` 기호를 활용하여 텍스트에 취소선을 추가

ex)

```
**굵게(bold)**
*기울림(italic)*
***굵고 기울림***
~~취소선~~
```

**굵게(bold)** 

*기울림(italic)*

***굵고 기울림***

~~취소선~~

<br/><br/>


## 9. 수평선(hr)

`*, _, - ` 기호를 3개 이상 사용하여 수평선을 작성

ex)

```markdown
***
___
---
```
***
___
---

<br/><br/>

## 10. 이모지(Emoji)

`Window + .` 으로 작성

ex)

# 👍❤️😍👌😒😘😊😂🤣😁🙌

# HTML 

## HTML Introduction

https://www.w3schools.com/html/html_intro.asp

> HTML : Hyper Text Markup Language

> -  웹페이지 컨텐츠 표시
> - 웹페이지 구조 표시 

## HTML Element
https://www.w3schools.com/html/html_elements.asp

- 컨텐츠를 표시하는 언어 : 태그
- 시작태그 + 콘텐츠 + 종료태그 : Element (요소)

```
문법
<tagname>Contents</tagname>

콘텐츠, 종료태그 없는 요소 : 빈요소 (Empty Element)
<br>
```

> Nested Element (중첩,포함 관계)

```
<section>
<div>
  <p>텍스트</p>
</div)>
</section>

1. p 태그 기준
- 포함하는 요소
  - div : 부모요소 (parent element)
  - section : 조상요소 (ancestor)

2. div 태그 기준
- 포함하는 요소 : section - 부모요소 
- 포함되는 요소 : p - 자식요소 (children)

3. section 태그 기준 
- 포함되는 요소
 - div : 자식요소
 - p : 자손요소 (descendant)
```
# `MarkDown Language`


마크다운(이하 md) 언어는 마크업언어의 반대 개념이다.

---

## Header Text (타이틀)
<br>
타이틀을 입력할 때는 `#`을 사용합니다.
개수에 따라서 `html`의 `<hn>`으로 동작합니다.

```
# Header Level 1
## Header Level 2
### Header Level 3
#### Header Level 4
##### Header Level 5
```

# Header Level 1
## Header Level 2
### Header Level 3
#### Header Level 4
##### Header Level 5
<br>

>`이때 '#'뒤쪽은 반드시 1칸 공백을 유지해야 한다.`



---

## Text Emphasis (텍스트 강조)
<br>

*이탤릭체*는 단어의 앞뒤로 `*`를 붙여 사용한다.<br>
**볼드체**는 단어의 앞뒤로 `**`를 붙여 사용한다.<br>
~~취소선~~은 단어의 앞뒤로 `~~`를 붙여 사용한다.<br>
<u>밑줄</u>은 `<u></u>`를 사용한다.<br><br>

>`이때  공백은 사용하지 않는다.`

---

## List (목록)
### Order List (순서있는 목록)
```
1. 순서가 있는 목록
    1. 순서가 있는 목록
    1. 순서가 있는 목록
    1. 순서가 있는 목록
1. 순서가 있는 목록
    1. 순서가 있는 목록
    1. 순서가 있는 목록
    1. 순서가 있는 목록
1. 순서가 있는 목록
    1. 순서가 있는 목록
    1. 순서가 있는 목록
          1. 순서가 있는 목록
          1. 순서가 있는 목록
```
### Unorder List (순서없는 목록)
```
- 순서가 있는 목록
    - 순서가 있는 목록
    - 순서가 있는 목록
    - 순서가 있는 목록
- 순서가 있는 목록
    - 순서가 있는 목록
    - 순서가 있는 목록
    - 순서가 있는 목록
- 순서가 있는 목록
    - 순서가 있는 목록
    - 순서가 있는 목록
          - 순서가 있는 목록
          - 순서가 있는 목록
```

---

## Hyper Link (하이퍼링크)
```
[google](https://www.google.com)   
[naver](https://www.naver.com)   
[daum](https://www.daum.net)   
[Header Text (타이틀)](#Header-Text-(타이틀))   
[Text Emphasis (텍스트 강조)](#Text-Emphasis-(텍스트-강조))   
[List (목록)](#List-(목록))
```
[google](https://www.google.com)   
[naver](https://www.naver.com)   
[daum](https://www.daum.net)   
[Header Text (타이틀)](#Header-Text-(타이틀))   
[Text Emphasis (텍스트 강조)](#Text-Emphasis-(텍스트-강조))   
[List (목록)](#List-(목록))

>`하이퍼링크`는 외부파일로 링크 할 수 있고, 문서 내에서의 링크도 가능하다.
이때 문서 내부에서의 링크는 `#타이틀`로 링크 할 수 있으며, `타이틀`명의 공백은 `-`으로 구분한다.

---

## Insert Image (이미지 삽입)
```
![HTML](./img/skills_html.png)   
![CSS](./img/skills_css.png)   
![javaScript](./img/skills_js.png)   
![PhotoShop](./img/skills_ps.png)   
```
![HTML](./img/skills_html.png)
![CSS](./img/skills_css.png)
![javaScript](./img/skills_js.png)
![PhotoShop](./img/skills_ps.png) 

---

---

layout: post
title:  "Markdown 문법"
subtitle: "Markdown 사용법과 간단한 예제 정리"
categories: [study]
date:   2021-10-27
last_modified_at: 2021-10-27
published: true

---

### 목차
1. [HEADER](#header)
2. [LIST](#list)
3. [FONT](#font)
4. [BLOCK QUOTE](#block-quote)
5. [LINK](#link)
6. [IMAGE](#image)
7. [TABLE](#table)
8. [CODE BLOCK](#code-block)

---

### HEADER
```
# #1
## #2
### #3
#### #4
##### #5
###### #6
```
# #1
## #2
### #3
#### #4
##### #5
###### #6
```
header1
======
header2
------
```
header1<br>
======<br>
header2<br>
------<br>

---

### LIST
```
1. 100
2. 101
3. 102
+ 1
    - 2
        * 3
            + 4
```
1. 100
2. 101
3. 102
+ 1
    - 2
        * 3
            + 4

해당 기호를 그대로 작성하고 싶을 때는 기호 앞에 `\` 추가하여 작성 → `\+ \- \*`

```
- [ ] : false
- [x] : true
```
- [ ] : false
- [x] : true

---

### FONT
```
__bold__
_italic_
~~line~~
<u>underline</u>
__bold *italic* bold__
`hightlight`
공백&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;공백
<!-- 주석 -->

```
__bold__<br>
_italic_<br>
~~line~~<br>
<u>underline</u><br>
__bold *italic* bold__<br>
`hightlight`<br>
공백&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;공백<br><br>

📘📒📚👀✨<br>
window10 `윈도우 키` + `.`<br>
mac `command` + `control` + `space bar`


---

### BLOCK QUOTE
```
> text 1
>> text 2
>>> text 3
```
> text 1
>> text 2
>>> text 3

---

### LINK
```
1. <http://www.google.com>
2. [google](http://www.google.com)
3. [문단 이동](#목차)
```
1. <http://www.google.com>
2. [google](http://www.google.com)
3. [문단 이동](#목차)
    1. 이동할 제목(header)을 복사/붙여넣기
    2. 특수문자 제거
    3. 스페이스 → 하이픈 `-` 으로 변경
    4. 대문자 → 소문자로 변경
    __(# Move! 이동!) → (#move-이동)__

---

### IMAGE
```
1. 원본이미지
![image](https://www.google.co.kr/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png "google logo image")
2. 원본+링크
[![image](https://www.google.co.kr/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png)](http://www.google.com)
3. 사이즈
<img src="https://www.google.co.kr/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png" width="100" height="40">
```
1. 원본이미지
![image](https://www.google.co.kr/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png "google logo image")
2. 원본+링크
[![image](https://www.google.co.kr/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png)](http://www.google.com)
3. 사이즈
<img src="https://www.google.co.kr/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png" width="100" height="40">

---

### TABLE
```
|       | colum1 | colum2 | colum3  |  
|:----- | ------:| -----: | :-----: |  
| data1 | 1      | 100    | ABCDEFG |  
| data2 | 2      | 200    | abc     |
```
|       | colum1 | colum2 | colum3  |  
|------ | :------| -----: | :-----: |  
| data1 | 1      | 100    | ABCDEFG |  
| data2 | 2      | 200    | abc     |

왼쪽정렬 `:---`<br>
오른쪽정렬 `---:`<br>
양쪽정렬 `:---:`<br>

---

### CODE BLOCK
    ```java
    private String name;
    ```

    ```html
    <div>
        <p>hello</p>
        </div>
    ```


```java
private String name;
```

```html
<div>
    <p>hello</p>
</div>
```
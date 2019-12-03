---
title: "Penetration Test Report"
author: ["student@youremailaddress.com", "OSID: XXXX"]
date: "2017-02-20"
subject: "Markdown"
keywords: [Markdown, Example]
subtitle: "PWK Lab & OSCP Exam"
lang: "en"
titlepage: true
titlepage-color: "DC143C"
titlepage-text-color: "FFFFFF"
titlepage-rule-color: "FFFFFF"
titlepage-rule-height: 2
book: true
classoption: oneside
code-block-font-size: \scriptsize
---


* Typora Only Feature for title
<div style="text-align:center;font-size:2em;">Typora學習記錄</div>
<div style="text-align:center;font-size:1.4em;">練習是必要的</div><br />
<div style="text-align:center;font-size:1.2em;">Richard Luo (richard_luo@phison.com)</div>
<div style="text-align:center;font-size:1.2em;">2019/11/30</div><br /><br />


# Typora 學習記錄



## A. 環境設定



## B. 寫作技巧



### titlepage

```html
<h1 style="text-align:center">12345</h1>
<div style="text-align:center;font-size:2em;">Vinaque sanguine metuenti</div>
<div style="text-align:center;font-size:1.4em;">12345</div><br />
<div style="text-align:center;font-size:1.2em;">Richard Luo (richard_luo@phison.com)</div>
<div style="text-align:center;font-size:1.2em;">2019/11/30</div><br /><br /><br />
```



### 文字格式

範例：   **粗體**  *斜體*    <u>底線</u>   ~~刪除線~~  ==高亮==

```markdown
**粗體**     *斜體*    <u>底線</u>  ~~刪除線~~  ==高亮==
```





### 超連結

範例： [Latex](https://www.latex-project.org/)

```markdown
 [Latex](https://www.latex-project.org/)
```



### 待辦項目

範例： 

* [ ] 

```markdown
- [ ] 
```

<div style="page-break-after: always;"></div> 
### 表格



| A         | B    |      |
| --------- | ---- | ---- |
| This is a |      |      |





### 圖片

範例：

<img src="icon.png" align="right" height="60"/>

```markdown
<img src="icon.png" align="right" height="110"/>
```



### 分頁



```markdown
<div style="page-break-after: always;"></div>
```

<div style="page-break-after: always;"></div> 
### 參考連結
[連接到標題表格](#表格)



### html技巧

* 黃底backdround
<span style="font-size:2rem; background:yellow;">**Bigger**</span>
* 紅色文字
<span style='color:red'>This is red</span>
* 加入注音 / 日文讀音
<ruby> 漢 <rt> ㄏㄢˋ </rt> </ruby>
<ruby> 車子 <rt> くるま </rt> </ruby>
* 鍵盤文字
<kbd>Ctrl</kbd>+<kbd>F9</kbd>
* 匯出隱藏
<span style="display:none">I am hidden after export</span>

* html comment

  <!-- I am some comments not end,not end... here the comment endscdsdscscdcdsfdfdsdsfsds -->



This is [an example][id] reference-style link.

Then, anywhere in the document, you define your link label on a line by itself like this:

[id]: http://example.com/  "Optional Title Here"



### 數學工具 / Latex 語法

* Typora Only Feature for Latex
$Latex$

$$
-\frac{1}{m}=\frac{\sum_{i=1}^n{X_iY_i}-\frac{1}{n}\sum_{i=1}^n{X_i\sum_{i=1}^n{Y_i}}}{\sum_{i=1}^n{X_{i}^{2}-\frac{1}{n}\left(\sum_{i=1}^n{X_i}\right)^2}}\\
 
 \frac{1}{m}\lg C=\frac{1}{n}\left(\sum_{i=1}^n{Y_i+\frac{1}{m}\sum_{i=1}^n{X_i}}\right)\\
$$


[math]: 連結到這裡



### Table of Content

範例：
* Typora Only Feature for TOC
[TOC]

```markdown
[TOC]
```



<div style="page-break-after: always;"></div> 

### 流程圖
* Typora Only Feature for flow chart
```flow
// define state
st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes or No?:>http://www.google.com
io=>inputoutput: catch something...

// flow
st->op1->cond
cond(yes)->io->e
cond(no)->sub1(right)->op1
```



### Sequence Diagram


* Typora Only Feature for Sequence
```
'''sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
'''
```


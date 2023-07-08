
# Welcome to Arthur Pages
HI 測試並紀錄markdown的基本功能

###### tags: `note`

> This note is yours, feel free to play around.  :video_game: 
> Type on the left :arrow_left: and see the rendered result on the right. :arrow_right: 

產生目錄
===
- Auto-generated Table of Content
[ToC]
---

完整教學網站
===
[點這邊](https://hackmd.io/features-tw?both)

## 字體變色教學
[挑顏色的網站](https://htmlcolorcodes.com/color-picker/)

兩種方法
- 使用 HTML 的 font 元素
 
```
H<font color="#f00">e</font>llo, World
```
H<font color="#f00">e</font>llo, World

- 使用 css 的 class 功能
```
<style>
.blue {
  color: blue;
}
</style>

Hello, <span class="blue">World</span>
```
<style>
.blue {
  color: blue;
}
</style>

Hello, <span class="blue">World</span>

自製的測試
<style>
.aya_green {
  color: #33FFAD;
}
</style>

Hello, <span class="aya_green">World</span>

## :memo: Where do I start?

### Step 0: aya note
空行的方法
&nbsp;
下一行

一次空兩行的方法
<br />
下一行

&emsp;前面空4小格

    &emsp;
&ensp;前面空2小格
    
    &ensp;
&nbsp;前面空1小格

    &nbsp;
&thinsp;插入一個細空格

    &thinsp;
python code範例
```python=
a=1
b=2
```
打出灰色區域
```
asd
```

或是這打完要打的標題後，往下跳一行再給他一個tab

    123
    
- 小標題內的話這邊就不能用單純空行跟tab的方法了
123
```
456
```


emoji sheet
https://github.com/ikatyang/emoji-cheat-sheet
打:再輸入代碼
:+1: 
或是去這邊直接複製emoji圖片
https://www.emojiall.com/zh-hant


打特殊符號
![](https://img-blog.csdnimg.cn/20181219093911247.png)

### Step 1: Change the title and add a tag

- [x] Create my first HackMD note (this one!)
- [ ] Change its title
- [ ] Add a tag

:rocket: 

### Step 2: Write something in Markdown

Let's try it out!
Apply different styling to this paragraph:
**HackMD gets everyone on the same page with Markdown.** ==Real-time collaborate on any documentation in markdown.== Capture fleeting ideas and formalize tribal knowledge.

- [x] **Bold**
- [ ] *Italic*
- [ ] Super^script^
- [ ] Sub~script~
- [ ] ~~Crossed~~
- [x] ==Highlight==

:::info
:bulb: **Hint:** You can also apply styling from the toolbar at the top :arrow_upper_left: of the editing area.

![](https://i.imgur.com/Cnle9f9.png)
:::

> Drag-n-drop image from your file system to the editor to paste it!

### Step 3: Invite your team to collaborate!

Click on the <i class="fa fa-share-alt"></i> **Sharing** menu :arrow_upper_right: and invite your team to collaborate on this note!

![permalink setting demo](https://i.imgur.com/PjUhQBB.gif)

- [ ] Register and sign-in to HackMD (to use advanced features :tada: ) 
- [ ] Set Permalink for this note
- [ ] Copy and share the link with your team

:::info
:pushpin: Want to learn more? ➜ [HackMD Tutorials](https://hackmd.io/c/tutorials) 
:::

---

## BONUS: More cool ways to HackMD!

- Table

| Features          | Tutorials               |
| ----------------- |:----------------------- |
| GitHub Sync       | [:link:][GitHub-Sync]   |
| Browser Extension | [:link:][HackMD-it]     |
| Book Mode         | [:link:][Book-mode]     |
| Slide Mode        | [:link:][Slide-mode]    | 
| Share & Publish   | [:link:][Share-Publish] |

[GitHub-Sync]: https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github
[HackMD-it]: https://hackmd.io/c/tutorials/%2Fs%2Fhackmd-it
[Book-mode]: https://hackmd.io/c/tutorials/%2Fs%2Fhow-to-create-book
[Slide-mode]: https://hackmd.io/c/tutorials/%2Fs%2Fhow-to-create-slide-deck
[Share-Publish]: https://hackmd.io/c/tutorials/%2Fs%2Fhow-to-publish-note

- LaTeX for formulas

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

- Code block with color and line numbers：
```javascript=16
var s = "JavaScript syntax highlighting";
alert(s);
```

- UML diagrams
```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
Note left of Alice: Alice responds
Alice->Bob: Where have you been?
```


> Leave in-line comments! [color=#3b75c6]

- Embed YouTube Videos

{%youtube PJuNmlE74BQ %}

> Put your cursor right behind an empty bracket {} :arrow_left: and see all your choices.

- And MORE ➜ [HackMD Tutorials](https://hackmd.io/c/tutorials)

大標題的間隔線
===
標題的字會變超大

其他方便功能
===
## 代辦清單

- [ ] 待辦
  - [ ] 辦護照
  - [ ] 刷牙
  - [x] 喝水
  - [x] 摸水獺


## UML 圖表
### 循序圖

您可以像是以下使用循序圖：

```sequence
行程A->成田機場: 剛下飛機
Note right of 成田機場: 從要搭哪個車子
成田機場-->上野: 搭京成SKYLINER
Note left of 行程A: 或是搭到別的地方
成田機場->上野: 成田Express
```

### 項目間的區隔用```

### 流程圖

您可以像是以下使用流程圖：
```flow
st=>start: 成田機場
e=>end: 結束
op=>operation: 搭京成SKYLINER
op2=>operation: 成田Express
op3=>operation: 到上野
cond=>condition: 是或否？

st->op->op3->cond
cond(yes)->e
cond(no)->op2
```
這兩個圖不太好用

警告區塊
---
:::success
耶 :tada:
:::

:::info
這是訊息 :mega:
:::

:::warning
注意 :zap:
:::

:::danger
喔不 :fire:
:::

摺疊區塊
---
:::spoiler 點選顯示更多內容
找到我了！ :stuck_out_tongue_winking_eye:
:::

:::spoiler {state="open"} 預設展開摺疊內容
不點開就能看到我:stuck_out_tongue_winking_eye:
:::


### 清單

#### 項目

+ 在行開頭使用 `+` `-` 或是 `*` 來建立清單
+ 空兩個空白就可以產生子清單
  - 當清單標記使用的字元不同，會強制建立新的清單
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ 非常簡單！

#### 編號

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
1. 您可以逐次增加項目數字...

---

1. ...或是全部都使用 `1.`
1. feafw
2. 332
3. 242
4. 2552
1. e2

從其他範圍開始編號清單

57. foo
1. bar
## 建立表格
<table border="1">
　<tr>
　<td>這裡是第一行的第一個欄位</td>
　<td>這裡是第一行的第二個欄位</td>
　</tr>
　<tr>
　<td>這裡是第二行的第一個欄位</td>
　<td>這裡是第二行的第二個欄位</td>
　</tr>
</table>
## 打一段廢話
<p>
    雖然現在下著雨，不代表要去的地方沒有陽光。<br>
    The path is not the destination. Even if it rains now, doesn’t mean it isn’t sunny up ahead. <br>
    <small align="right">- 風起 (Kaze tachinu)</small>
</p>

## 圖片公式
`![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)`

## 試試看放圖片
![Cute_Dog](https://images.unsplash.com/photo-1517840815742-3b666760d5e0?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=ad7d6f0472ed62a0e27e2aa2435a724a&auto=format&fit=crop&w=1350&q=80)
## 點擊式的超連結
[點我看小狗狗原圖](https://images.unsplash.com/photo-1517840815742-3b666760d5e0?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=ad7d6f0472ed62a0e27e2aa2435a724a&auto=format&fit=crop&w=1350&q=80)
## 字串中參雜超連結
有一隻[柴犬](https://i2.kknews.cc/SIG=397126f/18nq000206nqr7op68pp.jpg) 胖胖的
## 條列項目
+ A
+ B
- C
* D
1. HI
2. YA
## 水平線
***************
____________
-----
## 粗體、斜體、刪除線
**粗粗的**
*斜斜的*
~~要被刪掉的字串~~
## 置入影片
[![AM](http://img.youtube.com/vi/EEMwA8KZAqg/0.jpg)](http://www.youtube.com/watch?v=EEMwA8KZAqg)

## 置入影片2 新分頁開啟影片的狀態
[![IMAGE ALT TEXT](http://img.youtube.com/vi/ARwVe1MYAUA/0.jpg)](https://www.youtube.com/embed/ARwVe1MYAUA "CameraMaster")

## 置入影片3 超連結至youtube
[![](http://img.youtube.com/vi/ARwVe1MYAUA/0.jpg)](http://www.youtube.com/watch?v=ARwVe1MYAUA "")

## 區塊程式碼測試
```
for (let i =0; i<10; i++){
    setTimeout(function(){
        console.log('執行次數第'+i+'次');
    },0);
    } 
```



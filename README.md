
## Welcome to Aya Pages
HI 這是阿亞的測試網頁
首先是建立表格
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

  <p>
    雖然現在下著雨，不代表要去的地方沒有陽光。<br>
    The path is not the destination. Even if it rains now, doesn’t mean it isn’t sunny up ahead. <br>
    <small align="right">- 風起 (Kaze tachinu)</small>
  </p>

圖片公式
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

試試看放圖片
![Cute_Dog](https://images.unsplash.com/photo-1517840815742-3b666760d5e0?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=ad7d6f0472ed62a0e27e2aa2435a724a&auto=format&fit=crop&w=1350&q=80)

# 試試看小栗子
<!doctype html>
<html>
<head>
  <meta charset="utf-8"/>
  <title>Example</title>
  <script src="https://cdn.bootcss.com/marked/0.3.6/marked.min.js"></script>
</head>
<body>
  <div id="content"></div>
  <script>
$.ajax({
　　url: "https://api.github.com/repos/tinyallen/blog/issues/1",
　　type: "GET",
　　dataType:'json',
　　success:function(data){
　　   document.getElementById('content').innerHTML =
      marked(data.body);
   },
　　error:function(err){
　　   console.log(err);
   }
});
  </script> 
</body>
</html>

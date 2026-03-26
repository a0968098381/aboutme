<!DOCTYPE html>
<html lang="zh-TW">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>蔡淳彥個人首頁</title>

 <style type="text/css">
  * { font-family:"標楷體"; margin-left:auto; margin-right:auto;}
  h1 {color:blue; font-size:60px;}
  h2 {color:#33ff33; font-size:40px;}
 </style>

 <script>
  function change1() {
     document.getElementById("pic").src = "/1.jpg";
     document.getElementById("h2text").innerText = "靜宜資管";
  }

  function change2() {
     document.getElementById("pic").src = "/2.jpg";
     document.getElementById("h2text").innerText = "Chun Yen Tsai";
  }
 </script>
</head>
<body>
 <img src="/1.jpg" width="70%" id="pic" onmouseover="change1()" onmouseout="change2()"></img>
 <h1>蔡淳彥</h1>
 <h2 id="h2text">Chun Yen Tsai</h2>

 <table width="70%" border="1">
  <tr>
   <td>
    phone-num: <a href="0968-098-381">0968-098-381</a><br>

    ig:habit_943<br>

    E-Mail: <a href="https://mail.google.com/mail/u/0/#inbox">b0966031908@gmail.com</a><br>
   </td>

   <td>
    大象席地而坐電影配樂<br>
    <audio controls>
     <source src="/static/elephant.mp3" type="audio/mP3">
    </audio><br>
   </td>

   <td>
    不要去臺灣<br>
    <iframe src="https://www.youtube.com/embed/pW88QFpHXa8" allowfullscreen></iframe>
   </td>
  </tr>
 </table>
</body>
</html>

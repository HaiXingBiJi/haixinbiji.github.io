<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
</head>
<body>
<h1 class="a" id="a"><strong>  <img src="http://chuantu.xyz/t6/703/1572872622x1031866013.png" width="96" height="100" /> 海星笔记用户反馈系统
</strong></h1>
<form
  action="https://formspree.io/xoqqkaoz"
  method="POST"
>
  <label>
    Your email:
    <input type="text" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <button type="submit">Send</button>
</form>
<script type="text/javascript">
  function getNowFormatDate() {
    var date = new Date();
    var seperator1 = "-";
    var seperator2 = ":";
    var month = date.getMonth() + 1;
    var strDate = date.getDate();
    if (month >= 1 && month <= 9) {
      month = "0" + month;
    }
    if (strDate >= 0 && strDate <= 9) {
      strDate = "0" + strDate;
    }
    var currentdate = date.getFullYear() + seperator1 + month + seperator1 + strDate
            + " " + date.getHours() + seperator2 + date.getMinutes()
            + seperator2 + date.getSeconds();

   alert(currentdate);
  }
</script>
<a href="javascript:void(0)" onclick="getNowFormatDate()">Time</a>
</body>
</html>

<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材２ー５
</title>

<script type="text/javascript">

function kieru(){
	var span = document.getElementById("target");
	span.style.display = "none";
}

function mieru(){
	var span = document.getElementById("target");
	span.style.display = "";
}

</script>
</head>
<body>
【ボタンをクリックしたら見えたり消えたりします】<br>
<input type="button" value="クリックしたら消えます" onclick="kieru()">
<input type="button" value="クリックしたら見えます" onclick="mieru()"><br>
<br>
<span id="target">ここが見えたり消えたりします</span><br>
<br><br>
<span id="mihon" style="display:none">
スタイルの見本です。<br>
ここは見えません。
</span>
</body>
</html>






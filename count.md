<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材３
</title>

<script type="text/javascript">

function check(){

	var tb = document.getElementById("txtbox");
	var moji = tb.value;
	var mojisu = moji.length;
	
	var span = document.getElementById("mojisu_span");
	span.innerHTML = mojisu;
	
	if(mojisu > 6){
		// var div = document.getElementById("mojisu_div");
		// div.style.color="#ff0000";
		change("#ff0000")
	}else if(mojisu === 3){
		// var div = document.getElementById("mojisu_div");
		// div.style.color="#0000ff";
		change("#0000ff")
	}else{
		// var div = document.getElementById("mojisu_div");
		// div.style.color="#000000";
		change("#000000")
	}
}

function change(c){
	var div = document.getElementById("mojisu_div");
	div.style.color=c;
}

</script>
</head>
<body>
【文字数オーバーを検知します】<br>
<input type="text" onkeyup="check()" id="txtbox">
<br>
<div id="mojisu_div">
文字数：<span id="mojisu_span">0</span>/6
</div>
</body>
</html>






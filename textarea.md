<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材４ー６
</title>

<script type="text/javascript">

function check(tb){

	var moji = tb.value;
	var mojisu = moji.length;
	
	var span = document.getElementById("mojisu_span");
	span.innerHTML = mojisu;
	
	if(mojisu > 6){
		var div = document.getElementById("mojisu_div");
		div.style.color="#ff0000";
	}else{
		var div = document.getElementById("mojisu_div");
		div.style.color="#000000";
	}
}

</script>
</head>
<body>
【テキストエリア】<br>
<textarea onkeyup="check(this)" 
style="width:300px;height:100px;font-size:30px;"></textarea><br>
<div id="mojisu_div">
文字数：<span id="mojisu_span">0</span>/6
</div>
</body>
</html>






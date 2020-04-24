<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材５
</title>

<script type="text/javascript">

function haikei(){

	var divs = document.getElementsByTagName("div");
	var div = divs[0];
	div.style.backgroundColor = "#ffeeee";

	div = divs[2];
	div.style.backgroundColor = "#ffeeee";

}

function haikeiIkki(){
	var divs = document.getElementsByTagName("div");
	
	var i;
	for(i = 0 ; i < divs.length ; i++){
		var div = divs[i];
		div.style.backgroundColor = "#ffeeee";
	}
}

</script>
</head>
<body>
【配列と繰り返し処理】<br>
<div>a</div>
<div>b</div>
<div>c</div>
<div>d</div>
<div>e</div>
<div>f</div>
<div>g</div>
<input type="button" value="背景色をつける" onclick="haikei()">
</body>
</html>



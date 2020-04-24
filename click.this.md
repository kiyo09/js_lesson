<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材６ー２
</title>

<script type="text/javascript">

function haikei(target){

	var divs = document.getElementsByTagName("div");
	
	var i;
	for(i = 0 ; i < divs.length ; i++){
		var div = divs[i];
		div.style.backgroundColor = "#ffffff";
	}
	
	target.style.backgroundColor = "#ffeeee";

}

</script>
</head>
<body>
【クリックされた行にだけ色をつけます】<br>
<div onclick="haikei(this)">a</div>
<div onclick="haikei(this)">b</div>
<div onclick="haikei(this)">c</div>
<div onclick="haikei(this)">d</div>
<div onclick="haikei(this)">e</div>
<div onclick="haikei(this)">f</div>
<div onclick="haikei(this)">g</div>
</body>
</html>



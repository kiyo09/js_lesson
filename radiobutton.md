<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材４ー３
</title>

<script type="text/javascript">

function iroKaeru(){

	var aka = document.getElementById("aka");
	var midori = document.getElementById("midori");
	var ao = document.getElementById("ao");
	var c;
	if(aka.checked){
		c = "#ff0000";
	}else if(midori.checked){
		c = "#00ff00";
	}else if(ao.checked){
		c = "#0000ff";
	}
	
	var moji = document.getElementById("moji");
	moji.style.color = c;
}

</script>
</head>
<body>
【ラジオボタン】<br>
<input type="radio" name="c" onclick="iroKaeru()" id="aka" checked>赤<br>
<input type="radio" name="c" onclick="iroKaeru()" id="midori">緑<br>
<input type="radio" name="c" onclick="iroKaeru()" id="ao">青<br>
<span id="moji" style="color:#ff0000">ここの文字の色が変わります。</span><br>
</body>
</html>






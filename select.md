<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材４ー５
</title>

<script type="text/javascript">

function iroKaeru(){

	var aka = document.getElementById("aka");
	var midori = document.getElementById("midori");
	var ao = document.getElementById("ao");
	var c;
	if(aka.selected){
		c = "#ff0000";
	}else if(midori.selected){
		c = "#00ff00";
	}else if(ao.selected){
		c = "#0000ff";
	}else{
		c = "#000000";
	}
	
	var moji = document.getElementById("moji");
	moji.style.color = c;
}

</script>
</head>
<body>
【セレクトボックス】<br>
<select onchange="iroKaeru()">
<option id="aka">赤</option>
<option id="midori">緑</option>
<option id="ao">青</option>
</select><br>
<span id="moji" style="color:#ff0000">ここの文字の色が変わります。</span><br>
</body>
</html>






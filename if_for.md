<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材６ー３
</title>

<script type="text/javascript">

function hantei(){

	var inputs = document.getElementsByTagName("input");
	
	var i;
	for(i = 0 ; i < inputs.length ; i++){
		var input = inputs[i];
		if(input.type==="text"){
			
			input.style.backgroundColor = "#ffeeee";
			
			/*
			if(input.value !== ""){
				input.style.color = "#ff0000";
			}else{
				input.type="button";
				input.value="ボタンになりました";
			}
			*/
		}
	}
}

</script>
</head>
<body>
【forとif】<br>
<input type="text" value="a"><br>
<input type="text" value=""><br>
<input type="text" value="c"><br>
<input type="text" value="d"><br>
<input type="text"><br>
<input type="text" value="f"><br>
<input type="text"><br>
<input type="button" value="forとif" onclick="hantei()">
</body>
</html>



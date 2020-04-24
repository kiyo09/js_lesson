<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>
教材４ー１
</title>

<script type="text/javascript">

document.onkeydown = function(e){
//	alert(e.keyCode);
	var cc;
	switch(e.keyCode){
		case 90:
				cc = "#ff0000";
				break;
		case 88:
				cc = "#00ff00";
				break;
		case 67:
				cc = "#000000";
				break;
		default:
				cc = "#000000";
				break;
	}


	// var cc;
  //   if(e.keyCode===90){//z
	// 	cc = "#ff0000";
  //   }else if(e.keyCode===88){//x
	// 	cc = "#00ff00";
	// 	}else if(e.keyCode===67){//c
	// 		cc = "#0000ff";
	// 	}else{
	// 		cc = "#000000";
	// 	}

	
	var msg = document.getElementById("msg");
	msg.style.color = cc;

}

</script>
</head>
<body>
<span id="msg" style="font-size:30px;">【キー入力を受け取り、色を変えます。】</span>
</body>
</html>


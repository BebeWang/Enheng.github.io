# Enheng.github.io
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
	<meta charset="UTF-8">
	<title>铺满整屏</title>
	<style type="text/css">
		html,body {
			height: 100%;
			
    		margin: 0;
   			 padding: 0;
			}
#border{
	width: 100%;
	height: 100%;
}
#wrap{	width: 100%;
		height: 100%;
		float: 100%;
	}
	#left {
		margin-left: 200px;
	
	   
	 	height:100%;
	    background-color: green;
}

	  	
	 	

	#right {
		width: 200px;
		height:100%;
	    background-color: orange;
	    float: left;
	    margin-left: 100%;
}

	</style>
</head>
<body>
	<div id="border">
		<div id="wrap">
			<div id="right"></div>
		</div>
		<div id="left"></div>
	</div>
</body>
</html>

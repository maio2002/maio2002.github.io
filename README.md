<!DOCTYPE html>
<html>
<head>
<title>HTML5 Canvas Tag</title>
</head>

<body>
<canvas id = "newCanvas" width = "500" height = "300" style = "border:1px solid #000000;"></canvas>
<script>
var c = document.getElementById('newCanvas');
var ctx = c.getContext('2d');
ctx.beginPath();
ctx.moveTo(75,40);
ctx.bezierCurveTo(75,37,70,25,50,25);
ctx.bezierCurveTo(20,25,20,62.5,20,62.5);
ctx.bezierCurveTo(20,80,40,102,75,120);
ctx.bezierCurveTo(110,102,130,80,130,62.5);
ctx.bezierCurveTo(130,62.5,130,25,100,25);
ctx.bezierCurveTo(85,25,75,37,75,40);
ctx.fill();
</script>

</body>
</html>

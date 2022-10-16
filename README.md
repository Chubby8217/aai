<!doctype html>
<html>
<head>
<style>
body{
	background-color: #dfdfdf;
}
.box {
	display: block;
	width: 800px;
	height: 600px;
	padding: 30px 50px;
	background-color: white;
	box-shadow: 0 2px 6px rgba(0, 0, 0, .1);
	border: 1px solid rgba(0, 0, 0, .3);
	border-radius: 20px;
	text-shadow: 0 2px 2px rgba(0, 0, 0, .1);
	font-family: Arial, sans-serif;
	font-size: 40px;
	color: rgb(102, 102, 102);
}
</style>
</head>
<body>

<div id="impress">

<div class="step box" data-x="0" data-y="0">
<p>This is my first slide!!</p>
</div>

<div class="step box" data-x="0" data-y="1000">
<p>This is my second slide!!</p>
</div>

<div class="step box" data-x="2000" data-y="1000">
<p>This is my third slide!!</p>
</div>

</div>

<script src="js/impress.js"></script>
<script>
impress().init();
</script>
</body>

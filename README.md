<html>
<head>
<style type="text/css">
body {
    display: flex;
    flex-direction: column;
    height: 100vh;
    margin: 0;
}

.header {
    height: 10%;
    background: #ccc;
}
.menu {
    height: 5%;
    background: #ccc;
}

.main-content {
    height: 80%;
    display: flex;
}

.left {
    width: 10%;
    background: #eee;
}

.right {
    width: 90%;
    background: #fff;
}

.footer {
    height: 5%;
    background: #ddd;
}
</style>
</head>
<body>
    <iframe class="header" src="header.html"></iframe>
    <iframe class="menu" src="menu.html"></iframe>
    <div class="main-content">
		<iframe class="left" src="left.html"></iframe>
		<iframe class="right" name="main-frame" src="right.html"></iframe>
	</div>
    <iframe class="footer" src="footer.html"></iframe>
</body>
</html>


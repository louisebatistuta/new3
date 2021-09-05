ody
{
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #222;
}
a {
	text-decoration: none;
	color: white;
	font-family: sans-serif;
	font-size: 40px;
	border: 3px solid white;
	padding: 40px 80px;
	position: relative;
	transition: all 1s;
	overflow: hidden;
}

a:before {
	content: '✔️ Dia 16';
	color: rgb(0, 90, 0);
	background-color: #c1f1c8f6;
	display: flex;
	align-items: center;
	justify-content: center;
	position: absolute;
	left: 0;
	top: 0;
	height: 100%;
	width: 100%;
	transform: translateY(-100%);
	transition:all .5s;
}

a:hover:before {
	transform: translateY(0);
}

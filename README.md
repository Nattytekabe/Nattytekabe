- 👋 Hi, I’m @Nattytekabe
- 👀 I’m interested in Designing and Development
- 🌱 I’m currently learning Computer Sceince
- 💞️ I’m looking to collaborate on Web and Android App Development
- 📫 Reach me out from my  <a href = "http://nattytekabe.42web.io/">website  </a>
<!---
Nattytekabe/Nattytekabe is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<style>
  body{
	margin: 0;
	background-color: #4C9BA6;
	font-family: sans-serif;
}
main{
	display: flex;
	width: 100%;
}
.flex-container {
    display: flex;
    margin: 30vh auto;
    width: 600px;
	border-radius: 20px;
	box-shadow: 0px 6px 16px 10px black;
}
aside{
	flex: 1;
	background-color: #41848F;
	display: flex;
	flex-direction: column;
	border-radius: 18px 0px 0px 18px;
	border-right: 7px solid white;
}
aside div{
	flex: 1;
    display: flex;
    padding: 10px;
}
aside div a{
	text-decoration: none;
	margin: auto auto;
	font-size: 45px;
	color: white;
}
aside div a:hover{
	cursor: pointer;
	color: black;
}
section{
	flex:4;
	background-color: white;
	height: 80%;
	margin: auto;
	border-top: 5px solid gray;
	border-bottom: 5px solid gray;
}
section div {
    height: 45px;
    padding-bottom: 15px;
    display: flex;
}
section div p{
    text-align: center;
    font-size: 25px;
    margin: auto auto;
    color: #324D5C;
	font-weight: 400;
}
.name{
	font-weight: 700;
	font-style: italic;
	font-size: 30px;
	border-bottom: 3px solid green;
	padding: 5px 70px 5px 70px;
	color: black;
}

@media screen and (max-width: 700px){
	.flex-container{
		width: 90%;
		margin: 0 auto;
		height: 500px;
	}
	main{
		flex-direction: column;
	}
	aside{
		flex-direction: row;
		border-radius: 0px;
		border-right: none;
		border-bottom: 15px solid white;
	}
	section{
		border-bottom: 3px solid gray;
		border-top: 3px solid black;
	}
	section div p{
		font-size: 25px;
		color: #324D5C;
	}
	.name{
		border-bottom: 16px solid #41848F;
		font-size:20px;
	}
}
  </style>
<body>
		<div class="flex-container">
			<main>
				<aside>
					<div>
						<a href="#"><i class="fa fa-github icons"></i></a>
					</div>
					<div>
						<a href="#"><i class="fa fa-google icons"></i></a>
					</div>
					<div>
						<a href="#"><i class="fa fa-linkedin icons"></i></a>
					</div>
					<div>
						<a href="http://instagram.com/natty_rock_"><i class="fa fa-instagram icons"></i></a>
					</div>
				</aside>
				<section>
					<div><p class="name">Nathnael Tekabe</p></div>
					<div><p>nathnaeltekabe@gmail.com</p></div>
					<div><p>nattytekabe.42web.io</p></div>
					<div><p>Ethiopia, Addis Abeba</p></div>
				</section>
			</main>
		</div>
	</body>
</html>

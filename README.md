# WEB_Portfolio
# front_page.html
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport"
		content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="resume.css">
</head>
<body>
	<div class="full">
		<div class="left">
			<div class="image">
				<img src="C:/Users/manoj/Downloads/WhatsApp Image 2023-09-04 at 3.52.15 PM.jpeg"
					alt="resume-image1"
					style="width:100px;height:100px;">
			</div>
			<div class="Contact">
				<h2>Contact</h2>
				<p><b>Email id:</b>vishwassakri123@gmail.com</p>
				<p><b>Mobile no :</b>9513429153</p>
			</div>
			<div class="Skills">
				<h2>Skills</h2>
				<ul>
					<li><b>Programming Languages :
					Python</b></li>
					<li><b>Frontend : HTML5, CSS3,
					JavaScript,</b></li>
					<li><b>Framework: Django</b></li>
                    <li><b>MySQL professional </b></li>
				</ul>
			</div>
			<div class="Language">
				<h2>Language</h2>
				<ul>
					<li>English</li>
					<li>Kannada</li>
				</ul>
			</div>
			<div class="Hobbies">
				<h2>Hobbies</h2>
				<ul>
					<li>Badminton</li>
					<li>kabaddi</li>
                    <li>Swimming</li>
				</ul>
			</div>
		</div>
		<div class="right">
			<div class="name">
				<h1>Vishwas Sakri</h1>
			</div>
			<div class="title">
				<p>Web Developer</p>
			</div>
			<div class="Summary">
				<h2>Summary</h2>
				<p>To secure a challenging position in a
				reputable organization
					to expand my learning knowledge and skill
				</p>
			</div>
			<!-- <div class="Experience">
				<h2>Experience</h2>
				<h3>Abc webdev pvt ltd - Senior Web Developer</h3>
				<p>January 2022 to Present</p>
				<ul>
					<li>Actively engaged in web creative
					design and development.</li>
					<li>Designing project & planning</li>
				</ul>
				<h3>Xyz webdev pvt ltd - junior web developer</h3>
				<p>August 2021 to December 2021</p>
				<ul>
					<li>Actively engaged in web creative
					design and development.</li>
					<li>Designing project & planning</li>
					<li>Working on designing</li>
				</ul>
			</div> -->
			<div class="Education">
				<h2>Education</h2>
				<table>
					<tr>
						<th>University/college</th>
						<th>Passing year</th>
						<th>percentage/cgpa</th>
					</tr>
					<tr>
						<td>Kittle Science <br>
                            College Dharwad</td>
						<td>2022</td>
						<td>57</td>
					</tr>
					<tr>
						<td>SDM Ujire</td>
						<td>2017</td>
						<td>57.33</td>
					</tr>
				</table>
			</div>
			<div class="project">
				<ul>
					<li>
						<h2>Project_URA</h2>
						<p>This project is based on Html,css,Python,Django
						& used React</p>
                        <p>https://github.com/vishwas9513/URA.git</p>
					</li>
                    <br>
					<li>
						<h2>Web Portfolio</h2>
						<p>This project is based on  HTML, CSS, Python 
						</p>
                        <p>https://github.com/vishwas9513/Web-Profile.git</p>
					</li>
                    <br>
                    <li>
						<h2>Processing orders for boxes</h2>
						<p>This project is based on  HTML, CSS, Python 
						</p>
                        <p>https://github.com/vishwas9513/vishwas9513.github-io.git</p>
					</li>
				</ul>
			</div>
		</div>
	</div>
</body>
</html>

# resume.css
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
body {
	background-color: rgb(253, 254, 255);
	display: flex;
	justify-content: center;
	align-items: center;
}
.full {
	width: 50%;
	max-width: 1000px;
	min-height: 100px;
	background-color: rgb(245, 239, 231);
	margin: 0px;
	display: grid;
	grid-template-columns: 2fr 4fr;
}
.left {
	position: initial;
	background-color: rgb(126, 219, 231);
	padding: 20px;

}
.right {
	position: initial;
	background-color: rgb(162, 202, 206);
	padding: 20px;

}
.image, .Contact, .Skills, .Language, .Hobbies, .title,
.Summary, .Experience, .Education, .project {
	margin-bottom: 30px;
}
.h2 {
	background-color: rgb(4, 96, 150);
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <style>
		.line {
			width: 100%;
			height: 5px;
			background-color: red;
			position: absolute;
			top: 50%;
			left: 0;
		}
	</style>
</head>
<body>
  <h1>Sachintha Pasindu</h1>
  <div class="line"></div>
  <h2>Introduction</h2>
  <p>I'm a Web developer with a passion for coding and editing. I'm currently learning at eLearning.lk and exploring new technologies to enhance my skills.</p>

  <h2>Skills and Experience</h2>
  <ul>
    <li>Proficient in PHP, JavaScript, HTML, and CSS</li>
    <li>Familiar with popular software development tools such as Git and VSCode</li>
    <li>Completed online courses in web development, data science, and machine learning</li>
    <li>Participated in several hackathons and coding competitions</li>
  </ul>

<!--   <h2>Projects</h2>
  <ul>
    <li><a href="https://www.example.com">Portfolio Website</a> - A personal website showcasing my projects and skills</li>
    <li><a href="https://github.com/example/data-analysis-project">Data Analysis Project</a> - A data analysis project using Python and pandas library</li>
  </ul> -->

  <h2>Contact Information</h2>
  <ul>
    <li>Email: sachintha4949@gmail.com</li>
    <li>LinkedIn: <a href="[https://www.linkedin.com/in/sachintha-pasindu/](https://www.linkedin.com/in/sachintha-pasindu-gamge-8b8a63206/)">linkedin.com/in/sachintha-pasindu</a></li>
  </ul>
  <script>
		const line = document.querySelector('.line');
		let hue = 0;
		let direction = 1;

		function changeColor() {
			hue += direction;
			if (hue >= 360) {
				hue = 0;
			}
			line.style.backgroundColor = `hsl(${hue}, 100%, 50%)`;
			window.requestAnimationFrame(changeColor);
		}

		changeColor();
	</script>
</body>
</html>

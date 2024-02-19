<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HaoChinash</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 5vw; /* Adjusted padding to be relative to viewport width */
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 3vw; /* Adjusted font size to be relative to viewport width */
            font-weight: bold;
            text-transform: uppercase;
        }
        .navigation {
            display: flex;
            align-items: center;
        }
        .navigation a {
            color: #fff;
            text-decoration: none;
            margin-right: 2vw; /* Adjusted margin to be relative to viewport width */
            font-size: 1.5vw; /* Adjusted font size to be relative to viewport width */
        }
        .content {
            display: none; /* Hide content by default */
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 80vh; /* Adjusted height to be 80% of the viewport height */
            background-color: #000;
            padding: 0 5vw; /* Adjusted padding to be relative to viewport width */
            position: relative; /* Added position property */
        }
        .logo-img {
            width: 30vw; /* Adjusted width to be relative to viewport width */
            max-width: 200px; /* Added max-width to prevent logo from becoming too large */
            height: auto;
            margin-bottom: 5vh; /* Adjusted margin to be relative to viewport height */
        }
        .contact {
            margin-top: 3vh; /* Adjusted margin to be relative to viewport height */
            color: #fff;
            font-size: 2vw; /* Adjusted font size to be relative to viewport width */
            text-align: center;
        }
        img.background-img {
            width: 100vw; /* Adjusted width to be 100% of the viewport width */
            height: auto;
            object-fit: cover;
            position: absolute; /* Added position property */
            top: 0; /* Added top property */
            left: 0; /* Added left property */
            z-index: -1; /* Added z-index property */
        }
    </style>
</head>
<body>

<header>
    <div class="logo">HaoChinash</div>
    <nav class="navigation">
        <a href="#" onclick="showEducation()">Education</a>
        <a href="#experience">Experience</a>
        <a href="#hobby">Hobby</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="content" id="educationContent">
    <section id="education">
        <h2>Education</h2>
        <p>University of California – San Diego (UCSD)</p>
        <p>Rensselaer Polytechnic Institute (RPI)</p>
        <p>Jserra Catholic High School (JSerra)</p>
    </section>
</div>

<img src="background.jpg" alt="Background Image" class="background-img">

<script>
    function showEducation() {
        var educationContent = document.getElementById("educationContent");
        educationContent.style.display = "flex"; // Show content when "Education" is clicked
    }
</script>

</body>
</html>

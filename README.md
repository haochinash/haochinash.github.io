<!DOCTYPE html>
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
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 24px;
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
            margin-right: 20px;
            font-size: 16px;
        }
        .content {
            display: none;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 80vh;
            padding: 20px;
            position: relative;
        }
        .logo-img {
            width: 150px;
            height: auto;
            margin-bottom: 20px;
        }
        .contact {
            margin-top: 20px;
            color: #fff;
            font-size: 18px;
            text-align: center;
        }
        .black-background {
            background-color: #000;
            height: 40vh; /* Adjusted height to cover 2/5 of the viewport height */
            width: 100%;
            position: absolute;
            top: 0;
            left: 0;
            z-index: -1;
        }
        img.background-img {
            width: 100%;
            height: auto;
            object-fit: cover;
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

<div class="black-background"></div> <!-- Black background covering 2/5 of the top of the page -->

<div class="content" id="educationContent">
    <section id="education">
        <h2>Education</h2>
        <p>University of California – San Diego (UCSD)</p>
        <p>Rensselaer Polytechnic Institute (RPI)</p>
        <p>Jserra Catholic High School (JSerra)</p>
    </section>
</div>

<img src="140fabfc1588825f1864973aafdb86d.jpg" alt="Background Image" class="background-img">

<script>
    function showEducation() {
        var educationContent = document.getElementById("educationContent");
        educationContent.style.display = "flex";
    }
</script>

</body>
</html>

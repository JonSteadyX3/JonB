<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Author Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    background: #0a0a0f;
    color: white;
    overflow-x: hidden;
}

/* STAR BACKGROUND */
.stars {
    position: fixed;
    width: 100%;
    height: 100%;
    background: black;
    z-index: -1;
    overflow: hidden;
}

.stars::before, .stars::after {
    content: "";
    position: absolute;
    width: 200%;
    height: 200%;
    background-image: radial-gradient(white 1px, transparent 1px);
    background-size: 3px 3px;
    animation: moveStars 120s linear infinite;
    opacity: 0.4;
}

.stars::after {
    background-size: 2px 2px;
    animation-duration: 200s;
    opacity: 0.2;
}

@keyframes moveStars {
    from { transform: translate(0,0); }
    to { transform: translate(-50%, -50%); }
}

/* HERO SECTION */
.hero {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 3rem;
    letter-spacing: 2px;
}

.scroll {
    position: absolute;
    bottom: 30px;
    font-size: 0.9rem;
    opacity: 0.6;
}

/* TAN SECTION */
.about {
    background: #d6c3a3;
    color: #1a1a1a;
    padding: 80px 20px;
}

.container {
    max-width: 800px;
    margin: auto;
}

.about h2 {
    font-family: 'Playfair Display', serif;
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.about p {
    line-height: 1.7;
    font-size: 1.1rem;
}

/* SMOOTH SCROLL */
html {
    scroll-behavior: smooth;
}
</style>
</head>

<body>

<div class="stars"></div>

<section class="hero">
    <div>
        <h1>Your Name</h1>
        <div class="scroll">Scroll ↓</div>
    </div>
</section>

<section class="about">
    <div class="container">
        <h2>About Me</h2>
        <p>
            Replace this with your author bio. Talk about your themes, your stories, and what drives your writing.
            You can describe your worlds, your characters, or your philosophy on storytelling.
        </p>
    </div>
</section>

</body>
</html>

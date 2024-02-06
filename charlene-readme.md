## The Project:
 Our team was put in charge of creating a fashion website for the clothing company, Anissa & Tam CO. which was a company that focused on reducing their carbon footprint and making their products as eco-friendly as possible, using organic materials to make their products.

## My contribution:
I was in charge of the design of the website, as well as the overall layout of the About Us page. I determined what would be the best layout and what colors would go well and compliment each other, and create the kind of environment that would not only suit the website, but also meet the expectations of the client.

## My code:

<!--
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <title>About US - A&T</title>
</head>
<body>
    <section class="container">
        <div class="wrapper">
            <div class="header">
                <p class="header-title">About A&T</p>
            </div>
            <div class="header-nav">
                <nav>
                    <a class="nav-bar" href="index.html">Home</a>
                    <a class="nav-bar" href="">New Arrivals</a>
                    <a class="nav-bar" href="">Mens</a>
                    <a class="nav-bar" href="">Women</a>
                    <a class="nav-bar" href="">Apparel</a>

                    <i class='bx bx-cart' id="cart"></i>
                    <i class='bx bx-user'></i>
                </nav>
            </div>
            <div class="branding-marketing" style="background-image: url(./img/banner2.png);">
                <h2 class="section-title">BRANDING AND MARKETING</h2>
                <p class="info" style="margin-top: 0;">The brand’s identity is built around it’s commitment to the planet and community.
                    Their marketing campaigns focus on story telling, highlighting the journey of their
                    products from sustainable sources to fashionable wardrobes. Annisa&Tam Co. represents 
                    a new wave in the fashion industy, creating a harmonious relationship between fashion
                    and environment.</p>
            </div>
            <div class="side-info">
                <div class="products-container">
                    <h2 class="section-title" style="text-align: center;">PRODUCTS</h2>
                    <p class="info">Anissa& Tam Co. offers a range of fashion products,
                        including clothing, accessories, and foot ware. All products are made
                        from sustainable materials like organic cotton, recycled polyester,
                        and natural dyes. The designs blend contemporary fashion trends with
                        timeless styles, catering to a board audience.</p>
                </div>
                <hr>
                <div class="future-goals-container">
                    <h2 class="section-title">FUTURE GOALS</h2>
                    <p class="info">The company aims to continuously innovate in
                        sustainable fashion, exploring new matierals and techniques. They plan
                        to expand their reach globally while maintaining their core values of
                        local sourcing and environmental responsibilty.</p>
                </div>
            </div>
            <div class="main-info-background">
                <div class="main-info-container">
                    <div class="market-position">
                        <h2 class="section-title" id="market-position-title">MARKET POSITION AND AUDIENCE</h2>
                        <p class="info" id="market-position-info">Anissa&Tam Co. targets environmentally conscious consumers
                            who value both style and sustainability. They position themselves a
                            premium brand, offering high-quality, sustainiable options for the
                            fashion-forward individual.</p>
                    </div>
                    <div class="founding-story">
                        <h2 class="section-title" id="founding-story-title">FOUNDING STORY</h2>
                        <p class="info" id="founding-story-info">Anissa & Tam Co. Established by two fashion enthusiasts,
                            Anissa and Tam, who shared a passion for eco-friendly fashion. They
                            recognized the need for sustainable practices in the fashion industry
                            and set out to create a brand that would set new standards.</p>
                    </div>
                </div>
            </div>
            <div class="footer-container">
                <div class="mission-values-container">
                    <h2 class="section-title">MISSION AND VALUES</h2>
                    <p class="info" id="mission-values-info">The company’s mission is to revolutionize the fashion
                        industry by offering stylish, sustainable clothing. It’s vision is
                        to create a world where fashion and sustainabilty co-exist, reducing
                        the industry’s carbon footprint and promoting ethical practices.</p>
                </div>
                <div class="eco-friendly-container">
                    <h2 class="section-title">ECO-FRIENDLY-PRACTICES</h2>
                    <p class="info" id="eco-friendly-info">Beyond sustainable materials, Anissa&Tam Co. implements
                        eco-friendly practices in every aspect of its operations. This includes
                        energy - efficient manufacturing, minimal packaging, and recycling
                        program for used garments.</p>
                </div>
            </div>
        </div>




<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display&display=swap');

section.container {
    background-color: #17968B;
    padding: 40px;
    /* text-align: center; */
}

* {
    margin: 0;
    padding: 0;
    text-decoration: none;
    list-style: none;
    color: #494949;
    font-family: 'Montserrat', sans-serif;
}

body {
    background-color: #17968B;
}


/* HEADER */
div.header {
    width: 97%;
    height: 150px;
    background-color: #F3EDE5;
    display: block;
    padding: 25px;
    /* color: #494949; */
    /* border: solid red; */
    margin-bottom: 30px;
}
/* TEXT INSIDE HEADER */
p.header-title {
    font-family: 'DM Serif Display', serif;
    font-size: 3rem;
    text-align: center;
    padding: 25px;
    /* border: solid lime */
}



/* NAV BAR */
div.header-nav {
    /* border: solid blue; */
    text-align: center;
}
a, i {
    /* border: solid magenta; */
    color: white;
    margin: 0 1.5rem;
    margin-top: 25px;
    text-decoration: none;
    /* display: inline-block; */
    letter-spacing: 1px;
    font-size: 1rem;
    font-family: 'DM Serif Display', serif;
    transition: all .40s ease;
}
.nav-bar:hover {
    color: #D8D628;
    transform: translateY(-5px)





/* THE FIRST BOX */
div.branding-marketing {
    border: solid 20px #D1ADCD;
    width: 95%;
    height: 200px;
    background-color: #F3EDE5;
    display: block;
    padding: 25px;
    margin-top: 30px;
}



/* HEADER OF THE BOXES */
h2.section-title {
    /* border: solid magenta; */
    font-weight: 1000;
    height: 2rem;
    width: 50%;
    margin-left: 25%;
    margin-top: 0;
    padding-top: 30px;
    text-align: center;
}
/* TEXT INSIDE THE INFO BOXES */
p.info {
    /* border: solid blue; */
    font-family: 'DM Serif Display', serif;
    font-size: 1.5rem;
    text-align: center;
    font-weight: 100;
    padding: 2%;
    margin-top: 50px;
}



/* PRODUCTS AND FUTURE GOALS */
div.side-info {
    border: solid 20px #d8d628;
    width: 500px;
    height: 1000px;
    background-color: #F3EDE5;
    display: block;
    padding: 25px;
    margin-top: 50px;
    display: inline-block;
}
div.future-goals-container {
    margin-top: 75px;
    /* padding-top: 25%; */
}
hr {
    margin-top: 25%;
}



/* MAIN INFO BOXES*/
div.main-info-background {
    /* border: solid 20px #F3EDE5; */
    width: 1125px;
    height: 1040px;
    background-color: #F3EDE5;
    display: block;
    padding: 25px;
    margin-top: 50px;
    padding: 25px;
    float: right;
    display: inline-block;
}
/* MAIN INFO BOXES */
div.main-info-container {
    /* border: solid cyan; */
    width: 1000px;
    height: 900px;
    padding: 55px;
}
div.market-position {
    /* border: solid black; */
    height: 450px;
    width: 1000px;
    background-color: #D1ADCD;
    margin-left: 15px;
}
/* #market-position-title, #founding-story-title {
    border: solid blue;
    padding: 2%;
} */
#market-position-info, #founding-story-info {
    width: 775px;
    margin: 75px;
    padding: 3%;
    /* border: solid magenta; */
}
div.founding-story {
    /* border: solid black; */
    height: 450px;
    width: 1000px;
    background-color: #d8d628;
    margin-top: 50px;
    margin-left: 15px;
}



/* FOOTER INFO BOXES */
div.footer-container {
    /* border: solid red; */
    width: 97.2%;
    height: 600px;
    margin-top: 50px;
    /* padding: 25px; */
}
#mission-values-info {
    margin-top: 0;
}
div.mission-values-container {
    width: 100.6%;
    height: 225px;
    background-color: #D1ADCD;
    text-align: center;
    border: solid 20px #494949;
}
div.eco-friendly-container {
    width: 100.6%;
    height: 225px;
    background-color: #F3EDE5;
    text-align: center;
    margin-top: 50px;
    border: solid 20px #d8d628;
}
#eco-friendly-info {
    margin-top: 0;
}


 -->
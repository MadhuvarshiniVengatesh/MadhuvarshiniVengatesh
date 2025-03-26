<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <link rel="icon" href="https://tse4.mm.bing.net/th?id=OIP.uGRakwJGGVX-d0kcGa9o0QHaHa&pid=Api&P=0&h=220">
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <div id="Header" style="background-image: url(https://tse1.mm.bing.net/th?id=OIP._0_jdcvBkngnX-x87IJPdgHaEo&pid=Api&P=0&h=220);" >
    <h1 >Upcoming Events📅</h1>
    <p style="padding:20px; color: aliceblue; font-size: 20px;">Don't Miss any of your important events. Here are the important events you have registered for !!</p>
   </div>
<hr>
<div id="menu" style="margin-top: 30px;">
    <a href="home.html"> Home</a>
    <a href="gallery.html">Plans</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact us</a>
</div>
<hr style="margin: 40px;">

<div id="container">
    <p style="color:white ;">We are welcoming everyone must come and visit our site !!</p>
    <center><img src="event1.png" alt="Sorry Not Avaliable"></center>
</div>
<p style="font-size: 30px;">Some of Our New Collections..</p>
<div id="new">
    <p style="color: white;">"Introducing SnapVision – your AI-powered photo gallery! 📸✨
        Organize, edit, and enhance your pictures effortlessly. With smart tagging, auto-enhancement, and cloud storage, your memories are safer and more vibrant than ever! 🌟
        Experience real-time filters, AI-driven photo organization, and seamless social media sharing – all in one app. 🌍💙
        Fast, secure, and designed for creativity, SnapVision makes every photo unforgettable! 🚀💫"</p>
</div>
<div id="main"> 
    
    <div id="img1">
        <img src="https://tse2.mm.bing.net/th?id=OIP.oywJOz55PYqj2cD3bb3r_gHaE8&pid=Api&P=0&h=220" alt="item1">
    </div>
    <div id="img2">
        <img src="https://tse1.mm.bing.net/th?id=OIP.5BseD8Sv1wZZT26cpuIyVgHaGC&pid=Api&P=0&h=220" alt="item2">
    </div>
    <div id="img3"> 
        <img src="https://tse1.mm.bing.net/th?id=OIP.CyMsbE4je6a-u6MAbaADawHaEK&pid=Api&P=0&h=220" alt="item3">
    </div>
    </div>
    <div id="main1"> 
    
        <div id="img1">
            <img src="https://tse3.mm.bing.net/th?id=OIP.PZ0ZmZFJgSJ_bjFTYHQFUgHaEn&pid=Api&P=0&h=220" alt="item1">
        </div>
        <div id="img2">
            <img src="https://tse1.mm.bing.net/th?id=OIP.PW7z64nPpJO00lm2LYLgKwHaEd&pid=Api&P=0&h=220" alt="item2">
        </div>
        <div id="img3"> 
            <img src="https://tse1.mm.bing.net/th?id=OIP.7iR8k3YcAV8ddGg784UNxAHaE6&pid=Api&P=0&h=220" alt="item3">
        </div>
        </div>
        <div id="det">
            
            <div id="future-plans">
                <h2>Our Future Plans</h2>
                <p>🚀 Expanding our gallery to showcase more global talent.</p>
                <p>🎨 Introducing AI-powered photo enhancements.</p>
            </div>
            <hr>
            <div id="About">
                <h1>About Us</h1>
                <p>📸 "Welcome to our Photo Gallery where every picture tells a story! From breathtaking landscapes to unforgettable moments, we capture the essence of beauty and creativity. Explore, get inspired, and relive memories through our lens!"</p>
             </div>
             <hr>
             <div id="con">
                <h1>Contact Us</h1>
                <p>📞 Contact: +123 456 7890</p>
                <p>📧 Email: contact@photogallery.com</p>
             </div>
            
        </div>
        
</div>
</body>
</html>
/* style sheets*/
<style>
  *{
    padding : 0px;
    margin: 0px;
    font-family: 'Times New Roman', Times, serif;
}
body{
    color : white;
    background-color: black;
}
#Header{
 
    text-align: center;
    padding: 20px;
}

#menu a {
        
        text-decoration: none;
        color: antiquewhite;
        padding: 10px 20px 10px ;
        font-size: 25px;
        border: 2px solid antiquewhite; 
        border-radius: 5px; 
        box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.3); 
        background-color: transparent;
        transition: 0.3s; 
    }
    
#menu a:hover {
        background-color: antiquewhite;
        color: black;
}
     
#menu{
    
    display: flex;
    justify-content: center; 
    align-items: center;              
    gap : 20px;
}

#container img{
    padding-top: 70px;
}
#container p{
    text-align: center;
    margin-top: 50px;
    font-size: 25px;
}
p{
    text-align: center;
    margin-top: 50px;
    font-size: 25px;
}
#main{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 40px;
    font-size: 25px;
    gap : 40px
}
#main1{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 40px;
    font-size: 25px;
    gap : 40px
}

  
#det {
    border: 3px solid gray; 
    padding: 30px;
    margin: 50px auto;
    width: 1100px; 
    height: auto; 
    background: #060000; 
    border-radius: 10px; 
    box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.1); 
    text-align: center;
}


#future-plans, #About, #con {
    background: rgba(255, 255, 255, 0.1); 
    padding: 20px;
    margin: 15px 0; 
    border-radius: 10px; 
    box-shadow: 3px 3px 12px rgba(0, 0, 0, 0.2); 
    transition: transform 0.3s, box-shadow 0.3s;
}


#future-plans:hover, #About:hover, #con:hover {
    transform: scale(1.05); 
    box-shadow: 5px 5px 20px rgba(0, 0, 0, 0.3); 
}


h1, h2 {
    color: whitesmoke;
    font-family: Arial, sans-serif;
    margin-bottom: 10px;
}


p {
    color: rgb(78, 161, 216);
    font-size: 18px; 
    line-height: 1.8; 
    font-family: Arial, sans-serif;
}

#main img, #main1 img {
    transition: transform 0.4s ease-in-out; 
}

#main img:hover, #main1 img:hover {
    transform: scale(1.2); 
}


#main img:active, #main1 img:active {
    transform: scale(1); 
}
</style>
/*Home*/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home | SnapVision</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    /* Global Styles */
* {
    padding: 0;
    margin: 0;
    font-family: 'Arial', sans-serif;
}

body {
    color: white;
    background-color: black;
    text-align: center;
}

/* Navigation Menu */
#menu {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    margin-top: 30px;
}

#menu a {
    text-decoration: none;
    color: antiquewhite;
    padding: 10px 20px;
    font-size: 22px;
    border: 2px solid antiquewhite;
    border-radius: 5px;
    background-color: transparent;
    transition: 0.3s;
}

#menu a:hover {
    background-color: antiquewhite;
    color: black;
}

/* Intro Section */
#intro, #about, #contact {
    text-align: center;
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    margin: 40px auto;
    width: 60%;
    border-radius: 10px;
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
}

h2 {
    color: #f8f8f8;
    font-size: 26px;
}

p {
    color: rgb(78, 161, 216);
    font-size: 18px;
    line-height: 1.8;
}

/* Featured Image */
#featured img {
    width: 50%;
    border-radius: 10px;
    margin-top: 20px;
    transition: transform 0.3s;
}

#featured img:hover {
    transform: scale(1.1);
}

/* Gallery Section */
.gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.gallery img {
    width: 250px;
    height: 180px;
    border-radius: 10px;
    transition: transform 0.3s;
}

.gallery img:hover {
    transform: scale(1.2);
}

</style>
<body>

    <div id="menu">
        <a href="home.html">🏠 Home</a>
        <a href="gallery.html">📷 Gallery</a>
        <a href="about.html">ℹ️ About</a>
        <a href="contact.html">📞 Contact</a>
    </div>

    <div id="intro">
        <h2>Welcome to SnapVision! 📸✨</h2>
        <p style="color:whitesmoke;">"Where memories come to life! Organize, enhance, and share your favorite moments seamlessly! 🚀"</p>
    </div>

    <div id="featured">
        <img src="event2.png" alt="Gallery Preview">
        <p style="color:whitesmoke;">📷 Explore our latest AI-enhanced collections!</p>
    </div>

</body>
</html>
/*gallery*/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery | SnapVision</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    /* Global Styles */
* {
    padding: 0;
    margin: 0;
    font-family: 'Arial', sans-serif;
}

body {
    color: white;
    background-color: black;
    text-align: center;
}

/* Navigation Menu */
#menu {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    margin-top: 30px;
}

#menu a {
    text-decoration: none;
    color: antiquewhite;
    padding: 10px 20px;
    font-size: 22px;
    border: 2px solid antiquewhite;
    border-radius: 5px;
    background-color: transparent;
    transition: 0.3s;
}

#menu a:hover {
    background-color: antiquewhite;
    color: black;
}

/* Intro Section */
#intro, #about, #contact {
    text-align: center;
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    margin: 40px auto;
    width: 60%;
    border-radius: 10px;
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
}

h2 {
    color: #f8f8f8;
    font-size: 26px;
}

p {
    color: rgb(78, 161, 216);
    font-size: 18px;
    line-height: 1.8;
}

/* Featured Image */
#featured img {
    width: 50%;
    border-radius: 10px;
    margin-top: 20px;
    transition: transform 0.3s;
}

#featured img:hover {
    transform: scale(1.1);
}

/* Gallery Section */
.gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.gallery img {
    width: 250px;
    height: 180px;
    border-radius: 10px;
    transition: transform 0.3s;
}

.gallery img:hover {
    transform: scale(1.2);
}

</style>
<body>

    <div id="menu">
        <a href="home.html">🏠 Home</a>
        <a href="gallery.html">📷 Gallery</a>
        <a href="about.html">ℹ️ About</a>
        <a href="contact.html">📞 Contact</a>
    </div>

    <h2>📸 Our Latest Collections</h2>

    <div class="gallery">
        <img src="https://tse1.mm.bing.net/th?id=OIP.PW7z64nPpJO00lm2LYLgKwHaEd&pid=Api&P=0&h=220" alt="Image 1">
        <img src="https://tse1.mm.bing.net/th?id=OIP.7iR8k3YcAV8ddGg784UNxAHaE6&pid=Api&P=0&h=220" alt="Image 2">
        <img src="https://tse3.mm.bing.net/th?id=OIP.PZ0ZmZFJgSJ_bjFTYHQFUgHaEn&pid=Api&P=0&h=220" alt="Image 3">
    </div>

</body>
</html>
/*about*/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About | SnapVision</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    /* Global Styles */
* {
    padding: 0;
    margin: 0;
    font-family: 'Arial', sans-serif;
}

body {
    color: white;
    background-color: black;
    text-align: center;
}

/* Navigation Menu */
#menu {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    margin-top: 30px;
}

#menu a {
    text-decoration: none;
    color: antiquewhite;
    padding: 10px 20px;
    font-size: 22px;
    border: 2px solid antiquewhite;
    border-radius: 5px;
    background-color: transparent;
    transition: 0.3s;
}

#menu a:hover {
    background-color: antiquewhite;
    color: black;
}

/* Intro Section */
#intro, #about, #contact {
    text-align: center;
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    margin: 40px auto;
    width: 60%;
    border-radius: 10px;
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
}

h2 {
    color: #f8f8f8;
    font-size: 26px;
}

p {
    color: rgb(78, 161, 216);
    font-size: 18px;
    line-height: 1.8;
}

/* Featured Image */
#featured img {
    width: 50%;
    border-radius: 10px;
    margin-top: 20px;
    transition: transform 0.3s;
}

#featured img:hover {
    transform: scale(1.1);
}

/* Gallery Section */
.gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.gallery img {
    width: 350px;
    height: 200px;
    border-radius: 10px;
    transition: transform 0.3s;
}

.gallery img:hover {
    transform: scale(1.2);
}

</style>
<body>

    <div id="menu">
        <a href="home.html">🏠 Home</a>
        <a href="gallery.html">📷 Gallery</a>
        <a href="about.html">ℹ️ About</a>
        <a href="contact.html">📞 Contact</a>
    </div>

    <div id="about">
        <h2 style="color:whitesmoke;">About SnapVision 📸</h2>
        <p style="color:whitesmoke;">"Welcome to SnapVision! Our AI-powered gallery brings you the best experience in organizing, editing, and sharing photos effortlessly.  
           Explore the latest technology that makes your memories even more beautiful! 🚀✨"</p>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact | SnapVision</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    /* Global Styles */
* {
    padding: 0;
    margin: 0;
    font-family: 'Arial', sans-serif;
}

body {
    color: white;
    background-color: black;
    text-align: center;
}

/* Navigation Menu */
#menu {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    margin-top: 30px;
}

#menu a {
    text-decoration: none;
    color: antiquewhite;
    padding: 10px 20px;
    font-size: 22px;
    border: 2px solid antiquewhite;
    border-radius: 5px;
    background-color: transparent;
    transition: 0.3s;
}

#menu a:hover {
    background-color: antiquewhite;
    color: black;
}


#intro, #about, #contact {
    text-align: center;
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    margin: 40px auto;
    width: 60%;
    border-radius: 10px;
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
}

h2 {
    color: #f8f8f8;
    font-size: 26px;
}

p {
    color: rgb(78, 161, 216);
    font-size: 18px;
    line-height: 1.8;
}

/* Featured Image */
#featured img {
    width: 50%;
    border-radius: 10px;
    margin-top: 20px;
    transition: transform 0.3s;
}

#featured img:hover {
    transform: scale(1.1);
}

/* Gallery Section */
.gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.gallery img {
    width: 250px;
    height: 180px;
    border-radius: 10px;
    transition: transform 0.3s;
}

.gallery img:hover {
    transform: scale(1.2);
}
</style>
<body>

    <div id="menu">
        <a href="home.html">🏠 Home</a>
        <a href="gallery.html">📷 Gallery</a>
        <a href="about.html">ℹ️ About</a>
        <a href="contact.html">📞 Contact</a>
    </div>

    <div id="contact">
        <h2>📞 Contact Us</h2>
        <p>📧 Email: contact@snapvision.com</p>
        <p>📞 Phone: +123 456 7890</p>
        <p>🏢 Address: 123 AI Street, Tech City</p>
    </div>

</body>
</html>


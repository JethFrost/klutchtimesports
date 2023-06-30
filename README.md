<!DOCTYPE html>

<html> 
<head>
 
 <title>Klutch Time Sports Website</title>

<style>
  
 
 .navbar a {
      color: #FFFFFF ;
      
      font-family:'Horizon', sans-serif;
      font-size: 18px;
      padding: 5px 10px;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }
    
    .navbar a:hover {
      font-size: 19px;
      background-color:orange;
      color:black;
    }
  .navbar {
  display: flex;
  align-items: center;
}
 
  .navbar a {
    margin-right: 25px; 
  }
 
  nav ul {
  list-style: none;
  margin: 1px;
  padding: 0;
}

nav li {
  display: inline-block;
  position: relative;
}

nav a {
  display: block;
  padding: 10px 25px;
  text-decoration: none;
  color: #333;
}

nav ul.sub-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background-color: #1A1A1A;
  padding: 0;
}

nav ul.sub-menu li {
  display: block;
}

nav li:hover > ul.sub-menu {
  
  display: block;
}
 .logo-container {
      display: flex;
      align-items: center;
    }
    
    .logo-image {
      max-width: 220px;
      margin-right: 130px;
      margin-left: 38px; 
    }

.logo-container {
  margin-right: 10px;
}

.search-container {
  position: relative;
  display: inline-block;
}



      .signup-button a {
      
      color: white;
      padding: 5px 8px;
       font-family:'Horizon', sans-serif;
      font-size: 18px;
      margin-left:117px;
      text-decoration: none;
       background-color:  #000000;
      font-family:'Horizon', sans-serif;
     
      transition: background-color 0.3s ease;
    }
    
    .signup-button a:hover {
    background-color: #ddd;
    }
 .signup-button a:hover {
      font-size: 19px;
      background-color:orange;
      color:black;
    }

  .signin-button a {
      
      color: white;
      padding: 5px 8px;
       font-family:'Horizon', sans-serif;
      font-size: 18px;
      text-decoration: none;
       background-color:  #000000;
      font-family:'Horizon', sans-serif;
     
      transition: background-color 0.3s ease;
    }
    
    .signin-button a:hover {
    background-color: #ddd;
    }
 .signin-button a:hover {
      font-size: 19px;
      background-color:orange;
      color:black;
    }


.search-toggle {
  display: none;
}

.search-input {
  width: 0;
  padding: 9px 25px;
  transition: all 0.5s ease;
  opacity: 0;
  font-family: 'Horizon', sans-serif;
  visibility: hidden;
  animation: slideIn 0.5s forwards;
  border-radius: 20px 20px 20px 20px;
  border: none;
  background-color: #FEF4F4;
  border-bottom: 2px solid #FFF;
  color: black;
}

.search-container:hover .search-input {
  width: 200px;
 
  opacity: 1;
  visibility: visible;
}

.search-button {
  position: absolute;
  top: 0;
  left: 0;
  border: none;
  background: none;
  cursor: pointer;
  transition: transform 0.5s ease;
  outline: none;
  display: flex;
  align-items: center;
}

.search-button img {
  width: 25px;
  height: 25px;
   margin-left: 0px;
  transition: transform 0.5s ease;
}

.search-container:hover .search-button img {
  transform: scale(1.2);
}

.search-button:focus {
  outline: none;
}


  .search-icon {
    margin-right: 60px; 
  }
 .search-input {
    margin-left: 50px;
  }
  

     {
  margin-bottom: 100px;
}
 
@font-face {
  font-family: "Breul Grotesk";
  src: url(path/to/breulgrotesk.woff2) format('woff2'),
       url(path/to/breulgrotesk.woff) format('woff');
}
@font-face {
  font-family: 'Horizon';
  src: url('horizon.woff2') format('woff2'),
       url('horizon.woff') format('woff'),
       url('horizon.ttf') format('truetype');
}

.page {
      display: none;
    }
.page {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
   main {
  padding: 150PX;
  background-image: url('https://drive.google.com/uc?export=open&id=1ZHr_AuMqTeZJFnX0nOb-6eMuezpxBvTi');
  background-size: cover; 
  background-position: center; 
  background-repeat: no-repeat;
       
   }
   
    .content-border {
      border: 2px solid #333;
      padding: 20px;
      background-color:#303030;
      box-shadow: 0px 0px 5px 0px rgba(0, 0, 0, 0.2);
     
    }
 
 .news-feed {
  max-width: 1100px;
  margin: 0 auto;
  font-family: Arial, sans-serif;
  color: #FEF4F4;
}
.news-feed :hover {
  transform: scale(1.02);
}
.main-article {
  margin-bottom: 20px;
}

.main-article img {
  width: 100%;
   flex-direction: column;
  border: 1px solid #ddd;
  border-radius: 8px;
  height: auto;
  border-radius: 8px;
}

.main-article-content {
  padding: 20px;
   flex-direction: column;
  border: 1px solid #ddd;
  border-radius: 8px;
  background-color: #1A1A1A;
}

.main-article h2 {
  font-size: 24px;
  color: white;
  margin-top: 0;
  margin-bottom: 10px;
}

.main-article p {
  font-size: 14px;
  margin-bottom: 20px;
}

.main-article a {
  display: inline-block;
  padding: 10px 20px;
   flex-direction: column;
  border: 1px solid #ddd;
  border-radius: 8px;
  background-color: #000000;
  color: #FEF4F4;
  text-decoration: none;
  border-radius: 4px;
  transition: background-color 2s ease;
}

.main-article a:hover {
  font-size: 17px;
  background-color:orange;
}

.secondary-articles {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 20px;
}

.article {
  display: flex;
  flex-direction: column;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.article img {
  width: 100%;
  height: auto;
  object-fit: cover;
  border-bottom: 1px solid #ddd;
}
.article img :hover {
  transform: scale(.5);
}

.article-content {
  padding: 15px;
}


.article h3 {
  font-size: 18px;
  margin-top: 0;
  margin-bottom: 10px;
}

.article p {
  font-size: 14px;
  margin-bottom: 15px;
}


.article a {
  align-self: flex-end;
  padding: 6px 12px;
  background-color: #000000;
  color: #fff;
  text-decoration: none;
  border-radius: 4px;
  transition: background-color 0.3s ease;
}

.article a:hover {
   font-size: 17px;
  background-color: orange;
}

  .newsfeed {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 20px;
      padding: 20px;
      background-color: #1A1A1A;
    }

    
    .video-card {
      background-color: #303030;
      border-radius: 5px;
      padding: 20px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
      cursor: pointer;
    }

    .video-card:hover {
      transform: translateY(-5px);
    }

    .video-card img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }

    .video-card h3 {
      margin-top: 10px;
      font-size: 18px;
      color: white;
    }

    .video-card p {
      margin-top: 5px;
      font-size: 14px;
      color: white;
    }
 
section h2 {
  color: #EDEDED;
  text-align: center;
}

section p {
  color: #EDEDED;
  text-align: center;
}
.service {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 20px;
  text-align: center;
  color: #ffffff; 
}

.service-image {
  width: 200px;
  height: 200px;
  margin-right: 20px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #1A1A1A;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 60vh;
  background-color: #303030;
}

.service:last-child {
  margin-right: 0;
}

.service h3 {
  margin: 0;
  font-size: 20px;
}

.service p {
  margin-top: 10px;
  color: #EDEDED;
}

.hire-button {
  display: inline-block;
  padding: 10px 20px;
  font-size: 16px;
  font-family: 'Breul Grotesk', sans-serif;
  text-decoration: none;
  background-color: #1A1A1A;
  color: white;
}

.hire-button:hover {
  font-size: 17px;
  background-color: orange;
  color: black;
}


.product {
  display: inline-block;
  width: 250px;
  padding: 20px;
  border: 1px solid #1A1A1A;
  margin-right: 25px;
  margin-left: 25px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
  text-align: center;
  transition: transform 0.3s ease-in-out;
}

.product img {
  max-width: 100%;
  height: 250px; 
  object-fit: cover; 
}

.product:hover {
  transform: scale(1.05);
}

.product img {
  max-width: 100%;
}

.product h3 {
  color: #EDEDED;
  margin-top: 40px;
  font-size: 18px;
}

.product p {
  color: #EDEDED;
}

.product button {
  background-color: #1A1A1A;
  color: white;
  border: none;
  padding: 10px 20px;
  margin-top: 15px;
  cursor: pointer;
  transition: background-color 0.3s ease-in-out;
}

.product button:hover {
  background-color: #FF9800;
}


@media (max-width: 768px) {
 
}

@media (max-width: 480px) {
 
}
.signup-container {
  background-color: #1A1A1A;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  padding: 40px;
  text-align: center;
  width: 400px;
}

h2 {
  color: #EDEDED;
  font-size: 24px;
  margin-bottom: 20px;
}

.input-group {
  margin-bottom: 20px;
}

label {
  color: #EDEDED;
  display: block;
  font-size: 16px;
  margin-bottom: 5px;
}

input.signup-input {
  border: none;
  background-color: white;
  color: #EDEDED;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  height: 30px;
  padding: 5px 10px;
  width: 100%;
}

button.signup-button {
  background-color: #000000;
  border: none;
  border-radius: 5px;
  color: #EDEDED;
  cursor: pointer;
  font-size: 16px;
  height: 40px;
  transition: background-color 0.3s ease;
  width: 100%;
}

button.signup-button:hover {
  background-color: #FF4626;
}

.login-container {
  background-color: #1A1A1A;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  padding: 40px;
  text-align: center;
  width: 400px;
}

h2 {
  color: #EDEDED;
  font-size: 24px;
  margin-bottom: 20px;
}

.input-group {
  margin-bottom: 20px;
}

label {
  color: #EDEDED;
  display: block;
  font-size: 16px;
  margin-bottom: 5px;
}

input[type="text"].login-input,
input[type="password"].login-input {
  border: none;
  background-color:  #EDEDED;
  color:#292929;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  height: 30px;
  padding: 5px 10px;
  width: 50%;
}

.login-button {
  background-color: #000000;
  border: none;
  border-radius: 5px;
  color: #EDEDED;
  cursor: pointer;
  font-size: 16px;
  height: 40px;
  transition: background-color 0.3s ease;
  width: 57%;
}

.login-button:hover {
  background-color: #FF4626;
}
 

.cta-button {
  display: inline-block;
  padding: 10px 20px;
  font-size: 16px;
  font-family: 'Breul Grotesk', sans-serif;
  text-decoration: none;
  background-color:  #000000;
  color: #fff;
}

.cta-button:hover {
      font-size: 17px;
      background-color:orange;
      color:black;
}


</style>

</head>  
 <body style="background-color: #1A1A1A ;">

 <header style="padding: 10px 0px; background-color:#000000;">
 
<nav class="navbar">
 <div class="navbar-item">
 <div class="logo-container">
 <img class="logo-image" src="https://drive.google.com/uc?export=open&id=1VQbiPBHEySvkRn5dZYKQY1kigQccV-bW">
   </div>   
  </div>
 <ul class="menu-items">
<li><a href="#" onclick="showPage(1)">Home</a></li>
<li>
      <a href="#" onclick="showPage(2)">Featured</a>
    <ul class="sub-menu">
 <li><a href="#"  style="font-size: 15px;">Today</a></li>
 <li><a href="#"  style="font-size: 15px;">Last 7 days</a></li>
 <li><a href="#"  style="font-size: 15px;">Last 30 days</a></li>
     </ul>
   </li>
   <li>
    <li><a href="#" onclick="showPage(3)">Video</a></li>
    <li>
     <a href="#" onclick="showPage(4)">About us</a>
      </li>
    </ul>
    <li>
    <a href="#" onclick="showPage(7)">Service</a>
      <ul class="sub-menu">
    <li><a href="#"  style="font-size: 15px;">Services</a></li>
    <li><a href="#"  style="font-size: 15px;">Products</a></li>
    </ul>
      </li>
       
    <li class="signup-button"><a href="#" onclick="showPage(6)">Sign Up</a></li>
    <li class="signin-button"><a href="#" onclick="showPage(5)">Login</a></li>
 
</nav>

 
 </header>

 <div class="page" id="page1">
  
  <main>
     <h1 style=" color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 25px; "><b>    &#8203;   Klutch Time Sports</b></h1>
      
      <div class="search-container"><input type="checkbox" id="search-toggle" class="search-toggle"><input type="text" id="search-input" placeholder="Search..." class="search-input"><button class="search-button"><img src="https://drive.google.com/uc?export=open&id=1QoDmPf7duU0XTxSqVSbtCLV8ndoax4bq" alt="Search Icon"></button></div>       
 <br><br><br> <br><br><br><br>   
  </main>
<footer style="padding: 3px 20px;  background-color: #000000 ;">
   <center>
        <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
 <br>
</footer>
  
  <div class="content-border">
  <br> <br>
  <center>  <h1 style="color:white;">Latest News</h1></center>
  <br> <br>
  <div class="news-feed">
  <div class="main-article">
    <img src="https://drive.google.com/uc?export=open&id=1dP8E1FdGMJ5FHxL6OM6bZO_Qy9kc9iS6" alt="Main Article Image">
    
    <div class="main-article-content">
      <h2>The Warriors trading Jordan Poole to the Wizards for Chris Paul</h2>
      <p>The Golden State Warriors have traded Jordan Poole and future draft assets to the Washington Wizards in exchange for Chris Paul. The trade is a major shakeup for both teams, as it sees the Warriors acquire a proven veteran point guard in Paul, while the Wizards get a young, promising guard in Poole.
</p>
      <a href="main-article-link">Read More</a>
    </div>
  </div>
  
  <div class="secondary-articles">
    <div class="article">
      <img src="https://drive.google.com/uc?export=open&id=1d5y96kI6cpNjf_Lea54E9pH16cRpXwxt" alt="Secondary Article 1 Image">
      <div class="article-content">
        <h3>NO.1 PICK NO. 2 PICK</h3>
        <p>VICTOR WEMBANYAMA VS BRANDON MILLER</p>
        <a href="secondary-article1-link">Read More</a>
      </div>
    </div>
    <div class="article">
      <img src="https://drive.google.com/uc?export=open&id=1dOM_uf22g9OmQU0zAABxTxoDxeN8RQZ3" alt="Secondary Article 2 Image">
      <div class="article-content">
        <h3>Summer Leauge</h3>
        <p>Kai Sotto lalaro sa Summer league team ng Orlando Magic Best situation para kay Kai!</p>
        <a href="secondary-article2-link">Read More</a>
      </div>
    </div>
    
    
   
  </div>

  <br><br>   
  
  <div class="secondary-articles">
    <div class="article">
      <img src="https://drive.google.com/uc?export=open&id=1cwyFoNQeGEgSC1Xrrsj01QxsMgla2Nfl" alt="Secondary Article 1 Image">
      <div class="article-content">
        <h3>Punishment</h3>
        <p>Memphis Grizzlies guard Ja Morant has been suspended for 25 games without pay, the NBA announced Friday. The suspension comes after Morant was seen with a gun on social media twice this year. NBA Commissioner Adam Silver called Morant's behavior "destructive" as well as "alarming and disconcerting."</p>
        <a href="secondary-article1-link">Read More</a>
      </div>
    </div>
    <div class="article">
      <img src="https://drive.google.com/uc?export=open&id=1e0iMljir7PezBL-njLaMtDl5dybK0L_W" alt="Secondary Article 2 Image">
      <div class="article-content">
        <h3>Zion Issue</h3>
        <p>Zion Williamson's Alleged Girlfriend Went of After Cheating Scandal</p>
        <a href="secondary-article2-link">Read More</a>
      </div>
    </div>
    
    
   
  </div>
<br> <br>

<br><br>
 <div class="newsfeed">
    <div class="video-card">
     <iframe width="305" height="185" src="https://www.youtube.com/embed/p4H_-Yed9wE" title="NBA TODAY | Woj [BREAKING NEWS] The Warriors trading Jordan Poole to the Wizards for Chris Paul" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Trade</h3>
      <p>The Warriors trading Jordan Poole to the Wizards for Chris Paul</p>
    </div>
    <div class="video-card">
       <iframe width="305" height="185" src="https://www.youtube.com/embed/yD3_d8AMtGA" title="🚨 Ja Morant suspended 25 games 🚨 Stephen A. and Woj offer opinions | First Take" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Punishment</h3>
      <p>Ja Morant suspended 25 games Stephen A. and Woj offer opinions | First Take"</p>
    </div>
    <div class="video-card">
      <iframe width="305" height="185" src="https://www.youtube.com/embed/PP8Pcv4QuzY" title="Kai Sotto lalaro sa Summer league team ng Orlando Magic Best situation para kay Kai!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

      <h3>Summer Leauge</h3>
      <p>Kai Sotto lalaro sa Summer league team ng Orlando Magic Best situation para kay Kai!</p>
    </div>
  </div>


  <div class="newsfeed">
    <div class="video-card">
<iframe width="305" height="185" src="https://www.youtube.com/embed/WZhqbThDsMg" title="🚨 BREAKING: Celtics trade Marcus Smart to Grizzlies, receive Porzingis in 3-team trade | SC with SVP" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Trade</h3>
      <p>Celtics trade Marcus Smart to Grizzlies, receive Porzingis in 3-team trade | SC with SVP</p>
    </div>
    <div class="video-card">
     <iframe width="305" height="185" src="https://www.youtube.com/embed/sij25UyDwro" title="Shaquille O&#39;Neal enters the 3rd annual Andre the Giant Memorial Battle Royal: WrestleMania 32" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>WrestleMania</h3>
      <p>Shaquille O&#39;Neal enters the 3rd annual Andre the Giant Memorial Battle Royal: WrestleMania 32</p>
    </div>
    <div class="video-card">
    <iframe width="305" height="185" src="https://www.youtube.com/embed/iPXGjAJ6jxQ" title="Houston Rockets vs Shanghai Sharks Full Game Highlights | 10.09.2018, NBA Preseason" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>What The Hill</h3>
      <p>Houston Rockets vs Shanghai Sharks Full Game Highlights</p>
    </div>
  <br><br>
  </div>
</div>
 </div>

    
<marquee  style="font-family: Arial, sans-serif; font-size: 20px;  border-radius: 4px 4px 4px 4px; padding: 5px 20px; background-color:  #1A1A1A ; color: white;"><span style="font-weight: bold;">Klutch Time Sports:</span> Crossing Through Generational Hardwood Stories
   <span style="font-weight: bold;">Created by:</span> John Ron Abris ➔ Mark Joseph Abutog ➔ Gerard Andrade ➔ Kyle Gabrielle Bajamundi ➔ Mark James Borja ➔ Jethro P. Colinares   </marquee>  
 <footer style="padding: 3px 20px;  background-color: #000000 ; ">
   <center>

<pre><span></span><span><a href="about.html" class="cta-button">ABOUT US</a></span><span><a href="https://www.example.com/social" target="_blank" class="cta-button">FOLLOW OUR SOCIALS</a></span><span><a href="contact.html" class="cta-button">CONTACT US</a></span></pre>
 <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
   <br> 
</footer>  
</div>
 
<br><br>
<div class="page" id="page7">
       <div class="content-border">
       <section>
      <h2>Our Sports Products</h2>
         <br><br>
          <center>
           <table style="border-spacing: 10px;">
         <tr>
         <td>
        <div class="product">
          <img src="https://drive.google.com/uc?export=open&id=1X7wu9najKd0XhiA-e83pdxOHbUUlHc1z" alt="Product 1">
          <h3>Wilson NBA Authenthic </h3>
          <p>Indoor Competition Basketball size 7</p>
            <p>₱3,875.00</p>
          <button>Add to Cart</button>
        </div>
        </td>
         <td>
        <div class="product">
          <img src="https://drive.google.com/uc?export=open&id=1XBHujibISqmBbvq7a4VWULJvUdHC7B8J" alt="Product 2">
          <h3>Wilson JR NBA</h3>
           <p>Aunthentic Series Outdoor</p>
            <p>₱1,220.00</p>
       <button>Add to Cart</button>
        </div>
       </td>
        <td>
        <div class="product">
        <img src="https://drive.google.com/uc?export=open&id=1XLgBLctc2sr-ULWBe39uDoRMttww3M2L" alt="Product 2">
         <h3>Wilson WNBA Authentic</h3>
          <p>Indoor/Outdoor Basketball</p>
        <p>₱2,559.00</p>
          <button>Add to Cart</button>
    </div>
     </td>
    </tr>
    <tr>
     <td>
    <div class="product">
    <img src="https://drive.google.com/uc?export=open&id=1WotHErtSV2_VH8tS1zPQ_K87gIboscIV" alt="Product 2">
         <h3>New Era</h3>
         <p>Phoenix Suns NBA Draft <br> 9FIFTY Snapback</p>
         <p>₱2,495.00</p>
         <button>Add to Cart</button>
        </div>
      </td>
      <td>
        <div class="product">
          <img src="https://drive.google.com/uc?export=open&id=1WkusO-fgR9TiVNp4uZATjbshgZzm1tYL" alt="Product 2">
          <h3>New Era</h3>
          <p>Sacramento Kings NBA Draft <br> 9FIFTY Snapback</p>
            <p>₱2,495.00</p>
          <button>Add to Cart</button>
        </div>
        </td>
        <td>
        <div class="product">
          <img src="https://drive.google.com/uc?export=open&id=1X36TXq6CSl4obmQqYr9qNi-U6b6sVwnH" alt="Product 2">
           <h3>New Era</h3>
          <p>Milwaukee Bucks NBA Draft<br> 9FIFTY Snapback</p>
            <p>₱2,495.00</p>
          <button>Add to Cart</button>
    </div>
     </td>
    </tr>
    <tr>
     <td>
    <div class="product">
    <img src="https://drive.google.com/uc?export=open&id=1WB-mOufDSee5txzFFPDe0FI7DrSH9TSv" alt="Product 2">
    <h3>Nike</h3>
    <p>Ja Morant Memphis Grizzlies Icon Edition 22/23 Nike NBA Swingman Jersey</p>
    <p>₱4,795.00</p>
    <button>Add to Cart</button>
    </div>
     </td>
     <td>
    <div class="product">
    <img src="https://drive.google.com/uc?export=open&id=1W8rPhTUIIxwutoGlgWOsPjGAVm4X-BnL" alt="Product 2">
    <h3>Nike</h3>
    <p>Luka Doncic Dallas Mavericks Icon Edition 22/23 Nike NBA Swingman Jersey</p>
    <p>₱4,795.00</p>
    <button>Add to Cart</button>
    </div>
     </td>
     <td>
    <div class="product">
    <img src="https://drive.google.com/uc?export=open&id=1XOBjCUpIHMrSVKMS2g2XuQ_IVmfhBaWd" alt="Product 2">
    <h3>Nike</h3>
    <p>Giannis Antetokounmpo Milwaukee Bucks Icon Edition 22/23 Nike NBA Swingman Jersey</p>
    <p>₱4,795.00</p>
    <button>Add to Cart</button>
    </div>
     </td>
    </tr>
    <tr>
     <td>
    <div class="product">
    <img src="https://drive.google.com/uc?export=open&id=1VzcdKjR6KupVKQxkBLw3y-9IDrdSuAvj" alt="Product 2">
    <h3>adidas</h3>
    <p>BYW SELECT Cloud White / Cream Black / Solar Red</p>
     <p>₱8,500.00</p>
    <button>Add to Cart</button>
    </div>
      </td>
      <td>
    <div class="product">
    <img src="https://drive.google.com/uc?export=open&id=1VwvN-NVlTlHyNYvQE4sQ6OMIHa_9PsNl" alt="Product 2">
    <h3>adidas</h3>
    <p>TRAE YOUNG 2 Core Black / Cream White / Semi Mint Rushr</p>
    <p>₱7,000.00</p>
    <button>Add to Cart</button>
    </div>
     </td>
     <td>
    <div class="product">
    <img src="https://drive.google.com/uc?export=open&id=1W8_EGbzM8Q79PN-Q7igKc8VqaFlkfvYr" alt="Product 2">
    <h3>adidas</h3>
    <p>TRAE YOUNG 2 Easy Green/ Grey One / Silver Metalic</p>
    <p>₱7,000.00</p>
    <button>Add to Cart</button>
    </div>
     </td>
    </tr>
    </table>
    </center>
    </section>
  </div>
 <br><br>
 <div class="content-border">
    <section>
      <h2>Our Sports Services</h2>
<div class="container">
          <table>
          <tr>
          <td>
          <div class="service">
          <img class="service-image" src="https://drive.google.com/uc?export=open&id=1VkM4yocLnfyKNehWUpVWSIpFB5kgBWsa" alt="Service 1">
          <div class="service-content">
            <h3>Beginner's Basketball Training</h3>
            <details>
             <summary>
            <p>Show Description</p>
            </summary>
            <p>
                Start your basketball journey with our beginner's training program designed to introduce you to the fundamentals of the game. Our experienced coaches will guide you through shooting, dribbling, and passing techniques, helping you build a solid foundation and gain confidence on the court.
              </p>
              <p>
                <strong>Price: ₱500 per session</strong>
              </p>
            </details>
            <a href="#" class="hire-button">Hire Coach</a>
          </div>
          </div>
          </td>
          <td>
           <div class="service">
          <img class="service-image" src="https://drive.google.com/uc?export=open&id=1VbIdh-Vxs9ZQkAOdy1X78yOZygXABzYV" alt="Service 2">
          <div class="service-content">
            <h3>Advanced Basketball Coaching</h3>
            <details>
          <summary>
         <p>Show Description</p>
             </summary>
            <p>
            Elevate your skills to new heights with our advanced coaching program. Our expert coaches will fine-tune your technique, enhance your tactical understanding, and help you refine your overall game. Benefit from personalized attention and guidance to unlock your full potential and achieve exceptional performance.
             </p>
              <p>
        <strong>Price: ₱800 per session</strong>
      </p>
            </details>
     <a href="#" class="hire-button">Hire Coach</a>
    </div>
    </div>
      </td>
     <td>
  <div class="service">
          <img class="service-image" src="https://drive.google.com/uc?export=open&id=1VheC4YpKbly7Jj6A_SaxJnEapgucTGz8" alt="Service 3">
      <div class="service-content">
       <h3>Personalized Basketball Coaching</h3>
           <details>
         <summary>
         <p>Show Description</p>
        </summary>
        <p>
      Experience the pinnacle of tailored training with our personalized coaching sessions. Our coaches will assess your strengths, weaknesses, and goals, creating a customized training plan tailored to your specific needs. Enjoy individualized instruction, detailed feedback, and focused skill development to accelerate your progress and achieve remarkable results.
              </p>
     <p>
        <strong>Price: ₱1,200 per session</strong>
     </p>
    </details>
    <a href="#" class="hire-button">Hire Coach</a>
</div>
    </div>
     </td>
 </tr>
 </table>
</div>

    </section>
    </div>
 <footer style="padding: 3px 20px;  background-color: #000000 ; ">
   <center>
<pre><span></span><span><a href="about.html" class="cta-button">ABOUT US</a></span><span><a href="https://www.example.com/social" target="_blank" class="cta-button">FOLLOW OUR SOCIALS</a></span><span><a href="contact.html" class="cta-button">CONTACT US</a></span></pre>
 <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
    <br>
</footer>  
  </div>
  <div class="page" id="page2">  
 <div class="content-border" >
  <center>
 <br><br><br>
 <p style=" color: #EDEDED; font-family: 'Breul Grotesk', sans-serif; font-size: 30px; display: inline;" ><b>FEATURED</b>
 <br><br>
</center> 

  <center>
  <img  width="800" height="300" style="padding: 10px 10px 10px 10px;  background-color: #1A1A1A;" src="https://drive.google.com/uc?export=view&id=1SVInlxvR8BytYXZoOoaHHy6a0FE7H6Mu" alt="Featured Image"> 
  </center>
 <br><br> <br><br>
  </div> 
 <footer style="padding: 3px 20px;  background-color: #000000 ; ">
   <center>
<pre><span></span><span><a href="about.html" class="cta-button">ABOUT US</a></span><span><a href="https://www.example.com/social" target="_blank" class="cta-button">FOLLOW OUR SOCIALS</a></span><span><a href="contact.html" class="cta-button">CONTACT US</a></span></pre>
 <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
    <br>
</footer>
  </div>

  <div class="page" id="page3">
      <div class="content-border">
      <center><p style="font-size:30px;color:#EDEDED; font-family: 'Breul Grotesk', sans-serif;"><b>Videos</b><p></center> 
   <div class="newsfeed">
    <div class="video-card">
     <iframe width="305" height="185" src="https://www.youtube.com/embed/p4H_-Yed9wE" title="NBA TODAY | Woj [BREAKING NEWS] The Warriors trading Jordan Poole to the Wizards for Chris Paul" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Trade</h3>
      <p>The Warriors trading Jordan Poole to the Wizards for Chris Paul</p>
    </div>
    <div class="video-card">
       <iframe width="305" height="185" src="https://www.youtube.com/embed/yD3_d8AMtGA" title="🚨 Ja Morant suspended 25 games 🚨 Stephen A. and Woj offer opinions | First Take" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Punishment</h3>
      <p>Ja Morant suspended 25 games Stephen A. and Woj offer opinions | First Take"</p>
    </div>
    <div class="video-card">
      <iframe width="305" height="185" src="https://www.youtube.com/embed/PP8Pcv4QuzY" title="Kai Sotto lalaro sa Summer league team ng Orlando Magic Best situation para kay Kai!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Summer Leauge</h3>
      <p>Kai Sotto lalaro sa Summer league team ng Orlando Magic Best situation para kay Kai!</p>
    </div>
    <div class="video-card">
   <iframe width="305" height="185" src="https://www.youtube.com/embed/WZhqbThDsMg" title="🚨 BREAKING: Celtics trade Marcus Smart to Grizzlies, receive Porzingis in 3-team trade | SC with SVP" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Trade</h3>
      <p>Celtics trade Marcus Smart to Grizzlies, receive Porzingis in 3-team trade | SC with SVP</p>
    </div>
    <div class="video-card">
     <iframe width="305" height="185" src="https://www.youtube.com/embed/sij25UyDwro" title="Shaquille O&#39;Neal enters the 3rd annual Andre the Giant Memorial Battle Royal: WrestleMania 32" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>WrestleMania</h3>
      <p>Shaquille O&#39;Neal enters the 3rd annual Andre the Giant Memorial Battle Royal: WrestleMania 32</p>
    </div>
    <div class="video-card">
    <iframe width="305" height="185" src="https://www.youtube.com/embed/iPXGjAJ6jxQ" title="Houston Rockets vs Shanghai Sharks Full Game Highlights | 10.09.2018, NBA Preseason" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Sheesh</h3>
      <p>2016 NBA Slam Dunk Contest - <br>Aaron Gordon vs Zach LaVine HD Full</p>
    </div>
  
    <div class="video-card">
     <iframe width="305" height="185" src="https://www.youtube.com/embed/FeXZY4eVLlo" title="NBA TODAY | Woj [BREAKING NEWS] The Warriors trading Jordan Poole to the Wizards for Chris Paul" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Sheesh</h3>
      <p>EVERY BUCKET From Kobe Bryant's 81-PT Performance!</p>
    </div>
    <div class="video-card">
       <iframe width="305" height="185" src="https://www.youtube.com/embed/s4QuUYG6kxI " title="🚨 Ja Morant suspended 25 games 🚨 Stephen A. and Woj offer opinions | First Take" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Baka Tmac yarn</h3>
      <p>Tracy McGrady scored 13 points in 33 seconds"</p>
    </div>
    <div class="video-card">
      <iframe width="305" height="185" src="https://www.youtube.com/embed/CZFQPupSEnk" title="Kai Sotto lalaro sa Summer league team ng Orlando Magic Best situation para kay Kai!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

      <h3>Summer Leauge</h3>
      <p>Kai Sotto lalaro sa Summer league team ng Orlando Magic Best situation para kay Kai!</p>
    </div>

    <div class="video-card">
    <iframe width="305" height="185" src="https://www.youtube.com/embed/rzQAC8kPJxo" title="🚨 BREAKING: Celtics trade Marcus Smart to Grizzlies, receive Porzingis in 3-team trade | SC with SVP" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Goat</h3>
      <p>THE G.O.A.T DEBATE: MICHAEL JORDAN</p>
    </div>
    
    <div class="video-card">
     <iframe width="305" height="185" src="https://www.youtube.com/embed/cnQfJfFVSqo" title="Shaquille O&#39;Neal enters the 3rd annual Andre the Giant Memorial Battle Royal: WrestleMania 32" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>Iyak si Kareem</h3>
      <p>THE ALL-TIME SCORING LEADER: LEBRON JAMES</p>
    </div>
   
    <div class="video-card">
    <iframe width="305" height="185" src="https://www.youtube.com/embed/46qX0Sa0McE" title="Houston Rockets vs Shanghai Sharks Full Game Highlights | 10.09.2018, NBA Preseason" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <h3>What The Hill</h3>
      <p>Houston Rockets vs Shanghai Sharks Full Game Highlights</p>
    </div>
    
    </div>
     </div>
   <footer style="padding: 3px 20px;  background-color: #000000 ; ">
   <center>
<pre><span></span><span><a href="about.html" class="cta-button">ABOUT US</a></span><span><a href="https://www.example.com/social" target="_blank" class="cta-button">FOLLOW OUR SOCIALS</a></span><span><a href="contact.html" class="cta-button">CONTACT US</a></span></pre>
 <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
    <br>
</footer>
    </div>
    <div class="page" id="page4">
    <div class="content-border">
    <div class="about-us">
    <h2 style="color:#EDEDED;">About Us</h2>
    <p style="color:#EDEDED;">Welcome to Klutch Time Sports, your ultimate destination for reliving and celebrating the greatest moments in NBA history. Our website aims to provide a comprehensive platform where fans can reminisce about the past or envision the future of basketball. As passionate sports enthusiasts, we utilize code snippets from various websites to enhance our learning and exploration of programming.This website is for educational purposes only. We are students of Golden Faith Academy:</p>
    <ul style="color:#EDEDED;">
      <li >Gerard Andrade - Website Content Planner</li>
      <li>Jethro Colinares - Coder</li>
      <li>Kyle Bajamundi - Interface Designer</li>
      <li>Mark Joseph Abutog - Assisting for Web Interface Design</li>
      <li>Mark James Borja - Picture and Video Finder for Website</li>
      <li>John Ron Abris - Caption and Font Finder for Website</li>
    
    </ul>
    <p style="color:#EDEDED;">True innovation lies in our ability to explore and learn from the source codes of gives free in a certain website. As we journey through the vast realm of programming, we embrace the wisdom found in the lines of code borrowed from various websites. With utmost respect and gratitude, we use these building blocks to craft a unique experience that celebrates the past, envisions the future, and leaves an indelible mark on the world of web development. Together, we strive to unravel the secrets hidden in the algorithms, one line at a time. Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
 <br>
 <h3 style="color:#EDEDED;">We learn are code from this source</h3>
  <a href=" https://trickuweb.com/"  target="_blank">https://trickuweb.com/</a>
   <br>
    <a href="https://www.quackit.com/html/codes/">https://www.quackit.com/html/codes/</a>
  <h3 style="color:#EDEDED;">Videos and Photo source</h3>
  <a href="https://www.gettyimages.com/"  target="_blank">https://www.gettyimages.com/</a>
  <br>
   <a href="https://www.youtube.com/playlist?list=PLQJ6-URvJolvFAz6mT3Zb2ao7CAOCLhot">https://www.youtube.com/playlist?list=PLQJ6-URvJolvFAz6mT3Zb2ao7CAOCLhot</a>
 <br>
  <br>
   <h3 style="color:#EDEDED;">Product & Service Pictures Source</h3>
  <a href="https://www.gettyimages.com/"  target="_blank">https://www.gettyimages.com/</a>
  <br>
   <a href="https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjtuPu22dP_AhVNMGAKHT5IBt8YABAAGgJ0bQ&ohost=www.google.com&cid=CAESaeD2m7M4k78IvgqolTIatv4SuR11WcGuu3zVbAGARVt4y6Ev3gEkOCHp_7tjp699-ZFrQuRFlMBBncOXoolTZpPHlz4D2MgnEbBI-dn69_IKAqZQmgD8Z6D7VBE8YSW2mwcgnuR3AKoXRQ&sig=AOD64_0EsWRr8ixILDnQMmJYDtD3ngSb9w&q&adurl&ved=2ahUKEwiKrvO22dP_AhVLklYBHXHPB1EQ0Qx6BAgJEAE" target="_blank">NBA Store Philippines</a>
 <br>
  <br>
   <h3 style="color:#EDEDED;">News Pictures And Imformation Source</h3>
  <a href="https://clutchpoints.com/warriors-news-golden-state-agrees-jordan-poole-chris-paul-trade-with-wizards"  target="_blank">Clutch Point</a>
  <br>
   <a href="https://clutchpoints.com/warriors-news-golden-state-agrees-jordan-poole-chris-paul-trade-with-wizards" target="_blank">Clutch Point</a>
 <br>
  <br>
  </div>
</div>
<footer style="padding: 3px 20px;  background-color: #000000 ;">
   <center>
<pre><span></span><span><a href="about.html" class="cta-button">ABOUT US</a></span><span><a href="https://www.example.com/social" target="_blank" class="cta-button">FOLLOW OUR SOCIALS</a></span><span><a href="contact.html" class="cta-button">CONTACT US</a></span></pre>
 <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
    <br>
</footer> 
</div>
<div class="page" id="page5">
<div class="content-border">
<br><br><br>
<center>
 <div class="login-container" style= "background-color:  #1A1A1A;">
 <h2>Login</h2>
<div class="input-group">
<label for="username">Username:</label>
 <input type="text" name="username" class="login-input" required>
 </div>

    <div class="input-group">
     <label for="password">Password:</label>
     <input type="password" name="password" class="login-input" required>
    </div>
    <input type="submit" value="Login" class="login-button">
</div>
</center>
<br><br><br><br>
</div>
<footer style="padding: 3px 20px;  background-color: #000000 ; ">
   <center>
<pre><span></span><span><a href="about.html" class="cta-button">ABOUT US</a></span><span><a href="https://www.example.com/social" target="_blank" class="cta-button">FOLLOW OUR SOCIALS</a></span><span><a href="contact.html" class="cta-button">CONTACT US</a></span></pre>
 <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
    <br>
</footer>
</div>
<div class="page" id="page6">
<div class="content-border">
<center>
<br><br><br>
<div class="signup-container">
  <h2>Sign Up</h2>
  <div class="input-group">
    <label for="name">Username:</label>
    <input type="text" class="signup-input" id="name">
  </div>
  <div class="input-group">
    <label for="email">Email:</label>
    <input type="email" class="signup-input" id="email">
  </div>
  <div class="input-group">
    <label for="password">Password:</label>
    <input type="password" class="signup-input" id="password">
  </div>
  <button class="signup-button">Create Account</button>
</div>
</center>
<br><br><br><br>
</div>
<footer style="padding: 3px 20px;  background-color: #000000 ; ">
   <center>
<pre><span></span><span><a href="about.html" class="cta-button">ABOUT US</a></span><span><a href="https://www.example.com/social" target="_blank" class="cta-button">FOLLOW OUR SOCIALS</a></span><span><a href="contact.html" class="cta-button">CONTACT US</a></span></pre>
 <br>   <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 11px;">Copyrigth @ 2023 Klutch Time Sports | GFA SHS. All rights reserved.</p>
    <p style= "color: white; font-family: 'Breul Grotesk', sans-serif; font-size: 10px;">Certain photos and videos are copyrigth @ Getty Images and Youtube Stories. This website is for school purposes only</p></center>
    <br>
</footer>
</div>

   <script>
  function showPage(pageNumber) {
   
    var pages = document.getElementsByClassName("page");
    for (var i = 0; i < pages.length; i++) {
      pages[i].style.display = "none";
    }

  
    var selectedPage = document.getElementById("page" + pageNumber);
    selectedPage.style.display = "block";
  }
  showPage(1);
</script>

</body>
</html>

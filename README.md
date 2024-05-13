<!DOCTYPE html>
<html>
  <head>
    <title>My profile</title>
    <meta charset="UTF-8">
    <meta charset="utf-8">
    <link <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Mono:wght@100&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500&family=Space+Mono:ital@0;1&display=swap" rel="stylesheet">    <title>My Profile</title>
  </head>
  <body>
    <div class="intro">    
      <h1>
        Hello, I'm Laura ☀️ 
      </h1>
      <img id ="profile-pic" src="https://scontent-cdg4-3.xx.fbcdn.net/v/t1.6435-9/139395630_2040405902766024_9110629190346674074_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=be3454&_nc_ohc=YPdkSwwynu4AX-taNTd&_nc_ht=scontent-cdg4-3.xx&oh=00_AfDU6LG24H8PQdnPup-tH01dnDHD4iMvNTNGURNlek_nBw&oe=65D72E7D" alt="Laura Bousquet" width="200">
      <p>
       I am 26 years old and I just started learning code. I'm an ex pastry chef and I'm really excited to start a new career as a Web Developer with Le Wagon !
        
      </p>
      <a href="https://www.lewagon.com" target="_blank">Le Wagon</a>
    </div>
    
    <div class="card">
      <h2>
        Hobbies 📚
      </h2>
      <p>
        During my free time I love to bake for my family. If I'm alone I take this time to read, paint and write novels. 
      </p>
    </div>
    
    <div class="card">
      <h2>
        Passions ❤️
      </h2>
      <p>
        One of my biggest passion is music ! I am a huge Taylor Swift fan (swiftie) and I can't wait to finally see her in concert in June this year. 
      </p>
    </div>
    
    <div class="card">
      <h2>
        Projects 💪🏾
      </h2>
      <p>
        Right now I'm really focusing on learning code to be able to get a new job. In the meantime I'm also learning Scottish Gaelic for a future trip. 🏴󠁧󠁢󠁳󠁣󠁴󠁿
      </p>
    </div>
    
    <div class="card">
      <h3>
        Follow me
      </h3>
      <ul>
        <li><a href="https://www.facebook.com/laura.bousquet1997" target="blank">Facebook</a></li>
        <li><a href="https://www.linkedin.com/in/laura-bousquet-6a8084184/" target="blank">LinkedIn</a></li>
        <li><a href="https://www.instagram.com/laurabousquette/" target="blank">Instagram</a></li>
      </ul>
    </div>
  </body>
</html>

body {
  font-family: Noto Sans Mono;
  background-color: #DBE7C9;
  color: #50623A;
  padding: 15px;
  text-align: center;
  }

h1, h2, h3 {
  font-family: Noto Sans Mono;
  font-weight: 900; 
  color: #294B29; 
}
li {
  display: inline;
}
ul {
  padding: 0;
}
a {
  text-decoration: none;
  background-color: #765827;
  border-radius: 50px;
  padding: 4px;
  color: #EAC696;
  font-size: 18px; 
  font-weight: bold;
  transition: 0.3s ease;
}
a:hover{
  color: #C8AE7D;
  background-color: #65451F;
}
#profile-pic{
  width: 200px;
  height: 200px;
  border-radius: 50%;
  border: 2px solid #65451F;
}
.intro {
  background-color: white;
  padding: 0;
  width: 700px;
  height: 450px;
  margin: 25px auto;
  border-radius: 10px;
  border: 1px solid #294B29;
} 
.card {
  background-color: white;
  padding: 0;
  width: 700px;
  
  margin: 25px auto;
  border-radius: 10px;
  border: 1px solid #294B29;  
}

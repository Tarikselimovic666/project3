<html>
<head>
<script src="https://unpkg.com/typewriter-effect@latest/dist/core.js"></script>
<title> TARIK SELIMOVIC </title>
</head>
<style>
body {
font-family: Consolas;
background-image:url("bg.png");
}
.about{
position:relative;
display:flex;
}
.about-text{
  position:center;
}



img {
  border-radius: 50%;
}

</style>
<body>

<script>
alert('Welcome to the CV Page of Tarik Selimovic. This is a project for the course Web Development on IUS');
</script>
<h1> <center> TARIK SELIMOVIC RESUME </center> </h1>
<hr>

<center> <img src="tare.jpg"   alt="Photo of me"> 
  <hr>
 </center>
 <div id="about"></div>
    <script>
      var about = document.getElementById('about');

      var typewriter = new Typewriter(about, {
        loop: false,
		delay: 25
      });

      typewriter.typeString('My name is  Tarik Selimovic  and I was born in Sarajevo, Bosnia and Herzegovina in 1999. I am currently studying Computer Science on the Inernational University of Sarajevo.  I went to Musa Cazim Catic primary school, and my highschool was The First Bosniak Highschool, Cambridge. I also went to a music school called Mladen Pozajic, where I learned how to play the guitar and drums. I speak English, Bosnian, German and a bit of Turkish and Swedish. I am also fluent in Old Norse Language. On my first University year I started a private worldwide 5 digit bussines that sells and provides apparel and clothing. The name of my Company is  NORSE SOULS® . You will find my website on the link below.')
        .start();
    </script>

<hr>
</div>
 <center> <a href="https://www.norsesouls.com/" target="_blank">CLICK HERE TO VISIT NORSE SOULS! </a> </center>
&nbsp;
<center> <img src="ns1.bmp" > </center>
&nbsp;
<center> <a href="https://www.instagram.com/norsesouls/?hl=en/" target="_blank">OUR INSTAGRAM! </a> </center>
&nbsp;
<hr>
 <div id="company"></div>
    <script>
      var company = document.getElementById('company');

      var typewriter = new Typewriter(company, {
        loop: false,
		delay: 25
      });

      typewriter.typeString('I established this community a year ago because of my life-long passion for heathen/norse culture, to meet like-minded people and promote the old ways for all modern-day vikings. My quest for knowledge and to find out more about the culture has brought the page and brand now to where it is - a overwhelmingly large community of heathens that follow my own passion and goals of promoting the old ways, which is, in all actuality, my main reason for keeping up the page, community and establishing the Norse Souls brand - to bring heathenism into the mainstream and to enlighten the bigger populace about it, to share my own and my friends ideas with other heathens around the globe.')
        .start();
    </script>
<hr>
<table border="4" cellpadding="2" cellspacing="2" width="100%">
<tr>
<td>TARIK SELIMOVIC</td>
<td>180302001</td>
</tr>
</table>
<center>
<h3>Click on the tabs below:</h3>
  <div class="tab">
    <a href="https://www.facebook.com/tarik.selimovic.560" target="_blank"><button >Facebook</button></a>
    <a href="https://www.instagram.com/elcakfo/?hl=en/" target="_blank"><button >Instagram</button></a>
    <a href="https://goo.gl/maps/q9AAw2KfkFwH9WqU9" target="_blank"><button>Location</button></a>
  </div>

  <div id="About me" class="tabcontent">
    <h3>Student </h3>
  </div>

  <div id="Norse Souls" class="tabcontent">
    <h3>My Company </h3>
  </div>

  <div id="Contact me" class="tabcontent">
    <h3>support@norsesouls.com</h3>
</div>
</center>
</body>
</html>
<script>
function clickHandle(evt, tabName) {
  let i, tabcontent, tablinks;

  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}


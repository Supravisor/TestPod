
 
<style>
 h1 {
  display: none;
 }
 
 #catphotoapp {
  display: unset;
  text-decoration: none;
 }
 
span::after {
  content: "<h1>Hello World</h1>";
}

 @keyframes myspan {
  0% {content: "<h1>Hello World</h1>";}
  3% {content: "<h1>Hello Worl</h1>";}
  6% {content: "<h1>Hello Wor</h1>";}
  9% {content: "<h1>Hello Wo</h1>";}
  12% {content: "<h1>Hello W</h1>";}
  15% {content: "<h1>Hello </h1>";}
  18% {content: "<h1>Hello</h1>";}
  21% {content: "<h1>Hell</h1>";}
  24% {content: "<h1>Hel</h1>";}
  27% {content: "<h1>He</h1>";}
  30% {content: "<h1>H</h1>";}
  33% {content: "<h1></h1>";}
  36% {content: "<h1>C</h1>";}
  39% {content: "<h1>Ca</h1>";}
  42% {content: "<h1>Cat</h1>";}
  45% {content: "<h1>CatP</h1>";}
  48% {content: "<h1>CatPh</h1>";}
  51% {content: "<h1>CatPho</h1>";}
  54% {content: "<h1>CatPhot</h1>";}
  57% {content: "<h1>CatPhoto</h1>";}
  60% {content: "<h1>CatPhotoA</h1>";}
  63% {content: "<h1>CatPhotoAp</h1>";}
  66% {content: "<h1>CatPhotoApp</h1>";}
  69% {content: "<h1>CatPhotoApp</h1>";}
}

span::after {
  animation-name: myspan;
  animation-duration: 15s;
  animation-iteration-count: infinite;
}
 
</style>

<h1 id="catphotoapp"><span></span><h1>

<p>Welcome, <span id="username">visitor</span>!</p>

<script>
  // Get username from query string, e.g. ?username=Supravisor
  const params = new URLSearchParams(window.location.search);
  const username = params.get('username');
  if (username) {
    document.getElementById('username').textContent = username;
  }
</script>

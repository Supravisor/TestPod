 
<style>
span::after {
  content: "Hello World";
}
@keyframes myspan {
  0% {content: "Hello World";}
  3% {content: "Hello Worl";}
  6% {content: "Hello Wor";}
  9% {content: "Hello Wo";}
  12% {content: "Hello W";}
  15% {content: "Hello ";}
  18% {content: "Hello";}
  21% {content: "Hell";}
  24% {content: "Hel";}
  27% {content: "He";}
  30% {content: "H";}
  33% {content: "";}
  36% {content: "C";}
  39% {content: "Ca";}
  42% {content: "Cat";}
  45% {content: "CatP";}
  48% {content: "CatPh";}
  51% {content: "CatPho";}
  54% {content: "CatPhot";}
  57% {content: "CatPhoto";}
  60% {content: "CatPhotoA";}
  63% {content: "CatPhotoAp";}
  66% {content: "CatPhotoApp";}
  69% {content: "CatPhotoApp";}
}

span::after {
  animation-name: myspan;
  animation-duration: 15s;
animation-iteration-count: infinite;
}
</style>

<h1><span></span><h1>

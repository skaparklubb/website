<div class="main">
	<span class="webdev">Skapar</span>
	<span class="socod">klubben</span>
</div>

<style lang="">
@font-face {
  font-family: 'neontubes';
  src: url("https://bitbucket.org/kennethjensen/webfonts/raw/fc13c1cb430a0e9462da56fe3f421ff7af72db71/neontubes/neontubes-webfont.eot");
  src: url("https://bitbucket.org/kennethjensen/webfonts/raw/fc13c1cb430a0e9462da56fe3f421ff7af72db71/neontubes/neontubes-webfont.eot?#iefix") format("embedded-opentype"), url("https://bitbucket.org/kennethjensen/webfonts/raw/fc13c1cb430a0e9462da56fe3f421ff7af72db71/neontubes/neontubes-webfont.woff2") format("woff2"), url("https://bitbucket.org/kennethjensen/webfonts/raw/fc13c1cb430a0e9462da56fe3f421ff7af72db71/neontubes/neontubes-webfont.woff") format("woff"), url("https://bitbucket.org/kennethjensen/webfonts/raw/fc13c1cb430a0e9462da56fe3f421ff7af72db71/neontubes/neontubes-webfont.ttf") format("truetype");
  font-weight: normal;
  font-style: normal;
}
body {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
 
.main {
  display: block;
  position: absolute;
  top: 50%;
  left: 30%;
  -webkit-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
  width: 50vw;
  height: auto;
  font-family: "neontubes";
  font-size: 16vw;
  text-align: center;
  white-space: nowrap;
}
.main span {
  
  
  -webkit-transform: translateZ(0) translate3D(0, 0, 0);
          transform: translateZ(0) translate3D(0, 0, 0);
  -webkit-backface-visibility: hidden;
          backface-visibility: hidden;
  will-change: opacity;
}
.main .webdev {
  color: #ffd9e2;
  text-shadow: 0 0 0 transparent, 0 0 10px #ff003c, 0 0 20px rgba(255, 0, 60, 0.5), 0 0 40px #ff003c, 0 0 100px #ff003c, 0 0 200px #ff003c, 0 0 300px #ff003c, 0 0 500px #ff003c, 0 0 1000px #ff003c;
  -webkit-animation: blink 4s infinite alternate;
          animation: blink 4s infinite alternate;
}
.main .socod {
  font-size: 11vw;
  color: #d4eaff;
  text-shadow: 0 0 0 transparent, 0 0 10px #2695ff, 0 0 20px rgba(38, 149, 255, 0.5), 0 0 40px #2695ff, 0 0 100px #2695ff, 0 0 200px #2695ff, 0 0 300px #2695ff, 0 0 500px #2695ff;
  -webkit-animation: buzz 0.01s infinite alternate;
          animation: buzz 0.01s infinite alternate;
}
 
@-webkit-keyframes buzz {
  70% {
    opacity: 0.80;
  }
}
 
@keyframes buzz {
  70% {
    opacity: 0.80;
  }
}
@-webkit-keyframes blink {
  40% {
    opacity: 1;
  }
  42% {
    opacity: 0.8;
  }
  43% {
    opacity: 1;
  }
  45% {
    opacity: 0.2;
  }
  46% {
    opacity: 1;
  }
}
@keyframes blink {
  40% {
    opacity: 1;
  }
  42% {
    opacity: 0.8;
  }
  43% {
    opacity: 1;
  }
  45% {
    opacity: 0.2;
  }
  46% {
    opacity: 1;
  }
}
@media screen and (min-width: 1000px) {
  .main {
    width: 400px;
    font-size: 150px;
  }
 
  .main .socod {
    font-size: 103px;
  }
}
</style>